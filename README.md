# Skills

My reusable agent skills, organized using the [Agent Skills format](https://learn.chatgpt.com/docs/build-skills).

## Available skills

| Skill | Purpose |
| --- | --- |
| [make-it-click](skills/make-it-click/SKILL.md) | Explain concepts through concrete examples, causal mechanisms, and useful mental models. |
| [evaluate-tech](skills/evaluate-tech/SKILL.md) | Research and compare tools by capability, cost, and learning value. Requires web browsing. |

## Install

With a current [GitHub CLI](https://cli.github.com/), install either skill for Codex:

```sh
gh skill install jaiamin/skills make-it-click --agent codex --scope user
gh skill install jaiamin/skills evaluate-tech --agent codex --scope user
```

Use `--scope project` to install in the current project instead. For other supported agents, change `--agent`; see `gh skill install --help`.

You can also ask Codex's built-in `$skill-installer` to install either skill from this repository, or copy a complete skill folder into your agent's skills directory. Keep each folder's supporting files together.

## Use

In Codex, invoke a skill explicitly:

```text
$make-it-click Explain how HTTP caching works.
$evaluate-tech Compare Python web frameworks for a small personal project.
```

Both skills also allow automatic selection when the request matches their descriptions.

## Layout

```text
skills/
  make-it-click/
    SKILL.md
    agents/openai.yaml
    assets/icon.svg
  evaluate-tech/
    SKILL.md
    agents/openai.yaml
    assets/icon.svg
    references/research-rubric.md
```

`SKILL.md` contains the portable instructions and required metadata. `agents/openai.yaml` supplies optional OpenAI-specific appearance and invocation settings. References and assets travel with each skill.

This repository stores the source files. Installing makes a local copy; later repository changes require an update or reinstall.
