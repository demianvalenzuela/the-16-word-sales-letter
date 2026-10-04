# The 16-Word Sales Letter

Improve your copy's clarity, credibility, and persuasive strength using Evaldo Albuquerque's *The 16-Word Sales Letter*.

This agent skill helps you diagnose and improve existing copy, or write new copy with a clear sales argument. Use it for sales letters, VSLs, landing pages, emails, ads, product pages, and other copy intended to drive action.

The skill adapts the method to your audience, format, and intended next step. A short ad may need a sharper promise and stronger proof. A sales email may need a clearer benefit and a more credible reason to respond. A full sales letter may need the complete argument.

## What it helps you improve

- Identify where the copy loses attention, leaves doubts unanswered, or asks for action before establishing enough value.
- Sharpen the main promise and connect it to what the reader wants.
- Make the offer's difference and mechanism easier to understand.
- Strengthen proof and address objections using the evidence available.
- Improve structure, flow, and wording while preserving the intended voice.
- Clarify the offer and call to action.

The core framework combines One Belief, ten reader questions, And/But/Therefore proof, mechanism explanations, offer construction, and push-pull closes. The skill selects the elements relevant to each piece rather than requiring every format to answer all ten questions.

It includes notes covering all 13 book chapters, annotated sales-copy examples, lecture additions, and practical references for planning and revision. It distinguishes the book's teaching from Evaldo's lecture, observed copy, third-party interpretation, and new adaptations.

## Installation

Install with the Skills CLI:

```bash
npx skills add https://github.com/demianvalenzuela/the-16-word-sales-letter --skill the-16-word-sales-letter
```

The skill's identifier is `the-16-word-sales-letter`. Its display name is **The 16-Word Sales Letter**.

## Usage

Provide your copy, audience, offer, available evidence, and intended action. Specify any constraints on length, tone, or format.

Example prompts:

```text
Use $the-16-word-sales-letter to improve this copy.
Identify the weaknesses in the sales argument, explain the most
important changes, and provide a revised version.
Preserve my voice and use only the evidence supplied.
```

```text
Improve this sales email for a Spanish B2B audience.
Make the benefit, credibility, and reason to respond clearer.
Keep it under 150 words and write in Spanish from Spain.
```

```text
Review this ad's hook, promise, proof, and call to action.
Rewrite it within the existing character limit.
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
