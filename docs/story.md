# Story

A case can **tell itself**. Story turns an investigation into a sequence of chapters — what was observed, the pattern, the question, possible explanations, the evidence needed, the next step, the current conclusion — while the case's network is directed on screen chapter by chapter. Status: `WORKING`.

![Story](../media/screenshots/06-story.png)

<sub>Real screenshot, v0.1.0. Chapter 1 of 7, narrated voice off.</sub>

- **Lengths** — short (≈1 min), brief (≈3 min), detailed (≈9 min).
- **Languages** — Russian, Latvian, English; a saved telling is rendered in each language from the same underlying plan.
- **Only confirmed** — an option to tell only what is directly supported, leaving partial links as traces rather than facts.
- **Versions** — tellings are saved as versions (12 in v0.1.0); when the case has changed since a telling was made, the telling says so. All saved versions are currently marked out of date.

## Assembled, not invented
The structure of every telling comes from the case's own records; 11 of the 12 saved versions contain no model wording. A language model may optionally help with wording inside that structure, and its sentences are checked against the plan's figures and claim counts.

## Traceability — in development
Chapters can carry links to the claims they tell. **Not every chapter has them yet:** 9 of the 12 saved versions have no chapter-level claim links, and some were planned from labelled model hypotheses. Linking every chapter to its claims (or refusing to tell an unlinked chapter) is in development — status `BETA`.

## Voice
Narration is optional: a browser voice (free), a local voice model (`PROTOTYPE`, needs a local worker), or a hosted voice service that is paid and used only after explicit confirmation. Voice is `BETA`. Known issue: choosing the browser voice also asks the server for a cached hosted-voice recording.

Details: [FEATURE_STATUS.md](FEATURE_STATUS.md#story-and-voice).
