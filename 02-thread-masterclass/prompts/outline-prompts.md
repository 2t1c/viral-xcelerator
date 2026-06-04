# Outline Prompts (Transcript → Outline)

## 1) Detailed Outline with Placeholders
Use after pasting a full thread transcript.

```
Transform the transcript below into a beginner-friendly detailed outline with placeholders, ready to fill.

1. Preserve the original order and message.
2. Extract a clean story arc using plain labels: Hook, Start + Goal, What worked (1), What worked (2), What changed, First move, Next move, Problem #1–#3 (add #4–#6 only if clearly present), Lessons, Where else this shows up, CTA.
3. Write one tweet per code block, with double line spacing between sentences.
4. Use simple sentences, 6th-grade reading level, no jargon.
5. Insert curly-brace placeholders like {subject}, {year}, {metric}, {example} wherever facts are specific.
6. Do not invent facts. If something is missing, leave a placeholder.
7. Keep each tweet under 280 characters where possible.

Transcript: {{TRANSCRIPT_GOES_HERE}}
```

## 2) Rough Outline (skeleton only)
Use when you just want headers first.

```
From the transcript below, output a single code block listing main tweet headers only (no body), one line per tweet, in order. Don't invent sections not implied by the transcript; if one is missing, still include the header.

T0 — HOOK
T1 — START + GOAL
T2 — WHAT WORKED (1)
T3 — WHAT WORKED (2)
T4 — WHAT CHANGED
T5 — FIRST MOVE
T6 — NEXT MOVE
T7 — PROBLEM #1
T8 — PROBLEM #2
T9 — PROBLEM #3
T10 — LESSONS
T11 — WHERE ELSE THIS SHOWS UP
T12 — CTA

Transcript: {{TRANSCRIPT_GOES_HERE}}
```

## Structure 3 skeleton (Bold Claim / Quote — recommended)
```
T0 — HOOK
T1 — WHO IS {X}?
T2 — THE PREDICTION / BIG IDEA / BIG QUESTION
T3–T7 — IDEA 1 through IDEA 5
T8 — WHY THIS MATTERS
T9 — PROBLEM STATEMENT
T10 — OUR MODEL / SOLUTION
T11 — WHY IT'S BETTER
T12 — AUTHOR INTRO
T13 — FOLLOW / CTA
```
