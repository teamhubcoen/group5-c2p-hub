# C2P Tech Hub — Website

**Live site:** https://teamhubcoen.github.io/group5-c2p-hub/
**Repository:** https://github.com/teamhubcoen/group5-c2p-hub

> *Rooted in knowledge, Branching into Innovation.*

A static promotional website for **C2P Tech Hub**, the student innovation hub within the Department of Computer Engineering, Ahmadu Bello University, Zaria. Built for **COEN 554 — Web Programming** (2025/2026 session, Question 3).

## About the Hub

C2P Hub exists to help Computer Engineering students turn coursework ideas into working prototypes, through mentorship, lab access, and a peer community that ships. This site covers the hub's programs, member directory, project showcase, gallery, events, and how to join.

## Assignment Constraints

This site was built under the assignment's core constraints:
- **No JavaScript, no CMS, no server-side code** — pure XHTML/HTML5 and CSS3
- **CSS-only interactivity** — checkbox-driven mobile navigation and `:target` modals for project/member detail views
- **Structured content** — page content modelled in `data/data.json` rather than hardcoded into markup
- **Semantic linked data** — every page embeds JSON-LD (`Schema.org`) structured data in `<head>` for search engine indexing

## Project Structure

```
.
├── index.html            Home
├── about.html            About the Hub
├── programs.html         Innovation Programs
├── projects.html         Student Projects
├── directory.html        Student Directory
├── gallery.html          Gallery
├── events.html           Events
├── join.html             Join the Hub
├── contact.html          Contact
├── assets/
│   ├── css/style.css     Shared stylesheet
│   └── images/           Logo, project photos, gallery images
└── data/
    └── data.json          Structured content (programs, projects, members, events)
```

## Pages

| Page | Description |
|---|---|
| Home | Hero, hub stats, featured award-winning project |
| About the Hub | Mission, story, and where the hub is based |
| Innovation Programs | The four tracks: AI & Data Science, Embedded Systems & IoT, Product Design & Prototyping, Startup Incubation |
| Student Projects | Real member-built projects, including award-winning work |
| Student Directory | Hub coordinators and track leads |
| Gallery | Photos from hub events |
| Events | Hackathons, workshops, and exhibitions |
| Join the Hub | Eligibility, how to apply, interest form |
| Contact | Hub location, email, and a contact form |

## Featured Project

**ParaVision** — a computer vision system that tests for malaria from a blood sample in under 5 minutes. Built by Olorunfemi Grace Temitayo, Ruqayya Labbo, and Khadija Khalid — 🏆 Winner, Huawei ICT Global Competition (Innovation Track), 2026.

## Deployment

Hosted on **GitHub Pages**, served directly from the `main` branch of this repository.

## Documentation

Full technical report — covering the visual design rationale, `data.json` schema, HTTP/MIME overview, and CMS-vs-manual justification, plus mobile and desktop screenshots — is included in the group's submission (`GROUP_5_COEN554_Documentation.docx`).

## Team

**Group 5** — Department of Computer Engineering, ABU Zaria
