# Drone Response ROI Calculator

Static web app to estimate the ROI of using drones to reduce traffic incident clearance times.

The calculator runs entirely in the browser (no backend).

## Features

- **Fixed $350/min economic cost of delay** based on FHWA and WSP research
- **Per-crash-type cost modeling** with editable incident counts, clearance times, and lanes blocked for:
  - Single Truck
  - Car vs. Deer
  - Single Car
  - Multi-Car
  - Multi-Truck
  - Multi-Vehicle (Mixed)
- **FHWA-sourced default clearance times**: 48 min (minor crashes), 64 min (multi-vehicle crashes) per the [FHWA I-270 Predictive Layered Operations report](https://ops.fhwa.dot.gov/fastact/atcmtd/ATCMTD_I270_Predictive_Layered_Operations_Initiatives.pdf)
- **Other/Unspecified incidents bucket** uses the editable total annual incidents as a fallback

## Inputs & Outputs

### Calculator Tab
- **Roadway Characteristics**: ADT, total lanes
- **Incident Counts by Type**: annual counts per crash category (editable)
- **Per-Type Parameters**: clearance time and lanes blocked for each crash type
- **Economic Values**: commercial vehicle percentage
- **Response Costs**: traditional vs. drone response costs
- **Drone Program Costs**: equipment & maintenance, personnel & operations, training & overhead

### Results & Analysis Tab
- Per-incident cost breakdown **by crash type**
- Annual baseline cost and annual savings
- Annual drone program cost and net annual benefit
- ROI (%), payback period, break-even incidents, and margin of safety

## Data Sources & Methodology

See the **Data Dictionary** and **Methodology** sections within the app for detailed formulas and citations.
