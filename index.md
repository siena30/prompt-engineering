---
layout: default
title: Prompt Engineering Library
description: Searchable collection of expert-level, token-efficient prompts
---

# 🎯 Prompt Engineering Library

*Expert-tier prompts for professionals who demand results*

<div class="search-container">
  <input type="text" id="searchBox" placeholder="Search prompts by keyword or tag..." />
  <div class="filter-tags">
    <button class="tag-filter" data-tag="all">All</button>
    <button class="tag-filter" data-tag="quick">Quick</button>
    <button class="tag-filter" data-tag="expert">Expert</button>
    <button class="tag-filter" data-tag="security">Security</button>
    <button class="tag-filter" data-tag="template">Template</button>
    <button class="tag-filter" data-tag="systematic">Systematic</button>
    <button class="tag-filter" data-tag="creative">Creative</button>
  </div>
</div>

---

## 📚 Browse by Category

<div class="category-grid">
  <div class="category-card">
    <h3><a href="prompt-library/coding/">💻 Coding</a></h3>
    <p>Security-first system design, elite code review, threat modeling</p>
    <span class="prompt-count">12+ prompts</span>
  </div>
  
  <div class="category-card">
    <h3><a href="prompt-library/business/">📊 Business</a></h3>
    <p>BCG strategy frameworks, PE deal analysis, M&A integration</p>
    <span class="prompt-count">15+ prompts</span>
  </div>
  
  <div class="category-card">
    <h3><a href="prompt-library/analysis/">🔍 Analysis</a></h3>
    <p>CIA intelligence methods, competitive analysis, decision frameworks</p>
    <span class="prompt-count">12+ prompts</span>
  </div>
  
  <div class="category-card">
    <h3><a href="prompt-library/writing/">✍️ Writing</a></h3>
    <p>Expert content creation, persuasive frameworks, storytelling</p>
    <span class="prompt-count">8+ prompts</span>
  </div>
  
  <div class="category-card">
    <h3><a href="prompt-library/creative/">💡 Creative</a></h3>
    <p>Innovation frameworks, design thinking, breakthrough ideation</p>
    <span class="prompt-count">8+ prompts</span>
  </div>
  
  <div class="category-card">
    <h3><a href="raw-prompts">📋 Raw Prompts</a></h3>
    <p>Copy-paste ready versions without formatting</p>
    <span class="prompt-count">All prompts</span>
  </div>
</div>

---

## 🏆 Featured Expert Prompts

### 🛡️ Security-First System Design
*Design systems with zero-trust architecture and STRIDE threat modeling*  
**Tags:** `expert` `security` `systematic`  
→ [View in Coding Section](prompt-library/coding/#secure-system-design)

### 🎯 BCG Strategy Canvas  
*Partner-level strategy development using BCG's proven frameworks*  
**Tags:** `expert` `consulting-grade` `systematic`  
→ [View in Business Section](prompt-library/business/#bcg-strategy-canvas)

### 🕵️ CIA Intelligence Analysis
*Structured analytical techniques used by intelligence professionals*  
**Tags:** `expert` `intelligence` `systematic`  
→ [View in Analysis Section](prompt-library/analysis/#cia-style-intelligence)

---

## 🚀 Quick Access

**For Developers:** [Security Code Review](prompt-library/coding/) • [Threat Modeling](prompt-library/coding/) • [Technical Debt](prompt-library/coding/)

**For Business Leaders:** [Strategy Development](prompt-library/business/) • [M&A Integration](prompt-library/business/) • [Executive Communication](prompt-library/business/)

**For Analysts:** [Decision Frameworks](prompt-library/analysis/) • [Competitive Intelligence](prompt-library/analysis/) • [Risk Assessment](prompt-library/analysis/)

---

<style>
.search-container {
  margin: 30px 0;
  text-align: center;
  background: #f8f9fa;
  padding: 30px;
  border-radius: 12px;
}

#searchBox {
  width: 70%;
  max-width: 500px;
  padding: 15px;
  font-size: 16px;
  border: 2px solid #ddd;
  border-radius: 25px;
  outline: none;
  transition: border-color 0.3s;
}

#searchBox:focus {
  border-color: #3498db;
  box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.1);
}

.filter-tags {
  margin: 20px 0;
}

.tag-filter {
  margin: 5px;
  padding: 8px 16px;
  background: #ecf0f1;
  border: none;
  border-radius: 20px;
  cursor: pointer;
  transition: all 0.3s;
  font-size: 14px;
}

.tag-filter:hover {
  background: #bdc3c7;
  transform: translateY(-1px);
}

.tag-filter.active {
  background: #3498db;
  color: white;
}

.category-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 30px 0;
}

.category-card {
  background: white;
  border: 1px solid #e1e5e9;
  border-radius: 12px;
  padding: 25px;
  text-align: center;
  transition: all 0.3s ease;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.category-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
  border-color: #3498db;
}

.category-card h3 {
  margin: 0 0 15px 0;
  font-size: 1.4em;
}

.category-card h3 a {
  color: #2c3e50;
  text-decoration: none;
}

.category-card h3 a:hover {
  color: #3498db;
}

.category-card p {
  color: #7f8c8d;
  margin: 0 0 15px 0;
  line-height: 1.5;
}

.prompt-count {
  background: #3498db;
  color: white;
  padding: 4px 12px;
  border-radius: 15px;
  font-size: 0.85em;
  font-weight: 500;
}

@media (max-width: 768px) {
  .category-grid {
    grid-template-columns: 1fr;
  }
  
  #searchBox {
    width: 90%;
  }
  
  .category-card {
    padding: 20px;
  }
}
</style>

<script>
// Search functionality - redirect to appropriate category
document.getElementById('searchBox').addEventListener('keypress', function(e) {
  if (e.key === 'Enter') {
    const query = e.target.value.toLowerCase();
    
    // Smart category detection
    if (query.includes('code') || query.includes('security') || query.includes('debug')) {
      window.location.href = 'prompt-library/coding/';
    } else if (query.includes('business') || query.includes('strategy') || query.includes('mckinsey')) {
      window.location.href = 'prompt-library/business/';
    } else if (query.includes('analysis') || query.includes('decision') || query.includes('cia')) {
      window.location.href = 'prompt-library/analysis/';
    } else if (query.includes('writing') || query.includes('content') || query.includes('story')) {
      window.location.href = 'prompt-library/writing/';
    } else if (query.includes('creative') || query.includes('innovation') || query.includes('design')) {
      window.location.href = 'prompt-library/creative/';
    } else {
      // General search - go to raw prompts for full-text search
      window.location.href = 'raw-prompts';
    }
  }
});

// Tag filtering - redirect to relevant category
document.querySelectorAll('.tag-filter').forEach(button => {
  button.addEventListener('click', function() {
    const tag = this.dataset.tag;
    
    if (tag === 'security') {
      window.location.href = 'prompt-library/coding/';
    } else if (tag === 'expert') {
      window.location.href = 'prompt-library/business/';
    } else if (tag === 'creative') {
      window.location.href = 'prompt-library/creative/';
    } else {
      window.location.href = 'prompt-library/';
    }
  });
});
</script>