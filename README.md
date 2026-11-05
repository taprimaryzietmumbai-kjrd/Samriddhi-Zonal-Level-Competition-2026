# SAMRIDDHI 2026 – Zonal Level Competition

Digital competition management portal for ZIET Mumbai, Kendriya Vidyalaya Sangathan.

## Application
- `index.html` is the static web application entry point.
- Responsive dashboard and modules: KV Registration, Competition Events, Participant Entries, Event Schedule, Evaluation, Results, and Reports.
- CSV export is available for stored records.

## Hosting
This repository is intended to deploy the same static application to:
1. GitHub Pages
2. Tencent EdgeOne Pages

### GitHub Pages
In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. The expected site URL is:
https://taprimaryzietmumbai-kjrd.github.io/Samriddhi-Zonal-Level-Competition-2026/

### Tencent EdgeOne Pages
Import this GitHub repository into EdgeOne Pages. Use the `main` branch, repository root as the project directory, and leave build command and output directory empty for this plain static HTML starter (if the EdgeOne wizard requires an output directory, use the repository root).

## Important data note
This first UI starter stores records in the current browser's local storage. It is suitable for interface review and local prototyping only. It does **not** provide shared multi-user storage, authentication, secure evaluator access, or cross-device synchronization. Before operational competition use, connect a central database/API and implement access controls. Do not enter sensitive student data into this prototype.

## Configuration pending
Official competition categories, eligibility, dates, event rules, scoring rubric, participating regions/KVs, and certificate format must be populated from the approved SAMRIDDHI 2026 circular/concept note. They are intentionally not invented in this starter.
