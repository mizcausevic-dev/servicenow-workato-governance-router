# servicenow-workato-governance-router

ServiceNow Workato Governance Router is a Kinetic Gain portfolio proof repo for **ServiceNow, Workato** across Compliance / Governance.

It turns workflow exceptions, integration ownership, approval latency, and evidence-ready remediation lanes into a small board-readable intelligence packet: where risk is building, where money is leaking, what deserves investment, and what story leaders can tell with evidence.

## Platform and company signals

- ServiceNow
- Workato

## What it includes

- runnable Node CLI for summarizing synthetic control-plane lanes
- JSON fixture with exposure, savings, and investment lanes
- static proof page in site/index.html
- lightweight CI using Node's built-in test runner
- no production credentials, no customer data, no external API calls

## Local run

`powershell
npm test
npm run demo
npm run build
`

## Output shape

`json
{
  "product": "ServiceNow Workato Governance Router",
  "signals": ["ServiceNow", "Workato"],
  "averageScore": 82,
  "priorityLane": "investment"
}
`

## Kinetic Gain fit

This repo supports the Platform and Company Signals layer of the portfolio atlas. It is intentionally small, readable, and evidence-oriented so executives can see the operating pattern without requiring access to live enterprise systems.