# Contributing to Awesome WEKAOU

Thank you for your interest in contributing to the Awesome WEKAOU list! This document provides guidelines for contributing high-quality resources to help the WEKAOU community discover valuable materials.

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Quality Standards](#quality-standards)
- [Submission Guidelines](#submission-guidelines)
- [Resource Categories](#resource-categories)
- [Formatting Rules](#formatting-rules)
- [Review Process](#review-process)

---

## How to Contribute

### Quick Start

1. **Fork** this repository
2. **Add** your resource to the appropriate section in README.md
3. **Ensure** it meets our quality standards
4. **Submit** a pull request with a clear description
5. **Respond** to any feedback from maintainers

### Types of Contributions

We welcome:

- ✅ **New resources**: Tools, tutorials, papers, implementations
- ✅ **Updates**: Corrections to existing entries
- ✅ **Improvements**: Better descriptions or categorization
- ✅ **New sections**: Propose new categories if needed

We generally don't accept:

- ❌ **Commercial promotions**: Unless genuinely valuable and clearly disclosed
- ❌ **Low-quality content**: Incomplete, unmaintained, or poorly documented
- ❌ **Duplicates**: Resources already listed
- ❌ **Off-topic content**: Not directly related to WEKAOU

---

## Quality Standards

All resources must meet these criteria:

### 1. Relevance ⭐⭐⭐⭐⭐
- **Directly related** to WEKAOU, its concepts, or implementations
- Addresses SPOC-M, CRL, K-Cycle, OOS, MST, or related frameworks
- Provides value to WEKAOU practitioners or learners

### 2. Quality ⭐⭐⭐⭐⭐
- **Well-documented**: Clear README, installation guides, usage examples
- **Maintained**: Recent updates or timeless reference material
- **Functional**: Works as advertised (for tools/implementations)
- **Complete**: Not a stub or placeholder project

### 3. Accessibility ⭐⭐⭐⭐⭐
- **Publicly available**: No login walls or paywalls for basic access
- **Properly licensed**: Clear license information
- **Language**: English or multi-language with English support

### 4. Description ⭐⭐⭐⭐⭐
- **Clear purpose**: Obvious what the resource is and what it does
- **Value proposition**: Why it's useful to the WEKAOU community
- **Honest representation**: No exaggerated claims

---

## Submission Guidelines

### Before Submitting

1. **Search existing entries** to avoid duplicates
2. **Review the quality standards** above
3. **Check the resource is live** and accessible
4. **Prepare a clear description** (see formatting rules below)

### Pull Request Format

Use this template for your PR:

```
## Resource Addition: [Resource Name]

**Category**: [e.g., Learning Materials > Getting Started]
**URL**: [Resource URL]
**Description**: [Brief description]

### Why This Resource?

[Explain why this resource is valuable to the WEKAOU community]

### Quality Checklist

- [ ] Resource is publicly accessible
- [ ] Documentation is clear and complete
- [ ] Resource is maintained or timeless
- [ ] No duplicates in the list
- [ ] Follows formatting guidelines
- [ ] Description is accurate and concise
```

### Multiple Resources

If adding multiple resources, create separate commits for each category:

```bash
git commit -m "feat(learning): add SPOC-M tutorial"
git commit -m "feat(tools): add validation CLI tool"
```

---

## Resource Categories

### Current Categories

- **Official Resources**: Canonical WEKAOU repos and documentation
- **Learning Materials**: Tutorials, guides, courses, concept explanations
- **Implementations**: Real-world deployments, example projects, templates
- **Tools & Utilities**: Development tools, validators, visualizations, integrations
- **Research & Papers**: Academic publications, technical reports, studies
- **Community**: Forums, social media, events, blogs
- **Related Projects**: Complementary systems, alternatives, foundational tech

### Proposing New Categories

If your resource doesn't fit existing categories:

1. Open an issue titled "New Category Proposal: [Category Name]"
2. Explain the category purpose and scope
3. Provide 3-5 example resources that would fit
4. Wait for community feedback before adding

---

## Formatting Rules

### Entry Format

```markdown
- [Resource Name](URL) - Brief description explaining value and purpose.
```

### Description Guidelines

**Good descriptions:**
```markdown
- [SPOC-M Validator](https://example.com) - CLI tool for validating SPOC-M knowledge representations against the canonical schema with detailed error reporting.
- [K-Cycle Tutorial](https://example.com) - Step-by-step guide to implementing the Knowledge Cycle with Python examples and best practices.
```

**Bad descriptions:**
```markdown
- [My Tool](https://example.com) - A tool for WEKAOU. (Too vague)
- [Amazing Resource](https://example.com) - The best WEKAOU tutorial ever created! (Exaggerated)
- [Resource](https://example.com) (No description)
```

### Description Length

- **Ideal**: 10-25 words
- **Maximum**: 40 words
- **Minimum**: 5 words

### Alphabetical Order

Within each section, maintain alphabetical order by resource name.

### Badges

Only official badges are allowed:

- ✅ Awesome badge (already in README)
- ✅ License badges (if relevant to the resource itself)
- ✅ Build status (for tools/implementations)

Do not add promotional badges like "stars", "downloads", or "trending".

---

## Review Process

### Review Timeline

- **Initial review**: Within 7 days
- **Revisions**: Within 3 days after feedback
- **Final decision**: Within 14 days of submission

### Review Criteria

Maintainers will evaluate:

1. **Quality**: Does it meet our standards?
2. **Relevance**: Is it valuable to the community?
3. **Formatting**: Does it follow guidelines?
4. **Accuracy**: Is the description accurate?
5. **Uniqueness**: Is it already listed?

### Possible Outcomes

- ✅ **Approved**: Merged immediately
- 🔄 **Revision requested**: Address feedback and resubmit
- ❌ **Declined**: Doesn't meet standards (with explanation)

### After Approval

- Your resource is added to the list
- You're acknowledged in the contributors section
- The community can discover and use your resource

---

## Questions?

- **General questions**: [Open a discussion](https://github.com/zaste/wekaou-community/discussions)
- **Technical issues**: [Open an issue](https://github.com/zaste/wekaou-awesome-wekaou/issues)
- **Governance**: See [WEKAOU Governance](https://github.com/zaste/wekaou-governance)

---

## Code of Conduct

This project follows the WEKAOU [Code of Conduct](https://github.com/zaste/wekaou-.github/blob/main/CODE_OF_CONDUCT.md). By participating, you agree to uphold this code.

---

## License

By contributing to this list, you agree that your contributions will be licensed under the same [CC BY 4.0](../LICENSE) license that covers the project.

---

Thank you for helping make the WEKAOU ecosystem more accessible and discoverable! 🎉
