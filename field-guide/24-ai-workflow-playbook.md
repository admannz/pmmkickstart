# 3.4 The AI Workflow Playbook

The previous sections covered the philosophy of Humans + AI and what AI can and can't do. This section is the practical version. Specific workflows, real prompts, actual patterns that work.

Not every workflow here will apply to your situation right now. Pick the one or two that would have the most immediate impact on work you're doing today, and start there.

## Workflow 1: Context File Setup

Everything else depends on this. Your AI is only as good as the context you give it.

Build a Markdown file (CLAUDE.md, or the equivalent for your tool) that captures: who you are, your ICP and personas, your messaging framework, your brand voice and rules, and your standing instructions. See section 4.4 for the full guide on building this.

Once this file exists and your AI can read it, you stop re-explaining yourself at the start of every prompt. Every draft it generates starts from your truth, not a generic approximation.

**The payoff:** This is the highest-leverage single investment in your AI workflow. Do it before anything else.

## Workflow 2: Messaging Stress-Test

You have messaging. You want to know where it falls apart before your buyers find out.

**The prompt:**
*"You are a skeptical [enterprise buyer / SMB owner / technical evaluator — pick your persona] evaluating [product category] for [use case]. I'm going to share our messaging framework. Your job is to interview it like a tough buyer would: push on the claims, identify the gaps, find the places where you'd object or disengage. Be honest, not kind."*

Then paste in your messaging.

What you get back won't all be actionable, but the pattern of objections it surfaces is consistently useful. The gaps it finds are almost always real.

**The human step:** Decide which gaps matter and which don't. AI finds the holes. You decide what to do about them.

## Workflow 3: Competitive Monitoring Digest

Set up a regular synthesis of competitive activity rather than doing manual research.

Feed AI a list of competitors and ask it to review their recent website changes, job postings, press releases, and review site updates. Ask it to summarise: what's new, what's changed in their messaging, and what this might signal strategically.

The prompt that works well: *"Here are [competitor names]. Based on what you know about their recent activity, what changes in messaging, positioning, or strategy are worth paying attention to? What signals suggest where they're investing or shifting focus?"*

**The human step:** Apply the "why now" question to everything it surfaces. A competitor changing their homepage headline is a data point. Understanding whether it's a strategic shift or a A/B test is judgment.

## Workflow 4: Win/Loss Synthesis

You have a set of call transcripts or notes from recent wins and losses. You want the themes without spending four hours in a spreadsheet.

**The prompt:**
*"Here are [N] notes from recent sales wins and losses. Synthesise the key themes: what were the most common reasons we won? What were the most common reasons we lost? What objections came up most frequently? What language did buyers use to describe the problem we solve? Organise by theme with supporting quotes."*

**The human step:** Validate the themes against your own read of the notes. AI is excellent at pattern matching. It occasionally invents patterns that aren't there, or misses subtext that a human reader would catch.

## Workflow 5: Content Transformation

You have one piece of long-form content — a whitepaper, a blog post, a recorded webinar transcript — and you need it in six formats.

**The prompt:**
*"Take this [content type] and transform it into the following formats, maintaining the key arguments and voice throughout: (1) a 500-word blog post, (2) a 3-email nurture sequence, (3) a LinkedIn post of 100-150 words, (4) five social proof pull-quotes, (5) a sales one-pager structured as problem/solution/proof, (6) five talking points for Sales to use in discovery calls."*

**The human step:** Review every output. The transformation usually loses nuance somewhere. Your job is to catch where the argument weakened or the voice drifted and fix it. But editing is always faster than creating from nothing.

## Workflow 6: Persona Interview Simulation

You've written a persona. You want to test whether your messaging actually resonates with that person.

**The prompt:**
*"You are [persona name]: [brief description of role, company size, primary challenge, what they care about, what they're afraid of]. I'm going to share some product messaging with you. Respond as this person would: tell me what lands, what doesn't, what questions you'd have, and what would make you want to learn more or walk away."*

This is the Humans + AI model at its most practical. The AI plays the skeptic; you decide what to do with the feedback.

## The Non-Negotiable Across All of These

Zero-Trust applies to every output from every workflow. The synthesis is a starting point, not a final answer. The draft is an input to your judgment, not a replacement for it. The competitive intelligence is a directional read, not a source of verified facts.

Read everything before it goes anywhere near a customer. The PMM is the last line of defense.
