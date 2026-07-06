<p align="center">
  <img src="https://img.shields.io/badge/status-MVP-blueviolet" alt="status" />
  <img src="https://img.shields.io/badge/AI-Claude%20(Anthropic)-orange" alt="ai" />
  <img src="https://img.shields.io/badge/license-MIT-green" alt="license" />
</p>

<h1 align="center">🧑‍🤝‍🧑 RUTAB</h1>
<p align="center"><b>AI-Assisted HR Hiring & Talent Pool Management</b></p>

<p align="center">
  RUTAB connects HR teams and job seekers in one platform — powered by AI that writes job posts,
  scores candidate fit, and gives applicants an honest read on their chances before they apply.
</p>

---

## 📽️ Demo

<!-- See the "How to embed the video" note below — replace this section once the clip is uploaded -->

> 🎬 A full walkthrough of the HR and candidate journeys is available in [`demo/Rutab_demo.mp4`](demo/Rutab_demo.mp4).

---

## 📌 Overview

Thousands of jobs are posted every day and thousands of candidates apply, yet hiring remains slow
and subjective. HR teams lose hours writing job descriptions and manually screening resumes, while
candidates apply blind, with no sense of whether they're actually a fit.

**RUTAB** closes that gap with an AI engine sitting on top of a normal hiring flow:

- HR posts jobs, reviews applicants, and keeps top talent in a reusable **Talent Pool**
- Candidates build a profile, browse jobs, and apply with a clear match score in hand
- AI handles the repetitive, subjective parts — job description writing, resume scoring, and gap analysis

## 👥 Who it's for

| Audience | Needs |
|---|---|
| **HR / Hiring Managers** | Post jobs faster, filter and rank applicants objectively, retain standout candidates for future roles |
| **Job Seekers / Candidates** | Understand real fit before applying, get actionable feedback on their resume |

## ⚙️ How it works

Two parallel journeys — HR posting/evaluating and candidates browsing/applying — share one database
and are connected by an AI matching engine that scores every resume against every job's requirements.

```
Candidate ─┬─ Register/Login ─ Build Profile ─ Browse & Filter Jobs ─ Apply / Save ─ CV/ATS Analysis
           │
           └──────────────► shared DB ◄──────────────┐
                                                       │
HR Manager ─┬─ Post Job (AI-generated) ─ Review Applicants (AI-ranked) ─ Update Pipeline ─ Save to Talent Pool
```

## 🤖 AI components

All three AI features are **optional** — triggered on demand, never mandatory:

| Feature | What it does |
|---|---|
| **Job Description Generation** | HR enters a job title + basics → AI drafts the description and required skills |
| **CV Matching Score** | On application, AI scores the resume against job requirements (0–100%) so HR can rank instead of reading randomly |
| **CV / ATS Analysis** | Candidates get a breakdown of strengths, gaps, and missing skills for a specific job |

**Model used:** Claude (Anthropic) via API

## 🧰 Tech stack

> Fill in with your actual stack — categories below are from the project (Frontend / Backend & AI / Database & Storage):

| Layer | Tools |
|---|---|
| Frontend | *e.g. React, Tailwind CSS* |
| Backend & AI | *e.g. Node.js, Claude API* |
| Database & Storage | *e.g. PostgreSQL / Supabase* |

## ✅ What works today

- Candidate: profile creation, CV upload, browse/save/apply to jobs, application status tracking
- HR: post jobs, view & rank applicants, update pipeline status, move strong candidates to Talent Pool
- AI layer: job description generation, CV match scoring, CV/ATS gap analysis

## 🚧 Known limitations

- CV analysis currently relies on the uploaded CV link + profile/job data — deeper in-file resume parsing is not yet implemented
- AI scoring would benefit from more training data, clearer scoring explanations, and richer filters
- No course recommendations, graduate support track, real-time notifications, or production deployment yet

## 🗺️ Roadmap

- [ ] Auto-extract skills directly from the uploaded CV file
- [ ] AI-powered CV improvement suggestions (wording, structure, clarity)
- [ ] Partnerships with training providers to close skill gaps
- [ ] Dedicated track for fresh graduates (guidance, internships, prep content)
- [ ] Smarter, deeper applicant filters for HR
- [ ] Conversational AI assistant ("Give me the top 5 candidates for this job")

## 👩‍💻 Team

Built during the Saudi Digital Academy × WeCloudData program.

- Esraa Ali Alzaylaee
- Rawan Adel Alfaifi
- Remas Abdullah Hamrun

Instructed by Zahy Aziz & Rizwan Chauhan

## 📄 License

MIT — or update this to match your project's actual license.
