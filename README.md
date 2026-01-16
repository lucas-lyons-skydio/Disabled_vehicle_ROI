# Drone Response ROI Calculator

Simple static web app to estimate the ROI of using drones to reduce disabled-vehicle incident clearance times.

## Running locally (Windsurf / browser)

- Open `index.html` in your browser, or
- Use Windsurf/VS Code "Open with Live Server" (or any static HTTP server) in this folder.

The calculator runs entirely in the browser (no backend).

## Deploying / Publishing

Because this is a single static page, you can deploy it as-is:

- **GitHub Pages**: point Pages to the repository root or `main` branch and use `index.html` as the entrypoint.
- **Netlify / Vercel / similar**: deploy the repo as a static site; no build step required.

## Inputs & Outputs

- Inputs on the **Calculator** tab cover roadway characteristics, incident data, economic values, response costs, and drone program costs.
- The **Results & Analysis** tab shows:
  - Per-incident cost breakdown
  - Annual baseline cost and annual savings
  - Annual drone program cost and net annual benefit
  - ROI (%), payback period, break-even incidents, and margin of safety.
