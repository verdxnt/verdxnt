# Tobi Onabanjo

CS student at Colgate University (Class of 2028), focused on application security and backend development. First-gen student. I build to understand how things work.

[LinkedIn](https://linkedin.com/in/tonabanjo) · [tonabanjo@colgate.edu](mailto:tonabanjo@colgate.edu)

---

## What I'm working on

**DLMC Video Downloader** — Replaced a single-machine desktop script with a multi-user Flask web service for Colgate ITS. Built concurrent background jobs with threading and subprocess management, UUID-scoped folders to prevent filename collisions, live progress polling, and optional email notifications via Gmail API. Before shipping, I audited my own code and wrote a full threat model. [Read the threat model →](https://github.com/verdxnt/media-downloader-threat-model) *(Private institutional repo)*

**Remote 3D Print Submission System** *(in progress)* — 
Replacing USB print flow across 5 lab printers with a remote submission system and slicing instructions plan.

*What I've done so far*:
- Flashed Rinkhals firmware after stock firmware couldn't be driven over serial to my test printer
- Built a Flask upload endpoint with path-traversal prevention, file-type validation, and identity format checks.
- Aggregates all 5 printers into a single status endpoint. *(Private institutional repo)* 

*Threat Model write-up coming as soon as I near completion* :)

*What I'm working on right now*:
- continuing to work on backend logic of the web app
- continuing to develop the front end of the web app
- Gathering all physical hardware pieces I might need for the server and printers
- continuing to build and test the app against any vulnerabilities (this is a nice one to test any file upload vulnerabilities ;)

**SAST Security Tool** *(in progress)* — Static analysis tool that detects vulnerable patterns in Python codebases: hardcoded secrets, dangerous function calls, missing input sanitization. Motivated directly by findings in my own threat model work. This project is a challenge i want to take on to imporve my security knowledge or fundamentals

**InTrack** *(in progress)* — I’m building InTrack (previously CareerTrack) as my school TIA venture -  an entrepreneurship program that helps students transform their ideas into functional businesses, nonprofits, and community projects. It is an application that will automatically track incoming emails of a specific subject, group them into a family of linked or chained germane-related emails, and automatically update their status to provide the user with a history of tracked records for how each specific event grew/developed/updated over time without the user ever having to track anything manually (e.g, job/internship applications, scholarships, Higher Ed applications, meetings, interviews, and so much more). The application will use an LLM at its core, and the hardest problem I’ve hit is entity resolution and reliability - making sure the model connects the right emails to the right related family. Don't worry, I plan to give it a cool and appealing status dashboard. This project is my venture for my Thought Into Action (TIA) program @ Colgate - a possible startup idea.

What I've done so far:
- Narrowed testing to Internship applications I've done in the past
- Connected the InTrack extension to my Gmail account via the Gmail API.
- Hardcoded backend Logic that grabs all internship applications using application keywords from automated emails like "Thank you for applying to/for...", "we have received your...", name of  organization like "noreply@mail.amazon.jobs", date, etc

What I'm working on solving:
- Instead of hardcoding the logic that tracks the chain of other germane-related emails (quite impossible btw), I am trying to solve the entity resolution problem since   I expect to get germane-related emails from non-automated emails like (e.g recruiters' email, subject organizer email, or essentially any other real human email that    might be connected to a previously automated email)

- 
---

## Skills

**Languages:** Python, Java, JavaScript, HTML/CSS
**Backend:** Flask, Node.js, Jinja2, REST APIs  
**Tools:** Linux/Unix, Docker, Git  
**Security:** PortSwigger Web Security Academy (path traversal, access control, authentication, SSRF, OS Command injection, SQL injection, File Upload Vulnerabilities), OWASP Top 10, threat modeling writeup
**Concepts:** Concurrency and threading, input validation, OAuth 2.0, HTTP/TCP-IP, client-server architecture

---

## Currently learning

- PortSwigger Web Security Academy — working through the OWASP Top 10
- Entity resolution
- TypeScript
- React
- A little bit of bash for testing
- more security tools that i may need for my SAST project

## Goals by the end of this year!
- Make Significant progress on my CareerTrack progress, pitch the venture, and get it somewhere big.
- Open source contribution to OWASP Juice shop or Bandit
- Improve skill sets
- Start technical write-ups on HashNodes

