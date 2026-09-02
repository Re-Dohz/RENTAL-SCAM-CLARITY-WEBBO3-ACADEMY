# RENTAL-SCAM-CLARITY-WEBBO3-ACADEMY
A COLLABORATION OF TEN ENTRY LEVEL FRONTEND DEVELOPERS
# Lagos Rent Check — Semantic Pod Collaboration

Welcome to the official repository for **Lagos Rent Check**, a community-driven rental verification and anti-scam platform built by Semantic Pod. Our mission is to protect first-time renters, young adults, and home seekers in Lagos by making agent and landlord verification transparent before any money changes hands.

---

## 🛠️ Project Overview & Architecture

This platform is structured around a multi-page HTML/CSS architecture sharing a cohesive design system (Calm Blue Edition).

* **Primary Color Palette:** Calm Blue (`#356B8C`), Deep Blue (`#1F4057`), Olive Secondary (`#808000`), and Crimson Warning (`#DC143C`).


* **Typography:** Arial, Helvetica, sans-serif.


* **Layout Foundation:** Fluid containers using `.wrap` with a maximum width of `1080px`.



---

## 📂 Page Mapping & File Structure

| UI Screen | Page Purpose | HTML File Name | CSS File Name |
| --- | --- | --- | --- |
| **1. Landing** | Homepage / Main Landing

 | `index.html`<br> | `landing.css`<br> |
| **2. The Problem** | Awareness & Scam Data

 | `the-problem.html`<br> | `problem.css`<br> |
| **3. How It Works** | Process Explanation

 | `how-it-works.html`<br> | `how-it-works.css`<br> |
| **4. Directory** | Agent & Landlord Search

 | `directory.html`<br> | `directory.css`<br> |
| **5. Record Detail** | Individual Profile View

 | `record-detail.html`<br> | `record-detail.css`<br> |
| **6. Trust & Verification** | Verification Status Guide

 | `trust-verification.html`<br> | `trust-verification.css`<br> |
| **7. Get Started (Report)** | Fraud/Agent Reporting Form

 | `report.html`<br> | `report.css`<br> |
| **8. Guide & FAQ** | Safety Resources & Help

 | `faq.html`<br> | `faq.css`<br> |
| **9. Rent Check Pod** | News & Articles Blog

 | `pod.html`<br> | `pod.css`<br> |
| **10. Contact** | Contact & Support Form

 | `contact.html`<br> | `contact.css`<br> |

---

## 👥 Semantic Pod Team Members

| Seat | Member | Role | Duty / Ownership |
| --- | --- | --- | --- |
| **1** | Tesleem Badmus | Landing Page | Brand keeper |
| **2** | Adubi Adebukola Halimat | The Problem Page | Research keeper |
| **3** | Oluwatitobi Dada | How It Works | Brand sheet owner |
| **4** | **Ademilade Adams** (Leader) | The Main Working Page (Directory) | Content realism |
| **5** | Odobi Confidence Obe | The Detail Page | Consistency check |
| **6** | Adejuyigbe Peace | Trust and Verification | Accessibility check |
| **7** | Afolabi Promise Ayokunle | Request or Get Started | Forms and flows |
| **8** | Samuel Ayomide | Guide and FAQ | Copy and tone |
| **9** | Faith Adedeji | The Pod Page | README owner |
| **10** | Saadudeen Abdulhaqq Olaide | Contact and Site Shell | Navigation and deploy |

---

## 🔀 Git Workflow & Contribution Rules

To keep our shared codebase clean and prevent merge conflicts, all team members must follow this branching workflow:

1. **Never commit directly to `main`.**
2. Pull the latest updates before starting work:
```bash
git checkout main
git pull origin main

```


3. Create a descriptive feature branch for your assigned page:
```bash
git checkout -b feature/your-page-name

```


4. Stage, commit, and push your work:
```bash
git add .
git commit -m "Complete [Page Name] layout and styling"
git push origin feature/your-page-name

```


5. Open a **Pull Request (PR)** on GitHub targeting the `main` branch for group review and merging.
