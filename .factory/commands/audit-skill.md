---
description: Audit skill for YAML compliance, pure XML structure, progressive disclosure, and best practices
argument-hint: <skill-path>
---

<objective>
Invoke the skill-auditor droid to audit the skill at $ARGUMENTS for compliance with Agent Skills best practices.

This ensures skills follow proper structure (pure XML, required tags, progressive disclosure) and effectiveness patterns.
</objective>

<process>
1. Invoke skill-auditor droid
2. Pass skill path: $ARGUMENTS
3. Droid will read updated best practices (including pure XML structure requirements)
4. Droid evaluates XML structure quality, required/conditional tags, anti-patterns
5. Review detailed findings with file:line locations, compliance scores, and recommendations
</process>

<success_criteria>
- Droid invoked successfully
- Arguments passed correctly to droid
- Audit includes XML structure evaluation
</success_criteria>
