https://github.com/user-attachments/assets/fe154908-3b17-4a53-b0b0-ad72122c24d0

<h1 align="center">Term Radar</h1>

<p align="center">
  A tiny skill that quietly surfaces relevant terms of art as you work with agents, growing your domain vocabulary over time so you can express your intent more precisely.
</p>

---

## How it works

Every professional domain has many established terms of art that compress lengthy descriptions into a short, clear concept.

For example:

```markdown
practical knowledge that people can use but struggle to articulate explicitly → **tacit knowledge**
```

This skill identifies these concepts in your prompts and adds the relevant term below the agent's response. That way, you naturally learn the established vocabulary for concepts you already describe in your own words.

Output example:

```markdown
[agent response...]

---

Term radar: [**Idempotency**](https://www.google.com/search?tbm=isch&q=Idempotency+%28software+engineering%29)
```

## Installation

```sh
npx skills add sidkh/term-radar
```
