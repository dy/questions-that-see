---
name: readiness
version: 1.0.0
description: Assess project completeness - Truth, Users, Developers, Agents, Ecosystem
disable-model-invocation: true
argument-hint: "[optional-output-file.md]"
---

# Project Readiness

Evaluate whether this project has reached its complete form - ready to offer to the world.

**Priority of constituencies** (adapted from W3C):
> Truth > Users > Developers > Agents > Ecosystem

**Ready when**: Adding more would make it worse. Removing anything would make it incomplete.

---

## 1. Truth

*The project's reason to exist and integrity of its form.*

1. **What exact pain does this heal?** — Can you state it in one sentence?
2. **Is it honest?** — Does it claim only what it delivers? No inflated promises?
3. **Is it complete?** — Nothing half-done? Nothing excess? Every feature finished?
4. **Will it last?** — Built on stable foundations? Minimal dependencies? Clear boundaries?
5. **Is it elegant?** — Simple core? Complex only where necessary?

---

## 2. Users

*Can someone use this successfully without help?*

1. **Can they start in 5 minutes?** — Install, run example, see it work?
2. **Does it do what it promises?** — Core functionality works as documented?
3. **Do errors help them recover?** — When things fail, do they know why and what to do?
4. **Are defaults sensible?** — Works well without configuration?

---

## 3. Developers

*Can someone contribute without asking questions?*

1. **Can they find things?** — File structure intuitive? Architecture discoverable?
2. **Can they understand the code?** — Readable? Functions do what names suggest?
3. **Can they verify changes?** — Tests exist, pass, give confidence?
4. **Is everything in the repo?** — No hidden knowledge in maintainer's head?

---

## 4. Agents

*Can AI complete tasks here autonomously?*

1. **Are instructions clear?** — README or AGENTS.md sufficient to understand the project?
2. **Is feedback fast?** — Lint/test/build under 2 minutes?
3. **Are patterns consistent?** — Similar problems solved similarly?
4. **Is the code self-documenting?** — Structure reveals intent?

---

## 5. Ecosystem

*Does it play well with its environment?*

1. **Does it follow conventions?** — Standard patterns for the language/framework?
2. **Does it integrate cleanly?** — Works with common tools? Composable?
3. **Is the environment clear?** — Runtime requirements documented? Platform constraints known?
4. **Is metadata complete?** — Package info, license, version present?

---

## Output

```
# Readiness: [Project Name]
**Date**: [date] | **Type**: [library/CLI/app/etc.]
**Verdict**: [Ready / Nearly Ready / Needs Work / Early Stage]

| Pillar | Verdict | Key Finding |
|--------|---------|-------------|
| Truth | | |
| Users | | |
| Developers | | |
| Agents | | |
| Ecosystem | | |
```

### The Hard Questions

1. What pain does this actually heal?
2. What would a harsh critic see in 5 seconds?
3. What are you avoiding or hiding from?
4. What removal would improve everything?
5. Is this ready to offer to the world?

### What's Blocking

- **Critical** — Fails core purpose
- **Important** — Hurts usability/quality significantly
- **Minor** — Polish, nice-to-have

### Next Steps

2-3 specific actions that would move toward Ready.

---

## Instructions

1. Read: README, manifest, main entry, docs
2. Run: Install, examples, tests
3. Explore: Code structure, patterns
4. Probe: Edge cases, error messages
5. Reflect: Answer the hard questions honestly

**Be honest, not kind.** A false "Ready" helps no one.

If $ARGUMENTS provided, save report to that path.
