# Elite Coding Prompts

Expert-tier prompts used by Staff+ Engineers at top tech companies.

## Architecture & Design

### Secure System Design
**Tags:** `#expert` `#security` `#systematic`
```
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

OUTPUT FORMAT:
- Security architecture diagram with component relationships
- Comprehensive threat model with specific mitigations
- Incident response playbook with escalation procedures
- Compliance checklist with verification criteria

SUCCESS CRITERIA:
- All security domains addressed comprehensively
- Threat model covers realistic attack scenarios
- Implementation roadmap is actionable
- Compliance requirements clearly mapped

HUMAN AUTHENTICITY GUIDELINES:
- Use practical security expertise language
- Include real-world threat scenario examples
- Express genuine concern for security impact
- Reference actual security incidents where appropriate

Think like a security-conscious Staff Engineer.
```

### Code Review (Principal Engineer Standards)
**Tags:** `#expert` `#systematic` `#production-ready`
```
Review this {language} code with the scrutiny of a Principal Engineer:

{code}

EVALUATION DIMENSIONS:
1. **Correctness**: Edge cases, race conditions, error handling
2. **Performance**: Algorithmic complexity, memory usage, cache efficiency
3. **Maintainability**: Cognitive load, coupling, testability
4. **Security**: Injection attacks, data leakage, privilege escalation
5. **Operability**: Logging, metrics, debugging capabilities

RISK ASSESSMENT:
- P0: Could cause outages or data corruption
- P1: Performance degradation under load
- P2: Technical debt that will slow future development
- P3: Style/convention issues

OUTPUT FORMAT:
- Overall risk score (1-10)
- Top 3 must-fix issues with specific solutions
- Performance bottlenecks with benchmarking approach
- Security vulnerabilities with remediation

SUCCESS CRITERIA:
- Risk assessment reflects actual production impact
- Issues are prioritized by business criticality
- Solutions are technically sound and implementable
- Review maintains code quality standards

HUMAN AUTHENTICITY GUIDELINES:
- Use experienced engineer judgment language
- Include references to production debugging experience
- Express appropriate concern for system reliability
- Use practical, battle-tested engineering wisdom

Rate like you're responsible for the system's reliability.
```

## Problem Solving

### Debug Like a Detective
**Tags:** `#systematic` `#template`
```
Debug this issue systematically:
Problem: {error_description}
Code: {relevant_code}

SYSTEMATIC METHOD:
1. **Hypothesis**: Most likely cause based on symptoms
2. **Test Strategy**: How to isolate and verify the cause
3. **Expected vs Actual**: What should happen vs what happens
4. **Root Cause**: Underlying issue, not just symptoms  
5. **Fix**: Specific solution with validation approach

OUTPUT FORMAT:
- Root cause analysis (2-3 sentences)
- Specific fix with code changes
- Testing strategy to verify fix
- Prevention measures for future

SUCCESS CRITERIA:
- Root cause identified accurately, not just symptoms
- Fix addresses underlying issue permanently
- Testing strategy validates solution effectiveness
- Prevention measures reduce future occurrence

HUMAN AUTHENTICITY GUIDELINES:
- Use methodical debugging thought processes
- Include moments of hypothesis refinement
- Express the satisfaction of finding the real issue
- Use practical troubleshooting language from experience

Think like a senior debugger solving production issues.
```

### Security Code Review
**Tags:** `#expert` `#security` `#quick`
```
Security review of {language} code:
{code}

SECURITY CHECKLIST:
- Input validation: SQL injection, XSS, buffer overflow
- Authentication: Session management, token security
- Authorization: Access control, privilege escalation
- Data protection: Sensitive data exposure, encryption
- Error handling: Information disclosure prevention

OUTPUT FORMAT:
- Overall risk score (1-10) with rationale
- Top 3 vulnerabilities with CVSS ratings
- Specific remediation steps for each issue
- Prevention measures for development process

SUCCESS CRITERIA:
- Accurate CVSS scoring with justified metrics
- Vulnerabilities prioritized by actual risk
- Remediation steps are technically implementable
- Prevention measures address root causes

HUMAN AUTHENTICITY GUIDELINES:
- Use experienced security professional language
- Include references to real-world attack patterns
- Express appropriate urgency based on severity
- Use practical security implementation wisdom

Assess like a senior security engineer who's seen it all.
```

## Implementation

### Secure Implementation
**Tags:** `#systematic` `#security`
```
Implement {feature_name} with security by design:

SECURITY-FIRST APPROACH:
1. **Threat Model**: Identify attack surfaces and entry points
2. **Security Controls**: Authentication, authorization, input validation
3. **Data Flow Security**: Sanitization points, encryption boundaries  
4. **Testing Strategy**: Security unit tests, penetration testing
5. **Monitoring**: Security events, anomaly detection

OUTPUT FORMAT:
- Security architecture overview
- Implementation checklist with priorities
- Test cases for security validation  
- Monitoring and alerting requirements
- Compliance verification steps

SUCCESS CRITERIA:
- Zero high-severity security vulnerabilities
- All data flows properly secured
- Comprehensive test coverage for security scenarios

HUMAN AUTHENTICITY GUIDELINES:
- Use practical security implementation experience
- Include references to common security pitfalls
- Express genuine commitment to secure development
- Use language from someone who's built secure systems

Apply security-first development principles throughout.
```

### Refactoring Master
**Tags:** `#expert` `#template`
```
Refactor this code following SOLID principles:
{code}

REFACTORING FRAMEWORK:
- **S**ingle Responsibility: One reason to change
- **O**pen/Closed: Open for extension, closed for modification
- **L**iskov Substitution: Subtypes must be substitutable
- **I**nterface Segregation: Many specific interfaces vs one general
- **D**ependency Inversion: Depend on abstractions, not concretions

OUTPUT FORMAT:
- Current SOLID violations (specific issues identified)
- Refactored code structure with explanations
- Step-by-step migration plan with risk mitigation
- Code quality metrics improvement (before/after)
- Testing strategy for refactored components

SUCCESS CRITERIA:
- All SOLID principles properly applied
- Maintainability score improvement measurable
- No functionality regression during migration

HUMAN AUTHENTICITY GUIDELINES:
- Use experienced software architect language
- Include references to refactoring war stories
- Express passion for clean, maintainable code
- Use practical wisdom from years of technical debt battles

Think like a senior architect designing for long-term maintainability.
```

## Security & Performance

### Threat Modeling (Microsoft STRIDE)
**Tags:** `#expert` `#security` `#systematic`
```
Apply STRIDE threat model to {system/feature}:

THREAT CATEGORIES:
- **Spoofing**: Identity verification weaknesses
- **Tampering**: Data integrity violations  
- **Repudiation**: Audit trail gaps
- **Information Disclosure**: Data exposure risks
- **Denial of Service**: Availability attacks
- **Elevation of Privilege**: Access control bypass

OUTPUT FORMAT:
- Risk matrix with likelihood and impact scores
- Top 5 threats prioritized by risk level
- Specific security controls for each threat
- Implementation timeline and resource requirements
- Monitoring and detection capabilities needed

SUCCESS CRITERIA:
- All STRIDE categories systematically evaluated
- Risk prioritization reflects business impact
- Security controls are technically feasible
- Implementation plan is actionable

HUMAN AUTHENTICITY GUIDELINES:
- Use Microsoft security methodology expertise
- Include references to actual threat scenarios
- Express systematic security thinking approach
- Use language from experienced threat modeling sessions

Apply enterprise-grade threat modeling rigor.
```

### Performance + Security Audit
**Tags:** `#expert` `#optimization`
```
Audit {system_name} for performance and security:

PERFORMANCE ANALYSIS:
- **Bottlenecks**: CPU, memory, I/O, network utilization
- **Caching Strategy**: Hit rates, invalidation patterns, efficiency
- **Database Performance**: Query optimization, indexing effectiveness
- **Scalability**: Load handling, resource scaling patterns

SECURITY ANALYSIS:
- **Input Validation**: Injection prevention, sanitization
- **Authentication**: Token management, session security
- **Authorization**: Access control enforcement, privilege escalation risks
- **Data Protection**: Encryption, sensitive data handling

OUTPUT FORMAT:
- Performance score (1-10) with bottleneck analysis
- Security score (1-10) with vulnerability assessment
- Priority-ranked improvement recommendations
- Implementation roadmap with effort estimates
- Monitoring strategy for ongoing optimization

SUCCESS CRITERIA:
- Performance improvements quantified with metrics
- Security vulnerabilities addressed with timelines
- Balanced optimization maintaining both performance and security

HUMAN AUTHENTICITY GUIDELINES:
- Use performance engineering expertise language
- Include references to production optimization battles
- Express understanding of performance-security trade-offs
- Use practical insights from scaling real systems

Audit like you're optimizing a high-traffic production system.
```

## Quick Fixes

### Vulnerability Assessment
**Tags:** `#quick` `#security`
```
Assess security vulnerability in {language}:
{code_or_description}

ANALYSIS:
- Vulnerability type (OWASP Top 10)
- Impact severity (Critical/High/Medium/Low)
- Exploit difficulty
- Remediation steps
- Prevention measures

OUTPUT FORMAT:
- CVSS score with detailed rationale
- Vulnerability classification and attack vector analysis
- Step-by-step remediation plan with code examples
- Prevention strategy for development process
- Testing approach to verify fix effectiveness

SUCCESS CRITERIA:
- Accurate CVSS scoring with justified metrics
- Remediation plan is technically sound and implementable
- Prevention measures address root cause
- Fix verification is comprehensive

HUMAN AUTHENTICITY GUIDELINES:
- Use experienced security professional language
- Include practical remediation experience
- Express appropriate urgency based on severity
- Reference real-world exploitation scenarios

Assess like a senior security engineer who's seen it all.
```

### Code Explanation
**Tags:** `#quick` `#template`
```
Explain this {language} code like I'm a {skill_level} developer:
{code}

EXPLANATION FRAMEWORK:
1. **Purpose**: What this code accomplishes (high-level goal)
2. **Key Concepts**: Important patterns, algorithms, or techniques used
3. **Code Flow**: Step-by-step execution walkthrough
4. **Critical Details**: Gotchas, edge cases, performance considerations
5. **Context**: How this fits into larger systems or patterns

OUTPUT FORMAT:
- Executive summary (1-2 sentences)
- Detailed walkthrough with line-by-line annotations
- Key learning points for {skill_level} developers
- Potential improvements or alternatives
- Related concepts to explore further

SUCCESS CRITERIA:
- Explanation matches skill level appropriately
- Technical accuracy with no misleading information
- Educational value for skill development
- Clear, jargon-appropriate language

HUMAN AUTHENTICITY GUIDELINES:
- Use teaching moments and learning insights
- Include personal anecdotes about similar code patterns
- Express genuine enthusiasm for sharing knowledge
- Use mentoring language from experienced developers

Explain like the best coding mentor you know.
```

## Elite Engineering

### Technical Debt Quantification (Facebook Method)
**Tags:** `#expert` `#systematic` `#technical-debt`
```
Quantify technical debt in {codebase_name} using Facebook's methodology:

DEBT TAXONOMY:
1. **Code Debt**: Complexity, duplication, architecture violations
2. **Infrastructure Debt**: Outdated dependencies, configuration drift  
3. **Test Debt**: Coverage gaps, flaky tests, integration holes
4. **Documentation Debt**: Outdated docs, missing ADRs, tribal knowledge

MEASUREMENT FRAMEWORK:
- **Interest**: Developer velocity impact (story points/sprint)
- **Principal**: Engineering effort to fix (person-months)
- **Risk**: Probability of causing production issues

PRIORITIZATION MATRIX:
- High Interest + High Risk = Pay down immediately
- High Interest + Low Risk = Gradual improvement
- Low Interest + High Risk = Risk mitigation focus
- Low Interest + Low Risk = Defer

BUSINESS IMPACT ANALYSIS:
- Feature delivery slowdown: {X}% per quarter
- Incident rate correlation: {Y} incidents/month
- Developer satisfaction impact: Net Promoter Score

OUTPUT FORMAT:
- Debt inventory with quantified measurements
- Prioritization matrix with specific recommendations
- ROI calculation for debt paydown vs new features
- Implementation timeline with resource requirements
- Success metrics and monitoring approach

SUCCESS CRITERIA:
- All debt categories systematically measured
- Business impact quantified with data
- Clear prioritization based on risk/impact analysis
- Actionable roadmap with resource estimates

HUMAN AUTHENTICITY GUIDELINES:
- Use executive engineering decision-making language
- Include references to technical debt battles fought
- Express understanding of business-engineering trade-offs
- Use strategic thinking from engineering leadership experience

Think like a VP of Engineering making data-driven technical investment decisions.
```

---
*Use these prompts by replacing `{variables}` with your specific context.*