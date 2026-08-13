---
name: decision-maker-mapper
description: Identify who actually holds the hiring or buying decision at a target organization, what their public track record reveals about their priorities, and one honest, sourced opening angle for outreach. Use before drafting any cold email, LinkedIn message, or application intro. Trigger this when the user names a company or organization and a role or goal (a job they're applying to, a service they're pitching) and asks who to contact, who the decision-maker is, or wants help finding an opening angle. If the user has not yet named a specific person or org, ask for it before starting.
---

# Decision-Maker Mapper

Finds the actual person behind a hiring or buying decision, not just a title, and reads their public record for what they genuinely care about. This runs BEFORE any outreach gets drafted. It is not a general company research tool — the deliverable is a specific person and a specific, verifiable reason to open with.

## Workflow

1. **Get the inputs.** Need: the organization name and the goal (a role being applied to, or a service/product being pitched). If either is missing, ask before starting.

2. **Identify the decision-maker.** For a job application, this is usually the hiring manager for the team, not HR or a general recruiter, unless the posting only lists a recruiter contact. For a client pitch, it's whoever owns the budget or the relationship, not the first name in a general inbox. Search the org's team/leadership page, recent press, and LinkedIn to confirm who currently holds that role. State a confidence level (confirmed / likely / unconfirmed) — do not present a guess as a fact.

3. **Pull their public track record.** Search for what this person has published, said in interviews, or posted recently: LinkedIn posts, panel appearances, bylined articles, podcast guest spots, conference talks. Look for patterns — what do they talk about unprompted, what language do they use for their own priorities. Every point needs a source.

4. **Note tenure and context.** How long has this person been in the role? Did they arrive with a stated mandate (turnaround, new initiative) or inherit steady-state work? A person six months into a role reads differently than someone five years in — say which, if it can be determined.

5. **Surface one honest opening angle.** Based on steps 2 through 4, suggest one specific thing the user could reference in an opening line — not a generic compliment, something that shows real research. If nothing solid turns up, say that directly rather than inventing a hook.

6. **Self-check before delivering:**
   - Every name, title, and claim traces to something actually found in search — no filled-in gaps presented as fact
   - Confidence levels are honest; "unconfirmed" is used freely where evidence is thin
   - No quote runs 15+ words, and no source is quoted more than once — paraphrase the rest
   - No em dashes

## Output format

Deliver inline in chat, not as a file:

- **Decision-maker:** name, title, confidence level
- **What they care about:** 2-4 bullets, each with a source
- **Tenure/context:** one line
- **Opening angle:** one specific, sourced suggestion, or a note that none surfaced clearly

## Notes

- Expect 4-8 searches per person: confirming the role holder, then their public statements, then tenure/context.
- If the organization is small enough that no individual has a public footprint, say so plainly rather than padding with a generic title-only answer.
- This complements Org Signal Scanner (the "why now" for the organization) and Role Strategy Analyzer (the "why this role") — run this one last, once the user knows who to actually write to.
