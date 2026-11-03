# Evaluation plan

**Commit and push this file before your first main session.** The commit time is the evidence that
your tasks and success criteria were decided before you saw any data. You may change it afterwards;
if you do, say what changed and why under *Deviations from the plan* in `SUBMISSION.md`.

Replace every line that starts with `REPLACE`. Keep the headings.

## 1. Facet

REPLACE with the facet code and name from the brief, and two or three sentences on what part of the kiosk this covers.

## 2. Divergent model

### 2.1 How kiosk visitors differ

At least five dimensions along which the people in the Lantai 1 lobby differ, as they matter for your facet.

| # | Dimension | Values it can take | Why it matters for this facet |
|:-:|---|---|---|
| D1 | Familiarity with the building | First-time / Visited before / Regular visitor | First-time visitors may rely more on the kiosk because they do not yet know the building layout, whereas regular visitors may have prior location knowledge. Familiarity may affect their ability to match room positions in the 3D model to actual locations. |
| D2 | Experience reading 3D maps | Familiar / Rarely uses them | Visitors familiar with 3D maps may find it easier to understand building orientation, floors, and relative room positions. Their ability to interpret spatial representations may affect how they translate digital information into walking directions. |
| D3 | Mobility | Can use stairs / Requires elevator access | Visitors requiring elevator access may need different route information from those who can use stairs. Locating a room in the 3D model may not be sufficient to identify a physical route that meets their mobility needs. |
| D4 | Time pressure | Hurried / Not hurried | Hurried visitors may make faster decisions but overlook information such as the floor or corridor orientation. Time pressure may affect navigation accuracy and success when moving from the kiosk to the actual room. |
| D5 | Viewing distance | Near / Far | Visitors standing farther from the screen may have difficulty reading small labels or distinguishing room details in the 3D model. The legibility of spatial information may affect their ability to identify a location before they begin walking. |

### 2.2 Model visitors

At least three, each one a combination of values from 2.1, in one sentence. Give each a code (M1, M2, …):
these codes go in the `model_visitor` column of `sessions.csv`.

| Code | Model visitor, one sentence | Dimension values |
|:-:|---|---|
| M1 | A first-time visitor to the Informatics building who rarely uses 3D maps, can use stairs, is not in a hurry, and views the kiosk from a near distance while trying to locate a room. | D1=First-time; D2=Rarely uses them; D3=Can use stairs; D4=Not hurried; D5=Near |
| M2 | A student from another department who has visited the building before, is familiar with 3D maps, can use stairs, is in a hurry, and initially views the kiosk from a far distance while searching for a room. | D1=Visited before; D2=Familiar; D3=Can use stairs; D4=Hurried; D5=Far |
| M3 | A regular visitor who knows the building layout, rarely uses 3D maps, requires elevator access between floors, is not in a hurry, and views the kiosk from a near distance. | D1=Regular visitor; D2=Rarely uses them; D3=Requires elevator access; D4=Not hurried; D5=Near |

### 2.3 Candidate research questions

At least three, before you choose. Each one is something you could find out by watching visitors use the kiosk.

1. REPLACE
2. REPLACE
3. REPLACE

### 2.4 The question you chose, and why

REPLACE with your primary research question (and at most one secondary), and the reason you chose it over the others: what the evidence would let you decide that the others would not.

### 2.5 Ambiguity log

At least three things that could be read two ways, and the rule you decided now so that you do not decide it later when you have seen the data.

| # | Ambiguity | Decision rule, fixed before the study |
|:-:|---|---|
| A1 | REPLACE, e.g. a visitor finds the right room but names the wrong floor | REPLACE, e.g. counts as partial (0.5) |
| A2 | | |
| A3 | | |

## 3. Study design

**Method family:** REPLACE (task-based, insight-based, controlled comparison, or a combination)

**Lam et al. (2012) scenario:** REPLACE, and one sentence on why this scenario fits your question

**Setting:** REPLACE (big screen, laptop or tablet in the lobby, participant's own phone)

**Conditions and order:** REPLACE (one condition, or which conditions and how the order is counterbalanced)

**Who you will recruit, and how you will reach at least two of your model visitors:** REPLACE

**Planned number of main sessions:** REPLACE (at least 8)

**Session length:** REPLACE (aim for 7 minutes or less: these are people on their way somewhere)

## 4. Tasks

At least three. Write the correct answer and the success rule **now**.

| Task | What you say to the participant (in Bahasa Indonesia, as you will say it) | Correct answer | Success rule (1 / 0.5 / 0) | What counts as an error |
|:-:|---|---|---|---|
| T1 | REPLACE | REPLACE | REPLACE | REPLACE |
| T2 | | | | |
| T3 | | | | |

## 5. Measures

| Measure | Type (performance, subjective, qualitative) | How it is taken | Column it goes in |
|---|---|---|---|
| Task success | performance | by the rule in section 4 | `trials.success` |
| REPLACE | | | |
| REPLACE | | | |

## 6. What you expect, and what would change your mind

REPLACE with one prediction per model visitor, and what result would show you were wrong.

## 7. Pilot

REPLACE with who you piloted with (a classmate is fine), what you changed after it, and the session codes (`P01`, …).
