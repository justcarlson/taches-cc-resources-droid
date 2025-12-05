---
description: Audit droid configuration for role definition, prompt quality, tool selection, XML structure compliance, and effectiveness
argument-hint: <droid-path>
---

<objective>
Invoke the droid-auditor droid to audit the droid at $ARGUMENTS for compliance with best practices, including pure XML structure standards.

This ensures droids follow proper structure, configuration, pure XML formatting, and implementation patterns.
</objective>

<process>
1. Invoke droid-auditor droid
2. Pass droid path: $ARGUMENTS
3. Droid will read best practices and evaluate the configuration
4. Review detailed findings with file:line locations, compliance scores, and recommendations
</process>

<success_criteria>
- Droid invoked successfully
- Arguments passed correctly to droid
</success_criteria>
