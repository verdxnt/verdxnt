# Tobi Onabanjo
# About Me
- Interested in Backend Engineering, Infrastructure, and Application Security
- Passionate about building and safely deploying scalable systems that work correctly and hold up under real security scrutiny
- Exploring containerization, concurrent systems, and static analysis tooling through hands-on projects
- Currently learning more about Abstract Syntax Trees, threat modeling, and cloud deployment (Docker, Kubernetes)

[LinkedIn](https://linkedin.com/in/tonabanjo) · [tonabanjo@colgate.edu](mailto:tonabanjo@colgate.edu)

---

## Projects

**DLMC Video Downloader** *(completed)*— Replaced a single-machine desktop script with a multi-user Flask web service for Colgate ITS. Built concurrent background jobs with threading and subprocess management, UUID-scoped folders to prevent filename collisions, live progress polling, and optional email notifications via Gmail API. Before deployment steps, I audited my own code and wrote a full threat model. [Read the threat model →](https://github.com/verdxnt/media-downloader-threat-model) *(Private institutional repo)*

**Remote 3D Print Submission System** *(in progress)* — 
Replacing USB print flow across 5 lab printers with a remote submission system and slicing instructions plan.

*What I've done so far*:
- Flashed Rinkhals firmware after stock firmware couldn't be driven over serial to my test printer
- Built a Flask upload endpoint with path-traversal prevention, file-type validation, and identity format checks.
- Aggregates all 5 printers into a single status endpoint. *(Private institutional repo)* 

*Threat Model write-up coming as soon as I near completion*


**SAST Security Tool** *(in progress)* — Static analysis tool that detects vulnerable patterns in Python codebases: hardcoded secrets, dangerous function calls, missing input sanitization. Motivated directly by findings in my own threat model work. This project is a challenge i want to take on to imporve my security knowledge or fundamentals

***InTrack** *(in progress)* — I'm building InTrack (previously CareerTrack) as my venture for Colgate's Thought Into Action program, an entrepreneurship program that helps students turn ideas into functional businesses, nonprofits, and community projects.

InTrack automatically tracks incoming emails on a given subject, groups them into a family of linked or chained related emails, and updates their status over time, so you end up with a full history of how something developed without ever having to record anything manually.

I'm testing it on internship applications first, since that's a category I know well and can validate against. **But the actual problem is much broader. Almost every workflow has correspondence that someone is currently tracking by hand: meetings, team collaborations, vendor relationships, promotional campaigns, newsletters, customer follow-ups, agreements, transactions, scholarships, higher-ed applications. Anything that unfolds across multiple emails over time and currently lives in someone's head or a spreadsheet**.

The application uses an LLM at its core, and the hardest problem I've hit is entity resolution and reliability, making sure the model connects the right emails to the right related family.

**What I've done so far:**
- Narrowed testing to internship applications I've done in the past
- Connected the InTrack extension to Gmail via the Gmail API
- Built backend logic that identifies application emails using keywords from automated messages ("Thank you for applying to...", "we have received your..."), sender organization, date, and similar signals

**What I'm working on solving:**
- Moving past hardcoded detection logic, which doesn't scale, toward real entity resolution. The hard case is non-automated mail: a recruiter's personal email, a scheduling message, any real human correspondence that belongs to a thread that started with an automated email
- A status dashboard that makes the tracked history actually readable at a glance


---

## Skills
- Languages: Python, Java, JavaScript, HTML/CSS
- Backend: Flask, Jinja2, REST APIs
- Tools: Linux/Unix CLI, Git/GitHub, Docker (familiar)
- Security: PortSwigger Web Security Academy — Path Traversal, Access Control, Authentication, SSRF, OS Command Injection, SQL Injection, File Upload Vulnerabilities; threat modeling writeup
- Concepts: OAuth 2.0, Concurrency & Threading, Input Validation, HTTP/TCP-IP, Client-Server Architecture
---

## Currently learning

- PortSwigger Web Security Academy. Working through the OWASP Top 10
- Entity resolution
- Abstract Syntax Trees (AST) and how they connect to Static Application Security Testing (SAST)

## Goals
- Make Significant progress on my InTrack progress, pitch the venture, and get it somewhere big.
- Open source contribution
- Improve skill sets
- Gain experience oppurtunities


