# Victor Shulga GTM skill stack — catalog

Every public skill of the GTM-system methodology by [Victor Shulga](https://victorshulga.com) (Fractional CRO): **70 skills in 7 packs + Max**, 4 standalone skills. Generated 2026-09-22 from the repos themselves, so this page is always the current version — bookmark this link, not a copy.

## Start here: Max, the orchestrator

`max` — Max — the GTM-system copilot: the advisor that sits ABOVE Victor Shulga's skill stack and guides a person who downloaded the skill bundles.

```bash
npx skills add victor-shulga/max
```

Then in Claude: `/max`. Max asks where you are, routes you to the right pack and skill for your stage, and carries the install command of every pack below.

## How to install (and update)

| You have | Do this | Updating later |
|---|---|---|
| a terminal | `npx skills add victor-shulga/<pack>` installs a whole pack; `npx skills add victor-shulga/<pack>/<path>` installs one skill (both commands are in the tables) | run the same command again |
| no terminal, Claude.ai or Claude Desktop | download the ZIP from the skill page (ZIP column) → Settings → Capabilities → Skills → Upload a skill | download and upload the ZIP again |
| no terminal, Claude Code | download the ZIP, unpack the folder into `~/.claude/skills/`, restart Claude | replace the folder |
| want everything at once | one ZIP with every pack: [victorshulga.com/stack](https://victorshulga.com/stack/) | download it again |

Skills that are not listed here are private to Viktor's own workspace and are run by him for you, not installed on your side.

## gtm-strategy-skills — strategy (15 skills)

Install the whole pack: `npx skills add victor-shulga/gtm-strategy-skills` · repo: https://github.com/victor-shulga/gtm-strategy-skills

Lost inside the pack? Run its orchestrator `gtm-run` first — it drives the other skills in order.

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `gtm-run` — orchestrator, start here | Orchestrate the full GTM strategy flow for an IT agency from a website URL (cold audit). | `npx skills add victor-shulga/gtm-strategy-skills/skills/gtm-run` | — |
| `01-intake` | Step 1 of the GTM flow. Scrape an IT agency website (cold audit) and produce a structured Company Snapshot — services, claims, positioning, proof and case studies,… | `npx skills add victor-shulga/gtm-strategy-skills/skills/01-intake` | — |
| `02-stage-diagnostic` | Step 2 of the GTM flow and CHECKPOINT 1. Diagnose an IT agency growth stage 0-5 from the Company Snapshot using the agency-path model, plus the Sales-Market-Fit lens (L,… | `npx skills add victor-shulga/gtm-strategy-skills/skills/02-stage-diagnostic` | — |
| `03-market-icp-persona` | Step 3 of the GTM flow and CHECKPOINT 2 (Market -> ICP -> Persona). Build the ICP top-down in three levels for an IT agency cold-audit — first propose the 3 best target… | `npx skills add victor-shulga/gtm-strategy-skills/skills/03-market-icp-persona` | — |
| `04-market-sizing` | Step 4 of the GTM flow. Size the market the client chose in step 3 using Viktor's TAM-SAM-SOM framework — computed BOTH top-down (public market data, cut to the relevant… | `npx skills add victor-shulga/gtm-strategy-skills/skills/04-market-sizing` | — |
| `05-competitor-gap` | Step 5 of the GTM flow (right after market sizing, BEFORE positioning and offers). | `npx skills add victor-shulga/gtm-strategy-skills/skills/05-competitor-gap` | — |
| `06-positioning` | Step 6 of the GTM flow (after competitor+GAP, before value prop). Builds the agency's positioning from the whitespace found in step 05, gated by the agency's stage (0-4). | `npx skills add victor-shulga/gtm-strategy-skills/skills/06-positioning` | — |
| `07-value-prop` | Step 7 of the GTM flow (right after the positioning step 06, which it CONSUMES — anchor/enemy/category/statement come from 06, not reinvented here). | `npx skills add victor-shulga/gtm-strategy-skills/skills/07-value-prop` | — |
| `08-offers` | Step 8 of the GTM flow. Turn the chosen market, ICP, tiers and VP into concrete offers — an offer ladder (hook/free -> entry/paid pilot -> core -> continuity) plus… | `npx skills add victor-shulga/gtm-strategy-skills/skills/08-offers` | — |
| `09-buyer-journey` | Step 9 of the GTM flow. Map the buyer's journey for the chosen persona — stages from unaware to advocacy (unaware -> problem-aware -> solution-aware -> vendor… | `npx skills add victor-shulga/gtm-strategy-skills/skills/09-buyer-journey` | — |
| `10-materials-plan` | Step 10 of the GTM flow. Plan the marketing materials/content as a SCORED inventory mapped to the buyer journey — each asset gets a status (To-Do/In progress/Done), a… | `npx skills add victor-shulga/gtm-strategy-skills/skills/10-materials-plan` | — |
| `11-channels-plan` | Step 11 of the GTM flow. Recommend which lead-gen channels to go into, driven by the stage, the SMF gap (usually L), where the ICP/persona actually hangs out (from 03),… | `npx skills add victor-shulga/gtm-strategy-skills/skills/11-channels-plan` | — |
| `12-docs-plan` | Step 12 of the GTM flow. Recommend which INTERNAL documents/playbooks to formalize, from the 47-docs-by-5-stages matrix (Doc 2), as a scored inventory (status, quality… | `npx skills add victor-shulga/gtm-strategy-skills/skills/12-docs-plan` | — |
| `13-action-plan` | Final step of the GTM flow and CHECKPOINT 3. Synthesize all prior artifacts into a 30-90-180 day action plan for an IT agency, derived from the diagnosed stage plus the… | `npx skills add victor-shulga/gtm-strategy-skills/skills/13-action-plan` | — |
| `gtm-audit` | Standalone GTM audit of a B2B service company on 23 weighted criteria in 4 blocks (Team 20% · Processes 30% · Data 25% · Interfaces 25%), maturity scale 0-4, band… | `npx skills add victor-shulga/gtm-strategy-skills/skills/gtm-audit` | — |

## outbound-engine-skills — outbound (27 skills)

Install the whole pack: `npx skills add victor-shulga/outbound-engine-skills` · repo: https://github.com/victor-shulga/outbound-engine-skills

Lost inside the pack? Run its orchestrator `signal-outbound` first — it drives the other skills in order.

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `signal-outbound` — orchestrator, start here | Master router for signal-based outbound — runs the full path from a service page to an email addressed to a named person with a verified address, routing to the right… | `npx skills add victor-shulga/outbound-engine-skills/skills/signal-outbound` | — |
| `ab-test-analyzer` | Use when asked to compare two campaign variants, determine a winner, or analyze the results of a split test | `npx skills add victor-shulga/outbound-engine-skills/skills/ab-test-analyzer` | — |
| `account-sourcing` | Builds a filtered, scored account list from job-posting signals — pulls postings from ATS career sites via Apify, strips the two thirds of results that are agencies,… | `npx skills add victor-shulga/outbound-engine-skills/skills/account-sourcing` | — |
| `campaign-naming` | Use when asked to name campaigns, generate a naming convention, or organize a hypothesis matrix into readable campaign names | `npx skills add victor-shulga/outbound-engine-skills/skills/campaign-naming` | — |
| `campaign-report` | Use when asked to generate a weekly or monthly campaign performance report, summarize outbound results, or brief a client or stakeholder on campaign status | `npx skills add victor-shulga/outbound-engine-skills/skills/campaign-report` | — |
| `campaign-tiering` | Use when asked to review running campaigns, decide what to scale vs. kill, or sort active hypotheses by performance | `npx skills add victor-shulga/outbound-engine-skills/skills/campaign-tiering` | — |
| `data-research` | Use when asked to turn a raw company list into a scored, evidenced prospect list — grade a base the client already has, enrich it from public sources, attach dated… | `npx skills add victor-shulga/outbound-engine-skills/skills/data-research` | — |
| `deliverability-audit` | Use when asked to check email deliverability, audit sending infrastructure, investigate spam issues, or set up domains and mailboxes correctly | `npx skills add victor-shulga/outbound-engine-skills/skills/deliverability-audit` | — |
| `followup-sequence` | Use when asked to write follow-ups, nurture warm non-responders, or build a re-engagement sequence for leads who went quiet | `npx skills add victor-shulga/outbound-engine-skills/skills/followup-sequence` | — |
| `hypothesis-builder` | Use when asked to generate campaign hypotheses, build a testing matrix, or create a list of ideas to run from an ICP and signal set | `npx skills add victor-shulga/outbound-engine-skills/skills/hypothesis-builder` | — |
| `icp-builder` | Use when asked to build an ICP from scratch, define the ideal customer profile, or structure ICP documentation for use across skills | `npx skills add victor-shulga/outbound-engine-skills/skills/icp-builder` | — |
| `icp-validation` | Use when asked to validate a company against ICP criteria, score fit, or check if a company is worth targeting | `npx skills add victor-shulga/outbound-engine-skills/skills/icp-validation` | — |
| `lead-scoring` | Score a lead AFTER contact — start from the pre-contact profile score and add what only a conversation reveals: engagement, confirmed deal size, the real decision path,… | `npx skills add victor-shulga/outbound-engine-skills/skills/lead-scoring` | — |
| `linkedin-sequence` | Use when asked to write a LinkedIn outreach sequence, connection request messages, or LinkedIn follow-ups for a specific hypothesis | `npx skills add victor-shulga/outbound-engine-skills/skills/linkedin-sequence` | — |
| `multi-channel-orchestrator` | Use when asked to build a multi-channel sequence, coordinate email and LinkedIn touchpoints, or plan a combined outreach flow for a hypothesis | `npx skills add victor-shulga/outbound-engine-skills/skills/multi-channel-orchestrator` | — |
| `persona-builder` | Use when asked to build a buyer persona, profile a specific role, or understand how to message a particular decision-maker type | `npx skills add victor-shulga/outbound-engine-skills/skills/persona-builder` | — |
| `personalization-pipeline` | Designs the pipeline that computes per-lead personalization before the sequencer — two generated fields, a confidence gate, and a push into the sending tool. | `npx skills add victor-shulga/outbound-engine-skills/skills/personalization-pipeline` | — |
| `prospect-scoring` | Score an account BEFORE any contact — profile fit only, from data you can read without talking to anyone. | `npx skills add victor-shulga/outbound-engine-skills/skills/prospect-scoring` | [ZIP](https://victorshulga.com/skills/lead-scoring/) |
| `ps-line-generator` | Use when asked to write a PS line, add a pattern interrupt to an email, or improve the bottom of a cold email sequence | `npx skills add victor-shulga/outbound-engine-skills/skills/ps-line-generator` | — |
| `reply-audit` | Runs a full forensic audit of outbound REPLIES (positive responses, objections, ghosts) for an agency client and writes the result as a structured page in an established… | `npx skills add victor-shulga/outbound-engine-skills/skills/reply-audit` | [ZIP](https://victorshulga.com/skills/reply-audit/) |
| `reply-objection-handler` | Per-reply engine for outbound. Takes ONE inbound reply, objection, ghost, lost proposal or trigger (a LinkedIn post, a work anniversary, company news) plus context,… | `npx skills add victor-shulga/outbound-engine-skills/skills/reply-objection-handler` | [ZIP](https://victorshulga.com/skills/reply-objection-handler/) |
| `sequence-writer` | Writes a multichannel cold outreach sequence (email + LinkedIn) for ONE hypothesis: ICP x anchor (signal / data-point / segment insight) x offer, for a B2B service… | `npx skills add victor-shulga/outbound-engine-skills/skills/sequence-writer` | [ZIP](https://victorshulga.com/skills/multichannel-sequence/) |
| `signal-catalog` | Builds a 50-trigger signal catalog for one niche, scores every signal on a 5-factor weighted model, and bundles the signals that cannot reach test volume alone. | `npx skills add victor-shulga/outbound-engine-skills/skills/signal-catalog` | — |
| `signal-research` | Runs a signal-research pass over an EXISTING firmographic account base (CSV, Google Sheet, Notion DB, CRM export) for a B2B service agency: decides which signals to hunt… | `npx skills add victor-shulga/outbound-engine-skills/skills/signal-research` | — |
| `subject-line-generator` | Use when asked to write subject lines, improve open rates, or generate subject line options for an email sequence | `npx skills add victor-shulga/outbound-engine-skills/skills/subject-line-generator` | — |
| `waterfall-enrichment` | Turns company domains into named decision-makers with verified work emails, or finds emails for contacts you already have — a people-search node keyed on domain, then a… | `npx skills add victor-shulga/outbound-engine-skills/skills/waterfall-enrichment` | — |
| `weekly-outreach-report` | Builds a canonical WEEKLY outreach report for a client as a standalone narrative page — the exact 7(+2)-section format instead of a dashboard dump. | `npx skills add victor-shulga/outbound-engine-skills/skills/weekly-outreach-report` | [ZIP](https://victorshulga.com/skills/weekly-outreach-report/) |

## sales-engine-skills — sales (6 skills)

Install the whole pack: `npx skills add victor-shulga/sales-engine-skills` · repo: https://github.com/victor-shulga/sales-engine-skills

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `cold-call-script` | Generates a structured cold call script from a target description (job title, company type, industry, trigger, etc.). | `npx skills add victor-shulga/sales-engine-skills/skills/cold-call-script` | — |
| `meeting-prep` | Generates a pre-call brief for a BOOKED meeting (discovery or demo): the handoff dossier that lets whoever takes the call walk in prepared, 500 words max. | `npx skills add victor-shulga/sales-engine-skills/skills/meeting-prep` | [ZIP](https://victorshulga.com/skills/meeting-prep/) |
| `offer-ladder` | Use when the user wants to build a vertical OFFER LADDER (value/ascension ladder) for an IT-agency client from their website — free → low → mid → high tiers around ONE… | `npx skills add victor-shulga/sales-engine-skills/skills/offer-ladder` | [ZIP](https://victorshulga.com/skills/offer-ladder/) |
| `pipeline-analysis` | Runs a full sales pipeline analysis and renders an interactive visual dashboard. | `npx skills add victor-shulga/sales-engine-skills/skills/pipeline-analysis` | — |
| `proposal-generator` | Generates two client-ready sales proposals as single-file HTML — built on the client's own brand/design system — and deploys them to Netlify. | `npx skills add victor-shulga/sales-engine-skills/skills/proposal-generator` | [ZIP](https://victorshulga.com/skills/proposal-generator/) |
| `value-prop-lister` | Extract and organize all value propositions from a company website or materials into a structured inventory, categorized by type and mapped to personas and outreach… | `npx skills add victor-shulga/sales-engine-skills/skills/value-prop-lister` | — |

## content-engine-skills — content (10 skills)

Install the whole pack: `npx skills add victor-shulga/content-engine-skills` · repo: https://github.com/victor-shulga/content-engine-skills

Lost inside the pack? Run its orchestrator `content-run` first — it drives the other skills in order.

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `content-run` — orchestrator, start here | Orchestrator of the Content Engine flow. Routes to the right step — strategy, profile audit, research, weekly plan, production, creatives, tracking — keeps per-client… | `npx skills add victor-shulga/content-engine-skills/skills/content-run` | — |
| `01-strategy` | Step 1 of the Content Engine flow. Build a machine-readable LinkedIn social selling strategy in Notion from a person LinkedIn profile + company site/LinkedIn —… | `npx skills add victor-shulga/content-engine-skills/skills/01-strategy` | — |
| `02-profile-audit` | Step 2 of the Content Engine flow. Audit a person LinkedIn profile against the 2026 optimization framework AND the client strategy, then propose concrete rewrites per… | `npx skills add victor-shulga/content-engine-skills/skills/02-profile-audit` | — |
| `03-research` | Step 3 of the Content Engine flow. Weekly research layer that refills the Idea Pool from six sources — call transcripts (Fathom), the author own work-stream, LinkedIn… | `npx skills add victor-shulga/content-engine-skills/skills/03-research` | — |
| `04-weekly-plan` | Step 4 of the Content Engine flow. The weekly recommender — the heart of the system. | `npx skills add victor-shulga/content-engine-skills/skills/04-weekly-plan` | — |
| `05-creative` | Step 5 of the Content Engine flow (creative-first). Takes an approved Idea Pool card and produces the visual creative — carousel, infographic, single image, or… | `npx skills add victor-shulga/content-engine-skills/skills/05-creative` | — |
| `06-write` | Step 6 of the Content Engine flow. Writes the publish-ready LinkedIn post text UNDER the creative from 05, in the author's voice — runs the writing process, picks the… | `npx skills add victor-shulga/content-engine-skills/skills/06-write` | — |
| `07-repurpose` | Step 7 of the Content Engine flow. Mines the author's best-performing posts (backfill of the year's top 30-50, or recent winners from the Posts DB) and proposes how to… | `npx skills add victor-shulga/content-engine-skills/skills/07-repurpose` | — |
| `08-engage` | Step 8 of the Content Engine flow. The comment radar in three modes — targets builds a live list of profiles worth commenting on by extracting the four audiences (ICP,… | `npx skills add victor-shulga/content-engine-skills/skills/08-engage` | — |
| `09-track` | Step 9 of the Content Engine flow. The tracking loop that closes the compound cycle — ingests LinkedIn analytics exports into the post archive and the Posts DB, scores… | `npx skills add victor-shulga/content-engine-skills/skills/09-track` | — |

## gtm-skills — single agents (6 skills)

Install the whole pack: `npx skills add victor-shulga/gtm-skills` · repo: https://github.com/victor-shulga/gtm-skills

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `agency-signal-sourcer` | Operational buying-signal engine for B2B service agencies (BIM/MEP, custom dev, GIS, AI/SaaS engineering outsourcing). | `npx skills add victor-shulga/gtm-skills/agency-signal-sourcer` | [ZIP](https://victorshulga.com/skills/agency-signal-sourcer/) |
| `anticopywriting-ai` | Знаходить і прибирає ознаки ШІ-генерації з тексту українською або англійською мовою. | `npx skills add victor-shulga/gtm-skills/anticopywriting-ai` | [ZIP](https://victorshulga.com/skills/anticopywriting-ai/) |
| `hypo-generator` | Use when Viktor wants to generate outreach hypotheses for an IT agency client from a website URL or text brief. | `npx skills add victor-shulga/gtm-skills/hypo-generator` | [ZIP](https://victorshulga.com/skills/hypo-generator/) |
| `hypothesis-scoring` | Scores and ranks outbound hypotheses BEFORE launch and turns them into a launch queue — the pre-launch evaluation method from Victor Shulga's guide on testing… | `npx skills add victor-shulga/gtm-skills/hypothesis-scoring` | — |
| `offer-factory` | Use when Viktor wants to invent offers FAST for an IT-agency client and test them with outbound. | `npx skills add victor-shulga/gtm-skills/offer-factory` | [ZIP](https://victorshulga.com/skills/offer-factory/) |
| `prospect-profiler` | Turns a SCORED account list into one tactical pre-touch dossier per account: a compact "60-second card" an SDR reads right before writing the first touch. | `npx skills add victor-shulga/gtm-skills/prospect-profiler` | [ZIP](https://victorshulga.com/skills/prospect-profiler/) |

## account-management-skills — retention (5 skills)

Install the whole pack: `npx skills add victor-shulga/account-management-skills` · repo: https://github.com/victor-shulga/account-management-skills

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `account-dossier` | Research ONE target company as an outbound prospect and produce a decision-ready account dossier: signal stack, fit against YOUR ICP, decision-makers, lead score, risks,… | `npx skills add victor-shulga/account-management-skills/skills/account-dossier` | — |
| `case-study-writer` | Turns a finished client project into a publishable case study in the canonical 12-section Case Study Kit structure: SME interview questionnaire → data collection →… | `npx skills add victor-shulga/account-management-skills/skills/case-study-writer` | [ZIP](https://victorshulga.com/skills/case-study-writer/) |
| `client-health-check` | Scores every active client account green / yellow / red on 6 health criteria and outputs a health table + action plan for the reds. | `npx skills add victor-shulga/account-management-skills/skills/client-health-check` | — |
| `customer-intelligence` | Mine a vendor's OWN case studies and review-site profiles (G2 / Capterra / TrustRadius) to extract why their customers actually buy: pain layers, buying triggers,… | `npx skills add victor-shulga/account-management-skills/skills/customer-intelligence` | — |
| `upsell-mapper` | Builds a client × services cross-sell map for a B2B service company: which active client uses which services, where the gaps are, and which gaps are realistic expansion… | `npx skills add victor-shulga/account-management-skills/skills/upsell-mapper` | — |

## mcp-skills — infrastructure (1 skills)

Install the whole pack: `npx skills add victor-shulga/mcp-skills` · repo: https://github.com/victor-shulga/mcp-skills

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `api-to-mcp` | Turn any REST/HTTP API into a working local MCP server that Claude Code can call: recon of the API surface, job-shaped tool design, a single-file Python server (uv + PEP… | `npx skills add victor-shulga/mcp-skills/api-to-mcp` | — |

## Standalone skills (not in a pack)

### design-system-generator

repo: https://github.com/victor-shulga/design-system-generator

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `design-system-generator` | Generates a complete, client-ready brand/design system as a single-file HTML page from a website URL — Viktor's repeatable client flow. | `npx skills add victor-shulga/design-system-generator/skills/design-system-generator` | — |

### page-builder

repo: https://github.com/victor-shulga/page-builder

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `page-builder` | Production line for website pages of a B2B service business (agency, outsourcing, consulting). | `npx skills add victor-shulga/page-builder/skills/page-builder` | [ZIP](https://victorshulga.com/skills/page-builder/) |

### linkedin-post-writing

repo: https://github.com/victor-shulga/linkedin-post-writing

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `linkedin-post-writing` | A proven 10-step process for writing lead-generating LinkedIn posts in the WRITER'S OWN voice — not a generic "copywriter" voice. | `npx skills add victor-shulga/linkedin-post-writing/skills/linkedin-post-writing` | — |

### linkedin-strategy-kit

repo: https://github.com/victor-shulga/linkedin-strategy-kit

| Skill | What it does | Install just this one | ZIP |
|---|---|---|---|
| `profile-audit` | Audit a person LinkedIn profile against the 2026 optimization framework AND their content strategy, then propose concrete rewrites per section plus a banner design brief… | `npx skills add victor-shulga/linkedin-strategy-kit/skills/profile-audit` | — |
| `strategy` | Build a machine-readable LinkedIn social selling strategy in Notion from a person LinkedIn profile + company site/LinkedIn — goals/KPI, ICP+persona, enemy+signature,… | `npx skills add victor-shulga/linkedin-strategy-kit/skills/strategy` | — |

---
Regenerated by `gen_catalog.py` from the live repos on 2026-09-22. If a skill is missing here it is not public yet; if a command fails, the pack is being updated — try again in an hour.
