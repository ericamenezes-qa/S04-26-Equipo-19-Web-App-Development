# 🛠️ OpsCore - Incident Management System (QA Portfolio)

This repository is a **Fork** of the original No Country project. I served as a **QA Analyst** during Sprint 1, ensuring software quality and system reliability.

## 🎯 My Contribution as a QA
I focused on verifying system robustness under network failure conditions and ensuring user data integrity during form submissions.

### 🐞 Critical Bugs Reported
* **BUG-006: False Success Feedback in Offline Mode**
  * **Description:** The system displayed a "Success" message and cleared the form even when there was no internet connection. This led to critical data loss as the data was never actually sent to the server.
  * **Status:** Reported / Pending Fix.
  * **Impact:** High - Risk of data loss and poor user experience.

### 🧪 Technical Testing Toolkit
* **Manual Testing:** Black-box testing focused on UI/UX and functional requirements.
* **Chrome DevTools:** * Network Throttling (Simulated Offline and Slow 3G environments).
    * Console monitoring for `net::ERR_INTERNET_DISCONNECTED` validation.
* **API Testing:** Initial endpoint exploration and status code verification.
* **Version Control:** Proficient use of Git (Branch management, fetching, and merging).

### 📋 QA Deliverables (Available in this Repo)
* **Test Cases:** Designed to validate form edge cases.
* **Bug Reports:** Detailed documentation with reproduction steps and expected vs. actual results.

---
*I certify my active participation in this cross-functional team, validating the integration between Frontend (Next.js) and Backend services.*
