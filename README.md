# Cultural Debt™ Calculator
**Culture Shift Consulting Group**
cultureshiftconsultinggroup.com

---

## Overview

An interactive business intelligence tool built for VPs of Engineering and R&D to quantify the annual operational cost of cultural debt across their engineering organization.

---

## Your Live Tool URLs

Once you create your GitHub account and activate GitHub Pages, your live URLs will be:

**Calculator (embed on your website):**
`https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-calculator.html`

**VP Summary Report (auto-opens after submission):**
`https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-vp-summary.html`

**Consulting Brief (internal use only — do not share with clients):**
`https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-armers-brief.html`

---

## Files in This Repository

| File | Purpose |
|---|---|
| `cultural-debt-calculator.html` | Client-facing 3-step calculator — embed on your website |
| `cultural-debt-vp-summary.html` | Executive summary — auto-opens with client's numbers after submission |
| `cultural-debt-armers-brief.html` | Your internal consulting brief — talking points, mitigation plan, revenue opportunity |
| `cscg-logo-transparent.png` | Culture Shift Consulting Group logo |
| `index.html` | Redirects your base URL to the calculator |
| `README.md` | This file |

---

## The Six Cultural Debt Drivers

Your proprietary framework ranked by organizational leverage:

| Rank | Driver | Why It Ranks Here |
|---|---|---|
| 1 | **Manager Capability Gap** | Root amplifier — creates and worsens all other debts |
| 2 | **Voice Suppression** | Gateway debt — without addressing this, nothing else can be surfaced |
| 3 | **Failure Punishment Reflex** | Kills innovation velocity — the debt technical teams feel most viscerally |
| 4 | **Communication Lag & Feedback Debt** | Connective tissue — amplifies all drivers above |
| 5 | **Brilliant Jerk Immunity** | Tolerated toxicity driving attrition and suppressing output |
| 6 | **Shadow Management** | The closing argument — VP time and salary consumed by cultural friction |

---

## How the Tool Works

1. VP completes the 3-step calculator — enters workforce inputs and adjusts 6 cultural debt sliders
2. Results page displays their total Cultural Debt™ cost with a breakdown by driver
3. VP enters their email and clicks **Get the Full Cultural Debt Report**
4. Their personalized VP Summary Report opens automatically in a new tab
5. A copy of the report is emailed to their inbox
6. You receive a BCC copy of every submission automatically

---

## How to Update the File Image References After Creating Your Account

Once you have your GitHub username, search for `Armers-ops` in all three HTML files and replace it with your GitHub username. This updates the logo image path.

Find: `raw.githubusercontent.com/Armers-ops/`
Replace with: `raw.githubusercontent.com/[your-username]/`

---

## WordPress Embed Code

Paste this into any WordPress page using the Custom HTML block:

```html
<iframe
  src="https://Armers-ops.github.io/cultural-debt-calculator/cultural-debt-calculator.html"
  width="100%"
  height="900px"
  frameborder="0"
  scrolling="yes"
  style="border:none; border-radius:12px; max-width:780px; display:block; margin:0 auto;">
</iframe>
```

---

## EmailJS Setup (Required for Email Delivery)

The calculator sends the VP Summary Report to clients via EmailJS. You will need to set up your own account:

1. Go to **emailjs.com** and create a free account
2. Click **Add New Service** → connect your Gmail or work email
3. Click **Email Templates** → **Create New Template** using the Contact Us template
4. Set the template body to include `{{report_link}}` and `{{to_email}}`
5. Add your email to the **BCC** field so you receive every submission
6. Copy your **Service ID**, **Template ID**, and **Public Key**
7. Send those three values to your developer to update the calculator

---

## Research Sources

The calculation methodology is built on peer-reviewed and institutional research:

- Gallup State of the Global Workplace 2025
- Google Project Aristotle 2016
- Amy Edmondson — The Fearless Organization, Harvard Business School
- McKinsey Global Institute — Organizational Performance Research
- Dylan Minor — Toxic Workers Study, Harvard Business School 2015
- Christine Porath — Georgetown University Workplace Civility Studies 2022
- Work Institute Retention Report 2020
- Harvard CEO Study 2018
- Accountemps Workplace Conflict Survey
- DORA State of DevOps Report 2019

---

## Intellectual Property

The Cultural Debt™ framework, Cultural Debt Index™, and all associated methodology are the sole and exclusive intellectual property of Armers Moncure and Culture Shift Consulting Group. This tool is proprietary and not for redistribution or white-labeling without written permission.

---

## Built By

Norrils Signature Consulting Inc. (NSC)
LaVonne Norrils, Founder & CEO
norrilssignature.com
