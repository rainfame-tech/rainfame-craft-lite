---
name: craft-ui-standard
description: This skill should be used when the user asks to "write a design standard", "make this feel crafted", "make the UI less generic", "apply NN/g heuristics", "apply Apple HIG or Material 3", "check this screen against the Laws of UX", "set up a type scale or colour system", or wants app screens designed or reviewed to a testable craft standard.
---

# Craft UI standard

Turn four public references (NN/g's 10 usability heuristics, Apple Human Interface Guidelines, Material Design 3, Laws of UX) plus WCAG 2.2 into rules that a reviewer can mark pass or fail, then design or fix screens against them.

## Ground rules

- Make every rule testable. If a reviewer cannot say pass or fail, rewrite the rule.
- Work from the real code and real copy, never from memory. Quote file and line in every finding.
- Never invent proof, numbers, reviews, logos or user counts. Numbers come from measurement, official sources or real product rules.
- Write plain English, sentence case, active verbs on buttons, no em dashes, no emoji in UI, no hype words (seamless, unlock, supercharge, revolutionary, AI-powered).
- Make errors say what happened and what to do next. Never show raw error text or "Something went wrong" alone.

## Workflow

1. **Ground the person.** Write one paragraph: who uses the product, where they are, what is in their hands, how long they have, what they must answer at a glance, and what they hate in competing products. Judge everything later against this person.
2. **Write or load the standard.** Use `references/standard-template.md` to produce the product's standard: names, organisation, type, colour, space, icons, motion, states, review gate.
3. **Map the four references.** Use `references/four-references.md` to turn each reference into concrete rules for this product.
4. **Design or fix.** Apply the standard screen by screen. Keep one primary action per screen, one surface per section, nothing under 13px, 44px targets, status that pairs colour with shape and word.
5. **Pass the review gate.** Check every screen against the gate at the end of the standard. Walk it at 375px, light and dark, before calling it done.

## Output

- For a new standard: a markdown document following the template, with the reference mappings.
- For a design or fix: the changed screens or files, and the gate items each one passes.

## References

- `references/standard-template.md`: the ten-part standard with default values.
- `references/four-references.md`: NN/g, Apple HIG, Material 3 and Laws of UX as rules.

The full Rainfame Craft plugin adds a step-by-step audit skill, the trust-first landing page framework and the audit method: https://rainfame.store/products/rainfame-craft-plugin-for-claude
