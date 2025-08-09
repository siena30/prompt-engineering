# Prompt Quality Standards

*Standardization guide for maintaining excellence across the prompt engineering repository.*

---

## 🎯 Quality Framework

### Core Quality Principles

1. **Token Efficiency**: Maximum impact with minimal words
2. **Expert-Level Output**: Prompts should generate professional-grade results
3. **Reusability**: Template-based design for multiple contexts
4. **Clarity**: Unambiguous instructions and expected outputs
5. **Systematic Approach**: Structured frameworks over ad-hoc requests

### Quality Rating System (1-10 Scale)

**10 - Exceptional**: Industry-leading prompt used by top consultancies/companies
**8-9 - Expert**: Professional-grade, systematic approach, comprehensive
**6-7 - Solid**: Good structure, clear instructions, reliable results
**4-5 - Basic**: Functional but lacks depth or systematic approach
**1-3 - Poor**: Vague, inefficient, or produces inconsistent results

---

## 📝 Formatting Standards

### Required Components

Every prompt MUST include:
```markdown
### Prompt Title
**Tags:** `#tag1` `#tag2` `#tag3`
```
[Prompt content in code block]
```

### Variable Placeholder Standards

**✅ Correct Format:**
- `{specific_variable}` - Use descriptive, lowercase with underscores
- `{system_type}`, `{target_audience}`, `{analysis_topic}`

**❌ Incorrect Format:**
- `{variable}` - Too generic
- `{Variable}` - Avoid camelCase
- `[placeholder]` - Use braces, not brackets
- `<input>` - Use braces, not angle brackets

### Tag Standards

**Required Tags (choose 1-3):**
- Complexity: `#quick`, `#expert`, `#systematic`
- Type: `#template`, `#creative`, `#workflow`
- Domain-specific: `#security`, `#intelligence`, `#constitutional-ai`

**Tag Definitions:**
- `#quick`: 1-2 minute execution, immediate results
- `#expert`: Requires domain expertise, sophisticated output
- `#systematic`: Multi-step structured approach
- `#template`: Highly customizable with variables
- `#creative`: Divergent thinking, innovation-focused
- `#workflow`: Multi-stage process or orchestration

---

## 🔍 Content Quality Criteria

### Instruction Clarity (8+ required)

**Excellent (9-10):**
- Specific, actionable instructions
- Clear success criteria
- Explicit output format requirements
- Context and constraints defined

**Example:**
```
Analyze {security_vulnerability} using STRIDE methodology:

OUTPUT FORMAT:
- Threat category (Spoofing/Tampering/Repudiation/etc.)
- Risk severity (Critical/High/Medium/Low)
- Specific mitigation steps (3-5 actions)
- Implementation timeline

SUCCESS CRITERIA:
- Actionable recommendations
- CVSS score included
- Prevention measures defined
```

### Structure & Organization (7+ required)

**Required Elements:**
1. **Clear objective** - What the prompt accomplishes
2. **Structured approach** - Step-by-step or framework-based
3. **Output specification** - Exact format expected
4. **Quality indicators** - How to measure success

### Expert-Level Thinking (8+ required)

**Characteristics:**
- Uses established frameworks (STRIDE, BCG, McKinsey, IDEO)
- References expert methodologies
- Encourages systematic analysis
- Includes quality validation steps

**Example Expert Patterns:**
```
Think like a {expert_role} with {specific_credentials}...
Apply {established_framework} methodology...
Use {professional_standard} approach...
Rate like you're responsible for {high_stakes_outcome}...
```

---

## 🧪 Testing & Validation

### Prompt Testing Protocol

**Phase 1: Self-Assessment**
1. Does it pass the 10-second clarity test?
2. Are variables clearly defined and necessary?
3. Is the output format specification complete?
4. Would this generate consistent results across users?

**Phase 2: Quality Checklist**
- [ ] Clear, specific instructions (no ambiguity)
- [ ] Proper variable placeholder format `{descriptive_name}`
- [ ] Expert-level thinking patterns included
- [ ] Success criteria explicitly defined
- [ ] Token-efficient (no unnecessary words)
- [ ] Professional output quality expected

**Phase 3: Effectiveness Testing**
- Test with 3 different inputs
- Evaluate output consistency
- Check for professional-grade results
- Verify adherence to specified format

### Model Performance Standards

**Minimum Requirements:**
- **Claude**: 8+ quality rating, leverages constitutional AI strengths
- **GPT-4**: 8+ quality rating, optimized for instruction-following
- **Cross-model**: 7+ quality rating across different AI models

**Optimization Indicators:**
- Appropriate context length usage
- Model-specific prompt engineering techniques
- Consistent high-quality outputs
- Token efficiency maintained

---

## 📊 Quality Assurance Process

### New Prompt Submission

1. **Self-Review**: Creator validates against quality standards
2. **Peer Review**: Second reviewer checks for improvements
3. **Testing**: Validate with multiple test cases
4. **Category Fit**: Ensure proper categorization and tagging
5. **Documentation**: Update category README with new prompt

### Existing Prompt Maintenance

**Quarterly Review Cycle:**
- Performance assessment against quality standards
- User feedback integration
- Model optimization updates
- Format standardization improvements

**Improvement Triggers:**
- Quality rating below 7
- Inconsistent output reports
- Better methodology available
- Model performance changes

### Quality Metrics Dashboard

**Track Monthly:**
- Average quality rating per category
- Prompt usage frequency
- User satisfaction scores
- Model performance benchmarks

---

## ⚡ Quick Quality Checklist

**Before Adding Any Prompt:**
- [ ] Title is descriptive and specific
- [ ] Tags follow standard format and definitions
- [ ] Variables use `{descriptive_name}` format
- [ ] Instructions are clear and unambiguous
- [ ] Output format is explicitly specified
- [ ] Success criteria are defined
- [ ] Expert-level thinking patterns included
- [ ] Token efficiency optimized
- [ ] Tested with multiple inputs
- [ ] Category placement verified

**Quality Score Target: 8+ for all prompts**

---

## 🔧 Continuous Improvement

### Feedback Integration
- Monitor prompt usage and effectiveness
- Collect user feedback on output quality
- Track model performance changes
- Update standards based on best practices

### Version Control
- Document prompt improvements with rationale
- Maintain backward compatibility where possible
- Archive outdated prompts with migration notes
- Update related documentation consistently

### Standards Evolution
- Review quality standards quarterly
- Incorporate latest prompt engineering research
- Adapt to new AI model capabilities
- Maintain alignment with industry best practices

---

*This quality framework ensures all prompts meet professional standards and deliver consistent, expert-level results.*