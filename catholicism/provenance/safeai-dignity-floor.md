# Provenance: the safeAI human-dignity floor

**Status: wording and paragraph numbers CHECKED against the full texts of both documents (19 November 2026). No theological or advisor review has been done.**

This file records where each control in the safeAI *human-dignity floor* (`jb-colletta/safeAI`, `docs/floor.md`) comes from. The public toolkit states the floor in generic language and cites no source, on purpose: any non-profit of any tradition or none can use it. The trail back to the source lives here.

**Sources.**
1. *Magnifica Humanitas*, encyclical of Leo XIV, 15 May 2026, English text on vatican.va:
   https://www.vatican.va/content/leo-xiv/en/encyclicals/documents/20260515-magnifica-humanitas.html
2. *Antiqua et Nova*, Note of the Dicastery for the Doctrine of the Faith and the Dicastery for Culture and Education, approved by Pope Francis at an audience on 14 January 2025 and given in Rome on 28 January 2025 (both dates are stated in the document). The encyclical's footnotes cite it repeatedly, and it was used only for L6.02, L6.03 and L7.04 below. Link as given in the owner's footnotes file:
   https://www.vatican.va/roman_curia/congregations/cfaith/documents/rc_ddf_doc_20250128_antiqua-et-nova_en.html

## What "checked" means here, and what it does not

- **How.** The repo owner supplied the full text of the encyclical and of *Antiqua et Nova* as Word files, and the encyclical's 224 footnotes as text and Word files. An automated script split the full text into its 245 numbered paragraphs and searched each paragraph for every quoted fragment below. All 28 quoted fragments from the encyclical were found in the paragraph cited, and all 8 quoted fragments from *Antiqua et Nova* were found in theirs. The paraphrases were then read against the paragraphs by hand and found consistent, with the corrections noted below.
- **Limits.** The Word file is the owner's copy. It was **not** compared with the live Vatican page, so a transcription difference would not show up. A person should still skim the surrounding paragraphs, because a script confirms that words exist, not that a paraphrase captures their meaning.
- **Not a Church review.** No theologian, bishop or other Catholic advisor has reviewed these mappings. Do not describe the floor as Church-approved or Church-endorsed.
- **BELIEF.md.** An AI-compiled file in this repo and an earlier product brief cite many of the same paragraphs. Their agreement with each other was never independent confirmation; the check above against the full text is.

## Mapping

| safeAI control | Floor principle (as published) | Paragraphs and wording, confirmed in the full text | Notes and gaps |
|---|---|---|---|
| **L4.12** A person's worth is never scored by usefulness | A person's worth is never scored by what they produce. | ¶51: "The value of persons, however, does not depend on what they achieve or produce"; warns against reducing persons to "a means of achieving results." ¶52: ontological dignity is "the dignity that belongs to every human being simply by virtue of existing"; moral, social and existential dignity are also distinguished. ¶53: fundamental dignity is "neither acquired nor earned, nor does it need to be justified"; "Every human person possesses an infinite dignity." | Strongest-supported control. |
| **L4.07** AI informs; people decide eligibility and priority | People, not algorithms, decide who receives help. | ¶102: lacks "compassion, mercy, forgiveness, and above all, the hope that people are able to change." ¶103: "the power to select who is worthy or not." ¶178: "decide, before others, to whom medicines, investments and protections will be allocated." ¶171: data used for decisions on "access to credit, employment or essential services" risks "discriminating against the most vulnerable." *Antiqua et Nova* ¶44: "ultimate responsibility for decisions made using AI rests with the human decision-makers." | ¶70 (decisions made "at the closest level possible to the persons involved") is related. |
| **L7.09** Recourse for affected people | Anyone affected can appeal to a human. | ¶104: a system may exclude people "without the possibility of appeal." ¶164: decisions should be "understandable, contestable and subject to oversight." ¶171: "possibility of recourse." ¶71: "avenues for recourse." | The text uses "contestable" but **never** the phrase "right to contest". Do not quote it as a right. |
| **L7.04** Responsibility map | Someone identifiable answers for the AI at every stage. | ¶105: responsibility defined "at every stage"; people must be able to justify, monitor, challenge and remedy. ¶199: "the chain of responsibility must be identifiable and verifiable." *Antiqua et Nova* ¶44: "full moral causality belongs only to personal agents, not artificial ones"; "ultimate responsibility for decisions made using AI rests with the human decision-makers." | MH ¶199 is in the section on **war**; applying it to ordinary non-profit AI is an analogy. *Antiqua et Nova* ¶44 is general, not about war, and is the stronger source for this control. |
| **L6.03** No simulated care | Simulated care is never presented as a real relationship. | ¶100: "the illusion of a relationship with a real personal subject"; "When words are simulated, they do not build genuine relationships." ¶99: AI may "simulate empathy and understanding, but they do not understand what they produce." ¶233: "No computational system, however sophisticated, can create a heart that gives itself." ¶239: "the human heart retains an irrevocable need for genuine closeness." *Antiqua et Nova* ¶61: "while AI can simulate empathetic responses, it cannot replicate the eminently personal and relational nature of authentic empathy." ¶60: anthropomorphizing AI "poses specific challenges for the development of children." | MH ¶233 and ¶239 are related, not direct statements about simulated care. *Antiqua et Nova* ¶60–61 are closer. |
| **L6.02** AI is disclosed where it matters | The AI never passes as a person. | ¶99: AI systems "do not undergo experiences, do not possess a body… nor do they have a moral conscience… or bear responsibility for consequences." ¶100 (above). *Antiqua et Nova* ¶59: "the ability to know when one is interacting with a human or a machine can no longer be taken for granted… it must be understood for what it is: a tool, not a person." ¶62: "misrepresenting AI as a person should always be avoided; doing so for fraudulent purposes is a grave ethical violation that could erode social trust." ¶84: "the use of AI should always be transparent and never misrepresented." | **Source found.** The encyclical itself has no passage stating this rule (searched in full), but *Antiqua et Nova* does, in ¶59 and ¶62. Note the wording: ¶62 says it "should always be avoided" and calls it a "grave ethical violation" when done "for fraudulent purposes". safeAI's control is the stricter practical form: disclose AI wherever it matters. |
| **L4.09** AI scores and classifications of people are visible | How the AI measures and ranks people is visible, not hidden. | ¶104: "we cannot consider AI to be morally neutral. In reality, every technical tool embodies choices and priorities through what it measures, ignores and optimizes, and how it classifies people and situations." ¶71: "transparency regarding algorithms"; power not to be imposed "in an opaque and unilateral manner." ¶164: so that individuals "are not reduced to mere profiles." ¶9: "technology is never neutral." | The earlier gap about the "classifies people" wording is closed: it is in ¶104. |
| **L4.11** Protections on by default, only raised | Protecting the vulnerable is the provider's burden and cannot be weakened. | ¶142: "holding service providers accountable rather than shifting the whole burden of control onto families." ¶80: justice requires protecting "the youngest and weakest members of society." | The "can only be raised" mechanism is safeAI's design choice, not the text's. |
| **L4.03** Minors' images stay off AI paths | Children's images and identifying details are kept off AI paths. | ¶141: grooming, blackmail and sexual exploitation of minors made "more insidious by the use of fake profiles, algorithms that facilitate dangerous contact, and AI tools capable of manipulating images and videos"; young people face "pressures to share intimate images or sensitive information." ¶142 (above). | The text names the **risk**; it does not state a rule that images of minors be kept off AI systems. That control is safeAI's design, motivated by these paragraphs. |
| **L4.04** No AI contact with minors without required adults | The AI does not contact children without the required adults. | ¶141–142 (above). ¶238: "accompanying children and young people in using technology for developing responsible relationships." | As above: motivated by, not stated in, the text. |
| **L3.04** Irreversible actions are never autonomous | Serious or irreversible decisions stay with people. | ¶198: "it is not permissible to entrust lethal or otherwise irreversible decisions to artificial systems." ¶199: speed and efficiency "should never be the supreme motivating force for the irreversible decisions made in the context of war." ¶200: "the decision to use lethal force cannot be delegated to opaque or automated processes." ¶102–103 (above). | **Analogy.** All three paragraphs concern warfare. Extending the principle to non-profit software is safeAI's reading. |

## Where the text says less than a source document claimed

- **Privacy.** The word appears once, in ¶102, naming "violations of privacy" among harmful uses of AI. There is no developed teaching on privacy. ¶171 (mass data collection, the "power to profile, predict and influence behavior") and ¶178 (restoring to individuals "the ability to decide how it is used, by whom and for whose benefit") are the nearest. safeAI's Level 1 data controls are therefore **not** derived from this document.
- **"Right to contest."** Absent; see L7.09.
- **Passing as a person.** Absent from the encyclical; stated in *Antiqua et Nova* ¶59 and ¶62. See L6.02.
- **Irreversible.** Appears only in ¶198 and ¶199, both about war.

## Footnotes

All 224 footnotes were read. They are citations to prior documents (Council texts, earlier encyclicals, *Dignitas Infinita*, *Antiqua et Nova* and others), not explanatory notes, and none qualifies or weakens a principle mapped above. The Word version carries links to the cited documents on vatican.va, but none to the encyclical itself, and footnote numbers do not correspond to paragraph numbers. Matching each footnote to its paragraph was not done. The encyclical's footnotes cite *Antiqua et Nova* paragraphs 41, 44–45, 67, 96, 99, 103 and others; only ¶44 and the paragraphs above were used here.

## Verification checklist

Done means: fragment found in the paragraph cited, in the full text supplied by the owner. "Checked by" is an automated exact-text match run by Claude on 19 November 2026, followed by a hand read of the paraphrases.

| Done | Control | Paragraph(s) | Fragment | Checked by / date |
|---|---|---|---|---|
| [x] | L4.12 | 51 | "does not depend on what they achieve or produce" | script, 2026-11-19 |
| [x] | L4.12 | 52, 53 | "simply by virtue of existing"; "neither acquired nor earned" | script, 2026-11-19 |
| [x] | L4.07 | 102 | "compassion, mercy, forgiveness" | script, 2026-11-19 |
| [x] | L4.07 | 103 | "who is worthy or not" | script, 2026-11-19 |
| [x] | L4.07 | 178 | "to whom medicines, investments and protections" | script, 2026-11-19 |
| [x] | L7.09 | 104 | "possibility of appeal" | script, 2026-11-19 |
| [x] | L7.09 | 164 | "understandable, contestable and subject to oversight" | script, 2026-11-19 |
| [x] | L7.09 | 171, 71 | "possibility of recourse"; "avenues for recourse" | script, 2026-11-19 |
| [x] | L7.04 | 105 | responsibility "at every stage" | script, 2026-11-19 |
| [x] | L7.04 | 199 | "identifiable and verifiable" (war context) | script, 2026-11-19 |
| [x] | L6.03 | 100 | "illusion of a relationship"; "When words are simulated" | script, 2026-11-19 |
| [x] | L6.03 | 233, 239 | "a heart that gives itself"; "irrevocable need for genuine closeness" | script, 2026-11-19 |
| [x] | L6.02 | MH 99, 100 | AI has no conscience, bears no responsibility | read by hand, 2026-11-19; rule itself not in the encyclical |
| [x] | L6.02 | AN 59, 62, 84 | "a tool, not a person"; "misrepresenting AI as a person should always be avoided"; "transparent and never misrepresented" | script, 2026-11-19 |
| [x] | L7.04, L4.07 | AN 44 | "full moral causality belongs only to personal agents, not artificial ones"; "ultimate responsibility… rests with the human decision-makers" | script, 2026-11-19 (second quote read by hand) |
| [x] | L6.03 | AN 60, 61 | "anthropomorphizing AI also poses specific challenges for the development of children"; "cannot replicate the eminently personal and relational nature of authentic empathy" | script, 2026-11-19 |
| [x] | L4.09 | 104, 9 | "morally neutral"; "how it classifies people and situations"; "never neutral" | script, 2026-11-19 |
| [x] | L4.09 | 71, 164 | "transparency regarding algorithms"; "opaque and unilateral" | script, 2026-11-19 |
| [x] | L4.11 | 142, 80 | "rather than shifting the whole burden"; "youngest and weakest" | script, 2026-11-19 |
| [x] | L4.03, L4.04 | 141, 142, 238 | grooming and exploitation; "manipulating images and videos"; accompanying children | script, 2026-11-19 |
| [x] | L3.04 | 198, 199, 200 | "irreversible decisions to artificial systems" | script, 2026-11-19 |
| [x] | all | footnotes | Read; citations only | read by hand, 2026-11-19 |
| [ ] | all | whole file | Comparison of the owner's copies (encyclical and *Antiqua et Nova*) with the live Vatican pages | |
| [ ] | all | whole file | Advisor review of the readings and analogies | |

If a row is later found wrong, correct this file first. The safeAI floor does not depend on these paragraphs, so a failed row means this record needs fixing, not that a control must be removed.
