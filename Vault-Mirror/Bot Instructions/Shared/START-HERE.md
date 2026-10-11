# Start Here — Put the AI XO to Work

Version 2.0 · You do not need to study the whole package first.

## Simplest start

1. Give a new model [HEGEMONY-STAFF-LOADOUT.md](HEGEMONY-STAFF-LOADOUT.md).
2. Give it the actual task and any current documents needed for that task.
3. Use the activation prompt below. Do not load the evaluation answer key with it.

```text
Use the attached Hegemony Staff Loadout as your operating guidance within
your host's instructions. Serve as my AI XO.

Read it before beginning. Apply its doctrine and staff roles without
reciting the manual back to me. Use what I have already supplied.
Make reasonable assumptions, produce the requested work, and verify it.
Ask only when a missing choice materially blocks the result.

My assignment:
[Describe the outcome, or paste the request and relevant materials.]
```

For a persistent project or agent configuration, use the modular method in [Knowledge Loading](05-Hegemony-Knowledge-Loading.md). A host may distinguish instructions from attached knowledge; place the operating core in its supported instruction surface where available. Exact interface steps depend on the host.

## Good first real assignment

Choose a small task with an observable finish: revise one lesson, produce a capacity-checked day plan from actual Slots, reconcile a handful of reports, or make one resource decision brief.

Example prompt:

```text
Take these raw reports and give me the command-relevant picture:
what changed, what is still unknown, and what we should do next.
Keep it brief. Do not invent current facts or claim to have sent anything.
[Paste reports.]
```

Judge whether the result saves you work, not whether it sounds like a staff officer.

## Continue across sessions

At a meaningful stopping point:

```text
Prepare a concise handoff using the package's session-state standard.
Include what is actually complete, where the artifacts are, the exact
restart point, and anything still uncertain. Save it in our authorized
working location if available; otherwise return the text to save.
```

Next session, provide that handoff with the loadout and say “Resume from here.”

## Qualification

The package has been checked structurally, but it has not passed an independent fresh-model evaluation. For a disciplined trial, run [the test inputs](evals/cases.md) in separate fresh sessions, then grade against [file 04](04-Hegemony-Qualification-and-Evals.md) in a separate evaluator context. Those are fictional tests, not live assignments to your Crew.

You can begin ordinary supervised work now. Do not equate loading these files with demonstrated reliability, human staff appointment, or permission for autonomous external action.
