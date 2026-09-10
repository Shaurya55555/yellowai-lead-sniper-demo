# yellowai-lead-sniper-demo

Demo repository for the **GitHub High-Value Lead Sniper** n8n workflow:
https://github.com/Shaurya55555/yellowai-lead-sniper

## Why this repo exists

GitHub restricted the stargazer-listing API (`GET /repos/{owner}/{repo}/stargazers`)
in July 2026 to repository **admins and collaborators**. Pointing the workflow at
a large public repo like `n8n-io/n8n` now returns `404`. This repo is one the
workflow owner controls, so the poll works.

## What starring this does

`new star -> GET /users/{login} enrichment -> followers > 100 OR public_repos > 50 -> one-sentence AI sales pitch -> Slack card`

Star it from a second account to trigger the workflow during the demo.
