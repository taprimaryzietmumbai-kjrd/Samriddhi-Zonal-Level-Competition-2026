# SAMRIDDHI 2026 – Zonal-Level Pedagogical Project / Lesson Plan Competition

Digital competition management portal for ZIET Mumbai, Kendriya Vidyalaya Sangathan.

## Application
- `index.html` is the static web application entry point.
- Includes the five ZIET Mumbai feeder Regional Offices: Mumbai, Patna, Ahmedabad, Jaipur and Raipur.
- Captures teacher/team entry information aligned with the revised Form A and Form B framework (sensitive Aadhaar data is intentionally not collected).
- Stage categories: Foundational (Balvatika–Grade II), Preparatory (III–V), Middle (VI–VIII), Secondary (IX–XII).
- Theme selection includes the six themes in the KVS guidelines; FLN is restricted to Foundational and Preparatory stages.
- Includes presentation scheduling, the official eight-criterion / 100-mark evaluation matrix, average-score calculation, provisional stage-wise rankings, CSV exports and JSON backup.
- Presentation timing: 20 minutes + 5 minutes jury interaction (25 minutes total).\n- Regional winners in all four categories represent their Regions at the Zonal-Level SAMRIDDHI competition at ZIET Bhubaneswar on 11–12 November 2026; the selected teacher/team should be relieved to participate.\n- Zonal winners represent KVS at the National-Level SAMRIDDHI event organised by NCERT.

## Hosting

The same static source can be deployed to:
1. GitHub Pages
2. Tencent EdgeOne Pages

### GitHub Pages
Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.

Expected site URL:
https://taprimaryzietmumbai-kjrd.github.io/Samriddhi-Zonal-Level-Competition-2026/

### Tencent EdgeOne Pages
Import this GitHub repository. Use branch `main`, repository root as the project directory, and no build command for this plain static HTML application.

## Data and security limitations
This release stores data in the current browser's local storage. GitHub Pages and EdgeOne deployments do not share or synchronize browser data. There is no central database, authentication, role-based access, secure evaluator login, or cross-device synchronization yet. Connect a central database/API and implement access controls before operational multi-user use.

The prescribed Form A includes sensitive personal information, including Aadhaar number. This app intentionally does not collect Aadhaar; complete the official prescribed form and handle it only through secure authorised channels. Avoid entering sensitive personal or student data in this prototype.

## Source basis
The current configuration is based on the uploaded *Guidelines for KVS Samriddhi* and revised *Samriddhi Form A and Form B*, along with the Regional Office instructions supplied in the project conversation.

## Important qualification
The app calculates provisional rankings using the average of recorded jury score sheets. The uploaded guidelines do not specify a tie-breaking procedure; any tie must be resolved under an authorised decision before formal result declaration. The jury should ensure stage-appropriate evaluation.
