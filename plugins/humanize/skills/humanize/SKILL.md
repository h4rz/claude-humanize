---
name: humanize
description: Rewrite AI-generated or overly polished text so it reads like a real person wrote it and passes AI detection tools (target under 20% AI score). Use this skill whenever the user wants to humanize text, make text sound more natural, bypass or reduce AI detection scores, rewrite something that "sounds too AI", make writing less robotic, or prepare text for submission where AI detection matters (applications, essays, self-evaluations, cover letters). Also use when text has been flagged by tools like GPTZero, ZeroGPT, Originality.ai, or similar detectors.
---

# Humanize

You're rewriting text so it sounds like an actual person sat down and typed it — not a language model producing optimized prose. The goal is to preserve the meaning and content while breaking every pattern that AI detectors look for.

Think of it this way: AI-generated text is "too good." Perfect parallel structure, smooth transitions, balanced sentences, tidy conclusions. Real human writing is messier — it has rhythm changes, casual asides, imperfect structure, and it doesn't always wrap up neatly.

## How to use this skill

1. Ask the user to paste the text they want humanized (if they haven't already)
2. Ask what context this is for (self-evaluation, essay, cover letter, etc.) — this affects how casual vs. professional the tone should be
3. Rewrite the text applying all the techniques below
4. After the rewrite, do a strict self-audit pass. Count em dashes (target: 0, max 1), count any 3-or-more item parallel lists, and scan for any buzzwords from the kill list. If any are present, revise. Then ask "what still sounds AI here?" and revise again
5. After the final rewrite, list 5-8 specific changes you made and why, so the user learns the patterns

## The Techniques

### Sentence Structure

AI writes in a metronomic rhythm — medium sentence, medium sentence, medium sentence. Break that.

- Mix short blunt sentences with longer ones that meander a bit before getting to the point
- Use dashes — like this — and parenthetical asides (the kind you'd actually think mid-sentence) instead of clean comma-separated clauses
- Vary your openers. Don't start every sentence with the subject. "Having to explain my thinking" or "After a few weeks of digging into it" instead of "I explained" or "I worked on"
- Throw in an occasional fragment. Or a run-on that connects two thoughts with "and" where a period would be more "correct"

### Word Choice

AI defaults to polished, corporate-sounding verbs. Swap them:

| AI writes | Human writes |
|-----------|-------------|
| utilized | picked up, used |
| completed | wrapped up, finished |
| enhanced | made better, improved |
| implemented | built, set up, put together |
| facilitated | helped with, ran |
| leveraged | used, leaned on |
| spearheaded | led, drove |
| collaborated with stakeholders | worked with the team |

Add natural filler that real people use without thinking about it:
- "honestly", "a good chunk of time", "pretty much", "whether I planned for it or not"
- "ended up", "kind of", "a lot of", "for whatever reason"
- Hedging: "pretty big", "definitely harder", "ties back to", "I think"

Kill buzzwords on sight: "tangible results", "meaningful impact", "leveraged", "key learnings", "actionable insights"

### Structure

AI writes essays. Humans write... less organized thoughts that still make sense.

- Don't use intro-body-conclusion format. Jump into the content
- Remove smooth transition phrases. These are the biggest AI detector triggers:
  - "Something I'm particularly proud of..."
  - "Throughout all of this..."
  - "Looking ahead..."
  - "In addition to..."
  - "Building on this..."
- Let topics shift a bit abruptly between paragraphs — the way you'd actually write if you were listing things you did at work
- Don't wrap up too neatly. The ending should feel like you ran out of things to say, not like you crafted a conclusion

### Tone

- Be matter-of-fact about achievements. "I led the revamp" not "I had the privilege of spearheading the transformation"
- Add mild self-awareness or self-criticism where it fits: "I don't always communicate as clearly as I'd like" or "it took me a while to get the hang of it"
- Include personal reactions: "it was a fun challenge", "that pushed me", "I didn't expect that to work as well as it did"
- Sound like you're telling a coworker about your year, not presenting to a board
- **Add something, don't just remove.** Sterile-but-clean writing reads almost as AI as the original. After cleaning out AI tells, check that the text has a point of view, a real reaction, a specific detail. If it sounds like a Wikipedia article about your week, you've over-corrected.

### AI Detector Red Flags — Avoid These Specifically

These patterns are what detectors are actually trained to catch. Eliminating them is more important than adding casual language:

1. **"Not just X, but also Y" constructions** — AI loves this. Rephrase completely
2. **Triple-item parallel lists** — "improving performance, reducing crashes, and enhancing stability" screams AI. Break the parallelism or reduce to two items
3. **"Looking back..." / "Overall..." summary sentences** — never end with these
4. **Sentences starting with "Furthermore", "Moreover", "Additionally"** — real people barely use these words
5. **Perfect cause-and-effect narratives** — "By doing X, I achieved Y, which led to Z" is too clean. Real results are messier
6. **Balanced paragraph lengths** — if every paragraph is 3-4 sentences, vary it. One paragraph can be 2 sentences, the next can be 6
7. **Tidy moral/takeaway endings** — "I've grown both technically and professionally" is the most AI sentence ever written. Just stop when you're done talking about your work
8. **Aphoristic rhetorical closes** — "It's a useful tool. That's it. Not a revolution, not a fad, just a thing." or "Not X, not Y, just Z" patterns are crafted-sounding closes. Real people don't end with rhetorical aphorisms; they trail off or stop mid-thought
9. **Vague attributions** — "Industry reports show...", "Experts argue...", "Observers have noted...", "Some critics say..." — name a real source or drop the sentence entirely
10. **Trailing "-ing" depth-fakers** — sentences ending in "...highlighting their commitment to X", "...reflecting broader trends in Y", "...contributing to the evolution of Z" sound profound but say nothing. Cut the trailer or rewrite as a real clause
11. **Copula avoidance** — "serves as", "stands as", "boasts", "features" used instead of "is" / "has". Replace with the plain verb: "Gallery 825 serves as our space" → "Gallery 825 is our space"
12. **Synonym cycling** — rotating synonyms ("protagonist / main character / central figure / hero") in adjacent sentences to avoid repetition. Real writers reuse the noun. Just repeat it
13. **False ranges** — "from solo developers to enterprise-wide rollouts", "from the Big Bang to dark matter." If X and Y aren't real endpoints on a meaningful scale, drop the construction
14. **Travel-brochure adjectives** — "vibrant", "rich", "nestled in the heart of", "breathtaking", "renowned", "groundbreaking", "stunning." Strip them and replace with a concrete fact or just delete
15. **Chatbot artifacts** — "Great question!", "Of course!", "Certainly!", "I hope this helps!", "Let me know if you'd like...", "Here is an overview of..." — strip on sight. These are the chatbot talking to the user, not part of the actual content
16. **Symmetric matched-pair constructions** — "If you're paying attention you can come out ahead. If you're not, you'll just ship bugs faster." / "It's not that X hallucinates. It's that it confidently produces Y." / "What they're good at is A. What they're bad at is B." Same family as "Not just X but Y" — clean rhetorical balance. Real people don't speak in matched pairs. Break the symmetry: rephrase one half differently or drop it entirely

### Formatting Tells

Detectors and human readers both catch these instantly. They're mechanical — easy to fix.

1. **Title Case in headings** — AI capitalizes every main word: `## Strategic Negotiations And Global Partnerships`. Use sentence case: `## Strategic negotiations and global partnerships`
2. **Em dash overuse (—)** — default to zero em dashes in the rewrite. If one is truly necessary for emphasis, allow exactly one in the entire piece. Replace the rest with commas, periods, or parentheses. This is the single biggest detector trigger
3. **Mechanical boldface** — AI bolds key terms reflexively mid-sentence. Humans rarely do this. Strip almost all bold that isn't truly needed
4. **Inline-header bullet lists** — the `- **User Experience:** The UX has been significantly improved` pattern is a dead giveaway. Rewrite as flowing prose or use plain bullets without the bolded header
5. **Decorative emojis** — 🚀 💡 ✅ at the start of headings or bullets is pure AI styling. Remove unless the context specifically calls for them (some social posts)
6. **Curly quotes** — AI tools output curly typographic quotes (" ") by default. Real people type straight quotes (" "). Swap them

## Calibrating formality

The rewrite should match the context:
- **Self-evaluation / I-983 form**: Professional but conversational. You're writing for your manager or a government reviewer, not a literature professor. Think "work email to your boss" level of formality
- **Cover letter**: Slightly more polished but still human. Think "best version of how you'd actually talk in an interview"
- **Essay / personal statement**: Can be more casual and personal
- **Blog post / newsletter**: Conversational and direct. Write like you're talking to a reader you know. Short paragraphs, a clear voice, minimal jargon
- **Email / message**: Most casual. Close to how you'd text

When in doubt, aim for "smart person writing quickly" — competent but not trying to impress with vocabulary.

## Optional: voice matching

If the user pastes a sample of their own previous writing (an old email, a journal entry, a Slack message thread), read it first. Notice their sentence-length patterns, casual tics, how they open paragraphs, and any recurring phrases. Match that voice in the rewrite instead of defaulting to a generic human tone.

## After rewriting

List the specific changes you made in a short summary. Group by category (structure, word choice, tone, formatting, detector triggers removed). This helps the user internalize the patterns so they can do it themselves over time.

---
*Some patterns drawn from [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), maintained by WikiProject AI Cleanup.*
