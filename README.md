# Socrates

> *"I know that I know nothing."* — Socrates of Athens (attr.)

A diagnostic-first adaptive learning skill for Claude. Socrates does not teach until it understands what you already know — and, more critically, what you *think* you know. Before generating a single line of curriculum, it maps your knowledge landscape across five dimensions, surfaces your reasoning through a constrained case study, and elicits self-identified gaps before revealing any of its own observations. The curriculum that follows is anchored in your Zone of Proximal Development, sequenced according to Bloom's revised taxonomy, and calibrated to your metacognitive accuracy.

**Modes:** Marathon (weeks/months) · Sprint (minutes/hours) — detected automatically from natural language.

---

## Table of Contents

1. [Why Diagnostic-First?](#why-diagnostic-first)
2. [Pedagogical Framework](#pedagogical-framework)
3. [How It Works](#how-it-works)
4. [Mode Detection](#mode-detection)
5. [The Four Awareness Quadrants](#the-four-awareness-quadrants)
6. [Curriculum Design Principles](#curriculum-design-principles)
7. [Usage](#usage)
8. [License](#license)
9. [References](#references)

---

## Why Diagnostic-First?

The central failure of most learning tools is **premature instruction**. Content is delivered before the learner's prior knowledge is mapped, producing one of two failure modes: re-teaching what is already known (cognitive waste and disengagement) or scaffolding on gaps the learner doesn't know they have (structural instability that compounds over time).

Socrates inverts this. Diagnosis precedes curriculum. Reflection precedes revelation. The learner's own thinking is surfaced and interrogated before any external correction is offered. This is not a procedural nicety — it is a load-bearing design decision derived from five interlocking frameworks in educational psychology and cognitive science.

---

## Pedagogical Framework

### 1. The Socratic Method (470–399 BCE)

Socrates of Athens employed two complementary dialectical techniques. The first, *elenchus* (ἔλεγχος), is systematic cross-examination designed to expose internal contradictions in the interlocutor's stated beliefs — leading them to *aporia*, a productive state of acknowledged confusion that marks the collapse of false certainty. The second, *maieutics* (μαιευτική), is the "midwifery" of knowledge: the skilled questioner does not inject understanding but helps the learner give birth to it from resources already latent within them (Plato, *Meno*, c. 380 BCE; *Theaetetus*, c. 369 BCE).

The sequencing is non-negotiable. Socrates never revealed a conclusion before the student had exhausted their own reasoning. The aporia is not a failure state — it is the necessary precondition for genuine learning, because it dismantles the illusion of understanding that blocks receptivity to instruction.

Socrates (the skill) operationalizes this in Phase 3: the learner must (a) attempt the case study, (b) articulate their full reasoning, and (c) identify their own gaps — in that order, without prompting from the skill — before any gaps or curriculum are revealed. The skill holds the answer in reserve until the learner has reached their own productive confusion.

### 2. Vygotsky's Zone of Proximal Development

Lev Vygotsky defined the Zone of Proximal Development (ZPD) as "the distance between the actual developmental level as determined by independent problem solving and the level of potential development as determined by problem solving under adult guidance or in collaboration with more capable peers" (Vygotsky, 1978, p. 86).

Two failure modes bookend the ZPD: instruction *below* it produces boredom, disengagement, and the false confidence of easy success; instruction *above* it produces confusion, learned helplessness, and the collapse of self-efficacy. Effective instruction scaffolds precisely at the upper edge of what the learner can almost do independently — the zone where effort is required but success remains achievable.

The five-question diagnostic maps the learner's **lower ZPD bound** (current independent performance level). The case study is then calibrated to sit at the **upper ZPD bound** — a problem that demands extension beyond current comfort but does not exceed the learner's proximal capacity. The constraint (time or no-LLM) is essential here: it prevents the learner from simulating competence through tool use, ensuring the case study genuinely probes the ZPD boundary rather than their ability to access it.

The personalized curriculum generated after Phase 4 is anchored at the lower ZPD bound and sequences upward, ensuring every instructional step is within reach while continuously expanding the boundary.

### 3. Bloom's Taxonomy (Revised, 2001)

Anderson and Krathwohl's revision of Bloom's original taxonomy (1956) establishes six hierarchical levels of cognitive engagement, ordered from lower-order to higher-order thinking:

| Level | Cognitive Operation | Indicator Verbs |
|-------|-------------------|-----------------|
| 1 — Remember | Retrieval of facts from long-term memory | define, list, recall, recognize |
| 2 — Understand | Construction of meaning from instruction | explain, summarize, classify, paraphrase |
| 3 — Apply | Execution of a procedure in a given situation | use, implement, solve, execute |
| 4 — Analyze | Breaking material into parts and detecting relationships | differentiate, organize, attribute, compare |
| 5 — Evaluate | Making judgements based on criteria | critique, judge, assess, justify |
| 6 — Create | Producing novel work by reorganizing elements | design, construct, generate, hypothesize |

(Anderson & Krathwohl, 2001)

Diagnostic Question 2 (depth of understanding) is specifically designed to assess which Bloom level the learner has activated for the target concept. A learner who can Remember definitions but fails to Apply them to a novel case sits at a different instructional entry point than one who can Analyze trade-offs but has never been asked to Create. The curriculum sequences from the learner's assessed entry level upward, one level at a time, respecting cognitive load constraints and ensuring that higher-order skills are never built before lower-order foundations are solid.

### 4. Flavell's Metacognitive Framework

John Flavell introduced metacognition as "thinking about thinking" and identified three interacting components: *metacognitive knowledge* (declarative beliefs about one's own cognitive processes and knowledge states), *metacognitive regulation* (executive control over learning — planning, monitoring, and evaluating cognitive activity), and *metacognitive experience* (the felt sense of understanding or confusion that accompanies a cognitive task in real time) (Flavell, 1979).

Flavell's research demonstrated that poor learners characteristically lack **metacognitive accuracy**: they cannot reliably distinguish what they genuinely know from what they merely recognize or can retrieve with external scaffolding. This produces systematic overconfidence at low competence levels and, paradoxically, underconfidence at high competence levels.

Socrates targets metacognitive accuracy as a primary learning objective in its own right — not as a precursor to domain learning, but as a parallel track running throughout the session. Phase 1, Question 4 ("What specifically do you feel least confident about?") assesses baseline metacognitive accuracy. The reflection protocol in Phase 3 — requiring the learner to identify their own gaps before external feedback — is not remediation. It is active training of metacognitive regulation. The quadrant mapping in Phase 4 externalizes the learner's metacognitive state visually, making previously invisible assumptions legible.

### 5. Black & Wiliam's Formative Assessment

Paul Black and Dylan Wiliam's landmark meta-analysis of over 250 studies on formative assessment demonstrated effect sizes of 0.4 to 0.7 standard deviations — among the largest of any educational intervention ever measured (Black & Wiliam, 1998a). Their *Inside the Black Box* framework identified five evidence-based strategies that produce these gains:

1. **Clarifying and sharing learning intentions and criteria for success** — learners perform better when they understand what mastery looks like before instruction begins.
2. **Engineering effective tasks that elicit evidence of understanding** — assessment must probe genuine comprehension, not recognition or tool-assisted performance.
3. **Providing feedback that moves learners forward** — feedback must be specific, actionable, and targeted at the gap between current and target performance.
4. **Activating students as instructional resources for one another** — peer explanation deepens understanding in the explainer.
5. **Activating students as owners of their own learning** — self-assessment and goal-setting are not peripheral; they are the mechanism of transfer.

(Black & Wiliam, 1998b)

Diagnostic Question 5 ("What does success look like for you after this?") implements Strategy 1. The constrained case study implements Strategy 2 — the constraint (time pressure or no-LLM) is specifically engineered to prevent performance from being decoupled from understanding. The reflection protocol implements Strategies 3 and 5. The curriculum, when delivered, implements Strategy 3 directly. Every element of the Socrates protocol maps to one or more of these empirically validated strategies.

---

## How It Works

### Phase 1: Diagnostic — Five Questions, Five Dimensions

Before teaching anything, Socrates conducts a five-question diagnostic. Questions are delivered **one at a time** — the response to each informs the framing of the next. This is not a form; it is a conversation.

| # | Dimension | What It Maps |
|---|-----------|-------------|
| 1 | **Prior Exposure** | Whether the concept is genuinely new, partially encountered, or misremembered — determines instructional entry point |
| 2 | **Depth of Understanding** | Active Bloom level — can the learner Remember, Understand, Apply, Analyze, Evaluate, or Create? |
| 3 | **Application History** | Operational vs. theoretical knowledge — distinguishes knowing *about* from knowing *how* |
| 4 | **Known Gaps** | Baseline metacognitive accuracy — do they know what they don't know? (Flavell's metacognitive knowledge) |
| 5 | **Learning Goal Clarity** | ZPD upper bound — what does success look like? What will they be able to do that they cannot do now? |

The diagnostic is not scored or graded. It is used to calibrate all subsequent phases. No answer is wrong; evasive or uncertain answers are themselves diagnostic signals.

### Phase 2: Case Study with Constraint

After the diagnostic, Socrates generates a scenario specific to the learner's stated goal and assessed level — calibrated to sit at the upper edge of their ZPD. The scenario is realistic, not contrived: it resembles an actual problem a practitioner in this domain would encounter.

Every case study includes one of two constraints, selected based on context:

- **Time constraint**: *"You have 15 minutes. No looking anything up. Begin."* — tests retrieval under pressure, simulating real deployment conditions.
- **No-LLM constraint**: *"Solve this without using any AI tool. Work from first principles and your own knowledge."* — tests genuine competence decoupled from tool-assisted performance.

The constraint is pedagogically non-negotiable. Without it, performance on the case study conflates understanding with access — the learner may produce a correct answer by retrieval augmentation rather than comprehension. The constraint creates the conditions Black and Wiliam identify as necessary for assessment to elicit genuine evidence of understanding.

### Phase 3: Socratic Reflection

After the learner submits their attempt, Socrates asks — in this exact order, without skipping or conflating:

**Step 1**: *"Walk me through your thinking."*
The learner narrates their reasoning process: what they noticed, what they decided, why. This surfaces the reasoning, not just the answer — and frequently reveals gaps invisible in the output.

**Step 2**: *"What could you have done differently?"*
The learner identifies their own weaknesses before being told what they missed. This operationalizes Flavell's metacognitive regulation and Socratic maieutics simultaneously — the learner midwifes their own insight.

**Step 3**: Only after both responses are received does Socrates reveal observed gaps, misconceptions, conceptual confusions, and missed approaches. The skill's observations are always specific, always comparative (what was done vs. what could have been done), and never delivered before the learner has reached their own productive aporia.

This sequencing is the core of the Socratic method in practice. Revealing gaps before the learner has exhausted their own reasoning collapses the elenctic process and reduces the interaction to passive reception rather than active construction.

### Phase 4: Awareness Quadrant Mapping

Synthesizing the diagnostic and reflection phases, Socrates maps the learner's knowledge state across four quadrants adapted from Burch's Four Stages of Competence (Gordon Training International, c. 1970):

```
                    KNOWS IT          DOESN'T KNOW IT
                ┌─────────────────┬─────────────────────┐
  KNOWS THEY    │  Consciously    │  Consciously        │
  KNOW/DON'T   │  Competent      │  Incompetent        │
               │  (solid ground) │  (explicit gap —    │
               │                 │   ready to learn)   │
               ├─────────────────┼─────────────────────┤
  DOESN'T KNOW  │  Unconsciously  │  Unconsciously      │
  THEY          │  Competent      │  Incompetent        │
  KNOW/DON'T   │  (tacit —       │  (blind spot —      │
               │   needs naming) │   highest priority) │
               └─────────────────┴─────────────────────┘
```

The most instructionally critical quadrant is **Unconsciously Incompetent** — blind spots the learner cannot self-report because they are, by definition, unaware of them. The constrained case study and the reflection protocol are specifically designed to make this quadrant visible. A learner who says "I think I mostly understood it" while demonstrating a fundamental misconception in their walk-through is exhibiting classic Unconsciously Incompetent behaviour.

The curriculum addresses quadrants in this priority order:
1. Consciously Incompetent (explicit gaps — learner is primed and ready)
2. Unconsciously Incompetent (blind spots — reframing required before instruction lands)
3. Unconsciously Competent (tacit knowledge — naming it builds transferability)
4. Consciously Competent (confirmed ground — used as scaffolding, not re-taught)

### Phase 5: Personalized Curriculum

After the quadrant mapping is presented, Socrates generates a complete learning curriculum. It is sequenced according to three simultaneous constraints:

- **ZPD anchor**: Begin at the lower ZPD bound; expand toward the upper bound.
- **Bloom sequencing**: Enter at the assessed Bloom level; ascend one level at a time.
- **Quadrant priority**: Address Consciously Incompetent gaps before Unconsciously Incompetent blind spots.

In **Marathon mode**, the curriculum is structured as a multi-week arc with spaced repetition intervals, progressive case studies at increasing Bloom levels, and checkpoint diagnostics at defined milestones.

In **Sprint mode**, the curriculum collapses to highest-leverage concepts only: those sitting at the ZPD boundary and the current Bloom ceiling — the minimum viable knowledge surface that closes the most critical gaps in the available time.

---

## Mode Detection

Socrates detects session mode automatically from natural language signals in the initial request. No explicit flag is required.

### Marathon Mode
*Weeks to months. Full arc. Deep understanding.*

Triggered by signals of long-horizon intent or foundational gaps:

> *"I want to learn..."* / *"I want to master..."* / *"I'm new to..."* / *"teach me from scratch"* / *"deep dive"* / *"I've never really understood..."* / *"I want to actually get this"*

Marathon sessions produce a structured multi-week curriculum with spaced review, escalating case studies, and Bloom-level progression gates.

### Sprint Mode
*Minutes to hours. Highest leverage. Sharpest gaps only.*

Triggered by signals of time pressure, catch-up intent, or scoped review:

> *"quickly"* / *"in an hour"* / *"before my interview"* / *"refresh"* / *"catch up"* / *"just need to understand X"* / *"tonight"* / *"this afternoon"*

Sprint sessions produce a tightly scoped curriculum targeting only the highest-ZPD-gain concepts within the declared time window.

When mode is ambiguous, Socrates defaults to **Marathon**, states the assumption explicitly, and invites correction before proceeding.

---

## The Four Awareness Quadrants

The quadrant model used in Phase 4 is a pedagogical adaptation of the Four Stages of Competence (Burch, c. 1970), with naming conventions adjusted to emphasize *awareness* rather than *competence* — because the critical insight is epistemic, not performative.

| Quadrant | Learner Profile | Instructional Strategy |
|----------|----------------|----------------------|
| **Consciously Competent** | Knows it and knows they know it | Use as scaffolding; build upward to Evaluate/Create levels |
| **Unconsciously Competent** | Knows it but doesn't realize they know it | Name and formalize the tacit knowledge; increase transferability |
| **Consciously Incompetent** | Doesn't know it and knows they don't | Direct instruction with worked examples; learner is primed |
| **Unconsciously Incompetent** | Doesn't know it and doesn't know they don't | Reframe first; create productive aporia; then instruct |

The Unconsciously Incompetent quadrant requires the most careful instructional design. Direct instruction delivered before the learner recognizes the gap is rejected by the prior knowledge schema — the learner's existing (incorrect) model filters out contradicting information. The Socratic elenchus — surfacing the contradiction through questioning — must precede instruction for the instruction to land.

---

## Curriculum Design Principles

Regardless of mode, every Socrates curriculum adheres to the following constraints:

1. **ZPD respect**: No instructional step is placed outside the ZPD boundary. Content that is too far ahead is deferred, not omitted — it is scheduled for a later phase when the boundary has moved.

2. **Bloom sequencing**: Higher-order objectives (Analyze, Evaluate, Create) are never introduced before lower-order foundations (Remember, Understand, Apply) are confirmed. Bloom level is assessed, not assumed from topic familiarity.

3. **Formative checkpoints**: Every curriculum includes at least one formative checkpoint — a diagnostic moment where the learner demonstrates understanding in a new context before advancing. Per Black & Wiliam (1998a), feedback at these checkpoints is specific, comparative, and forward-looking.

4. **Metacognitive threading**: Every session includes explicit moments for metacognitive reflection — "What made this easier than you expected?" / "What surprised you?" These are not optional; they are how the skill trains metacognitive regulation alongside domain knowledge (Flavell, 1979).

5. **No premature resolution**: Socrates never resolves a question the learner hasn't grappled with. If the learner asks "what's the answer?" before attempting the case study, Socrates redirects: *"What's your current best guess, and why?"* The aporia is protected.

---

## Usage

Invoke Socrates within Claude by using `/socrates` followed by your topic or goal:

```
/socrates transformer attention mechanisms

/socrates I need to understand Docker networking before my interview tomorrow

/socrates teach me Bayesian inference from scratch — I have a statistics background
but I've never really understood priors

/socrates I need a quick refresher on database normalization in the next 45 minutes
```

Socrates will detect mode from your phrasing and begin Phase 1 immediately. No configuration required.

---

## License

MIT License. Copyright (c) 2026 Ashutosh Tripathi.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.

Repository: [github.com/zshqv/socrates](https://github.com/zshqv/socrates)

---

## References

Anderson, L. W., & Krathwohl, D. R. (Eds.). (2001). *A taxonomy for learning, teaching, and assessing: A revision of Bloom's educational objectives*. Longman.

Black, P., & Wiliam, D. (1998a). Assessment and classroom learning. *Assessment in Education: Principles, Policy & Practice*, *5*(1), 7–74. https://doi.org/10.1080/0969595980050102

Black, P., & Wiliam, D. (1998b). *Inside the black box: Raising standards through classroom assessment*. Phi Delta Kappan, *80*(2), 139–148.

Bloom, B. S., Engelhart, M. D., Furst, E. J., Hill, W. H., & Krathwohl, D. R. (1956). *Taxonomy of educational objectives: The classification of educational goals. Handbook I: Cognitive domain*. David McKay Company.

Burch, N. (c. 1970). *Four stages of competence*. Gordon Training International. (Widely attributed; original publication date uncertain.) The Four Stages of Competence is widely attributed to Noel Burch at Gordon Training International circa 1970; no verified primary publication exists. The model is cited here in its widely accepted attributed form.

Flavell, J. H. (1979). Metacognition and cognitive monitoring: A new area of cognitive–developmental inquiry. *American Psychologist*, *34*(10), 906–911. https://doi.org/10.1037/0003-066X.34.10.906

Plato. (c. 380 BCE / trans. Jowett, B., 1892). *Meno*. In *The dialogues of Plato* (Vol. 1). Oxford University Press.

Plato. (c. 369 BCE / trans. Jowett, B., 1892). *Theaetetus*. In *The dialogues of Plato* (Vol. 4). Oxford University Press.

Vygotsky, L. S. (1978). *Mind in society: The development of higher psychological processes* (M. Cole, V. John-Steiner, S. Scribner, & E. Souberman, Eds.). Harvard University Press.
