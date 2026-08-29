<!-- Profile README for github.com/verdxnt -->

<div align="center">

# Tobi Onabanjo

**CS @ Colgate University &nbsp;·&nbsp; Application Security + SWE &nbsp;·&nbsp; Class of 2028**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tonabanjo)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tonabanjo@colgate.edu)

</div>

---

## 👋 About me

- Building internal tools at **Colgate ITS – DLMC**: a multi-user Flask video downloader and a remote 3D print submission system
- Working toward application security — actively studying **PortSwigger Web Security Academy** (OWASP Top 10: path traversal, access control, authentication, SSRF done)
- Interested in the intersection of software development and AppSec — writing systems that are both functional and defensively built from the start
- First-gen CS student who started from scratch and builds everything by hand to actually understand it

---

## 🧰 Tech stack

<table>
  <tr>
    <td><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/HTML%2FCSS-E34F26?logo=html5&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Backend & frameworks</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" />
      <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Jinja2-B41717?logo=jinja&logoColor=white" />
      <img src="https://img.shields.io/badge/REST%20APIs-005571" />
    </td>
  </tr>
  <tr>
    <td><strong>Infrastructure & tools</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Linux%2FUnix-000000?logo=linux&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Git%2FGitHub-F05032?logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/cron-4D4D4D" />
    </td>
  </tr>
  <tr>
    <td><strong>Security (learning)</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PortSwigger%20WSA-FF6633" />
      <img src="https://img.shields.io/badge/OWASP%20Top%2010-000000" />
      <img src="https://img.shields.io/badge/Path%20Traversal-7C3AED" />
      <img src="https://img.shields.io/badge/Access%20Control-7C3AED" />
      <img src="https://img.shields.io/badge/Authentication-7C3AED" />
      <img src="https://img.shields.io/badge/SSRF-7C3AED" />
    </td>
  </tr>
  <tr>
    <td><strong>Concepts</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Concurrency%20%26%20Threading-0F766E" />
      <img src="https://img.shields.io/badge/Input%20Validation-0F766E" />
      <img src="https://img.shields.io/badge/OAuth%202.0-0F766E" />
      <img src="https://img.shields.io/badge/HTTP%20%2F%20TCP--IP-0F766E" />
      <img src="https://img.shields.io/badge/Client--Server%20Architecture-0F766E" />
    </td>
  </tr>
</table>

---

## 🚀 Projects

### 🎬 DLMC Video Downloader &nbsp; `shipped`
> Python · Flask · JavaScript · REST API · Linux · OAuth 2.0 · Concurrency

Replaced a single-machine tkinter script with a multi-user Flask web service. Built a concurrent background job system with threading and subprocess management, UUID-scoped folders to prevent filename collisions, live progress polling via `fetch`/`setInterval`, and optional Gmail email notifications. Filed a scoped OAuth 2.0 access request to Colgate ITS for send-only Gmail API permissions after finding the Workspace policy blocked app-password auth.

Before shipping, I audited my own code and wrote a full threat model — 14 findings including a critical argument-injection RCE. [Read the threat model →](https://github.com/verdxnt/media-downloader-threat-model)

*Source code is held in a private institutional repository — available upon request.*

---

### 🖨️ Remote 3D Print Submission System &nbsp; `in progress`
> Python · Flask · REST API · Linux · Input Validation · Firmware

Replacing in-person USB print handoffs with remote submission across 5 lab printers. Flashed Rinkhals firmware after the stock firmware couldn't be driven over serial, then drove printers over Moonraker's REST API. Built a file-upload endpoint with path-traversal prevention, file-type validation, and identity format checks before touching the filesystem. Aggregates all 5 devices into a single status endpoint.

*Source code is held in a private institutional repository — available upon request.*

---

### 🔬 SAST Security Tool &nbsp; `building`
> Python · Static Analysis · AppSec

A static analysis tool for detecting vulnerable code patterns in Python codebases — hardcoded secrets, dangerous function calls, missing input sanitization, and other common security issues. Motivated directly by the argument-injection and path-traversal findings in the video downloader threat model.

---

### 📋 CareerTrack &nbsp; `building`
> JavaScript · Chrome Extension · Gmail API · OAuth 2.0 · PostgreSQL

Chrome extension for tracking job applications — Gmail API integration with OAuth 2.0, auto-parsing of application confirmation and recruiter emails, and a dashboard for status tracking. Built on personal equipment with timestamped commit history.

---

## 📚 Currently learning

| Status | Topic |
|--------|-------|
| 🟢 Active | PortSwigger Web Security Academy — OWASP Top 10 |
| 🟢 Active | NeetCode 150 — DSA fundamentals |

---

## 🔗 Connect

<a href="https://linkedin.com/in/tonabanjo">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:tonabanjo@colgate.edu">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
