---
title: User Stories and Tasks — Evidence
---

# User Stories and Tasks — Evidence

[← Back to portfolio](../) · [Reflection](reflection.html)

| | |
|---|---|
| **Student** | Tlou Masebe (230128521) |
| **Module** | Project Presentation 3 (PRP370S/371S/372S) |
| **Host employer** | Soluon |
| **Project** | YES Quality Work Experience app — Host/SME side |

> Format: *As an SME host, I want to register once and log in, so that I do not re-register and my profile is protected.* Each story has acceptance criteria (AC) that say when it is done, and tasks (T) that break the work into steps. Example: *As an SME host, I want to register once and log in, so that I do not re-register and my profile is protected.*

---

## Epic A — Getting Started

### US-01 · Environment setup and onboarding

**As a** developer intern, **I want** to run the app and backend locally on the correct branch, **so that** I can start contributing safely.
**AC:** Repo cloned; correct branch confirmed with the team lead; Expo web app runs in Chrome; Flask backend runs from the `Server` folder.

- T1.1 Read the problem statement and README
- T1.2 Clone the repo
- T1.3 Confirm the correct branch with Shaun and switch to it
- T1.4 Run the Expo app in Chrome
- T1.5 Run the Flask backend and confirm the app talks to it

## Epic B — Host/SME Side

### US-02 · Host login and profile

**As an** SME host, **I want** to register once and log in, **so that** I do not re-register and my profile is protected.
**AC:** Host can register and log in; profile persists in SQLite; approach approved by the team lead.

- T2.1 Agree the login feature with Shaun (approved)
- T2.2 Add register and login endpoints to the Flask backend
- T2.3 Build the host login/registration screens
- T2.4 Persist and load the host profile

### US-03 · Host posts a work-experience task

**As an** SME host, **I want** to post a task or opportunity, **so that** suitable youth can be matched to it.
**AC:** Host can create and edit a task with the required details; the task is saved in the backend.

- T3.1 Define task fields with Shaun
- T3.2 Build the create/edit task screen
- T3.3 Add task endpoints and storage
- T3.4 Test on the local setup

### US-04 · AI task matching

**As an** SME host, **I want** my task routed to suitable youth, **so that** I receive relevant candidates.
**AC:** A posted task produces matched candidates from the Youth side; the result is visible to the host.

- T4.1 Agree the matching inputs with Inam (Youth side)
- T4.2 Connect the host task data to the matching logic
- T4.3 Display matches on the host screen

### US-05 · Host tracks progress

**As an** SME host, **I want** to see matched youth and task progress, **so that** I can manage the placement.
**AC:** Host sees matches and a status per task.

- T5.1 Design the host dashboard
- T5.2 Build the dashboard from backend data

### US-06 · Offline-first host use

**As a** host with limited connectivity, **I want** the app to keep working offline, **so that** I do not lose my work.
**AC:** Host data is kept on the device and syncs when a connection returns.

- T6.1 Review how offline storage works in the existing app
- T6.2 Make host actions work offline
- T6.3 Test with the network off

## Epic C — Team and WIL Admin

### US-07 · Hackathon demo

**As a** team, **we want** a working demo of the host flow, **so that** we can show progress at the hackathon.
**AC:** Host flow demonstrable end to end on the local setup.

- T7.1 Agree the demo scope with Shaun
- T7.2 Build and test the host flow
- T7.3 Report progress to the team

### US-08 · Version control and integration

**As a** developer, **I want** to commit and push my host-side changes to the agreed branch after team confirmation, **so that** the Youth side can integrate them.
**AC:** Changes committed with clear messages; pushed only after Shaun confirms; no conflicts with the Youth work.

- T8.1 Commit changes on the working branch
- T8.2 Confirm the push with Shaun
- T8.3 Push and check the integration

### US-09 · Agile portfolio and WIL documentation

**As a** student, **I want** my Agile evidence and reflections published on GitHub Pages, **so that** I can submit my portfolio.
**AC:** Five sections with Evidence and Reflection pages; link submitted on Blackboard.

- T9.1 Write the charter, stories, backlogs and logbook
- T9.2 Write the five reflections
- T9.3 Publish on GitHub Pages and submit the link
