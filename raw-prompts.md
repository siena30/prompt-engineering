---
layout: default
title: Raw Prompts - Copy Ready
description: Plain text versions of all expert prompts optimized for easy copying
---

# 📋 Raw Prompts - Copy Ready

*Expert-tier prompts in plain text format - ready to copy and paste into your AI tool.*

---

## 💻 CODING PROMPTS

### Secure System Design
```
Design {system_type} for {scale} with security-first approach:

SECURITY MODEL:
- Authentication: {method} with MFA
- Authorization: RBAC/ABAC permissions
- Data encryption: At rest + in transit
- Network security: Zero-trust architecture

THREAT ANALYSIS:
1. Attack vectors: STRIDE model application
2. Trust boundaries: Data/service isolation
3. Failure modes: Security + availability
4. Monitoring: Anomaly detection, audit logs

OUTPUT:
- Security architecture diagram
- Threat model with mitigations
- Incident response playbook
- Compliance checklist

Think like a security-conscious Staff Engineer.
```

### Security Code Review
```
Security review of {language} code:
{code}

SECURITY CHECKLIST:
- Input validation: SQL injection, XSS, buffer overflow
- Authentication: Session management, token security
- Authorization: Access control, privilege escalation
- Data protection: Sensitive data exposure, encryption
- Error handling: Information disclosure prevention

OUTPUT: Risk score (1-10) + top 3 vulnerabilities with fixes.
```

### Threat Modeling (Microsoft STRIDE)
```
Apply STRIDE threat model to {system/feature}:

THREAT CATEGORIES:
- Spoofing: Identity verification weaknesses
- Tampering: Data integrity violations
- Repudiation: Audit trail gaps
- Information Disclosure: Data exposure risks
- Denial of Service: Availability attacks
- Elevation of Privilege: Access control bypass

OUTPUT: Risk matrix + security controls for top 5 threats.
```

### Technical Debt Quantification (Facebook Method)
```
Quantify technical debt in {codebase/system} using Facebook's methodology:

DEBT TAXONOMY:
1. Code Debt: Complexity, duplication, architecture violations
2. Infrastructure Debt: Outdated dependencies, configuration drift
3. Test Debt: Coverage gaps, flaky tests, integration holes
4. Documentation Debt: Outdated docs, missing ADRs, tribal knowledge

MEASUREMENT FRAMEWORK:
- Interest: Developer velocity impact (story points/sprint)
- Principal: Engineering effort to fix (person-months)
- Risk: Probability of causing production issues

PRIORITIZATION MATRIX:
- High Interest + High Risk = Pay down immediately
- High Interest + Low Risk = Gradual improvement
- Low Interest + High Risk = Risk mitigation focus
- Low Interest + Low Risk = Defer

Output: ROI calculation for debt paydown vs new features.
```

---

## 📊 BUSINESS PROMPTS

### BCG Strategy Canvas (Partner-Level)
```
Develop strategy for {company/situation} using BCG's advanced frameworks:

STRATEGIC HYPOTHESIS:
- Where to play: Market segments, geographies, customer types
- How to win: Sustainable competitive advantage sources
- What capabilities: Assets, skills, processes required

ADVANTAGE STAIRCASE:
1. Table Stakes: Minimum requirements to compete
2. Differentiators: What makes you better today
3. Game Changers: What could make you win long-term

SCENARIO MODELING:
- Bull case: Everything goes right (P10 scenario)
- Base case: Most likely outcome (P50 scenario)
- Bear case: Major challenges (P90 scenario)

VALUE CREATION LEVERS:
- Revenue optimization: Pricing, mix, volume
- Cost transformation: Fixed cost flexibility, variable cost efficiency
- Capital efficiency: Working capital, asset utilization
- Portfolio optimization: Core/growth/emerging business balance

COMPETITIVE DYNAMICS:
- Red ocean: Direct competition, zero-sum dynamics
- Blue ocean: Uncontested market space creation
- Game theory: Competitor response prediction

Deliverable: Strategy deck ready for board presentation.
Think like a BCG Partner pitching to a Fortune 50 CEO.
```

### Private Equity Deal Analysis
```
Evaluate {target_company} as a PE investment using KKR's framework:

INVESTMENT THESIS:
- Market Position: Leadership in attractive segments
- Value Creation Plan: 3-5 specific improvement levers
- Exit Strategy: Strategic/financial buyer profile

DUE DILIGENCE:
1. Commercial: Market size, growth, competitive dynamics
2. Financial: Quality of earnings, working capital, cash generation
3. Operational: Management team, systems, scalability
4. ESG: Environmental impact, governance, stakeholder risks

VALUE CREATION PLAYBOOK:
- Revenue Growth: New products, markets, channels, pricing
- Operational Excellence: Cost reduction, process improvement
- Strategic Repositioning: M&A, divestitures, business model changes

IRR SENSITIVITY ANALYSIS:
- Base case: {X}% IRR at {Y}x exit multiple
- Upside: Top quartile outcome scenarios
- Downside: Stress test assumptions

Output: Investment committee memo with go/no-go recommendation.
```

### M&A Integration (McKinsey Approach)
```
Design integration plan for {acquirer} + {target}:

INTEGRATION PRINCIPLES:
- Day 1 Ready: Critical decisions pre-close
- 100-Day Plan: Early wins and momentum building
- Cultural Integration: Values alignment and change management

SYNERGY QUANTIFICATION:
1. Revenue Synergies: Cross-selling, market expansion, innovation acceleration
2. Cost Synergies: Duplicate elimination, procurement leverage, tech rationalization

INTEGRATION WORKSTREAMS:
- Commercial: Sales force, customer retention, pricing
- Operations: Supply chain, manufacturing, quality
- Technology: Systems integration, data migration
- HR: Organization design, talent retention, culture

RISK MITIGATION:
- Customer attrition: Retention programs, communication plan
- Talent flight: Retention packages, clear career paths
- Cultural clash: Integration team, change champions

Success Metrics: Revenue retention, synergy capture, employee engagement.
Think like someone who's integrated 10+ billion-dollar acquisitions.
```

---

## 🔍 ANALYSIS PROMPTS

### CIA-Style Intelligence Analysis
```
Analyze {situation/threat/opportunity} using structured analytical techniques:

ANALYTICAL FRAMEWORK:
1. Key Assumptions Check: What must be true for this to matter?
2. Alternative Hypotheses: Generate 4-5 competing explanations
3. Inconsistent Evidence: What contradicts the leading hypothesis?
4. Deception Check: How might we be deliberately misled?

INFORMATION EVALUATION:
- Source credibility: Track record, access, motivation
- Information reliability: Corroboration, logical consistency
- Recency and relevance: Time-decay factors
- Collection gaps: What don't we know that matters?

BIAS MITIGATION:
- Confirmation bias: Actively seek disconfirming evidence
- Availability heuristic: Weight base rates over vivid examples
- Anchoring: Consider multiple starting points
- Groupthink: Red team the consensus view

CONFIDENCE ASSESSMENT:
- High confidence: Multiple independent sources, consistent with patterns
- Moderate confidence: Some gaps but logical consistency
- Low confidence: Limited sources, significant uncertainties

Output: Analytical judgment with confidence intervals and key uncertainties.
Think like a senior CIA analyst briefing the President.
```

### Competitive Intelligence (Fortune 500 Standards)
```
Conduct competitive analysis of {competitor} using enterprise CI methods:

INTELLIGENCE REQUIREMENTS:
1. Strategic Intent: Where are they heading? Why?
2. Capabilities: What can they actually execute?
3. Vulnerabilities: Where are they exposed?
4. Likely Moves: What will they do next?

COLLECTION PLAN:
- Primary sources: Earnings calls, conference presentations, job postings
- Secondary sources: Industry reports, patent filings, regulatory submissions
- Human intelligence: Former employees, suppliers, customers
- Technical intelligence: Product teardowns, technology benchmarking

EARLY WARNING SYSTEM:
- Leadership changes: New hires signal strategic shifts
- Investment patterns: R&D, capex, M&A activity
- Partnership announcements: Ecosystem positioning
- Patent applications: Future product capabilities

COUNTERINTELLIGENCE:
- Information security: What are you revealing?
- Deception detection: Are they misleading the market?
- Source protection: Maintaining intelligence access

Deliverable: Monthly CI briefing for executive team.
Think like a Fortune 50 competitive intelligence director.
```

### First Principles Analysis
```
Analyze {problem} using first principles thinking:

DECONSTRUCTION:
1. Core assumptions (what do we take for granted?)
2. Fundamental truths (what's actually proven?)
3. Build up: New approach from basics
4. Comparison: Traditional vs first principles solution

Think like Elon Musk approaching this fresh.
```

---

## ✍️ WRITING PROMPTS

### Expert Content Writer
```
Write {content_type} about {topic} for {audience}.

Expert approach:
- Hook: Compelling opening
- Structure: Clear, logical flow
- Voice: {tone} and engaging
- Value: 3 key takeaways
- CTA: Specific next step

Length: {word_count} words.
```

### Persuasive Writing
```
Write persuasive {document_type} to convince {audience} to {action}.

Framework:
- Problem: Pain point they face
- Solution: Your proposal
- Evidence: 3 supporting points
- Objections: Address top concern
- Call: Clear, specific ask
```

### Story Structure Master
```
Create a {story_type} with this premise: {idea}

Structure:
- Setup: Character + conflict in 50 words
- Confrontation: 3 escalating challenges
- Resolution: Satisfying conclusion
- Theme: Underlying message

Target: {word_count} words, {tone} tone.
```

---

## 💡 CREATIVE PROMPTS

### Innovation Framework
```
Innovate on {existing_solution} for {target_audience}:

IDEO Method:
- Empathize: User pain points
- Define: Core problem statement
- Ideate: 20+ wild solutions
- Prototype: Simplest testable version
- Test: Key assumptions to validate

Think like a design thinking expert.
```

### SCAMPER Method
```
Apply SCAMPER to {existing_solution}:

- Substitute: What can be substituted?
- Combine: What can be combined?
- Adapt: What can be adapted?
- Modify: What can be modified?
- Put to other uses: Alternative applications?
- Eliminate: What can be removed?
- Reverse: What can be rearranged?

Systematic innovation approach.
```

### Divergent Thinking Catalyst
```
Generate breakthrough ideas for {challenge}:

Techniques:
- What if: 10 impossible scenarios
- Reverse: What if we did the opposite?
- Combine: Mix unrelated concepts
- Exaggerate: Take to extremes
- Abstract: Core principles only

Target: 50 ideas, no judgment. Quantity breeds quality.
```

---

## 🤖 AI OPTIMIZATION PROMPTS

### Claude Constitutional Framework
```
Use Claude's constitutional training to refine {task/decision/analysis}:

CONSTITUTIONAL PRINCIPLES:
- Helpful: Provide genuinely useful outputs
- Harmless: Avoid any potential negative impacts
- Honest: Acknowledge uncertainty and limitations

SELF-CRITIQUE PROCESS:
1. Generate initial response to: {your_prompt}
2. Evaluate against constitutional principles
3. Identify potential improvements or issues
4. Refine response incorporating feedback
5. Final quality check against helpfulness/harmlessness/honesty

OUTPUT FORMAT:
- Initial response
- Self-critique analysis
- Refined final response
- Confidence level and remaining uncertainties

Leverage Claude's built-in self-reflection capabilities.
```

### GPT-4 Token Efficiency Optimization
```
Optimize {task} for GPT-4's token efficiency:

COMPRESSION TECHNIQUES:
- Use abbreviations for repeated terms
- Bullet points over full sentences
- Structured formats (tables, lists)
- Reference previous context rather than repeating

EFFICIENCY PATTERNS:
1. Front-load key information: Most important details first
2. Use markdown structure: Headers, bullets, numbered lists
3. Minimize filler words: Direct, concise language
4. Leverage GPT-4's context: Reference earlier parts of conversation

Target: 30-50% token reduction while maintaining output quality.
```

### Universal Model Adaptation
```
Adapt {prompt/task} for optimal performance across AI models:

MODEL-AGNOSTIC PRINCIPLES:
- Clear task definition
- Structured input/output format
- Explicit reasoning requirements
- Quality criteria specification

ADAPTATION FRAMEWORK:
1. Core Prompt: Model-neutral version
2. Claude Variant: Leverage constitutional training, long context
3. GPT-4 Variant: Utilize system messages, few-shot learning
4. General LLM: Fallback version for other models

Output: Multi-model prompt family with performance benchmarks.
```

---

*Copy any prompt above and replace the `{variables}` with your specific context. These prompts are optimized for immediate use with minimal setup.*