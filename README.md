# Rishav Kumar — Product Portfolio

Live product portfolio built as a static, self-contained HTML site. No build step, no dependencies — every file here just needs to sit in the same folder together, since the demos link to each other with relative paths.

## View it live

Deployed on Vercel from the `main` branch (framework preset: Other, no build command):

```
https://rishav-kumar-portfolio-iota.vercel.app
```

Pushing to `main` redeploys automatically.

## Files

- `index.html` — the main portfolio site
- `rishav-photo.png` — profile photo, referenced by the hero section (720×720, circular alpha mask)
- `Rishav-Kumar-Resume.pdf` — served by both "Resume" buttons

### Live prototypes (the "Live Demo" tab on each project)

| File | Project |
|---|---|
| `demo-support-enterprise-console.html` | Anchor — Vertex AI Search support console |
| `demo-sdr-rep-console.html` | Pursuit — outbound SDR console |
| `demo-invoice-ai-assistant.html` | Invoice renewal AI assistant (Salesforce-styled) |
| `demo-customer-insights-console.html` | Customer Insights / churn engine console |

### Design workflows (the "Design" tab on each project)

| File | Project |
|---|---|
| `design-anchor-architecture.html` | Anchor — interactive API data flow & architecture |
| `design-sdr-workflow.html` | Pursuit — 27-stage manual SDR pipeline walkthrough |
| `demo-invoice-dataflow.html` | Invoice renewal — animated pipeline architecture |
| `demo-customer-insights-dataflow.html` | Customer Insights — animated system data flow |

`demo-gtm-agentic.html` is the GTM agent architecture animation, linked from the Pursuit project's Code tab.

Note that `demo-invoice-dataflow.html` and `demo-customer-insights-dataflow.html` each serve double duty — they are both the project's architecture animation and its Design tab target.

### Removed

The **AI Use-Case Prioritization Scorecard** and **Customer Health Score Pipeline** projects were removed from the site, along with their `demo-scorecard.html` and `demo-health-score.html` files.

## Updating

Plain static site — edit the HTML file and commit. GitHub's web UI lets you edit files directly or drag a replacement in. No build step.
