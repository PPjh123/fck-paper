# fck-paper

Evidence-based, brutally direct manuscript critique for private review work.

`fck-paper` is a Codex skill for turning rigorous scientific peer review into a high-aggression private roast without losing factual discipline. It is designed for cases where a user explicitly asks for a savage, profane, or no-mercy evaluation of a scientific manuscript.

## What It Does

- Inspects the manuscript before judging it.
- Identifies the central claim and compares it with the actual evidence.
- Prioritizes broken claim-method-evidence chains, invalid task definitions, unsupported generalization, weak validation, missing baselines, leakage, and reproducibility gaps.
- Produces a blunt critique that targets the manuscript, methods, claims, experiments, and writing.
- Keeps hard boundaries against personal attacks, identity-based abuse, invented defects, and unsupported misconduct allegations.

## Install

Copy this folder into your Codex skills directory:

```powershell
Copy-Item -Recurse .\fck-paper "$env:USERPROFILE\.codex\skills\fck-paper"
```

Then restart Codex or reload skills if your environment supports skill reloads.

## Usage

Ask Codex to use `fck-paper` on a manuscript:

```text
Use fck-paper to evaluate this manuscript.
```

The skill is intended for private critique. For formal author or editor comments, translate the critique back into professional peer-review language.

## Safety Boundaries

This skill attacks the paper, not the people. It should not be used to harass authors, target protected traits, allege misconduct without evidence, or invent defects.

## License

MIT
