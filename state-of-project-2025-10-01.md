# State of the Lowell Makes DAKboard Project (October 1, 2025)

## Overview

This document summarizes the status of the DAKboard project at Lowell Makes as of **October 1, 2025** (America/New_York time zone). It highlights current subscription details, device usage, documentation completeness, and next steps for the initiative.

## Subscription & Devices

- **Plan**: Essentials plan at $21/month. The plan includes 2 custom screens and 3 add‑ons.
- **Devices in use**: 5 active devices – front entrance, front warehouse, The Studio, Lowell Makes projector, and one unassigned unit.
- **Billing cycle**: Monthly. Switching to annual billing could reduce per‑screen costs.

The Essentials plan meets current needs, but the team is evaluating the **Plus plan** to unlock loops (flows), scheduling, and unlimited calendars – features that are important for engaging displays.

## Documentation Status

The project repository includes a README, a contribution guide, and several documentation files covering device setup, network setup, screen design, flows & scheduling, and billing strategy. There are, however, areas that need attention:

- A **`resources/`** directory exists solely for screenshots and printouts referenced in the documentation. It is **not** intended for long‑term storage of invoices or template files; those should be handled elsewhere.
- Some files referenced in the contribution guide and screen‑design notes—such as `docs/troubleshooting.md` and a `docs/templates/` directory—were missing. A basic troubleshooting guide has been drafted and the references have been corrected.
- The roles & responsibilities section in the README contained duplicate entries; it has been consolidated for clarity.
- Additional documentation, such as a style guide and more thorough device/network setup instructions, remains a **TODO**.

### Existing Files

- **README.md**: Project overview, opportunities, roles, and repo structure【199162995247853†L46-L59】.
- **docs/index.md**: Index of documentation topics, including setup guides and billing notes【613064415469940†L46-L55】.
- **docs/device-setup.md**: Basic instructions for imaging and configuring DAKboard devices【699257229580648†L0-L7】.
- **docs/network-setup.md**: Brief guidance on Wi‑Fi and network stability【553748013161683†L2-L6】.
- **docs/screen-design.md**: Best‑practice notes for designing screens【723869275911786†L21-L24】.
- **docs/flows-scheduling.md**: A high‑level overview of loops and scheduling【571719845687898†L4-L18】.
- **docs/billing.md**: Notes on cost optimization【409067675175840†L4-L9】.
- **CONTRIBUTING.md**: Guidelines for providing content and screen templates【59129516491696†L9-L17】, recently updated to point to the new `docs/templates/` location for exported screen definitions.

## Areas Needing Attention

1. **Comprehensive Documentation** – Many files (device setup, network setup, flows & scheduling) contain only outlines and TODOs. These sections need fleshing out with step‑by‑step instructions, screenshots, and examples.
2. **Templates Library** – A collection of reusable screen templates, including JSON exports and README explanations, should be organized under `docs/templates/` so contributors can find and reuse them easily.
3. **Training & Onboarding** – Develop a concise style guide and training plan for shop champions and volunteers. Consider holding regular workshops to ensure consistent screen quality.
4. **Plus Plan Evaluation** – Estimate the cost/benefit of upgrading to the Plus plan by identifying the number of screens needing flows and scheduling. Consider a pilot upgrade on one device before moving all devices.

## Next Steps

- Finalize documentation revisions, including detailed troubleshooting, style guidelines, and installation scripts.
- Create a `docs/templates/` folder in the repository and begin populating it with exported screen templates and associated README files.
- Draft a comprehensive style guide covering fonts, colors, layouts, and logos.
- Survey shop champions and volunteers to understand what content and screens they need.
- Prepare a short presentation for Lowell Makes leadership summarizing the benefits and costs of upgrading to the Plus plan.

---

This **state of the project** report should be revisited regularly (at least quarterly) to ensure the DAKboard initiative continues to meet the needs of the Lowell Makes community.
