# 🌸 Atrajit | Poems & Literature

> *A beautiful, modern Jekyll theme designed for poets, writers, and literature enthusiasts*

<div align="center">

![Poetry Website](https://img.shields.io/badge/Poetry-Website-blueviolet?style=for-the-badge&logo=bookstack)
![Jekyll](https://img.shields.io/badge/Jekyll-4.3.4-red?style=for-the-badge&logo=jekyll)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Live Site](https://img.shields.io/badge/Live-www.atrajit.xyz-blue?style=for-the-badge&logo=firefox)

**[🌐 Live Demo](https://www.atrajit.xyz)** • **[📖 Documentation](#-features)** • **[🚀 Quick Start](#-quick-start)**

</div>

---

## ✨ Features

### 🎨 **Modern Card-Based Design**
- **12+ Color Variants**: Default, Purple, Green, Blue, Orange, Pink, Red, Yellow, Indigo, Gray, Teal, Slate, Black, Light
- **3 Card Styles**: 
  - 🌈 **Gradient** - Beautiful gradient backgrounds with vibrant colors
  - 🪟 **Glass** - Modern glassmorphism effect with backdrop blur
  - � **Minimal** - Clean, minimal design with subtle borders

### 🌙 **Dual Theme System**
- **Light Mode**: Clean, bright interface perfect for day reading
- **Dark Mode**: Easy on the eyes for night-time poetry sessions
- **Seamless Switching**: Toggle between themes with smooth transitions
- **Auto Contrast**: Text colors automatically adjust for optimal readability

### 📱 **Responsive & Accessible**
- **Mobile-First Design**: Perfect on phones, tablets, and desktops
- **Grid Layout**: Automatic responsive card arrangement
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **SEO Optimized**: Structured data and meta tags included

### 🎭 **Poetry-Focused Features**
- **Hero Section**: Prominent display for your main message
- **Card Grid**: Beautiful showcase for your poems and writings
- **Flexible Layouts**: Multiple page templates included
- **Tag System**: Organize your work by themes and topics

---

## 🎨 Card System Showcase

<details>
<summary>📸 <strong>View All Card Styles & Colors</strong></summary>

### 🌈 Gradient Cards (Default Style)
```yaml
# In your post front matter:
card_color: "purple"     # Creates purple gradient background
card_color: "green"      # Creates green gradient background  
card_color: "blue"       # Creates blue gradient background
# ... and 9 more colors!
```

### 🪟 Glass Cards (Glassmorphism Effect)
```yaml
# In your post front matter:
card_style: "glass"      # Creates frosted glass effect
card_color: "blue"       # Optional: adds subtle color tint
```

### 📄 Minimal Cards (Clean & Simple)
```yaml
# In your post front matter:
card_style: "minimal"    # Creates clean bordered card
```

</details>

---

## 🚀 Quick Start

### 🛠️ Prerequisites
- Ruby 2.7+
- Jekyll 4.3+
- Git

### ⚡ One-Click Setup
```bash
# 1. Clone this repository
git clone https://github.com/your-username/poetry-website.git
cd poetry-website

# 2. Install dependencies
bundle install

# 3. Start local development
bundle exec jekyll serve --livereload

# 🎉 Your site is now running at http://localhost:4000
```

### 🎯 Customize for Your Poetry

#### 1. **Update Site Configuration**
```yaml
# _config.yml
title: "Your Name | Poems & Literature"
description: "Your beautiful poetry description"
url: "https://yourwebsite.com"
email: "your@email.com"

# Social links
github_username: yourusername
twitter_username: yourusername
```

#### 2. **Replace Hero Content**
```markdown
# index.md
---
layout: home
---

# Your Beautiful Tagline
*Your inspiring subtitle about poetry and literature*

[Explore My Poems](/posts){: .btn .btn-primary}
```

#### 3. **Add Your First Poem**
```markdown
# _posts/2025-08-13-my-first-poem.md
---
layout: post
title: "My Beautiful Poem"
date: 2025-08-13
categories: [poetry, nature]
tags: [love, life, beauty]
card_color: "purple"
card_style: "gradient"
---

Your beautiful poem content goes here...
```

---

## 🎨 Customization Guide

### 🌈 **Available Card Colors**

#### 🎨 **Basic Colors**
| Color | Preview | Usage | Description |
|-------|---------|-------|-------------|
| `default` | 🔵 Blue-Purple Gradient | `card_color: "default"` | Default blue-purple gradient |
| `purple` | 🟣 Purple Gradient | `card_color: "purple"` | Rich purple gradient |
| `green` | 🟢 Green Gradient | `card_color: "green"` | Fresh green gradient |
| `blue` | 🔵 Blue Gradient | `card_color: "blue"` | Ocean blue gradient |
| `orange` | 🟠 Orange Gradient | `card_color: "orange"` | Warm orange gradient |
| `pink` | 🩷 Pink Gradient | `card_color: "pink"` | Soft pink gradient |
| `red` | 🔴 Red Gradient | `card_color: "red"` | Bold red gradient |
| `yellow` | 🟡 Yellow Gradient | `card_color: "yellow"` | Bright yellow gradient |
| `indigo` | 🟣 Indigo Gradient | `card_color: "indigo"` | Deep indigo gradient |
| `gray` | ⚫ Gray Gradient | `card_color: "gray"` | Neutral gray gradient |
| `teal` | � Teal Gradient | `card_color: "teal"` | Calm teal gradient |
| `slate` | ⬛ Slate Gradient | `card_color: "slate"` | Professional slate gradient |
| `black` | ⚫ Black Gradient | `card_color: "black"` | Elegant black gradient |
| `light` | ⚪ Light Theme | `card_color: "light"` | Clean light background |

#### ✨ **Extended Colors**
| Color | Preview | Usage | Description |
|-------|---------|-------|-------------|
| `rose` | 🌹 Rose Gradient | `card_color: "rose"` | Romantic rose gradient |
| `emerald` | 💚 Emerald Gradient | `card_color: "emerald"` | Precious emerald gradient |
| `sky` | 🌌 Sky Gradient | `card_color: "sky"` | Clear sky gradient |
| `violet` | 💜 Violet Gradient | `card_color: "violet"` | Rich violet gradient |
| `amber` | 🟨 Amber Gradient | `card_color: "amber"` | Warm amber gradient |
| `cyan` | 🔵 Cyan Gradient | `card_color: "cyan"` | Electric cyan gradient |
| `lime` | 🍃 Lime Gradient | `card_color: "lime"` | Fresh lime gradient |
| `fuchsia` | 💖 Fuchsia Gradient | `card_color: "fuchsia"` | Vibrant fuchsia gradient |
| `stone` | 🪨 Stone Gradient | `card_color: "stone"` | Natural stone gradient |

#### 🌈 **Special Gradients**
| Color | Preview | Usage | Description |
|-------|---------|-------|-------------|
| `gradient-sunset` | 🌅 Sunset Gradient | `card_color: "gradient-sunset"` | Beautiful sunset colors |
| `gradient-ocean` | 🌊 Ocean Gradient | `card_color: "gradient-ocean"` | Deep ocean waves |
| `gradient-forest` | 🌲 Forest Gradient | `card_color: "gradient-forest"` | Mystical forest greens |

### 🎭 **Card Style Options**

#### 📐 **Basic Styles**
| Style | Preview | Usage | Description |
|-------|---------|-------|-------------|
| `default` | 🎨 Gradient | `card_style: "default"` | Standard gradient background |
| `minimal` | 📄 Clean | `card_style: "minimal"` | Clean minimal design with borders |
| `glass` | 🪟 Glass | `card_style: "glass"` | Modern glassmorphism effect |

#### ✨ **Advanced Styles**
| Style | Preview | Usage | Description |
|-------|---------|-------|-------------|
| `bordered` | 🔲 Bordered | `card_style: "bordered"` | Transparent with colored border |
| `shadow` | 🌑 Shadow | `card_style: "shadow"` | Deep shadow elevation |
| `neon` | ⚡ Neon | `card_style: "neon"` | Glowing neon border effect |
| `embossed` | 🏛️ Embossed | `card_style: "embossed"` | 3D embossed appearance |
| `gradient-border` | 🌈 Gradient Border | `card_style: "gradient-border"` | Animated gradient border |

### 🎨 **Style Combinations**

You can combine any color with any style:

```yaml
# Examples of combinations
card_color: "rose"
card_style: "glass"

card_color: "gradient-sunset"
card_style: "neon"

card_color: "emerald"
card_style: "shadow"

card_color: "violet"
card_style: "embossed"
```

### 🖼️ **Complete Card Setup Example**

```yaml
---
layout: post
title: "My Beautiful Poem"
date: 2025-08-13
categories: [Poetry, Nature]
tags: [love, beauty, dreams]
card_color: "gradient-sunset"    # Choose from 25+ colors
card_style: "glass"              # Choose from 8 styles
excerpt: "A brief description of your poem"
---

Your poem content here...
```

### 🖼️ **Adding Images**
```markdown
# In your posts
![Beautiful Image](path/to/your/image.jpg)
```

### 🏷️ **Using Tags and Categories**
```yaml
# In post front matter
categories: [poetry, prose, fiction]
tags: [love, nature, life, dreams, hope]
```

---

## 📁 Project Structure

```
├── 📄 _config.yml              # Site configuration
├── 📄 index.md                 # Homepage content
├── 📁 _layouts/                # Page templates
│   ├── 📄 default.html         # Base template
│   ├── 📄 home.html            # Homepage template
│   ├── 📄 page.html            # Static pages
│   └── 📄 post.html            # Blog post template
├── 📁 _pages/                  # Static pages
│   └── 📄 posts.md             # Posts archive
├── 📁 _posts/                  # Your poems & writings
├── 📁 assets/                  # CSS, JS, images
│   ├── 📁 css/
│   │   └── 📄 main.css         # Main stylesheet
│   ├── 📁 js/
│   └── 📁 images/
└── 📁 _site/                   # Generated site (ignored)
```

---

## 🔧 Advanced Customization

### 🎨 **Adding New Card Colors**
```css
/* In assets/css/main.css */
.poem-card[data-card-color="mystic"] {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: #ffffff;
}

.poem-card[data-card-color="mystic"] .poem-title a {
    color: #ffffff !important;
}
```

### 🌙 **Customizing Themes**
```css
/* Light theme variables */
:root {
    --primary-color: #667eea;
    --text-primary: #2d3748;
    --bg-primary: #ffffff;
}

/* Dark theme variables */
[data-theme="dark"] {
    --primary-color: #9f7aea;
    --text-primary: #f7fafc;
    --bg-primary: #1a202c;
}
```

### 📱 **Responsive Breakpoints**
```css
/* Mobile first approach */
.posts-grid-cards {
    grid-template-columns: 1fr;          /* Mobile */
}

@media (min-width: 768px) {
    .posts-grid-cards {
        grid-template-columns: repeat(2, 1fr);  /* Tablet */
    }
}

@media (min-width: 1024px) {
    .posts-grid-cards {
        grid-template-columns: repeat(3, 1fr);  /* Desktop */
    }
}
```

---

## 🚀 Deployment Options

### 📡 **GitHub Pages (Recommended)**
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch
5. Your site will be live at `username.github.io/repository-name`

### 🌐 **Custom Domain**
```bash
# Add CNAME file
echo "yourwebsite.com" > CNAME
git add CNAME
git commit -m "Add custom domain"
git push
```

### ☁️ **Other Platforms**
- **Netlify**: Connect your GitHub repo
- **Vercel**: Import your repository
- **Firebase Hosting**: Build and deploy manually

---

## 📚 Example Poems

Here are some example poems with different card styles:

<details>
<summary>🌸 <strong>Nature Poem (Green Gradient)</strong></summary>

```markdown
---
layout: post
title: "Whispers of the Forest"
date: 2025-08-13
categories: [poetry, nature]
tags: [forest, tranquility, growth]
card_color: "green"
card_style: "gradient"
---

In the quiet depths of emerald green,
Where sunlight filters through the leaves,
The forest whispers ancient dreams,
And every breath the soul relieves.
```

</details>

<details>
<summary>💙 <strong>Love Poem (Glass Effect)</strong></summary>

```markdown
---
layout: post
title: "Ethereal Love"
date: 2025-08-13
categories: [poetry, love]
tags: [romance, dreams, ethereal]
card_color: "blue"
card_style: "glass"
---

Like morning mist upon the lake,
Your love surrounds me, soft and true,
In every breath that I partake,
I find myself lost deep in you.
```

</details>

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🌿 **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. 💫 **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. 📤 **Push** to the branch (`git push origin feature/amazing-feature`)
5. 🎉 **Open** a Pull Request

### 🐛 **Bug Reports**
Found a bug? Please open an issue with:
- Detailed description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

### 💡 **Feature Requests**
Have an idea? We'd love to hear it! Open an issue with:
- Clear description of the feature
- Use case explanation
- Mockups or examples (if applicable)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Jekyll Team** for the amazing static site generator
- **GitHub Pages** for free hosting
- **Poetry Community** for inspiration
- **Open Source Contributors** who make projects like this possible

---

## 💬 Support

Need help? Here are your options:

- 📖 **Documentation**: Check this README
- 🐛 **Issues**: [Open an issue](https://github.com/your-username/poetry-website/issues)
- 💬 **Discussions**: [Join the discussion](https://github.com/your-username/poetry-website/discussions)
- 📧 **Email**: kobi@atrajit.xyz

---

<div align="center">

### 🌟 **Made with ❤️ for the Poetry Community**

**[⭐ Star this repo](https://github.com/your-username/poetry-website)** if you found it helpful!

*Transform your words into a beautiful digital experience* ✨

---

**📍 [Live Demo](https://www.atrajit.xyz)** • **🚀 [Get Started](#-quick-start)** • **🎨 [Customize](#-customization-guide)**

</div>
