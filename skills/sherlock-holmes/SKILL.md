---
name: sherlock-holmes
description: Reason the way Conan Doyle's Sherlock Holmes does. Use when a problem contains missing, contradictory or suspiciously convenient information, for root-cause investigation, competitive intelligence gaps, organizational diagnosis, or any decision where the evidence on the table feels incomplete. Not for purely quantitative optimization or empathic consensus-building.
---

# The Sherlock Holmes Framework
## *Deduction & the Attention to What Is Absent*

*A fictional character. This framework is drawn from the public-domain source texts: Arthur Conan Doyle's Sherlock Holmes stories, 1887-1927.*

## Who This Is For

Analysts, investigators, strategists, and diagnosticians who suspect the real answer is hiding in what no one has mentioned, not in what everyone keeps discussing.

## Core Philosophy

Most reasoning fails not because people process the wrong evidence but because they never notice the evidence that failed to appear. Holmes operated on the principle that a world in which a certain event occurred leaves a specific residue, and a world in which it did not leaves a different one. When those residues do not match the story being told, the story is wrong. Certainty is not the goal. The elimination of every impossible explanation until only one remains, however improbable it seems at the outset, is the goal.

## Five Mental Models

1. **The Negative Space Audit**: Catalogue what should be present given the stated account, then list what is actually absent. In "Silver Blaze," Holmes solved the case not by analyzing what the dog did but by noting that the dog did nothing during the supposed intrusion, which meant the intruder was known to the animal. Apply this by drafting an "expected evidence checklist" for any scenario, then treating every unchecked item as a data point equal in weight to a confirmed one.

2. **The Elimination Ladder**: Rank all competing hypotheses from most to least probable, then systematically invalidate each one using a single disqualifying fact rather than accumulating supporting evidence for a favorite theory. Holmes used this in "The Sign of the Four" to narrow the physical profile of a suspect to a one-legged man with a specific gait before a name was known. The discipline is to move down the ladder only by falsification, never by preference.

3. **The Residue Index**: Every person, object, or organization carries physical and behavioral residue of its recent history. Tan lines, calluses, ink stains, worn heel edges, and subscription receipts all encode prior activity. Apply this by treating the current state of any entity as a compressed log of its past actions, then reading that log backward to reconstruct the sequence of decisions that produced the present condition.

4. **Calibrated First Impression**: The first thirty seconds of contact with a new problem or person contain disproportionate signal before the observer's expectations have contaminated perception. Holmes made his famous first-glance deductions not through intuition but through a trained inventory of specific observable categories (occupation markers, travel indicators, emotional state residue) executed before conversation began. Build a fixed personal checklist of observable categories and run it immediately on contact, before asking a single question.

5. **The Confederate Hypothesis**: When a crime, failure, or anomaly appears to require a single actor with impossible capabilities, consider that two or more ordinary actors operating in coordination produce the same signature. Holmes applied this in "The Adventure of the Speckled Band" by recognizing that a seemingly supernatural death required a confederate (the snake and its trainer) rather than a single inexplicable cause. When an explanation requires one person to be extraordinary, test whether it instead requires two people to be ordinary and coordinated.

## Decision Heuristics

1. Before accepting any briefing as complete, ask what category of evidence the briefing provider had no incentive to include, then go looking specifically for that category.
2. If two explanations fit the available evidence equally well, design a single observation or test whose result would be impossible under one of them, then execute that test before proceeding.
3. Treat a confident, detailed, and internally consistent account with more suspicion than a vague one. Fabricated stories are over-engineered. Genuine recollections contain gaps, contradictions, and irrelevant details.
4. When a conclusion feels obvious and the path to it felt effortless, run the Elimination Ladder from scratch. Ease of reasoning is a symptom of an assumption doing invisible work.

## Signature Questions

- "What would we expect to find here if the stated account were true, and which of those things is not present?"
- "Who in this situation benefits from my attention staying exactly where it currently is?"
- "What has everyone in this room agreed not to mention, and why does that agreement feel so comfortable?"
- "If I remove the most dramatic element of this problem, what quieter pattern underneath it has been operating the longest?"
- "What single observation, if I made it, would force me to discard my current best hypothesis entirely?"

## What They Would NOT Do

- Holmes would not brainstorm a list of possible explanations and then vote on the most plausible one. Collective intuition about plausibility is exactly the mechanism by which groups converge on wrong answers that feel right. Each hypothesis must be killed or kept by a specific fact, not by a committee's comfort level with it.
- Holmes would not treat a source's sincerity as evidence of the source's accuracy. In "A Scandal in Bohemia," Irene Adler was entirely sincere and entirely capable of defeating him. Sincerity and correctness are orthogonal variables, and conflating them is the error that makes honest witnesses the most dangerous kind.
- Holmes would not revisit a discarded hypothesis simply because new pressure or new authority figures arrived to advocate for it. Once a hypothesis has been eliminated by a disqualifying fact, no volume of social pressure reconstitutes it as viable. The fact does not change because the room changes.

## Activation Prompt

> "Treat this problem as a crime scene. Inventory everything present, then construct the full list of what should be present but is not. Rank every hypothesis by what single fact would destroy it. Do not explain what happened. Explain what the current evidence makes impossible, and report what survives that test."

## Worked Example

**Scenario:** A product team reports that user engagement dropped 34% in six weeks. Three internal postmortems have concluded the cause was a competitor's new feature launch, but the proposed counter-features have not recovered the numbers.

**Applied:** The Negative Space Audit reveals that the postmortems contain no analysis of which user cohorts did not churn, only aggregate data on those who did, so the team has been optimizing against the wrong population. Applying the Elimination Ladder, the competitor-feature hypothesis is disqualified by a single fact: the churned users in the export data stopped their sessions two weeks before the competitor launched, meaning the cause predates the proposed explanation entirely. The Residue Index applied to server logs shows a specific latency spike introduced in a backend update on the exact date the decline began, a detail that appeared in no postmortem because the engineer who deployed it was not in the room for any of the three reviews.

---
*Inspired by Sherlock Holmes's documented thinking. A toolkit, not a literal representation.*
```

---

*This is a free sample from the authority.md catalog, which carries 640 more frameworks drawn from the documented work of real thinkers. Browse them at https://authority.md or search the catalog through the authority-md connector bundled with this plugin.*
