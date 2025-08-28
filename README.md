# covernote
Profile
# **Ryad Juliano**

**Software Engineer — Mobile & Web**
Jakarta / Indonesia · [ryadjuliano@gmail.com](mailto:ryadjuliano@gmail.com) · +62-812-7632-7000 · [GITHUB](https://github.com/ryadjuliano) · [LINKEDLN](https://www.linkedin.com/in/ryad-juliano-55646746/)

---

## Summary

Product-focused software engineer with experience building cross‑platform apps (React Native), modern web apps (React/Next.js), and backend APIs (Node.js, PHP/CodeIgniter). Comfortable leading end‑to‑end delivery—from planning and architecture to deployment. Interested in logistics, e‑learning/LMS, IoT/GPS tracking, and finance/ERP modules.

---

## Skills

* **Languages:** TypeScript, JavaScript, PHP, SQL, Python
* **Mobile:** React Native (CLI & Expo), Android basics, iOS simulator/Xcode
* **Web:** React, Next.js, Tailwind CSS, shadcn/ui
* **Backend:** Node.js (Express/Nest basics), PHP (CodeIgniter), RESTful APIs
* **Data & Infra:** PostgreSQL/MySQL, Redis (caching/queues), RabbitMQ (concepts), GitHub Actions, Docker (basics)
* **Other:** Realtime (WebSocket/MQTT concepts), GPS tracking integration, Geofencing, Payment & Notifications

---

## Experience

**Software Engineer / Freelancer** — *Remote*
*YYYY – Present*

* Built Android & web modules for **attendance with anti-fake GPS**, including geofencing and map visualizations; integrated with paid GPS platforms (e.g., Cartrack) for asset tracking.
* Developed LMS/KMS features for a **government training SuperApp** (data competency management, learning content, and knowledge sharing).
* Implemented **K3 (Health & Safety) reporting** app with role-based access (worker/company/government), violational reports, and educational video modules.
* Created **inventory & invoicing** dashboards, including stock movement notifications and chart-based overviews.
* Collaborated with stakeholders, wrote technical docs, and shipped iteratively using GitHub Projects & Actions.

**Mobile & Web Developer** — *Company / Client Name*
*YYYY – YYYY*

* Delivered React Native features (navigation, animations, push notifications).
* Built REST APIs and admin dashboards for internal ops.
* Improved performance and reliability through profiling and error monitoring.

> *Add more roles/clients as needed. Quantify your impact: metrics, users, uptime, response time, etc.*

---

## Selected Projects

* **GPS Attendance & Asset Tracking**
  React Native + Web dashboard; anti-fake GPS checks, geofencing, and integration with a paid GPS platform; alerting and activity history.

* **BPSDM Kepri SuperApp (KMS/LMS)**
  SuperApp for training and competency management; modules for learning content, discussion, and user progress; roles & permissions; Next.js + React + API layer.

* **K3 Reports & Education**
  Android & web app where workers submit violations with photos/video; educational content delivery; analytics for companies and regulators; simple deployment.

* **General Journal / Money Management**
  Web app with journal entries, P\&L, balance, budget charts, and reports; built with React.js; database/API design for accounting flows.

* **Inventory & Invoicing Dashboard**
  Mobile-friendly dashboard for invoices, transactions, and stock movement alerts; implemented notifications for recent stock changes.

> *Link each project to a repository or demo if possible.*

---

## Education

**Your University / Bootcamp** — *Degree / Major*
*YYYY – YYYY*

---

## Certifications (optional)

* React (Institution / Platform, YYYY)
* Cloud/DevOps fundamentals (YYYY)

---

## Open Source

* **Repo Name** — short description of what it does and your role.
* **Repo Name** — short description of what it does and your role.

---

## Speaking & Writing (optional)

* *Title* — Event/Blog, YYYY. Topic and outcome.

---

## Contact

* Email: **[ryad@email.com](mailto:ryad@email.com)**
* GitHub: **@your-github**
* LinkedIn: **/in/your-handle**

---

### How to use this CV on GitHub

1. Create a new repository named `cv` or `resume` (or use your profile repo `your-github/your-github` to show it on your profile).
2. Add this file as `README.md` at the root.
3. Commit & push. Your CV will render nicely on GitHub.
4. *(Optional)* Turn it into a website: enable **GitHub Pages** → set branch to `main` and path `/`.

### (Optional) Export to PDF via GitHub Actions

Add a workflow file at `.github/workflows/export-pdf.yml`:

```yaml
name: Export CV to PDF
on:
  workflow_dispatch:
  push:
    paths:
      - README.md
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Convert Markdown to PDF
        uses: baileyjm02/markdown-to-pdf@v1
        with:
          input_dir: .
          output_dir: ./dist
      - name: Upload PDF artifact
        uses: actions/upload-artifact@v4
        with:
          name: cv-pdf
          path: dist/README.pdf
```

Then run the workflow from the **Actions** tab to download `README.pdf`.

---

> **Tip:** Keep the top section compact (name + role + links). Use bullet points with action verbs and measurable results. Link to repos/demos to prove your work.
