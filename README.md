# Write Technical English

`write-technical-english` is a Codex skill for consolidating terminology and replacing
unnecessary jargon in technical prose. It favors consistent terminology and direct
language while preserving technical meaning, exact identifiers, requirement force,
evidence scope, and uncertainty.

The skill applies principles adapted from ASD-STE100 Simplified Technical English to
software and general technical writing. It does not claim strict ASD-STE100
compliance.

## Install

Ask Codex to install the skill from this repository:

> Use `$skill-installer` to install `write-technical-english` from
> `https://github.com/sdewell/write-technical-english-codex/tree/v0.1.0/.agents/skills/write-technical-english`.

If the skill does not appear after installation, restart Codex.

## Use

Invoke the skill explicitly with `$write-technical-english`. Automatic invocation is
disabled so that the skill does not change ordinary conversation or unrelated work.

Examples:

```text
Use $write-technical-english to revise README.md for a mixed technical audience.
```

```text
Use $write-technical-english to review this release note for ambiguity. Report issues,
but do not edit the file.
```

```text
Use $write-technical-english to review this specification and implementation plan,
then draft a report from these results. Preserve requirements, measured values,
evidence limits, and uncertainty at their original strength.
```

## What it does

The skill:

- Identifies the audience, artifact type, and governing terminology.
- Consolidates competing terms for one concept and replaces unnecessary jargon only
  when a simpler term preserves the meaning.
- Protects identifiers, commands, paths, formulas, quotations, and canonical labels.
- Preserves actors, conditions, evidence scope, uncertainty, requirement force, and
  technical meaning.
- Applies writing profiles for reports, procedures, specifications, and code-related
  prose.
- Uses a null edit when the source has no demonstrated correctness or clarity defect.
- Respects named passage and file boundaries.

It can help with documentation, reports, plans, specifications, procedures, agent
instructions, code comments, diagnostics, release notes, and terminology reviews for
broad or mixed audiences.

## Limitations

This skill is a writing aid. It does not:

- Replace technical review or subject-matter expertise.
- Certify text as ASD-STE100 compliant.
- Apply the complete ASD-STE100 controlled dictionary.
- Override project terminology, schemas, standards, or other governing sources.
- Invent or expand technical content from sparse source material.
- Apply to code, casual conversation, or unrelated brainstorming.

For strict ASD-STE100 interpretation or compliance work, obtain the current standard
from the [official ASD-STE100 downloads page](https://www.asd-ste100.org/STE_downloads.html).

## Package contents

The installable skill is under
[`.agents/skills/write-technical-english`](.agents/skills/write-technical-english/).
It contains the skill instructions, Codex interface metadata, and the references that
the workflow loads when needed.

## License

The project-authored files are available under the [MIT License](LICENSE).

## Independence and trademarks

This independent project is not affiliated with, endorsed by, certified by, or
approved by ASD or the ASD Simplified Technical English Maintenance Group (STEMG).
ASD-STE100 Simplified Technical English is a registered trademark of ASD.
