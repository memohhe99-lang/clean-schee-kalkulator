# Clean & Schee Kalkulator

Separate, offline-capable German-language project costing web app for GitHub Pages.

## Publish
1. Create a new public or private GitHub repository (GitHub Pages availability depends on plan).
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. Go to **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. Open the published GitHub Pages URL on iPhone, iPad, or Mac. In Safari choose **Share → Add to Home Screen**.

## Notes
- Customer data is stored **locally in the browser** using localStorage, not on GitHub. Back up frequently with JSON export. Data does not sync between devices.
- Offline support works after the app has been opened online and assets have cached. Browser storage can be cleared by the OS.
- The PDF offer is generated using the browser print-to-PDF dialog; check the print preview and tax treatment before sending.
- All cost inputs are **estimates**. The employee effective hourly rate must include paid absences, payroll overhead and unbillable time as appropriate; verify with payroll adviser.
- Insurance and fixed costs are allocated over estimated billable cleaning hours; actual workload may differ.
- Monthly visits = weekly visits × 52 / 12.
- Target profit margin is calculated as profit / sales, not markup on costs.
- Existing saved projects keep rate snapshots when defaults change.
- No external dependencies; no login or cloud sync.
