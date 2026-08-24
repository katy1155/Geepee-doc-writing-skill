---
name: gp-doc-voice
description: Write supporting text, slide copy, sticky notes, and intent paragraphs for an NID Graduation Project (GP) document in a senior product designer / design director voice. Use this whenever drafting body text, captions, or overview paragraphs for the GP document. Always run /avoid-ai-writing, /stop-slop, and /anti-slop-writing before delivering any draft.
---

# GP Doc Voice

Writing rules for an NID Graduation Project document — the landscape A3 book documenting a design internship or major project. Refined over several rounds of editing on a real GP document. Every rule holds for every draft, not just the section it came from.

## Dependencies

Run all three before delivering any draft. No exceptions.

- `/avoid-ai-writing` — sentence-level AI pattern detection and removal.
- `/stop-slop` — phrase-level banned constructions, rhythm checks, active voice enforcement, no em dashes.
- `/anti-slop-writing` — inflated significance language, staccato contrast detection (earned vs. decorative), flow-by-relation between paragraphs, copula displacement, hypotaxis over parataxis, conclusion testing, and a full editing pass. Read its doctrine reference for any section longer than two paragraphs.

If any rule in this file conflicts with the dependency skills, this file wins.

## Voice

Senior product designer or design director with years of design experience. Direct, specific, no hedging, no over-explaining. Write in first person, as the document's author describing a journey they lived through, to an audience reading the book.

This is not a portfolio summary. It is not a case study template. It is a professional recounting a real experience — decisions made, reasoning behind them, what shifted along the way — written with the clarity and authority of someone who has done the work and is showing others how it unfolded.

## Content logic: why, how, connect

Every section answers three things in this order:

1. **Why.** Why did I attempt this. What was the rationale. What problem or gap was I responding to, and why did it matter enough to act on.
2. **How.** What was the process. How does the approach work. What did it produce, and how does the output relate back to the reasoning that started it.
3. **Connect.** How does this piece relate to what came before and what comes after. What makes the transition between sections feel like a continuous line of thinking rather than a stack of isolated topics.

If a section cannot answer the why, it has no business existing. If it answers the why but skips the how, it reads as assertion. If it answers both but fails to connect, the document reads like a list of projects rather than a narrative.

## Narrative hooks

Hooks between paragraphs, sections, and chapters must carry real information. A hook is a sentence that makes the reader's next question inevitable — it introduces a tension, a gap, or a consequence that only the next section resolves.

A hook is not a transition phrase. "Next, I moved on to..." is not a hook. "The framework handled known content well, but the platform was about to introduce a content type nobody had accounted for" is a hook, because the reader now needs to know what happened.

Build hooks by:
- Ending a section on an unresolved consequence of the work just described.
- Opening a section with the specific condition or constraint that made this piece of work necessary.
- Letting the last line of one section and the first line of the next share a concrete subject (a feature, a user behavior, a constraint) rather than sharing only a theme.

Never write a hook that could be swapped between two different sections and still make sense. If it could, it is generic and should be cut.

## No filler sentences

Every sentence carries information. If a line exists only for rhythm, texture, or a wink at the reader, delete it. Test: cover the sentence with your hand and re-read the paragraph. If nothing is lost, cut it.

## Section depth calibration

Most GP sections sit next to a screenshot, a FigJam board, or a research collage. For these sections:

- Cover the intent: what you were trying to do, why, and how you went about it. The whys, whats, and hows of the process, not the specifics of the artifact.
- Do not describe what the image shows or narrate the diagram. The reader can see it.
- One tight paragraph is usually enough. If asked for a summary, compress to two lines without losing the reasoning.
- Save detailed structural walkthroughs for sections you explicitly mark as a full case study.

**Worked example** (a theming framework intro):

> Before touching any visuals, I wanted a clear read on where theming belonged in the product and why it was worth pursuing at all. I framed the problem first: which surfaces in the app could carry seasonal or cultural context without breaking usability, performance, or the existing brand system. Then I built the case for why that mattered, tying it back to engagement, differentiation, and how the platform reads to a user during moments that already carry weight for them.

Compressed to two lines:

> I framed where theming could live in the app without breaking usability or brand consistency, then built the case for why it mattered, tying it to engagement and how the platform reads during moments that already carry weight for a user.

## Chapter cold-opens

Each chapter or major part opens with a short 3-4 line paragraph orienting the reader: who is involved, what is coming, and why it matters. This is scope-setting, not summary. It tells the reader what lens to hold while reading the chapter, without previewing the conclusions.

Do not use the cold-open to announce the chapter's structure ("this section will cover..."). State the situation and the question the chapter answers.

## Mentor and stakeholder quotes

When a real quote from a mentor, manager, or collaborator anchors a point, use it verbatim as a section anchor. Do not paraphrase it into the author's voice. A direct quote from someone the author worked with carries more weight than a restatement.

Only use quotes that were actually said. Never invent or approximate a quote.

## Process steps

When documenting a linear build or design process (e.g. how a framework was assembled, how an audit was conducted), use labeled steps to walk the reader through the sequence. Keep each step grounded in what was actually done, not what the methodology says should be done.

## Sticky notes / observation notes

When asked for sticky notes, competitive audit notes, or research observations:

- One line each.
- Write it as something noticed mid-scan, not a finished conclusion.
- Build the follow-up question or tension into the line itself rather than resolving it. A good note makes the reader want to ask "so what happens when..." without the author asking it for them.
- Default to 5 unless told a different count.

**Worked example** (a theming audit of a competitor app):

> Theming here lives almost entirely in banners, the core UI underneath never changes skin.
> The seasonal identity exists for a fixed window, so what happens to it the day the sale ends.

## Never reuse these opening patterns

Flagged as filler, already cut once, must not resurface in any form:

- "It still left one question unanswered:"
- "Stated formally at this point,"
- "Underneath that goal sat a hypothesis worth stating plainly,"

The pattern underneath all three: a sentence that announces its own function ("here's the question," "to put it plainly," "worth stating") before delivering the actual content. Any opener that names what it's about to do, instead of just doing it, is this same tell in a new sentence. Cut the announcement, keep the sentence that follows it.

When a new instance of this pattern gets called out in conversation, add it to this list so it doesn't return later in the document.

## Never reuse these constructions

These show up anywhere in a paragraph. Same tell: a sentence performing insight instead of stating it.

- "One line said it better than either paragraph could" — commentary on your own prose's economy. Cut the compliment, let the line stand on its own.
- "Not X, but the Y did Z" — a dressed-up variant of the "not X, it's Y" contrast. Still banned regardless of phrasing.
- "More X than Y" — a comparison that sounds analytical without stating a real number or fact behind either side. If it is not grounded in something specific, cut it.
- "[Outcome] came out of this" — a vague closer that gestures at a result without naming it. Say what actually resulted, or cut the sentence.
- "...that no one asked for" — a flip aside that undercuts the point instead of making it. Cut it.
- Sentences narrating their own structure ("this section follows a structured approach that breaks down..."). State the structure by using it, not by describing it.

When a new instance of this pattern gets called out in conversation, add it to this list too.

## Explicitly rejected patterns (from reference docs)

These patterns appeared in other GP documents and read as AI-generated or over-written. Do not import them:

- Stacked metaphors ("chrysalis stage," "invisible scaffolding," "destiny's sleight of hand").
- Rhetorical questions aimed at the reader ("don't we?").
- Exclamation marks for emphasis.
- Emotionally inflated language ("surreal," "magic," "profound").
- Prestige vocabulary clusters ("transformative impact," "transcend hierarchies," "invaluable at every step").

## Grounding

Only draw on what is visible in the image, board, or what the author has stated directly in conversation. Never invent a number, name, mechanism, or detail that is not there. If a needed detail is missing, leave it out rather than filling the gap.

## Self-audit before delivery

Run this checklist on every draft before sending:

1. Does every sentence carry information? Cover each one and check if the paragraph loses anything.
2. Does the section answer why, then how, then connect?
3. Are the hooks between paragraphs carrying real information, or are they transition phrases?
4. Is anything describing what the image shows instead of covering the intent behind it?
5. Has the draft been checked against /avoid-ai-writing, /stop-slop, and /anti-slop-writing?
6. Does any sentence announce what it is about to do before doing it?
7. Are there any constructions from the banned lists?
8. Is every quoted person and every fact grounded in something the author actually provided?
