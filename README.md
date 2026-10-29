# agnthub skill fixture

Public test fixture for agnthub Skill Dependencies. Each skill declares (or deliberately omits) a strict semantic `metadata.version` in its `SKILL.md`:

| Skill | `metadata.version` at `v1` | at `v2` |
| --- | --- | --- |
| fixture-greeter | `1.2.0` | `2.1.0` |
| fixture-unversioned | missing | missing |
| fixture-loose | `1.0` (not strict semver) | `1.0` |
| fixture-preview | `2.0.0-rc.1` | `2.0.0-rc.1` |
