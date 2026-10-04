# The 16-Word Sales Letter

An agent skill for planning, writing, and reviewing sales letters and video sales letters using Evaldo Albuquerque's *The 16-Word Sales Letter*.

Extended with a supplied lecture, sales promotion, third-party breakdown, and partial sales-letter example.

## What it helps you do

- Define the selling belief connecting the reader's desire, the new opportunity, and the offer's mechanism.
- Build a sales argument around the book's ten questions.
- Integrate proof using And, But, Therefore.
- Explain the real obstacle, establish trust, and make the mechanism understandable.
- Build offers with clear pricing, useful bonuses, and accurate guarantee terms.
- Diagnose gaps in existing copy and propose specific repairs.

The skill includes chapter notes, practical procedures, and annotated examples. It distinguishes the book's teaching from Evaldo's lecture, observed copy, third-party interpretation, and new adaptations.

## Installation

Install with the Skills CLI:

```bash
npx skills add https://github.com/demianvalenzuela/the-16-word-sales-letter --skill the-16-word-sales-letter
```

The skill's identifier is `the-16-word-sales-letter`. Its display name is **The 16-Word Sales Letter**.

## Usage

Provide the audience, offer, available evidence, format, and intended action. Include existing copy when requesting a review.

Example prompts:

```text
Use $the-16-word-sales-letter to plan a sales letter.
First define the selling belief and identify missing evidence.
Then develop the argument around the ten questions.
```

```text
Use $the-16-word-sales-letter to review this VSL.
Identify unanswered questions, unsupported claims, and offer inconsistencies.
Propose specific revisions.
```

```text
Use $the-16-word-sales-letter to write a landing page
for a Spanish B2B audience. Write in Spanish from Spain.
Use only the evidence supplied in my brief.
```

Internal instructions and references are in English. The skill writes deliverables in the language requested for the audience.

## Contents

| File or folder | Purpose |
|---|---|
| `SKILL.md` | Main instructions, framework, and reference indexes |
| `chapters/` | Notes covering all 13 book chapters |
| `examples/` | Five references covering book examples, a promotion, a lecture, commentary, and a partial sales letter |
| `patterns.md` | Reusable planning and revision procedures |
| `cheatsheet.md` | Quick reference |
| `glossary.md` | Terminology and chapter pointers |
| `references/working-brief.md` | Briefing and review framework |
| `references/source-coverage.md` | Source coverage, attribution, and corrections |
| `references/source-manifest.json` | Source inventory |
| `agents/openai.yaml` | Agent interface metadata |

## Sources and attribution

Evaldo Albuquerque authored *The 16-Word Sales Letter*. This repository is an independent implementation of its methodology and is not affiliated with or endorsed by the author or publishers.

The repository contains synthesized notes and analytical examples. It does not include the complete book, full source promotions, or original recordings.

Source disagreements remain documented. Third-party commentary is identified separately, and examples without confirmed authorship are not attributed to Evaldo.

## Evidence and limitations

Revenue figures, performance claims, historical anecdotes, and scientific explanations in the sources have not been independently verified. The examples do not establish conversion results for new campaigns.

When generating copy, the skill requires supported claims, genuine deadlines, clear prices, and guarantees that reflect the actual offer. It adapts the method to the brief rather than carrying historical financial claims into new work.

## License

Original contributions by the repository maintainer are released under the [MIT License](LICENSE).

Third-party source material remains subject to its respective rights. The MIT license does not license the underlying book, source promotions, recordings, or trademarks.
