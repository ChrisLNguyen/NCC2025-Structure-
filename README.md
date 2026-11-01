# Construction Knowledge Map

## Test the NCC 2025 Compliance Agent (development version)

This prototype is on the `feature/ncc-compliance-agent` branch. It does not change the live Knowledge Map.

### Windows: download and open the application

1. Open the [development branch](https://github.com/ChrisLNguyen/NCC2025-Structure-/tree/feature/ncc-compliance-agent).
2. Select **Code → Download ZIP**.
3. In **Downloads**, right-click the ZIP file and choose **Extract All**. Do **not** open `compliance.html` directly inside the ZIP archive or a temporary compressed folder.
4. Open the **extracted** folder. Its name may resemble `NCC2025-Structure--feature-ncc-compliance-agent`. There is no folder literally named `NCC Compliance Agent`.
5. In that folder, locate **`compliance.html`**, **`compliance.css`** and **`compliance.js`**. Keep them together.
6. Double-click **`compliance.html`** to launch it in your browser. You should see a styled heading, progress guide and two clear steps.

### Using the prototype

- **Step 1: Project setup.** Enter a reference, site classifications and building system information. Leave unknown classifications as `Not established`. Click **Continue to Step 2**.
- **Step 2: Building finishes.** Select wall finishes, bulk insulation and other products, entering manufacturer documents where available. Click **Review design readiness**.
- Continue to the WBS inspections and defect register. Use **Export JSON** for a project backup and **Export inspection CSV** for the checklist.
- This is a local browser prototype, not a cloud-connected application. Testing in a private browser window or on another computer will not automatically display the same saved data.

### If the page looks unformatted

If the page looks like plain black text and default browser buttons, the CSS is not loading. Check that the file was **extracted** and the three compliance files are in the **same directory**, then reopen `compliance.html`. Download a new ZIP after updates to obtain the latest version.

### Safety and compliance

Rule references and numerical requirements are not independently verified yet. Do not treat the prototype as statutory certification or a source of approved construction dimensions. Do not put private client records into a shared device's browser storage.

---


An interactive, collapsible construction knowledge map for teaching and learning about building stages, NCC provisions and Australian Standards.

## Features

- Expand and collapse branches
- Decision cards that show one selected pathway or all options
- Create and edit multiple maps and nodes
- Pan, zoom, focus, fit to screen and presentation mode
- Automatic local browser storage
- Export and import JSON backups
- Export visible diagram as SVG
- Works on GitHub Pages without dependencies or build tools

## Publish to GitHub Pages

1. Create a public GitHub repository named `construction-knowledge-map`.
2. Upload `index.html`, `style.css`, `app.js`, `.nojekyll` and `README.md` to the repository root.
3. Open repository **Settings → Pages**.
4. Choose **Deploy from a branch**, **main**, **/(root)**, then **Save**.
5. Open `https://YOUR-USERNAME.github.io/construction-knowledge-map/` once deployed.

## Saving and privacy

The app runs entirely in the browser. Your edited maps are stored in **that browser's localStorage**, not in the GitHub repository or a cloud database. Browser data can be lost when site data is cleared or when switching devices. Download regular JSON backups and import them on another device. Public GitHub Pages websites are publicly reachable. Do not embed private student data in the source files or publish sensitive information.

## Important education note

All NCC and Australian Standard labels in the example are illustrative navigation prompts. They have **not** been independently verified for current edition, clause numbering, applicability or copyright permissions. Confirm all technical references using authorised current source documents before teaching or compliance use. Do not reproduce copyrighted standards text without permission.

## Local use

Open `index.html` in a modern browser. Hosting through GitHub Pages is recommended for consistent browser origin and storage.
