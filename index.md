---
layout: default
title: Prompt Engineering Library
description: Searchable collection of expert-level, token-efficient prompts
---

# 🎯 Prompt Engineering Library

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

<div class="category-nav">
  <a href="#coding">💻 Coding</a> |
  <a href="#writing">✍️ Writing</a> |
  <a href="#analysis">🔍 Analysis</a> |
  <a href="#business">📊 Business</a> |
  <a href="#creative">💡 Creative</a>
</div>

---

## 💻 Coding {#coding}

### Secure System Design
**Tags:** `expert` `security` `systematic`
<div class="prompt-container">
<div class="prompt-text">
Design {system_type} for {scale} with security-first approach:

SECURITY MODEL:
- Authentication: {method} with MFA
- Authorization: RBAC/ABAC permissions
- Data encryption: At rest + in transit
- Network security: Zero-trust architecture

THREAT ANALYSIS:
1. **Attack vectors**: STRIDE model application
2. **Trust boundaries**: Data/service isolation
3. **Failure modes**: Security + availability
4. **Monitoring**: Anomaly detection, audit logs

OUTPUT:
- Security architecture diagram
- Threat model with mitigations
- Incident response playbook
- Compliance checklist

Think like a security-conscious Staff Engineer.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Security Code Review
**Tags:** `expert` `security` `quick`
<div class="prompt-container">
<div class="prompt-text">
Security review of {language} code:
{code}

SECURITY CHECKLIST:
- Input validation: SQL injection, XSS, buffer overflow
- Authentication: Session management, token security
- Authorization: Access control, privilege escalation
- Data protection: Sensitive data exposure, encryption
- Error handling: Information disclosure prevention

OUTPUT: Risk score (1-10) + top 3 vulnerabilities with fixes.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Debug Like a Detective
**Tags:** `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Debug this issue systematically:
Problem: {error_description}
Code: {relevant_code}

Method:
1. Hypothesis (most likely cause)
2. Test strategy
3. Expected vs actual behavior
4. Root cause + fix
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Code Optimization Expert
**Tags:** `expert` `template`
<div class="prompt-container">
<div class="prompt-text">
Optimize this {language} code for {performance_metric}:
{code}

Think like a performance engineer:
- Bottleneck identification
- Algorithmic improvements
- Language-specific optimizations
- Benchmark validation approach
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Feature Implementation Strategy
**Tags:** `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Implement {feature} following best practices:

Strategy:
1. Break into 3-5 subtasks
2. Define interfaces first
3. Identify dependencies
4. Test strategy
5. Rollout plan

Start with the most critical component.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Refactoring Master
**Tags:** `expert` `template`
<div class="prompt-container">
<div class="prompt-text">
Refactor this code following SOLID principles:
{code}

Output:
- Current design issues
- Refactored structure
- Migration steps
- Risk assessment
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

---

## ✍️ Writing {#writing}

### Expert Content Writer
**Tags:** `expert` `template` `systematic`
<div class="prompt-container">
<div class="prompt-text">
Write {content_type} about {topic} for {audience}.

Expert approach:
- Hook: Compelling opening
- Structure: Clear, logical flow  
- Voice: {tone} and engaging
- Value: 3 key takeaways
- CTA: Specific next step

Length: {word_count} words.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Story Structure Master
**Tags:** `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Create a {story_type} with this premise: {idea}

Structure:
- Setup: Character + conflict in 50 words
- Confrontation: 3 escalating challenges  
- Resolution: Satisfying conclusion
- Theme: Underlying message

Target: {word_count} words, {tone} tone.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Persuasive Writing
**Tags:** `expert` `template`
<div class="prompt-container">
<div class="prompt-text">
Write persuasive {document_type} to convince {audience} to {action}.

Framework:
- Problem: Pain point they face
- Solution: Your proposal
- Evidence: 3 supporting points
- Objections: Address top concern
- Call: Clear, specific ask
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Clear Explanation
**Tags:** `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Explain {complex_topic} to {audience} in {format}.

Method:
- Analogy: Familiar comparison
- Breakdown: 3-5 key components
- Examples: Concrete illustrations
- Summary: One-sentence takeaway

Make it impossible to misunderstand.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

---

## 🔍 Analysis {#analysis}

### First Principles Analysis
**Tags:** `expert` `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Analyze {problem} using first principles thinking:

Deconstruction:
1. Core assumptions (what do we take for granted?)
2. Fundamental truths (what's actually proven?)
3. Build up: New approach from basics
4. Comparison: Traditional vs first principles solution

Think like Elon Musk approaching this fresh.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Root Cause Analysis
**Tags:** `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Find the root cause of {problem}:

5 Whys Method:
- Why 1: {immediate_cause}
- Why 2: What caused that?
- Why 3: What caused that?
- Why 4: What caused that?  
- Why 5: What caused that?

Root cause + prevention strategy.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Decision Analysis Framework
**Tags:** `expert` `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Analyze this decision: {decision}

Structure:
- Stakes: What's at risk?
- Options: 3-5 viable paths
- Criteria: Success metrics (weighted)
- Trade-offs: Each option's pros/cons
- Recommendation: Best choice + reasoning
- Reversibility: Can we change course?

Decide like a top consultant.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

---

## 📊 Business {#business}

### Business Strategy Framework
**Tags:** `expert` `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Develop strategy for {business_context}:

Strategic Analysis:
- Market: Size, trends, opportunities
- Competition: Key players, positioning
- Capabilities: Strengths, gaps
- Options: 3-5 strategic choices
- Recommendation: Best path + rationale

Think like a McKinsey partner.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Go-to-Market Strategy
**Tags:** `expert` `template`
<div class="prompt-container">
<div class="prompt-text">
Create GTM strategy for {product/service}:

Framework:
- Target: Ideal customer profile
- Positioning: Unique value proposition
- Channels: How to reach customers
- Pricing: Strategy + rationale
- Launch: 90-day execution plan

Focus on fastest path to revenue.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Business Case Development
**Tags:** `expert` `template`
<div class="prompt-container">
<div class="prompt-text">
Build business case for {initiative}:

Financial Model:
- Investment: Upfront costs
- Returns: Revenue impact
- Timeline: Payback period
- Scenarios: Conservative/optimistic
- ROI: Expected return

Risk assessment + recommendation.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

---

## 💡 Creative {#creative}

### Divergent Thinking Catalyst
**Tags:** `creative` `template` `systematic`
<div class="prompt-container">
<div class="prompt-text">
Generate breakthrough ideas for {challenge}:

Techniques:
- What if: 10 impossible scenarios
- Reverse: What if we did the opposite?
- Combine: Mix unrelated concepts
- Exaggerate: Take to extremes
- Abstract: Core principles only

Target: 50 ideas, no judgment. Quantity breeds quality.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### Innovation Framework
**Tags:** `expert` `creative` `template`
<div class="prompt-container">
<div class="prompt-text">
Innovate on {existing_solution} for {target_audience}:

IDEO Method:
- Empathize: User pain points
- Define: Core problem statement
- Ideate: 20+ wild solutions
- Prototype: Simplest testable version
- Test: Key assumptions to validate

Think like a design thinking expert.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

### SCAMPER Method
**Tags:** `systematic` `template`
<div class="prompt-container">
<div class="prompt-text">
Apply SCAMPER to {existing_solution}:

- Substitute: What can be substituted?
- Combine: What can be combined?
- Adapt: What can be adapted?
- Modify: What can be modified?
- Put to other uses: Alternative applications?
- Eliminate: What can be removed?
- Reverse: What can be rearranged?

Systematic innovation approach.
</div>
<button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
</div>

---

<style>
.search-container {
  margin: 20px 0;
  text-align: center;
}

#searchBox {
  width: 60%;
  padding: 10px;
  font-size: 16px;
  border: 2px solid #ddd;
  border-radius: 5px;
  margin-bottom: 10px;
}

.filter-tags {
  margin: 10px 0;
}

.tag-filter {
  margin: 0 5px;
  padding: 5px 10px;
  background: #f0f0f0;
  border: none;
  border-radius: 15px;
  cursor: pointer;
}

.tag-filter.active {
  background: #007cba;
  color: white;
}

.category-nav {
  text-align: center;
  margin: 20px 0;
  font-size: 18px;
}

.category-nav a {
  text-decoration: none;
  margin: 0 10px;
}

.prompt-container {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 5px;
  margin: 15px 0;
  position: relative;
}

.prompt-text {
  padding: 15px;
  font-family: 'Courier New', monospace;
  white-space: pre-line;
  background: white;
  margin: 0;
  border-radius: 5px 5px 0 0;
}

.copy-btn {
  position: absolute;
  top: 5px;
  right: 5px;
  padding: 5px 10px;
  background: #007cba;
  color: white;
  border: none;
  border-radius: 3px;
  cursor: pointer;
  font-size: 12px;
}

.copy-btn:hover {
  background: #005a87;
}

.hidden {
  display: none;
}
</style>

<script>
function copyPrompt(button) {
  const promptText = button.previousElementSibling.textContent;
  navigator.clipboard.writeText(promptText).then(() => {
    const originalText = button.textContent;
    button.textContent = 'Copied!';
    button.style.background = '#28a745';
    setTimeout(() => {
      button.textContent = originalText;
      button.style.background = '#007cba';
    }, 2000);
  });
}

// Search functionality
document.getElementById('searchBox').addEventListener('input', function(e) {
  const searchTerm = e.target.value.toLowerCase();
  const prompts = document.querySelectorAll('.prompt-container');
  
  prompts.forEach(prompt => {
    const text = prompt.textContent.toLowerCase();
    if (text.includes(searchTerm)) {
      prompt.style.display = 'block';
    } else {
      prompt.style.display = 'none';
    }
  });
});

// Tag filtering
document.querySelectorAll('.tag-filter').forEach(button => {
  button.addEventListener('click', function() {
    // Remove active class from all buttons
    document.querySelectorAll('.tag-filter').forEach(btn => btn.classList.remove('active'));
    // Add active class to clicked button
    this.classList.add('active');
    
    const tag = this.dataset.tag;
    const sections = document.querySelectorAll('h3');
    
    sections.forEach(section => {
      const nextElement = section.nextElementSibling;
      if (nextElement && nextElement.textContent.includes('Tags:')) {
        const tags = nextElement.textContent.toLowerCase();
        const promptContainer = nextElement.nextElementSibling;
        
        if (tag === 'all' || tags.includes(tag)) {
          section.style.display = 'block';
          nextElement.style.display = 'block';
          promptContainer.style.display = 'block';
        } else {
          section.style.display = 'none';
          nextElement.style.display = 'none';
          promptContainer.style.display = 'none';
        }
      }
    });
  });
});

// Set 'All' as default active
document.querySelector('[data-tag="all"]').classList.add('active');
</script>