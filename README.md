# Rishav Kumar — Product Portfolio

Live product portfolio built as a static, self-contained HTML site. No build step, no dependencies — every file here just needs to sit in the same folder together, since the demos link to each other with relative paths.

## View it live

Once GitHub Pages is turned on for this repo (Settings → Pages → Deploy from branch → `main` → `/root`), the site is served from:

```
https://<your-username>.github.io/rishav-portfolio/index.html
```

## Files

- `index.html` — the main portfolio site (rename from `rishav-portfolio.html` on upload)
- `rishav-photo.png` — profile photo, referenced by the hero section

### Live prototypes (linked from the Projects section)

| File | Project |
|---|---|
| `demo-sdr-rep-console.html` | Pursuit — outbound SDR console |
| `demo-gtm-agentic.html` | GTM pipeline agent architecture |
| `demo-support-enterprise-console.html` | Anchor — Vertex AI Search support console |
| `demo-invoice-ai-assistant.html` | Invoice renewal AI assistant (Salesforce-styled) |
| `demo-invoice-dataflow.html` | Invoice pipeline architecture animation |
| `demo-customer-insights-console.html` | Customer Insights / churn engine console |
| `demo-customer-insights-dataflow.html` | Customer Insights architecture animation |
| `demo-health-score.html` | Health Score refresh demo |
| `demo-scorecard.html` | AI use-case prioritization scorecard |

### Superseded (safe to skip on upload)

`demo-support-agent.html`, `demo-gtm-engine.html`, `demo-invoice-renewal.html` — earlier drafts, nothing in `index.html` links to these anymore.

## Updating

Since this is a plain static site, editing is just: edit the HTML file, re-upload/overwrite it in the repo (GitHub's web UI lets you edit files directly, or drag a replacement in), done. No build or deploy step beyond that.
