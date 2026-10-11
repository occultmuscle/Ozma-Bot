*Section of [[Hegemony Standard Time]]. Consolidated — Stardate 120260813.*
*Supersedes: Draft 120260811 · [[Designation and the Envelope]]*
*Related: [[Battle]] (Interval, the Five Constraints, PATER SAGO) · [[Time and Fire]] · [[Treasury]] · [[The Attention Codex]] · [[Praetor's Battle Rhythm — Command Cycle]]*

---

## Premise

**Time is not perceived. It is modeled.**

No faculty senses time. What passes for perception is stored duration retrieved and projected forward — you ran this before, it cost this much, so this will cost about that. A person who forecasts well has a stocked library. A person who forecasts badly does not have a defective sense; they have a thin library. There is no organ to be missing.

This section defines the objects that scheduling collapses into one word. [[Time and Fire]] defines the mechanism that stocks the library.

---

## The Hierarchy

```
Timeline
└── Phase — a bounded division of the Timeline
    └── Objective — the condition the Phase must achieve
        └── Target — selected for engagement toward the Objective
            └── Interval — the span in which the Target can be hit
                └── Task / Order — the action assigned against the Target
```

**Timeline** — the ordered span of the Operation. Everything below sits on it.

**Phase** — a bounded division of the Timeline. An Interval at operational altitude, with conditions that open and close it. A Phase is not a length of time; it is a length of time *plus the conditions that hold while it runs*.

**Objective** — the condition the Phase must achieve. Not an Interval. Not a Position. A **state**. Objectives have no duration; they are either met or not met when the Phase closes.

**Target** — what is selected for engagement in service of the Objective. The thing force is applied to. *(See [[Battle]] — Target as recipient of force; PATER SAGO's Target phase for selection and class declaration.)*

**Task / Order** — one object. The action plus its purpose, with the Order as the vehicle that transmits it.

**PATER SAGO runs inside a Phase, continuously — not once per Operation.** Each loop selects a Target, engages it, and reports. Perceive detects Phase-level Drift. AAR feeds the next loop. *(See [[Time and Fire]] — one pass of the loop at task scale is a **Run**.)*

---

## Interval

**An Interval is the bounded span between two Positions.** *(See [[Battle]] — the span across which Intention travels before contact.)*

In time, this resolves precisely:

> **The temporal Interval is the span within which a Target can be hit** — the affordance of force over the Target across the possible interaction.

Outside the Interval, force does not reach. The Target is not defended; it is simply **unengageable**. This is the object that scheduling actually manipulates.

Corollaries of the definition:

- A Target with no Interval cannot be engaged, regardless of readiness.
- Two Targets whose Intervals do not overlap cannot be engaged in one crossing.
- A dependency is one Target whose Interval must close before another's opens.

---

## The Objects

**Position** — a single point on the Timeline. No duration.

**Deadline** — a Position, not an Interval. The last moment a disposal may occur. It holds nothing; you cannot work inside it. When the last available Interval closes *on* the Deadline, there is no retry. That configuration is the one worth flagging.

**Estimated Duration** — the forecast of the crossing, before it is made. Expressed in Moments. *(See [[Time and Fire]] — the crossing decomposes as **Run = Delay + Work**.)*

**Duration** — defined. What the crossing actually cost. **Enters the library.**

**Target Board** — Objectives and untriaged Targets. Silent; nothing on it fires. An item here has not been gated and may not yet be a Task. *(Added 120260813. The Docket assumed a Task already existed; nothing named where a thing lives before that. Gating procedure: [[Praetor's Battle Rhythm — Command Cycle]], The Gate.)*

**Docket** — Tasks owed disposal. Ordered by dependency. Not time-bound. Exists independent of any designation and independent of any Order.

**The Docket is the register.** Designation is a state change *within* it, not a move to another list.

> **Schedule — struck 120260813.** Not an object. A Schedule is the *view* of designations already made, rendered by the Calendar. Nothing is ever placed on it. What exists is the Target Board, the Docket, the Timeline, and the designations cut into it.

---

## The Two Acts

Scheduling is two acts. Collapsing them is what breaks the model.

**Allot** — cut the Interval. Set the edges. Claims **Time**. An empty allotment is a real object.

**Assign** — bind the Task to that Interval. Claims **Attention**. Assigning allots nothing.

Either order is valid:

- **Allot then assign** — hold the Interval, load it after. Salat anchors work this way.
- **Assign then allot** — the Task exists on the Docket, then an Interval is cut to fit its Estimated Duration.

The **Order** transmits the result of both acts. It is the record and the vehicle, not the act itself.

### States

| State | Condition |
|---|---|
| Undocketed | Not claimed. Nothing owed. |
| Docketed, unassigned | Owed. No designation. The **Backlog**. |
| Phased | Bound to a Phase, not yet to an Interval. |
| Assigned | Bound to a designated Interval. |
| Ordered | Transmitted. Now another party's obligation. |
| **Pending** | Was assigned, ran, did not dispose. Carries envelope residue. |
| Disposed | Resolved. |

### Pending

**Carry-forward is the act. Pending is the state.** An unresolved Task returns to the Docket *unassigned* — but not as a fresh item.

| | Docketed | Pending |
|---|---|---|
| History | Never started | Was assigned, ran, did not dispose |
| Envelope | Full Attack when it runs | **Attack already paid. Release already running.** |
| Cost to resume | Full **Load** | **Reload** — depends on elapsed gap |

**Pending has a half-life.** Returned to before Release completes, it resumes cheap from a partial fall. Left a week, it resumes at full Load — the residue is gone and it is functionally fresh again.

> **Docket-sorting rule: Pending items with Release still running outrank fresh Docket items for the next available Block.** The residue is perishable capital. Spending it is free; letting it expire is not.

At operational altitude, carry-forward is issued as a **FRAGO**.

---

## Bounds and Envelope

Designation has **two axes**, not one. Collapsing them is what made the old grade table never sit right.

### Axis 1 — Bounds: who set the edges

| Grade | Edges set by | Character |
|---|---|---|
| **Slot** | External barriers | Not yours to move. Salat, class times, store hours, Crew Intervals. |
| **Block** | You | Declared. "Block out time." The Hour is a Block of ten Moments. |

That is the entire grade list. Two entries.

> **Window — retired 120260812.** It was carrying three jobs at once: opportunity, aperture, and HST's "tactical window." Dropped for collision, not for error — in signal processing a window function *is* an amplitude envelope over a bounded segment, which is precisely why it kept sliding between the two axes. The bounds sense becomes Slot or Block; the shape sense becomes the Envelope.

**Reserve — retired 120260813.** Proposed as a replacement for Block when Block was thought to collide with [[Battle]]'s *denies effect*. Context disambiguates; Block stands.

**Reading rule:** identify the grade before moving anything **on the Timeline**. You can move a Block. You cannot move a Slot.

**Nesting:** a Block may be cut inside a Slot, or between two Slots. Externally-set office hours are a Slot; the portion you commit is a Block within it. The Battle Rhythm's four operational spans are Blocks cut between Salat Slots.

### Axis 2 — Envelope: the shape inside the bounds

The Envelope is Effort plotted over time — the rise and fall of Force on the Target across the Interval. [[Battle]] holds that Force is the power to cause change and Effort is intention made measurable; the Envelope is that measure given a shape.

**ADSR** — Attack, Decay, Sustain, Release.

| Stage | In the crossing |
|---|---|
| **Attack** | The **Load**. Getting on target the first time. This is where Delay is paid. |
| **Decay** | Settling from peak effort to working effort. |
| **Sustain** | The productive span. Hold folds in here. |
| **Release** | Falling off the target. Residue keeps running after hands come off. |

**Delay is a held Attack.** It belongs to the gate — PATER SAGO's Set phase — not to the Envelope as a parameter.

### Load · Reload · Recovery

| Term | Meaning |
|---|---|
| **Load** | The Attack. Getting on target the first time. |
| **Reload** | Getting back on after a gap. Derived: Release × gap ÷ Attack. |
| **Recovery** | Back on target after the shot, no gap paid. *(See [[Time and Fire]].)* |

### The calendar's lie

A calendar draws every allotment as a **rectangular envelope** — instant on, full amplitude, instant off. No Attack, no Release. This is why calendars consistently overstate what an allotment contains.

Rectangular windows also cause **spectral leakage**: energy smears past the boundary because the hard discontinuity is unphysical. A hard-cut Task does the same. Attention does not stop at the edge; it bleeds into the next allotment, which is why back-to-back hard cuts degrade both.

**The Grace Shift is the taper.** It was built before it was named.

### Superseded vocabulary

| Retired | Replaced by |
|---|---|
| Window (as a grade) | **Bounds** — Slot or Block |
| Window (as shape) | **Envelope** |
| Ramp | **Attack** / **Load** |
| Reserve | **Block** |
| Allotment (as a grade) | Not a grade — a share, budgeted at the Week |
| Bracket | Notation only. Not an object. |

---

## Placement — plot Slots first

The first act of planning a Day is not budgeting. It is **plotting the Slots** — the fixed, externally-set engagement Intervals — and only then cutting Blocks into what remains.

1. **Plot Slots** — Salat, RVs, Crew Intervals, store hours, class times
2. **Cut Blocks** into what remains
3. **Assign** from the Docket
4. **Allot** against Estimated Duration

**Budget at the Week. Designate at the Day. Cross at the Moment.**

Work runs mostly on Block — your edges. Household runs mostly on Slot — theirs. A budget can be met and the Day still fail, because the binding constraint was never quantity. It was **overlap**.

---

## Duration Against Designation

The Task carries an Estimated Duration. The designated Interval has a length. These are different numbers, and their relationship is the whole of scheduling:

| Relation | Result |
|---|---|
| Estimate **<** designation | Slack. Absorption available. |
| Estimate **=** designation | Zero slack. No absorption. |
| Estimate **>** designation | Overrun. Carry-forward. |

**Overrun is an allotment failure, not an assignment failure.** The Task was correct. The cut was too short — because a Constraint was not stored.

---

## The Constraints on the Crossing

Variance is not one thing. It is five, acting orthogonally on the crossing between Estimated and defined Duration. *(See [[Battle]] — The Five "Classical" Constraints of Force.)*

| Constraint | Corrupts | Expression in duration |
|---|---|---|
| **Uncertainty** | the input | You cannot estimate what you cannot see. Unknown scope. |
| **Friction** | the transmission | The crossing costs more per unit than clean. |
| **Time** | by duration | The longer it runs, the more the plan rots. |
| **Drift** | the direction | You finish something adjacent to what you started. |
| **Chance** | by external variance | Uncorrelated forces intersect the Interval. |

Each Constraint is either **stored** — in the library, foreseeable, countable — or **unstored**. The unstored set is never empty. Therefore the forecast lands under 100% by definition. This is structural, not a defect in the forecaster.

**Retrieval is the only lever.** It converts unstored to stored. Calling ahead to obtain office hours is Uncertainty converted by hand — and it resolves the engagement Interval before committing to it.

**Phase-level Drift is what kills Operations.** Tasks finish; the Objective moves. Task-level accuracy does not protect against it. Perceive is the countermeasure.

> **The quantitative form of this finding** is the Utilization Ceiling on [[Hegemony Standard Time]]. Because the unstored set is never empty, booking above ~80% of available Moments produces queue collapse rather than throughput.

---

## Corollaries

**Prediction quality is a function of stored duration data.** No library, no forecast — only guessing dressed as forecast. The Watch Log is a duration library. *(It is not currently storing Duration — see [[Time and Fire]], the standing defect.)*

**Variance belongs to Constraints, not to the operator.** A Task that ran long revealed a Constraint not yet stored. It did not reveal a defect in you.

**Attention accumulates. Time does not.** If the target is Time, work the Attention.

**Investment cancels future claims. It does not bank Time.** Every system built now kills a recurring claim on a later Interval.

**A chain reports what slips. A list fails silently.** Order the Docket by dependency or lose the report.

**An Objective without a Phase has no closing condition.** It cannot be failed, therefore it cannot be assessed.

**An unordered Task is yours alone.** Until an Order transmits it, no one else is obligated and no one else can be assessed against it.

---

## Scale

The same objects run at operational altitude:

| Task scale | Operational scale |
|---|---|
| Designated Interval | Phase |
| Task / Order | Objective / Decisive Point |
| Docket | Unphased task list |
| Carry-forward | FRAGO |
| AAR | Assess / BDA |

---

## Open Items

1. ~~**Terminology collision.** The Hour as "tactical window."~~ **RESOLVED 120260813 — Window is retired entirely.** Bounds and Envelope are the two axes; the Hour is a **Block** of ten Moments. Amended on [[Hegemony Standard Time]].

2. **Drift, two readings.** [[Battle]] lists Drift as one of the Five Constraints. HST amendment 120260803 rules Drift a *symptom*, detected at Perceive, not a target. Both hold — a Constraint can present as a symptom — but the relationship should be stated rather than inferred.

3. **The Timeline object.** OPORDs exist; the Ops Log exists; no explicit Timeline sits between them. Phases are unnamed, so AAR has nothing to report against except individual Tasks. *Candidate resolution:* name the **Epoch as Phase** — proposed in the Resources and the Moment amendment, not yet ratified.

---

## Consolidation Note — 120260813

This note replaces the 120260811 draft and the appended amendment block. Folded into the body: Schedule struck, Target Board added, Ordered state restored, reading rule corrected, unordered-Task corollary added, placement order added, Open Item 1 closed.

**Vault housekeeping:** [[Designation and the Envelope]] is the older, longer draft of this same material. It should be archived or deleted.
