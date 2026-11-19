# How to run the advisor review

**Purpose.** A person with formal training in Catholic moral and social teaching reads how `safeai-dignity-floor.md` uses *Magnifica Humanitas* and *Antiqua et Nova*, and says whether the readings are fair. The advisor review is optional. It gates one thing: whether anyone may say publicly that safeAI's human-dignity floor is grounded in Church teaching. safeAI itself cites none of this and does not depend on the review.

**What it is not.** It is one person's reading, not an official position of the Church or of any diocese, and it should never be described as Church approval.

## 1. Choose the advisor

Look for someone with formal theological training and a working knowledge of Catholic social teaching, ideally also able to discuss technology ethics. Reasonable places to ask: a priest or deacon with theological formation, a theology or ethics faculty member at a Catholic college or university, or a Catholic organization's mission or ethics officer. Ask someone you can disagree with openly. Do not ask someone whose job depends on your project.

Agree before you start: they review as an individual, they may say no, and they may ask to stay anonymous.

## 2. Send a short packet

1. [`safeai-dignity-floor.md`](safeai-dignity-floor.md): the mapping from each floor control to the paragraphs behind it.
2. The "where the text says less" section of that file. It matters most.
3. [`belief-md-mh-citation-check.md`](belief-md-mh-citation-check.md), only if they are also reviewing `BELIEF.md`.
4. The public repository link, so they can see the floor in context: `https://github.com/jb-colletta/safeAI`, and its [floor page](https://github.com/jb-colletta/safeAI/blob/main/docs/floor.md).
5. The questions in section 3, and a requested date.

Say plainly that the texts were checked word by word against the paragraphs, so they need not redo that. What they are asked is whether the *readings* hold.

## 3. Questions to ask

For each of the 11 floor controls in the mapping:

1. Is the quoted passage fairly read? Is anything lifted out of its context?
2. Where the control stretches the text into a rule for software (for example, from "possibility of appeal" to "a person affected can ask for human review"), is the stretch a fair application, or does it overreach?
3. Is anything the control requires something the text would not support?

And for the whole mapping:

4. Is the "where the text says less" section accurate and complete? Does anything in it understate or overstate what the documents say?
5. Is the plain-language "does not claim" wording in `docs/floor.md` adequate? What would you add?
6. Does anything in the generic wording of the controls contradict Church teaching?
7. How should the grounding be described publicly, if at all? What is a fair sentence, and what should never be said?

## 4. Record the outcome

Ask for a short written reply. Then, in `safeai-dignity-floor.md`:

- Add a dated line to the status block: "Advisor review: [name or 'anonymous advisor'], [role], [date], scope: [what they read]."
- Tick the checklist items they confirmed. For each point they changed, edit the mapping and note the change.
- For each point they disagreed with, either change it or record the disagreement and your reason.
- Only with their written permission, name them.

## 5. What the result lets you say

| Outcome | You may say | You may not say |
|---|---|---|
| Reviewed, no objections to the readings | "The mapping was reviewed by [name or role], who found the readings fair" | "Approved by the Church", "official", "teaching-compliant" |
| Reviewed, with changes made | The same, plus "and we revised it in response" | Anything that hides the changes |
| Not reviewed | "The wording and paragraph numbers were checked against the texts. No theologian has reviewed the readings." | "Grounded in Church teaching" without that qualification |

The status line in the mapping file currently says the last row.

## 6. Keep it live

Re-run this when the floor changes, when a new Church document is added to the mapping, or when a reviewer says a reading was borderline. A review covers the mapping as it was on the date they read it.
