# Reddit Seed User Research

[中文说明](README.zh-CN.md)

[![GuanTou Lab](https://world.guantou.site/badge.svg?theme=dark&accent=red&lang=en&size=sm)](https://world.guantou.site/)

A Codex skill for finding Reddit seed-user opportunities for a project and drafting helpful, human replies. It is designed for demand discovery and value-first outreach, not automated posting.

## What It Helps With

- Building a local `brand.md` profile from a project directory.
- Searching Reddit for real user needs, repeated pain points, and relevant communities.
- Ranking opportunities by fit, intent, risk, and link policy.
- Drafting replies that help first and disclose affiliation when links are appropriate.
- Producing a bilingual report using `references/report-template.md`.

## Installation

```bash
git clone https://github.com/Leochens/skill-reddit-seed-user-research.git ~/.codex/skills/reddit-seed-user-research
```

Then ask Codex:

```text
Use $reddit-seed-user-research to find Reddit seed-user opportunities for this project.
```

## Usage Notes

This skill does not post automatically. The user should review every target thread, subreddit rule, account condition, and reply draft before publishing anything.

`brand.md` is treated as a local research artifact. In Git repositories it should be ignored through `.git/info/exclude`, not committed to the shared repository.

## Repository Layout

```text
SKILL.md                              Skill instructions
agents/openai.yaml                    Codex UI metadata
references/brand-template.md          Local brand profile template
references/report-template.md         Bilingual Reddit report template
```

## More From GuanTou Lab

This skill is part of GuanTou Lab's personal agent workflow toolkit. Visit [GuanTou World](https://world.guantou.site/) to see the broader project and product universe.

## License

MIT License. See [LICENSE](LICENSE).
