# IT Certification Study Library

A standalone certification study library for building an IT career path from Thailand-first employability toward Japan-ready cloud, security, and infrastructure roles.

The project is packaged as a single HTML app, `cert-prep.html`, with embedded course data and markdown content. It can be opened locally in a browser or deployed as a static GitHub Pages site.

## What This Course Covers

This library contains 405 chapters across 9 certification tracks and roadmap sections:

| Order | Course | Level | Chapters | Purpose |
| --- | --- | --- | ---: | --- |
| 0 | Priority Roadmap | Beginner | 17 | Thailand-first career order, strategy, and learning path guidance |
| 1 | AWS CLF-C02 | Beginner | 97 | AWS Cloud Practitioner foundation and cloud literacy baseline |
| 2 | PCEP + PCAP Python | Beginner | 39 | Python entry-level and associate certification preparation |
| 3 | CompTIA Security+ | Intermediate | 47 | Security fundamentals for IT, cloud, and cyber roles |
| 4 | AWS SAA-C03 | Intermediate | 43 | AWS Solutions Architect Associate and cloud engineering readiness |
| 5 | eJPT v2 | Intermediate | 37 | Junior penetration testing and practical offensive security entry |
| 6 | CKA | Advanced | 40 | Kubernetes administration for cloud-native infrastructure roles |
| 7 | CEH v13 | Advanced | 31 | Ethical hacking concepts for compliance and security hiring filters |
| 8 | CompTIA A+ | Beginner | 54 | Hardware, operating systems, networking, and IT support reference |

## Recommended Learning Order

The course is intentionally ordered for practical hiring value, not only exam difficulty.

1. Start with the Priority Roadmap to understand the strategy.
2. Finish AWS CLF-C02 for baseline cloud credibility.
3. Add PCEP or PCAP Python to prove programming ability.
4. Study CompTIA Security+ for security fundamentals and hiring filters.
5. Move into AWS SAA-C03 for cloud engineering and architecture depth.
6. Add eJPT v2 if targeting penetration testing or security operations.
7. Study CKA for Kubernetes and Japan/cloud-native infrastructure roles.
8. Use CEH v13 when a role, customer, or compliance path values it.
9. Use CompTIA A+ as a support and troubleshooting reference, especially for early IT foundations.

## Who This Is For

This study library is useful for:

- Fresh IT graduates building a cert-backed career roadmap.
- Learners in Thailand targeting cloud, security, or infrastructure roles.
- Learners planning a later move toward Japan tech opportunities.
- Self-study candidates who want one searchable certification library.
- Beginners who need a guided order instead of studying random certifications.

## App Features

- Single-file static app: no server required.
- Embedded markdown chapters for offline-friendly local use.
- Course browser with certification cards and chapter drawers.
- Reader mode with adjustable font size, width, spacing, and font family.
- Global search and in-chapter search.
- Progress tracking in local storage.
- Recently viewed and continue-reading sections.
- Chapter completion controls.
- Theme switcher with dark, light, cloud, and Japan-inspired themes.
- Code blocks, callouts, tables, links, and reader navigation.
- GitHub Pages deployment workflow.

## Repository Structure

```text
.
|-- .github/
|   `-- workflows/
|       `-- deploy.yml          # GitHub Pages deployment workflow
|-- cert-prep.html              # Standalone study app and embedded course content
|-- master-cert-guide-all.md    # Source-style combined markdown guide
`-- README.md                   # Project overview and usage guide
```

## How To Use Locally

No build step is required.

1. Clone or download the repository.
2. Open `cert-prep.html` in a modern browser.
3. Use the home page to choose a path or browse all courses.
4. Open a chapter and use the reader controls to adjust font size and spacing.
5. Track progress with the chapter completion controls.

Because progress is stored in browser local storage, progress is local to the browser and device you use.

## Deployment

The repository includes a GitHub Actions workflow that deploys `cert-prep.html` as both:

- `index.html`
- `cert-prep.html`

The workflow is located at `.github/workflows/deploy.yml` and uses GitHub Pages artifact deployment.

Current workflow trigger branches:

- `main`
- `claude/admiring-pascal-08pgak`

## Course Strategy

The guiding idea is simple: choose certifications based on employability sequence.

For Thailand-first career building, the priority is:

- Cloud literacy.
- Programming proof.
- Security fundamentals.
- Cloud architecture depth.
- Practical security or infrastructure specialization.

For Japan-oriented growth, the later focus shifts toward deeper infrastructure, Kubernetes, domain depth, and stronger role specialization.

## Notes On Content

- The HTML app embeds the course content directly for standalone use.
- `master-cert-guide-all.md` contains the full combined guide in markdown format.
- The course is a study aid, not an official certification vendor resource.
- Always confirm current exam objectives, pricing, and policies with the official certification providers before booking an exam.

## Maintenance Checklist

When updating the course:

1. Keep certification names and exam versions current.
2. Recheck chapter counts after content changes.
3. Verify `cert-prep.html` opens locally without console errors.
4. Confirm embedded markdown JSON is valid.
5. Confirm the GitHub Pages workflow still deploys the intended branch.

## Changelog

- Fixed reader default font size: base html/reader font now defaults to 16px (was incorrectly defaulting to 20px). Adjustable range remains 12px-22px via the A-/A+ controls.

## Author

Author: Hein Htet Zaw

Content format: AI-assisted certification study library.
