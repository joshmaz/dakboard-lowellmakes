# DAKboard Project for Lowell Makes

Lowell Makes has been using **DAKboard** for a number of years. Our utilization has fluctuated, and presently we are at a minimal implementation. I am offering to step up and volunteer to drive this project in a way that brings value to the Lowell Makes community.

---

## Current Status

- **Subscription**: Essentials Plan  
- **Devices**: 5 total (billed monthly at $21)  
- **Billing**: Monthly (potential savings if switched to annual billing)

---

## Opportunities for Improvement

We are very interested in using features available only in the **Plus Plan**, which comes at a small step up in cost. These features could allow us to greatly improve the experience for members.

### Key Plus Plan Benefits

- **Screen Loops (Flows):** String multiple screens together on a display for more informative and engaging layouts.
- **Screen Scheduling:** Automate display changes for special events, open houses, and recurring events.
- **Unlimited Calendars** and faster refresh rates.

---

## Example Use Cases

- Schedule **Open House nights** or **special events** directly on displays.  
- Rotate between **multiple screens** on a single device (e.g., shop updates, calendar, weather, and announcements).  
- Improve relevance and engagement by tailoring displays to what’s happening in the makerspace.  

---

## Pricing Ramp (Essentials vs Plus)

| Screens | Essentials Plan | Plus Plan |
|---------|-----------------|-----------|
| 3       | $11             | **$10** ✅ |
| 4       | $16             | $16       |
| 5       | **$21** ✅       | $22       |

*Note: Essentials cheaper at 5 screens, Plus cheaper at 3. Tie at 4.*

---

## Helpful Links & Resources

- [DAKboard Support Center](https://dakboard.freshdesk.com/support/home/)  
- Example screenshots and printouts referenced in the documentation are stored in the `resources/` directory. This folder is not meant to be a general storage area; it simply holds assets referenced by the guides.

---

## Next Steps

1. Evaluate **switch to annual billing** for cost savings.  
2. Consider **upgrade to Plus Plan** to unlock flows and scheduling.  
3. Identify potential **display loops and event schedules** for Lowell Makes.  
4. Document **best practices** and manage configurations in this repo.  

---

## Project Charter

### Purpose

Empower the Lowell Makes community to make better use of the DAKboard platform across the makerspace by:

- Enabling engaging, rotating content (calendars, videos, reservation info, announcements).
- Training shop champions to design effective screens.
- Providing documentation and processes so all displays deliver value to members.

### Current Status (Expanded)

- **Plan**: Essentials (monthly billing at $21, 2 custom screens + 3 add‑ons).
- **Devices in use**: 5 (Front Entrance, Front Warehouse, The Studio, LM Projector, plus one unassigned).
- **App Integrations**: Google Calendar, Google Photos, Google Drive, Instagram.

### Opportunities

- Switch to **annual billing** for lower per‑screen cost.
- Upgrade to **Plus Plan** for:
  - Screen loops (flows).
  - Scheduling (special events, recurring).
  - Unlimited calendars & integrations.
- Leverage Raspberry Pi hardware for flexible DIY expansion.

### Example Use Cases for Plus Features

- Rotate screens showing:
  - Open House schedules.
  - Shop reservation info.
  - Media Studio announcements.
  - Special events.
- Feature videos, photos, and social feeds to highlight member projects.
- Standardize layouts (calendar + rotating shop highlights + weather).

### Roles & Responsibilities

- **Project Captain (Josh)** – Coordinate overall project direction and task delegation; manage billing decisions (monthly vs annual, plan upgrades); maintain repo structure, documentation, and best practices; review display loops and content schedules with stakeholders.

- **Shop Champions** – Design and maintain engaging screens for their shop; contribute guides and shared templates; participate in training sessions; ensure their shop’s events and updates are reflected in displays.

- **Volunteers / Community Members** – Provide event information, calendars, videos, and photos for inclusion; suggest new features or display ideas; share feedback on the clarity, usefulness, and engagement of displays.

### Process & Documentation

1. **Content Creation**
   - Define screen templates and shared assets in `docs/`.
   - Maintain a “Media Library” for approved graphics and logos (outside the scope of this repo).

2. **Configuration Management**
   - Track all display configurations in this GitHub repo.
   - Version “screen definitions” and templates for reuse.

3. **Training & Onboarding**
   - Provide step‑by‑step guides for creating and editing screens.
   - Maintain a troubleshooting guide (see `docs/troubleshooting.md`) based on DAKboard support resources.

4. **Governance**
   - Conduct regular review of displays by the task force.
   - Establish a feedback loop from members → Shop Champions → Captain.

### Next Steps (Expanded)

- [ ] Decide on **annual vs monthly billing**.
- [ ] Consider **Plus Plan upgrade** to enable loops & scheduling.
- [ ] Define **initial rotating screen loop** for Media Studio display.
- [ ] Draft documentation & style guide.
- [ ] Train Shop Champions in screen design.

## Repo Structure

```
dakboard-lowellmakes/
├── README.md            # Project overview (this file)
├── CONTRIBUTING.md      # How to contribute content, screens, and documentation
├── docs/                # Supporting documentation, setup guides, and configuration notes
│   ├── index.md         # Documentation index
│   ├── device-setup.md  # Device setup instructions
│   ├── network-setup.md # Network & display setup notes
│   ├── screen-design.md # Screen design guidelines
│   ├── flows-scheduling.md # Guide for loops and scheduling
│   ├── billing.md       # Billing & subscription strategy
│   └── troubleshooting.md # Troubleshooting and FAQ
├── resources/           # Screenshots and printouts referenced by documentation
```

---

Cheers,  
Josh Mazgelis  
Media Studio Captain, Lowell Makes
