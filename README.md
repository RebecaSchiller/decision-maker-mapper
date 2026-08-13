# Decision-Maker Mapper

A Claude skill that identifies who actually holds a hiring or buying decision at a target organization, before you write to them.

Most outreach gets addressed to a title, not a person, or to a person with no real read on what they care about. This skill has Claude find the real decision-maker, pull their public track record (interviews, posts, talks), note their tenure and context, and surface one specific, sourced opening angle, honest about confidence level throughout.

Output covers:

- **Decision-maker** — name, title, and how confident the identification is
- **What they care about** — sourced points pulled from their own public statements
- **Tenure/context** — how long they've been in the role and what that suggests
- **Opening angle** — one specific, verifiable hook, or an honest note that none surfaced

Delivered inline in chat, not as a file, since this is meant to be used right before drafting a message.

## How to use it

1. Download [SKILL.md](./SKILL.md) from this repo.
2. In Claude, go to **Customize > Skills**, click **+ Create skill > Upload a skill**, and upload the file (as a .skill/.zip package, or package it yourself — see [Anthropic's skill docs](https://support.claude.com/en/articles/12512198-creating-custom-skills)).
3. Give Claude an organization name and what you're pursuing (a role, a pitch), and ask who the decision-maker is.

## Notes

- Requires web search / web fetch access in Claude.
- Works best for organizations and people with some public footprint. For very small teams with no public presence, the skill says so rather than guessing.
- No affiliation with or endorsement by Anthropic. Shared as-is; feel free to fork and adapt.
