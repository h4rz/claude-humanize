# humanize

A Claude Code skill that rewrites AI-generated text so it reads like a real person wrote it — and teaches you the patterns as it goes.

Tuned for the writing where AI detection actually matters: self-evaluations, cover letters, I-983 / OPT forms, application essays, blog posts, and personal statements.

## What makes this different

Most humanizer skills just rewrite. This one:

- **Calibrates for context** — different formality presets for self-evals, cover letters, essays, blog posts, and casual messages
- **Teaches as it rewrites** — every output ends with 5–8 specific changes and *why*, so you internalize the patterns and need the skill less over time
- **Catches 16 named detector traps** plus a formatting-tells section (em dashes, mechanical bold, decorative emojis, curly quotes, title-case headings, inline-header bullets)
- **Optional voice-matching** — paste a sample of your own previous writing and the rewrite mirrors your real voice instead of a generic one
- **Strict self-audit pass** — the model counts em dashes, parallel lists, and buzzwords on its own output before delivering

## Install

```
/plugin marketplace add h4rz/claude-humanize
/plugin install humanize@claude-humanize
```

Then in any session: `/humanize` and paste the text you want rewritten.

## Example

See [`examples/`](./examples/) for before-and-after samples.

## Intended use

This skill is for writing **you actually wrote yourself** that just sounds robotic — usually because you cleaned it up too much, or used AI as a first draft. Real use cases:

- Your I-983 self-evaluation reads like a press release
- Your cover letter is technically correct but soulless
- Your blog post got flagged by GPTZero even though you wrote it
- Your essay sounds like it's "trying too hard"

## Not intended use

Do not use this to launder fully AI-generated submissions where AI assistance is forbidden or must be disclosed. That includes:

- Academic submissions where AI is prohibited
- Job applications where AI assistance is prohibited
- Any context where you'd be expected to disclose AI use

The point is making *your own* writing sound less robotic, not pretending AI output is yours.

## How it works

The skill applies these in order:

1. Asks you for context (self-eval, cover letter, blog post, etc.) — tunes formality
2. Optional: takes a sample of your previous writing for voice matching
3. Rewrites applying 16 named detector traps + 6 formatting-tell rules + tone calibration
4. Self-audits: counts em dashes, parallel lists, buzzwords. Revises if any are present
5. Lists the specific changes it made and why

## Credits

Some patterns drawn from [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), maintained by WikiProject AI Cleanup.

## License

[MIT](./LICENSE)
