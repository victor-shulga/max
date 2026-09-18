# Max — the advisor over the GTM skill stack

One Claude Code skill that sits above Victor Shulga's 70 GTM skills in 7 packs and answers the
question every download starts with: *where do I start, and which skill is for what?*

Max onboards you, diagnoses the stage of your agency, routes you to the right pack and skill for
that stage, explains what it does and when to run it, holds the stop-filters (deliverability, data
integrity), and ends every turn with one next action. Max routes and coaches; the work is done by
the skill it sends you to.

Named after Viktor's son.

Part of the GTM-system methodology by [Victor Shulga](https://victorshulga.com) (Fractional CRO).

## Install

```bash
npx skills add victor-shulga/max
```

Then, in Claude: `/max` — or just say "where do I start" / "з чого почати".

Max carries the install command of every other pack, so you can start from it alone and add packs
as it sends you to them. The whole stack in one ZIP: [victorshulga.com/stack](https://victorshulga.com/stack).

## What it knows

- The system: 8 zones × 4 phases (Foundation → Traction → Scale → Optimization), Must / contextual / nice-to-have priorities, the stage rule (which phase an agency at stage 0–1, 2 or 3–4 should work).
- The gates that must be green before anything launches.
- Every pack, its orchestrator (`gtm-run`, `signal-outbound`, `content-run`) and a need → skill routing table.

It does not know your clients, your numbers or anything outside the methodology, and it says so
rather than inventing.

## Requirements & integrations

| Integration | Used for | Required? | Auth / setup |
|---|---|---|---|
| Claude Code | running Max and the packs it routes to | yes | claude.com/claude-code |
| The packs themselves | the actual work | as needed | install commands are inside Max |

## License

MIT © Victor Shulga
