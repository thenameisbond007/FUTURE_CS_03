# 🔐 API Security Risk Analysis — Task 3
### Future Interns | Cyber Security Track (CS) | May 2026

---

## 📌 About This Project

This project is part of my Cyber Security internship at Future Interns.
I performed a manual black-box security analysis on two publicly available
REST APIs — JSONPlaceholder and ReqRes — using Postman and browser DevTools.

The goal was to identify real-world API vulnerabilities, classify their
severity, explain their business impact, and suggest practical fixes —
exactly how a security analyst would approach it professionally.

---

## 🌐 APIs Tested

| API | URL |
|-----|-----|
| JSONPlaceholder | https://jsonplaceholder.typicode.com |
| ReqRes | https://reqres.in |

---

## 🛠️ Tools Used

- **Postman** — API request testing and response analysis
- **Browser DevTools** — Header and network inspection
- **ReportLab + Python** — Report generation

---

## 🔍 Vulnerabilities Found

| # | Vulnerability | Severity |
|---|--------------|----------|
| 1 | No Authentication Required | 🔴 High |
| 2 | Excessive Data Exposure | 🟡 Medium |
| 3 | No Rate Limiting | 🔴 High |
| 4 | IDOR (Insecure Direct Object Reference) | 🟡 Medium |
| 5 | Verbose Error Messages | 🟡 Medium |
| 6 | Mass PII Exposure via Unauthenticated Endpoint | 🔴 High |

---

## 📄 Report

👉 For Report check this out API Security Risk Analysis Report.docx

---

## 📸 Screenshots

All Postman test screenshots are posted

---

## 💡 Key Learnings

- Even demo APIs reflect critical real-world security gaps
- Authentication alone is not enough — object-level access control matters
- Rate limiting is commonly overlooked but essential against DoS and scraping
- Verbose error messages give attackers a roadmap into your API
- Mass PII exposure via one unauthenticated call can breach GDPR

---

*Submitted as part of Future Interns Cyber Security Internship*
*Intern: Shabbir Ahmed | Track: CS | Task: 3 | May 2026*
