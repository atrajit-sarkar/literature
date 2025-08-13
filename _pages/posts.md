---
layout: page
title: Poems
subtitle: Selected works & fragments
permalink: /posts/
---

## Collected Poems

<div class="posts-grid-cards">
{% for post in site.posts %}
  <article class="poem-card" 
           data-card-color="{{ post.card_color | default: 'default' }}"
           data-card-style="{{ post.card_style | default: 'default' }}"
           style="{% if post.card_bg %}background: {{ post.card_bg }};{% endif %}{% if post.card_text_color %}color: {{ post.card_text_color }};{% endif %}">
    
    <div class="poem-card-content">
      <h3 class="poem-title">
        <span class="poem-icon">🖋️</span>
        <a href="{{ post.url | relative_url }}" style="{% if post.card_text_color %}color: {{ post.card_text_color }};{% endif %}">
          {{ post.title }}
        </a>
      </h3>
      
      <div class="poem-excerpt">
        {{ post.excerpt | strip_html | truncatewords: 15 }}
      </div>
      
      {% if post.categories.size > 0 %}
        <div class="poem-categories">
          {% for category in post.categories limit: 2 %}
            <span class="poem-category">📁{{ category }}</span>
          {% endfor %}
        </div>
      {% endif %}
      
      {% if post.tags.size > 0 %}
        <div class="poem-tags">
          {% for tag in post.tags limit: 3 %}
            <span class="poem-tag">#{{ tag }}</span>
          {% endfor %}
        </div>
      {% endif %}
    </div>
    
    <div class="poem-meta">
      <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%d %b %Y" }}</time>
    </div>
  </article>
{% endfor %}
</div>{% if site.posts.size == 0 %}
<div class="no-posts">
  <h3>No poems yet</h3>
  <p>Pieces will appear here soon. Until then, the page holds its breath. ✨</p>
</div>
{% endif %}

---

### About

A small portfolio of poems, prose notes, and fragments. New pieces arrive as they’re ready.
