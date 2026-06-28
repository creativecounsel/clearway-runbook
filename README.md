# External Communications Runbook (Template)

A generic, three-part runbook for legal teams at any company who want to help marketing, GTM, comms, policy, or product, and raise the bar on which reviews get the closest review.

This is a template, not a finished system. It's built to be copied, renamed, and filled in with your own company's actual pre-cleared language, SLAs, and risk areas. Out of the box, it's a skeleton: the structure and the thinking behind it are real, the specific content is illustrative.

## The idea

Most legal bottlenecks aren't hard questions. They're easy, repeated ones, asked a lot because there's nowhere for the answer to live. This runbook is designed to give the common case a fast path and the uncommon case a clear one, instead of treating every request the same way.

## How it's organized

**Ground Floor** is for the moment someone just needs an answer. It should contain pre-approved language organized by category (`/clearway`) and turnaround times by request type (`/slas`), plus a router (`working-on-router.md`) that points to the right place based on what someone's actually working on. Most requests should resolve here without ever reaching a person.

**Workshop** is for anything that doesn't have a ready answer. It splits into drafting guidance (for whoever's writing the copy) and reviewing guidance (for whoever's checking it), plus three supporting tools: a comment-label taxonomy so reviewers can signal exactly what's required versus optional, a decision test for whether something needs legal review at all, and a table of common risky phrasing patterns with fixes.

**Archive** is for understanding why the rules exist, not just what they are. These are reference docs, not something anyone reads front to back. Drafters and reviewers dip into the relevant one when a question actually comes up.

**Maintenance** covers keeping the system current and routing within the legal team itself, since a runbook that goes stale loses trust fast, and a routing table only helps if it's accurate.

## Structure

```
/ground-floor
    working-on-router.md          → fast router: find your task, see what to watch for
    /clearway                      → pre-approved language, organized by category
    /slas                          → turnaround times by request type
/workshop
    comms-drafting-guidelines.md
    legal-reviewing-guidelines.md
    comment-labels.md              → REQUIRED / RECOMMENDED / OPTIONAL review taxonomy
    does-legal-need-to-review.md   → decision test for when review is actually needed
    language-patterns-to-watch.md  → common risky phrasing patterns and fixes
/archive
    ai-basics.md
    ip-basics.md
    eu-law-basics.md
    us-law-basics.md
    product-fundamentals.md
/maintenance
    runbook-maintenance.md
    team-routing.md                → who handles what within the legal team
ai-tool-instructions.md
```

## Design principle

The goal is the same rigor applied once, upstream, rather than re-litigated every time a similar request comes in. Consistency comes from doing the work once and reusing it, not from skipping the work.

## Adapting this for your own company

This is a generic skeleton, not a finished runbook. To make it real:

- Replace the Clearway entries with your own pre-cleared language
- Set actual SLAs and escalation contacts for your team
- Fill in the Archive docs with the risk areas that actually apply to your business. AI, IP, EU/US law, and product fundamentals are examples, not a fixed list.
- Run it for a stretch, then check the request log for whatever keeps showing up unhandled. That's your next Clearway entry.


---

*This page is a structural template, intended for plug-and-play use by any company. It is not legal advice and does not reflect the actual legal work product, internal guidance, or analysis of any real company, client, or matter.*
