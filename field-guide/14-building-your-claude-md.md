# 4.4 Building Your AI Brief

In the Starter Kit, step one is to write your context files. This is that step, in full.

Most people who use AI for writing start every session from scratch. Set the context, explain who they are, what tone they want, who they're writing for, what they won't tolerate. Every ... Single ... Time.

There's a better way. A persistent Markdown file that lives in your project folder and tells your AI everything it needs to know before you've typed a single prompt. In Claude, it's called a `CLAUDE.md`. In GitHub Copilot, it's `.github/copilot-instructions.md`. In ChatGPT, it's a Project with attached context files. The name and format vary. The concept is the same.

For a PMM, this should feel embarrassingly natural. We spend our careers building baseline documents, defining audiences, and documenting tone and voice. This is the same muscle, pointed at your own work.

## What Goes In It

Eight sections, in order of importance.

**Who you are.** Not a bio, a brief. Your role, your context, the lens through which everything else should be interpreted. "I'm a PMM" is not useful. "I'm a PMM who has spent 15 years at technical B2B companies and now advises early-stage founders on their first product marketing hire" is.

**Your audience.** Treat it like an ICP document, because it is one. Named segments, what they already know, what they're trying to solve, what would make them stop reading versus lean in.

**What you cover (and don't).** Your topic territory, and the explicit boundary around it. The boundary matters as much as the content.

**Voice and style.** The most important section, and the one most people either skip or fill with vague adjectives. Be specific. What punctuation habits do you have? What do you never do? What words are banned? Vague adjectives produce vague output.

**Your POV on AI.** If you write about AI, document your actual philosophy. Not "AI is a tool," which is a non-take. Your real, specific position. This anchors the AI to your worldview rather than the default narrative in its training data.

**Recurring vocabulary and frameworks.** The terms and phrases that have become shorthand for things you believe. When the AI uses them naturally, the output sounds like you. When it doesn't, it sounds like a competent stranger attempting to mimic you.

**Content format specs.** If you produce content in more than one format, give each format its own rules. Length, structure, tone, what's forbidden, how it opens and closes. The AI cannot guess what "write me a LinkedIn post" means to you.

**Standing instructions.** The explicit assumptions you want carried into every writing request without being told. These become defaults.

## It's a Living Document

The first version will be imperfect. Write it anyway.

The workflow that compounds: whenever AI-generated output doesn't sound right and you make significant edits, ask whether those edits reveal something the AI didn't know about your style. If yes, add it to the file. Over time, the gap between first draft and final draft gets smaller. The AI gets smarter about you. You spend less time fixing.

## How to Build It

Use the prompt below, drop it into Claude, and let it interview you. One section at a time, 15-20 minutes.

```
I want to build a CLAUDE.md file to use as a persistent context brief for all my AI writing work. Please interview me to gather everything you need, one section at a time. Cover: who I am and my role, my audience and what they're trying to solve, the topics I write about (and don't), my voice and style including specific rules and things I won't do, my POV on AI if relevant to my work, any recurring terms or frameworks I use, the content formats I write in with specific rules for each, and any standing instructions I want applied to every writing request. Ask follow-up questions if my answers are vague. When we've covered everything, write the complete CLAUDE.md file in Markdown, ready to save.
```

If you're using Cowork, there's also a downloadable skill that runs the interview automatically. Find it at the full post linked below.

The first version is never the best version. It just needs to exist.

*Full post: [Build Your CLAUDE.md: A PMM's Persistent AI Brief &rarr;](/2026/04/21/building-your-claude-md/)*
