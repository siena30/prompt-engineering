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

OUTPUT:
- Security architecture diagram
- Threat model with mitigations
- Incident response playbook
- Compliance checklist

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

Rate like you're responsible for the system's reliability.
```

## Problem Solving

### Debug Like a Detective
**Tags:** `#systematic` `#template`
```
Debug this issue systematically:
Problem: {error_description}
Code: {relevant_code}

Method:
1. Hypothesis (most likely cause)
2. Test strategy
3. Expected vs actual behavior
4. Root cause + fix
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

OUTPUT: Risk score (1-10) + top 3 vulnerabilities with fixes.
```

## Implementation

### Secure Implementation
**Tags:** `#systematic` `#security`
```
Implement {feature} with security by design:

1. **Threat model**: Identify attack surfaces
2. **Security controls**: Authentication, authorization, validation
3. **Data flow**: Sanitization, encryption boundaries
4. **Testing**: Security unit tests, penetration testing
5. **Monitoring**: Security events, anomaly detection

Security-first implementation approach.
```

### Refactoring Master
**Tags:** `#expert` `#template`
```
Refactor this code following SOLID principles:
{code}

Output:
- Current design issues
- Refactored structure
- Migration steps
- Risk assessment
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

OUTPUT: Risk matrix + security controls for top 5 threats.
```

### Performance + Security Audit
**Tags:** `#expert` `#optimization`
```
Audit {system} for performance and security:

PERFORMANCE:
- Bottlenecks: CPU, memory, I/O, network
- Caching strategy: Hit rates, invalidation
- Database: Query optimization, indexing

SECURITY:
- Input validation: Injection prevention
- Authentication: Token management, session security
- Authorization: Access control enforcement

Balanced optimization maintaining security posture.
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

CVSS score + actionable fix.
```

### Code Explanation
**Tags:** `#quick` `#template`
```
Explain this {language} code like I'm a {skill_level} developer:
{code}

Focus on: purpose, key concepts, gotchas.
```

## Elite Engineering

### Technical Debt Quantification (Facebook Method)
**Tags:** `#expert` `#systematic` `#technical-debt`
```
Quantify technical debt in {codebase/system} using Facebook's methodology:

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

BUSINESS IMPACT:
- Feature delivery slowdown: {X}% per quarter
- Incident rate correlation: {Y} incidents/month
- Developer satisfaction impact: Net Promoter Score

Output: ROI calculation for debt paydown vs new features.
```

---
*Use these prompts by replacing `{variables}` with your specific context.*