# Provenance: the safeAI human-dignity floor

**Status: UNVERIFIED. Do not quote from this file until the checklist at the bottom is complete.**

This file records where each control in the safeAI *human-dignity floor* (`jb-colletta/safeAI`, `docs/floor.md`) comes from. The public toolkit states the floor in generic language and cites no source, on purpose: any non-profit of any tradition or none can use it. The trail back to the source lives here.

**Source.** *Magnifica Humanitas*, encyclical of Leo XIV, 15 May 2026, English text on vatican.va:
https://www.vatican.va/content/leo-xiv/en/encyclicals/documents/20260515-magnifica-humanitas.html

## How this was gathered, and why it is unverified

- The page is about 318,000 characters. It was read through an automated fetch that **summarizes** the page and returns it in parts, not as raw text. About the first 95% was covered: the body through ¶245. The footnotes were not read.
- Paragraph numbers and quotations below come from those summaries. They have **not** been checked against the page by a person. Treat every quotation as "to be confirmed", including those marked verbatim.
- Two earlier AI-compiled documents (a product brief, and `catholicism/BELIEF.md`, whose own header says its citations are not yet verified) cite many of the same paragraphs. Their agreement with each other is **not** independent confirmation.
- Where the retrieved text did not contain something a source document attributes to the encyclical, that is said plainly below.

## Mapping

"Retrieved" means the summary returned it. Nothing is confirmed until the checklist is done.

| safeAI control | Floor principle (as published) | Paragraphs and wording retrieved | Notes and gaps |
|---|---|---|---|
| **L4.12** A person's worth is never scored by usefulness | A person's worth is never scored by what they produce. | ¶51: "The value of persons, however, does not depend on what they achieve or produce." ¶51 also warns against reducing persons to "a means of achieving results." ¶52: ontological dignity is "the dignity that belongs to every human being simply by virtue of existing"; moral, social and existential dignity can be enhanced or diminished. ¶53: fundamental dignity is "neither acquired nor earned, nor does it need to be justified"; "Every human person possesses an infinite dignity." | `BELIEF.md` cites MH 51–53 for the same ideas. Strongest-supported control. |
| **L4.07** AI informs; people decide eligibility and priority | People, not algorithms, decide who receives help. | ¶102: automated systems lack "compassion, mercy, forgiveness, and above all, the hope that people are able to change"; decisions on jobs, credit and services risk being fully delegated. ¶103: "the power to select who is worthy or not"; when no one answers for that judgment, political responsibility is lost. ¶178: those who "decide, before others, to whom medicines, investments and protections will be allocated." | ¶70 on decisions made close to those affected is related. |
| **L7.09** Recourse for affected people | Anyone affected can appeal to a human. | ¶104: a system may exclude people "without the possibility of appeal." ¶164: decisions should be "understandable, contestable and subject to oversight." ¶171: "the possibility of recourse." ¶71: "avenues for recourse." | The summaries found **no** passage using the phrase "right to contest". The wording above is the closest. |
| **L7.04** Responsibility map | Someone identifiable answers for the AI at every stage. | ¶105: responsibility must be defined at every stage, from designers to users; people must be able to account for, justify, monitor, challenge and remedy. ¶199: "the chain of responsibility must be identifiable and verifiable." | ¶199 is in the section on war. Applying it to ordinary non-profit AI is an **analogy**. |
| **L6.03** No simulated care | Simulated care is never presented as a real relationship. | ¶100: AI can create "the illusion of a relationship with a real personal subject"; "When words are simulated, they do not build genuine relationships." ¶233: "No computational system, however sophisticated, can create a heart that gives itself." ¶239: "the human heart retains an irrevocable need for genuine closeness." | ¶233 and ¶239 are related, not direct statements about simulated care. |
| **L6.02** AI is disclosed where it matters | The AI never passes as a person. | ¶99: AI imitates parts of human intelligence but has no conscience and does not bear responsibility. ¶100 (above). | The retrieved text did **not** contain an explicit rule that AI must not be presented as a person. A source document attributes that point to *Antiqua et Nova* (2025), which has **not** been read. Treat this mapping as partial. |
| **L4.09** AI scores and classifications of people are visible | How the AI measures and ranks people is visible, not hidden. | ¶104: "we cannot consider AI to be morally neutral." ¶71: digital power should not be imposed "in an opaque and unilateral manner"; "transparency regarding algorithms." ¶164: people should not be reduced to profiles. ¶9: "technology is never neutral." | The phrase about classifying people, attributed to ¶104 by a source document, was not retrieved verbatim. |
| **L4.11** Protections on by default, only raised | Protecting the vulnerable is the provider's burden and cannot be weakened. | ¶142: "holding service providers accountable rather than shifting the whole burden of control onto families." ¶80: justice requires that the digital age "protects the youngest and weakest members of society." | The "can only be raised" mechanism is safeAI's design choice, not the encyclical's. |
| **L4.03** Minors' images stay off AI paths | Children's images and identifying details are kept off AI paths. | ¶141: unsupervised early device use exposes minors to grooming and exploitation. ¶142 (above). | A source document cites ¶141–142 and ¶170 for AI tools that manipulate images and videos of minors. That wording was **not** retrieved. Treat the specific image control as safeAI's own design, motivated by these paragraphs. |
| **L4.04** No AI contact with minors without required adults | The AI does not contact children without the required adults. | ¶141–142 (above). ¶238: "accompanying children and young people in using technology for developing responsible relationships." | As above: motivated by, not stated in, the text. |
| **L3.04** Irreversible actions are never autonomous | Serious or irreversible decisions stay with people. | ¶198: "it is not permissible to entrust lethal or otherwise irreversible decisions to artificial systems." ¶200: "the decision to use lethal force cannot be delegated to opaque or automated processes." ¶102–103 (above). | **Analogy.** ¶198 and ¶200 are about warfare. Extending the principle to non-profit software is safeAI's reading, not the encyclical's claim. |

## Not found in the retrieved text

- A passage on **privacy** as such. Data appears in ¶67, ¶108, ¶171 and ¶178 (data as a good that should not be concentrated; control over data about oneself), but no passage on privacy was retrieved. safeAI's data-protection controls (Level 1) are therefore **not** derived from this document.
- The word **irreversible** outside ¶198.
- Any text from the footnotes.

## Verification checklist

**How to do it.** Open the vatican.va page above in a browser. For each row, use the browser's find function (Ctrl+F or Cmd+F) to search for the quoted fragment. Confirm (a) the wording exists, (b) it sits in the paragraph number given, and (c) the paraphrase here does not overstate it. Fix the number or wording if not. Then tick the box and record who checked and when. An advisor of your choosing can do the same; the file names no one.

| Done | Control | Paragraph(s) to check | Quoted fragment to search for | Checked by / date |
|---|---|---|---|---|
| [ ] | L4.12 | 51 | "does not depend on what they achieve or produce" | |
| [ ] | L4.12 | 52, 53 | "simply by virtue of existing"; "neither acquired nor earned" | |
| [ ] | L4.07 | 102 | "compassion, mercy, forgiveness" | |
| [ ] | L4.07 | 103 | "who is worthy or not" | |
| [ ] | L4.07 | 178 | "to whom medicines, investments and protections" | |
| [ ] | L7.09 | 104 | "possibility of appeal" | |
| [ ] | L7.09 | 164 | "understandable, contestable and subject to oversight" | |
| [ ] | L7.09 | 171, 71 | "possibility of recourse"; "avenues for recourse" | |
| [ ] | L7.04 | 105 | responsibility "at every stage" | |
| [ ] | L7.04 | 199 | "identifiable and verifiable" (war context) | |
| [ ] | L6.03 | 100 | "illusion of a relationship"; "When words are simulated" | |
| [ ] | L6.03 | 233, 239 | "a heart that gives itself"; "irrevocable need for genuine closeness" | |
| [ ] | L6.02 | 99, 100 | AI has no conscience, bears no responsibility | |
| [ ] | L4.09 | 104, 9 | "morally neutral"; "never neutral" | |
| [ ] | L4.09 | 71, 164 | "transparency regarding algorithms"; "opaque and unilateral" | |
| [ ] | L4.11 | 142, 80 | "rather than shifting the whole burden"; "youngest and weakest" | |
| [ ] | L4.03, L4.04 | 141, 142, 238 | grooming and exploitation; accompanying children | |
| [ ] | L3.04 | 198, 200 | "irreversible decisions to artificial systems" | |
| [ ] | all | footnotes | Not read at all. Check whether any footnote qualifies a paragraph above. | |

When every row is ticked, change the status line at the top from UNVERIFIED to "Verified on <date> by <name or role>". If any row fails, correct this file first. The safeAI floor itself does not depend on these paragraphs, so a failed row means this record needs fixing, not that a control must be removed.
