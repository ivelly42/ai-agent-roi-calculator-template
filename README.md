# AI Agent ROI Calculator Template

Public discovery mirror for Agent Ops Command Center, a Notion and spreadsheet template pack for builders running Codex, Claude Code, Cursor, and local AI coding agents.

This repository is a search and routing surface. The paid ZIP is not stored here.

## Main Links

- Interactive ROI calculator: https://ivelly42.github.io/agent-ops-command-center/roi-calculator.html
- Direct $203 team request: https://ivelly42.github.io/ai-agent-roi-calculator-template/
- Cost leak audit: https://ivelly42.github.io/agent-ops-command-center/cost-leak-audit.html
- Cost tracker page: https://ivelly42.github.io/agent-ops-command-center/cost-tracker-template.md
- Primary $203 team request URL: https://ivelly42.github.io/agent-ops-command-center/team-request-url.html
- Checkout status: https://ivelly42.github.io/agent-ops-command-center/checkout-status.json
- Buy page: https://ivelly42.github.io/agent-ops-command-center/buy.html
- Template gallery: https://ivelly42.github.io/agent-ops-command-center/template-gallery.html
- Catalog JSON: https://ivelly42.github.io/agent-ops-command-center/catalog.json
- Demand metrics: https://ivelly42.github.io/agent-ops-command-center/metrics/status.json
- Main repository: https://github.com/ivelly42/agent-ops-command-center

## Free ROI Calculator

Use this calculator when AI coding agents save review, debugging, release, or documentation time but the team needs a plain dollar case for approval.

| Field | What To Record |
| --- | --- |
| Workflow | Agent workflow or repeated task |
| Runs Per Month | How often the workflow repeats |
| Minutes Saved Per Run | Human time avoided per run |
| Hourly Value | Internal dollar value for one hour |
| Direct Agent Cost | Known cost per run, or `0` if unknown |
| Monthly Net Value | Calculated value after direct cost |
| Approval Note | Short manager/procurement summary |

Copy/paste table:

```markdown
| Workflow | Runs Per Month | Minutes Saved Per Run | Hourly Value | Direct Agent Cost | Monthly Net Value | Approval Note |
| --- | ---: | ---: | ---: | ---: | ---: | --- |
| Release proof review | 8 | 45 | $75 | $0 | $450 | Pays back a $203 team license inside month one if verified |
```

## Formula

```text
monthly_value_saved = runs_per_month * (minutes_saved_per_run / 60) * hourly_value
monthly_direct_cost = runs_per_month * direct_agent_cost
monthly_net_value = monthly_value_saved - monthly_direct_cost
```

Example:

```text
runs_per_month: 8
minutes_saved_per_run: 45
hourly_value: 75
direct_agent_cost: 0

monthly_value_saved = 8 * (45 / 60) * 75 = $450
monthly_net_value = 450 - 0 = $450
```

## Commercial Path

- Individual seat: `$29`
- Team license: seven seats for `$203`
- One confirmed team payment reaches the `$200` gross target only after payment proof exists

Open the fast team request:

https://ivelly42.github.io/agent-ops-command-center/team-request-url.html

The mirror homepage also opens a prefilled team-license request directly from the ROI calculator context.

## What The Full Pack Adds

- AI-agent run logs
- Verification ledgers
- Prompt versions
- Cost tracking
- ROI notes
- Failure modes
- Handoff notes
- Weekly operator review
- Revenue proof

## Revenue Rule

Revenue is not counted from this repository, page views, stars, discussions, order intent, or preview downloads.

Revenue is proven only by checkout, receipt, payout, or seller-dashboard evidence tied to the paid template pack.

## Preview Status

The public preview is live. Checkout is not live yet because a user-owned seller/payment channel is required.

The private paid ZIP should be delivered only after checkout, receipt, payout, or seller-dashboard proof exists.
