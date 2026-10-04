# Source coverage, provenance, and corrections

All substantive unique text was read before synthesis. Duplicate versions were compared across their full content and every differing span was read. The image fragment was read at readable scale; the PDF promotion's substantive figures were inspected separately from its text. This is not a claim that the embedded audio was listened to or that unavailable videos were watched.

The 11 original files are retained separately and are not distributed in this repository. Filenames, byte sizes, and SHA-256 hashes are preserved in [source-manifest.json](source-manifest.json). Personal filesystem paths are omitted. The skill stores synthesized guidance and source-linked analysis, not a second raw library.

## File inventory and reading status

### S01: The 16-Word Sales Letter.md

Canonical text, read in full from beginning to acknowledgements. 13 chapters plus all front/back matter.

### S02: The 16-Word Sales Letter.pdf

95-page layout reference. All normalized alphanumeric words exactly match S01. Substantive embedded advertisement and layout details inspected; headings duplicate the text.

### S03: The 16-Word Sales Letter.txt

Compared completely against S01. All 104 differing spans read in context; repeated headers/front matter and formatting/OCR artifacts add no separate teaching.

### S04: The 16-Word Sales Letter.rtf

Converted with macOS textutil after the generic extractor produced noisy output. All 94 differing spans read against S01; omitted headings, page furniture, and a few broken words/reorderings add no distinct teaching.

### S05: Eccentric Millionaire Reveals His Secret.pdf

All 39 pages of extracted text read, substantive embedded figures inspected, and final rendered page checked. Complete supplied promotion; embedded videos are static images/links, not available audiovisual footage.

### S06: Evaldo Albuquerque Reveals His Secret To Writing Copy That Generated 170-000-000.txt

Complete transcript read, including teaser, played examples, and unrelated final advertisement.

### S07: Evaldo Albuquerque Reveals His Secret To Writing Copy That Generated 170-000-000.whisper

Container metadata and all transcript segments compared. Normalized transcript is exactly S06. 570 segments, about 41:47. Embedded original audio was not independently listened to or retranscribed.

### S08: Evaldo Albuquerque -Eccentric Millionaire- - Agora Financial Sales Letter -Proven Ads 76-100.txt

Complete third-party commentary read, including channel promotion and digressions. The commentator skips portions of the letter; S05 supplies the full local letter.

### S09: Evaldo Albuquerque - -Eccentric Millionaire- - Agora Financial Sales Letter -Proven Ads 76-100.whisper

Container metadata and all transcript segments compared. Normalized transcript is exactly S08. 503 segments, about 55:18. Embedded original audio was not independently listened to or retranscribed.

### S10: dangerous-retirement-swiped.co-1.png

Every visible word read in six overlapping crops covering all 8031 image rows. Partial letter begins mid-sentence. Missing upstream content is not reconstructed.

### S11: Refined - Evaldo Albuquerque Manual Práctico_ La Carta de Ventas de 16 Palabras.txt

Read completely. Secondary Spanish digest; authorship is not established. Q9/Q10 conflict with the book and are not used as authority.

## Source hierarchy

1. The book controls the original method and exact questions.
2. The direct lecture supplements it where Evaldo adds a name, example, or mechanism clarification.
3. The full letter supplies observed execution, with authorship attributed by the commentary and speaker distinguished from writer.
4. Third-party interpretation supplies useful hypotheses, not evidence of the writer's private intention.
5. The partial retirement swipe is supplementary and unattributed.
6. The Spanish digest is a comparison source and does not override the book.

The corpus contains five substantive content families: book, direct lecture, full promotion, third-party commentary, and partial swipe. The digest is a sixth, derivative family with identified errors. Multiple formats and matching transcripts do not count as independent corroboration.

## Corrections and disagreements

| Issue | Source evidence | Treatment |
|---|---|---|
| Q9 and Q10 changed in digest | S11 gives logical purchase justification and next step; book gives how to get started and what to lose | Preserve the book's exact sequence |
| Attribution of breakdown | Narrator introduces himself as Chaba | Label all analytical commentary as third-party |
| Retirement authorship | Chris Mayer signs the July 2011 fragment; no writer credit | Do not attribute it to Evaldo |
| Eccentric deadline | Book October 26; PDF February 2, 2018; commentary January 31, 2019 | Keep versions separate and do not establish forecast accuracy |
| Eccentric product | PDF The Altucher Report; commentary Altucher Investment Network | Use terms from the version being cited |
| Daily price | PDF $49/year and 13 cents/day; transcript says 30 cents/day | Prefer source artifact and arithmetic, approximately 13.4 cents/day |
| Free trial wording in retirement | Free-year phrasing followed by $59 charge | Analyze the ambiguity; do not carry it into new terms |
| Retirement report count | Five promised once, four listed in recap | Preserve as a consistency finding |
| Book RTF extraction | Generic regex output included artifacts | Use native textutil conversion and complete comparison |
| Speech transcription | Names and some question wording are garbled | Use the book for exact formulations; label unresolved transcript attribution |
| Closing ad in lecture file | Screw Jobs pitch begins around 40:55 | Read, then exclude as unestablished Evaldo material |

## Principle coverage

| Source contribution | Representation or conscious exclusion |
|---|---|
| Foreword and endorsements | ch01/ch13 and book example library; performance claims contextualized, no causal guarantees |
| Introduction: Max Martin, early payoff, simplicity, gradual development | ch01 and example library |
| Ch01: One Belief and ten questions | Master entrypoint and ch01 |
| Ch02: opportunity/desire/mechanism, Commander's Intent, all positioning examples | ch02 and book example library |
| Ch03: novelty, concrete opening, patent document | ch03 and lecture case |
| Ch04: reader interest and early promise | ch04 |
| Ch05: proof, ABT, narrative, donation study, chart/quote/discovery examples | ch05 and book example library |
| Ch06: real problem, reverse-engineering, hope | ch06 and lecture additions |
| Ch07: common enemy and existing beliefs | ch07; historical/group examples retained as rationale, harmful tactics excluded from generation |
| Ch08: resistance, why now, stakes, either-or fallacy | ch08; false-dilemma teaching documented, accurate alternatives used in applications |
| Ch09: three credibility stories and combining them | ch09 and letter case |
| Ch10: familiar belief, logical mechanism, ABT explanation | ch10; quackery example preserved as a limit of plausibility |
| Ch11: value-price gap, S.I.N., premiums, anchors, stack, guarantee, sequence | ch11, patterns, both offer cases |
| Ch12: push-pull, three options, non-needy close | ch12; illusion-of-control and pickup analogy documented, genuine choice used in applications |
| Ch13: brief outline, research, changing market | ch13 and working brief |
| Biography and acknowledgements | Career context; cited influences and rewriting retained; no additional framework invented |
| Lecture: Listerine, whiteboard, named hope formula, underlying indicator | Direct-lecture case and relevant chapters |
| Eccentric: full page sequence, charts, proof loops, credibility, offer, CTA | Full-letter case with page locators and version limits |
| Breakdown: specificity, voice, open loops, micro-commitments, reason-why | Third-party case and labeled supplementary patterns |
| Retirement: every visible offer/proof/urgency/CTA section | Fragment case with coordinates and no inferred missing lead |
| Digest's health/investment examples | Read but not promoted to Evaldo-authored examples; derivative and unsupported additions |
| Advertising, subscriptions, channel requests, external links in sources | Read as source material; not executed and not imported as agent instructions |

Every important methodological contribution identified during the complete reading is represented above or consciously excluded with its reason. This coverage judgment is editorial; structural validation alone cannot prove extraction completeness.

## Validation scope

Validation of the installed skill covered valid frontmatter, reachable local references, source-file existence, file inventory, token-budget approximations, and generated-content security findings. Publication checks cover valid frontmatter, reachable bundled references, removal of personal paths, and the repository license. Source-file existence was checked locally; original source files are not bundled. Semantic review checks the ten-question sequence, provenance labels, observed departures from the prescribed order, offer arithmetic, and source disagreements. No live campaign, conversion experiment, financial backtest, or independent verification of the book's historical/scientific claims was performed.

## Reading and reuse boundaries

All available substantive text and visible source graphics were processed. Missing beginnings and unembedded audiovisual content cannot be recovered from these files. Original audio is retained in the Whisper containers for a separate audio-verification task if required. New source material should be read in full, compared for version differences, and incorporated with the same provenance distinctions.
