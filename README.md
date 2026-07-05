# M-Tech Summer Internship 2026 – Week 1, Task 1

## 🔐 Cross-Site Scripting (XSS) – PortSwigger Web Security Academy

**Intern:* Adan Fatima
**Reg No:* Mtech-CS26034
**Domain:* Cybersecurity
**Level:* Advanced
**Tool Used:* PortSwigger Web Security Academy (free/legal)

---

 Task Overview

This task involved completing two beginner-level (APPRENTICE-tier) labs on Cross-Site Scripting (XSS) using PortSwigger's Web Security Academy — a free, legal platform for practicing web application security testing in a safe, sandboxed environment.

XSS is a client-side vulnerability that allows an attacker to inject malicious JavaScript into a web page, which then executes in another user's browser. It can be used to steal session cookies, hijack accounts, or deface websites.

 Labs Completed

1. **Reflected XSS into HTML context with nothing encoded**
   Exploited an unencoded search field to inject and execute a JavaScript payload reflected directly in the page's HTML.

2. **Stored XSS into HTML context with nothing encoded**
   Exploited a blog comment field to permanently store a malicious script that executed for every visitor viewing the post.

**Payload used for both labs:**
```
<script>alert(1)</script>
<script>alert('HACKED')</script>
```

🗂️ Repository Structure

```
├── report/            → Full Week 1 task report (.docx), including all screenshots
└── README.md
```

 Learning Outcomes

- Understood the difference between Reflected, Stored, and DOM-based XSS
- Practiced identifying vulnerable input fields in a live web application
- Learned how missing input validation/output encoding leads to script execution
- Gained hands-on familiarity with PortSwigger Web Security Academy

📄 Full Report

See [`report/XSS_Week1_Report.docx`](./report/XSS_Week1_Report.docx) for the complete task documentation, including methodology, findings, and all supporting screenshots.

---
*Submitted as part of the M-Tech Summer Internship 2026 – Task  Submission.*
