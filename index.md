---
layout: home
---

<!-- Hero Section -->
<section class="hero-section">
    <div class="hero-background">
        <div class="hero-particles"></div>
        <div class="hero-grid"></div>
    </div>
    
    <div class="container">
        <div class="hero-content">
            <div class="hero-image-container">
                <div class="status-indicator">
                    <span class="status-dot"></span>
                    Friend Quest Active
                </div>
                <div class="dual-profile-container">
                    <img src="/atrajit.jpg" alt="Atrajit" class="hero-image">
                </div>
                <div class="hero-glow"></div>
            </div>
            
            <div class="hero-text">
                <div class="typing-animation">
                    <h1 class="hero-title hero-with-logo">
                        <span class="hero-logo">
                            <img src="/assets/images/favicon.svg" alt="Atrajit logo" width="72" height="72" loading="eager" />
                        </span>
                        <span class="welcome-text">Poems by</span>
                        <span class="text-gradient">Atrajit</span>
                    </h1>
                    <div class="typing-container">
                        <span class="typing-text"></span>
                        <span class="cursor">|</span>
                    </div>
                </div>
                
                <p class="hero-description">
                    <strong>Minimal words. Lasting echoes ✨</strong><br>
                    A portfolio of poems, small prose, and notes.
                </p>
                
                <div class="hero-stats">
                    <div class="stat-item">
                        <span class="stat-number">∞</span>
                        <span class="stat-label">Verses</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number">1</span>
                        <span class="stat-label">Voice</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number">24/7</span>
                        <span class="stat-label">Reading</span>
                    </div>
                </div>
                
                <div class="hero-actions">
                    <a href="/posts/" class="btn btn-primary">
                        <span>Read Poems</span>
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M13.025 1l-2.847 2.828 6.176 6.176h-16.354v3.992h16.354l-6.176 6.176 2.847 2.828 10.975-11z"/>
                        </svg>
                    </a>
                    <a href="#features" class="btn btn-secondary">
                        <span>About</span>
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Features Section -->
<section class="features-section" id="features">
    <div class="container">
        <div class="section-header">
            <h2 class="section-title">
                <span class="section-emoji">🖋️</span>
                About the Work
            </h2>
            <p class="section-description">
                Quiet poems, spare lines, and little essays — arranged simply.
            </p>
        </div>
        
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">
                    <span>�</span>
                </div>
                <h3>Poems</h3>
                <p>Selected verses — final, fragment, and in-between.</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">
                    <span>�</span>
                </div>
                <h3>Notes</h3>
                <p>Short prose, annotations, drafts, and stray thoughts.</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">
                    <span>🔍</span>
                </div>
                <h3>Simple</h3>
                <p>Clean reading experience with focus on the words.</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">
                    <span>📚</span>
                </div>
                <h3>Collected</h3>
                <p>All pieces gathered in one place, easy to browse.</p>
            </div>
        </div>
    </div>
</section>

<!-- Recent Poems Section -->
<section class="recent-chats-section">
    <div class="container">
        <div class="section-header">
            <h2 class="section-title">
                <span class="section-emoji">✨</span>
                Recent Poems
            </h2>
            <p class="section-description">
                Latest pieces from the portfolio
            </p>
        </div>
        
        <div class="posts-grid">
            {% for post in site.posts limit:3 %}
            <article class="post-card">
                <div class="post-meta">
                    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
                    <div class="post-category">{{ post.categories | first | capitalize }}</div>
                </div>
                <h3 class="post-title">
                    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
                </h3>
                <p class="post-excerpt">{{ post.excerpt | strip_html | truncate: 150 }}</p>
                <div class="post-tags">
                    {% for tag in post.tags limit:3 %}
                    <span class="post-tag">{{ tag }}</span>
                    {% endfor %}
                </div>
                <a href="{{ post.url | relative_url }}" class="post-link">
                    Read Poem
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M13.025 1l-2.847 2.828 6.176 6.176h-16.354v3.992h16.354l-6.176 6.176 2.847 2.828 10.975-11z"/>
                    </svg>
                </a>
            </article>
            {% endfor %}
        </div>
        
        <div class="section-cta">
            <a href="/posts/" class="btn btn-primary">View All Poems</a>
        </div>
    </div>
</section>
