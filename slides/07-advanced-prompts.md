# For the Techies: Advanced Prompting 

[Back to main README](../README.md) | [Previous](06-gemini-guide.md) | [Next: Resources](08-resources.md)

---

## Switching Gears

We've been romantic. Now let's get technical.

These techniques are for code generation, reviews, and automation workflows.

---

## Technique 1: Negative Constraints

**Instead of just saying what to do, say what NOT to do.**

\\\xml
<epistemic_standards>
- If unsure about syntax, APIs, or edge cases - say so explicitly
- If you don't know, say 'I don't know' - never fabricate
</epistemic_standards>
\\\

**Why:** Reduces hallucinations. The AI won't make things up.

---

## Technique 2: Force Chain-of-Thought

**Don't ask for an answer. Make it show its work first.**

\\\xml
<understand_before_changing>
- Before modifying, explain what the existing code does
- Trace data flow: origin -> propagation -> consumption
- If code seems odd, investigate before removing
</understand_before_changing>
\\\

**Why:** Forces the model to reason through problems, catching errors early.

---

## Technique 3: Structured XML Output

**Use XML tags for ~98% compliance (vs ~70% for freeform).**

\\\xml
<validation_mode>
  <review_checklist>
    <correctness>Does this solve the problem?</correctness>
    <impact_analysis>What could break?</impact_analysis>
    <security>Any vulnerabilities?</security>
  </review_checklist>
</validation_mode>
\\\

**Why:** Parseable output, consistent structure, easier automation.

---

## How to Choose XML Tags

**There's no global standard.** Use semantic tags that match your domain:

| Purpose | Tag Examples |
|---------|-------------|
| **Instructions** | \<task>\, \<code_review>\, \<analysis>\ |
| **Context** | \<codebase_info>\, \<requirements>\ |
| **Output** | \<summary>\, \<issues>\, \<recommendations>\ |
| **Constraints** | \<rules>\, \<style_guide>\, \<security>\ |

*Pick names that are clear and self-documenting.*

---

## Real-World Workflow

**Request Prompt:** Sets the rules for how the AI should code
**Review Prompt:** Structured checklist for PR-readiness

Both use XML for structure and negative constraints to prevent hallucination.

*See the \prompts/\ folder for our actual production prompts.*

---

## Model Comparison

| Model | XML Compliance | Best For |
|-------|----------------|----------|
| **Claude** | ~98% | Structured analysis |
| **GPT-4** | ~95% | Complex reasoning |
| **Gemini** | ~90% | Creative + structured |

---

## Learn More

- [Prompt Engineering Deep Dive (YouTube)](https://www.youtube.com/watch?v=0XoXNG65rfg)
- [Structured Output Patterns (YouTube)](https://www.youtube.com/watch?v=LsQGilvXAfE)

---

## Quick Summary

1. **Negative constraints** reduce hallucinations
2. **Chain-of-thought forcing** catches errors early
3. **XML structure** gets ~98% compliance
4. **Semantic tags** make prompts self-documenting

*These techniques level up your AI coding workflows.*
