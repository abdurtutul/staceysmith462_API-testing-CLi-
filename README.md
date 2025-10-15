# 🧪 API Automation Testing – StaceySmith Project

This repository contains automated API testing scripts for the **StaceySmith** application, built and executed using **Postman** and **Newman**. All tests are designed to validate backend API stability, data integrity, and workflow consistency using dynamic scripting and environment variables.

---

## 📁 Project Overview

| Component              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Project Name**       | StaceySmith                                                                |
| **Testing Tool**       | Postman                                                                    |
| **Automation Runner**  | Newman CLI                                                                 |
| **Report Generator**   | Newman HTML Extra                                                          |
| **CI/CD Integration**  | GitHub Actions                                                             |
| **Assertions Covered** | ✅ Status code validation<br>✅ Schema validation<br>✅ Field verification<br>✅ Dynamic variable chaining |

---

## ⚙️ Environment Setup

### **1️⃣ Install Dependencies**

Make sure you have [Node.js](https://nodejs.org/) installed, then install Newman and the HTML Extra reporter:

```bash
npm install -g newman
npm install -g newman-reporter-htmlextra
```

---

## 🧩 Dynamic Scripts & Chaining

All requests use dynamic scripting for realistic test flows:

- **Pre-request Scripts**:
  - Random data generation (passwords, slugs, quiz IDs)
  - Variable extraction and reusability
- **Tests**:
  - Auto-validate success, message, and code fields
  - JSON schema verification
  - Response chaining across dependent APIs

---

## 📊 Newman HTML Extra Report

After execution, an advanced HTML report is generated:

```plaintext
📁 reports/staceySmith-newman-report.html
```

**Sample Run Summary**:

```
┌─────────────────────────┬───────────────────────┬──────────────────────┐
│                         │ executed              │ failed               │
├─────────────────────────┼───────────────────────┼──────────────────────┤
│ iterations              │ 1                     │ 0                    │
│ requests                │ 64                    │ 0                    │
│ test-scripts            │ 63                    │ 0                    │
│ prerequest-scripts      │ 40                    │ 0                    │
│ assertions              │ 214                   │ 0                    │
├─────────────────────────┴───────────────────────┴──────────────────────┤
│ total run duration: 1m 51.9s                                          │
│ average response time: 1270 ms [min: 138 ms, max: 4.3 s]              │
└───────────────────────────────────────────────────────────────────────┘
✅ Uploaded successfully! View Report on Postman Cloud →
```

---

## 🧠 QA Best Practices Followed

- Dynamic test data generation
- Automated chaining of request dependencies
- Environment variable isolation
- Zero hardcoded tokens
- Visual HTML reporting
- CI/CD integration with GitHub Actions

---

## 🏁 Summary

| Metric             | Value         |
|--------------------|---------------|
| Total Requests     | 64            |
| Total Assertions   | 214           |
| Failures           | 0             |
| Execution Time     | 1m 51.9s      |
| Average Response Time | 1270 ms    |

✅ All tests passed successfully under automated workflow conditions.

---

## 👨‍💻 Author

**Md Abdur Rahaman Tutul**  
Software Quality Assurance Engineer (FSD – Softvence)  
📧 [abdurtutul6@gmail.com](mailto:abdurtutul6@gmail.com)  
🌐 [Softvence FSD](https://softvence.com/)
