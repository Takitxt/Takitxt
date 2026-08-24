# Varun Sharma

**Software engineer in training · CS student · open-source contributor**
`@Takitxt` · he/him · [takitxt.vercel.app](https://takitxt.vercel.app/)

I work on someone else's production codebase in public. Nine of my pull requests
are merged into [PictoPy](https://github.com/AOSSIE-Org/PictoPy), a privacy-first
desktop image gallery under the AOSSIE organisation — starting with a
documentation fix in mid-July 2026 and, five weeks later, converting its indexing
pipeline from serial to parallel. Everything below is verifiable from that PR
history.

<!-- FILL: add one line stating what you are looking for — internship, new grad
     role, GSoC with AOSSIE. Recruiters scan for this and it is the single
     highest-value sentence you can add to this file. I have left it out rather
     than guessing. -->

---

## Contents

[How I work](#how-i-work) · [Open source](#open-source) · [Merged pull requests](#merged-pull-requests) · [Projects](#projects) · [Technologies](#technologies) · [Activity](#activity) · [Contact](#contact)

---

## How I work

**I earn context before I ask for trust.** My first PR to PictoPy was a
documentation alignment fix. Nothing in it was impressive; that was the point. It
taught me the review culture and the layout of the repo at zero risk to anyone's
runtime. The features came after.

**I treat review comments as the deliverable.** Across nine PRs, maintainers left
112 comments. [#1424](https://github.com/AOSSIE-Org/PictoPy/pull/1424) alone drew
44 and a formal "changes requested" before it merged. Reworking it repeatedly was
the most useful thing that happened to me this year.

**Depth over breadth.** One organisation, one repository, nine merges. I could
have scattered small commits across twenty projects for a greener graph. Nine
reviewed merges into a single real codebase is a claim someone can actually check.

**Bugs first, features second.** Five of my nine PRs are labelled `bug`. Fixing
things is how I learn where a system's assumptions are hiding.

---

## Open source

### `AOSSIE-Org/PictoPy` — contributor

A desktop image gallery with a privacy-first architecture: object detection and
face clustering run on-device, so photos never leave the machine.

| | |
| :-- | :-- |
| Pull requests merged | **9** |
| Reverted | **0** |
| Currently open | **1** |
| Review comments received | **112** |
| First merge | 16 July 2026 |
| Most recent merge | 23 August 2026 |
| Areas touched | indexing · YOLO model management · folder management · semantic search · UI · docs |

**Trajectory.** Four of the nine started life as `good first issue`, and all four
are in the July cluster. The two August PRs labelled `backend` are
[#1447](https://github.com/AOSSIE-Org/PictoPy/pull/1447) (a stale async state that
hung semantic search) and
[#1464](https://github.com/AOSSIE-Org/PictoPy/pull/1464) (serial indexing made
parallel). The progression from cosmetic fixes to the indexing path took six weeks.

<!-- FILL: AOSSIE runs programmes I could not verify from your profile. If you are
     working toward GSoC with them, state it explicitly here — it changes how a
     reviewer reads this whole section. -->

---

## Merged pull requests

Newest first. Auto-updated daily; the state below is accurate as of 25 August 2026.

<!-- PR-FEED:START -->
| PR | Title | Labels | Merged |
| :-- | :-- | :-- | :-- |
| [#1466](https://github.com/AOSSIE-Org/PictoPy/pull/1466) | Cropped image fix in `addImagesCropDialog` | `bug` `UI` | 23 Aug 2026 |
| [#1464](https://github.com/AOSSIE-Org/PictoPy/pull/1464) | Indexing works in parallel instead of series | `backend` `enhancement` `frontend` | 17 Aug 2026 |
| [#1447](https://github.com/AOSSIE-Org/PictoPy/pull/1447) | Fix infinite "searching by meaning" loading state on back navigation | `backend` `bug` | 4 Aug 2026 |
| [#1443](https://github.com/AOSSIE-Org/PictoPy/pull/1443) | Folder-management loading-state cleanup | `cleanup` `UI` | 4 Aug 2026 |
| [#1424](https://github.com/AOSSIE-Org/PictoPy/pull/1424) | Implementation of profile-picture uploads | `frontend` `good first issue` | 4 Aug 2026 |
| [#1380](https://github.com/AOSSIE-Org/PictoPy/pull/1380) | Folder appears empty if AI tagging is enabled before indexing completes | `bug` `frontend` `good first issue` | 24 Jul 2026 |
| [#1387](https://github.com/AOSSIE-Org/PictoPy/pull/1387) | Fix navbar disappearing on scroll past one viewport | `bug` `frontend` | 20 Jul 2026 |
| [#1384](https://github.com/AOSSIE-Org/PictoPy/pull/1384) | Documentation: download-section alignment, remove link underlines | `documentation` `good first issue` | 19 Jul 2026 |
| [#1371](https://github.com/AOSSIE-Org/PictoPy/pull/1371) | Settings page does not update active YOLO model after change in Model Manager | `bug` `frontend` `good first issue` | 16 Jul 2026 |
<!-- PR-FEED:END -->

[View all my pull requests →](https://github.com/AOSSIE-Org/PictoPy/pulls?q=is%3Apr+author%3ATakitxt)

---

## Projects

### chat_app — author

Realtime chat application on the MERN stack. React client, Express and Node
server, MongoDB for persistence, Socket.IO for live message delivery and presence.
Built end to end.

**Stack:** React · Node.js · Express · MongoDB · Socket.IO
**Repository:** [Takitxt/chat_app](https://github.com/Takitxt/chat_app)

### PictoPy — contributor

Nine merged PRs across the indexing pipeline, model management and UI. See
[Open source](#open-source) above.

**Stack:** Python · frontend · on-device inference
**Repository:** [AOSSIE-Org/PictoPy](https://github.com/AOSSIE-Org/PictoPy)

### DSA — author

Daily algorithm and data-structure solutions in C++, maintained as a working log
rather than a showcase.

**Stack:** C++
**Repository:** [Takitxt/DSA](https://github.com/Takitxt/DSA)

### Personal site — author

[takitxt.vercel.app](https://takitxt.vercel.app/), deployed on Vercel.

<!-- FILL: list the stack for your site if you would like it here. -->

---

## Technologies

Only what is demonstrable from the repositories and merged PRs above.

| Category | Technologies |
| :-- | :-- |
| **Languages** | JavaScript · Python · C++ |
| **Frontend** | React |
| **Backend** | Node.js · Express · Socket.IO |
| **Data** | MongoDB |
| **Computer vision** | YOLO models · face clustering *(via PictoPy contributions)* |
| **Infrastructure** | Vercel · Git · GitHub Actions |

<!-- FILL: this table is deliberately conservative. Add rows only for things you
     have shipped with — an interviewer will ask about every entry here. -->

---

## Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/dashboard-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/dashboard-light.svg">
    <img alt="Merged pull requests by month, review load, and label distribution" src="./assets/dashboard-dark.svg" width="100%">
  </picture>
</div>

<p align="center">
  <sub>
    Generated inside this repository by a scheduled GitHub Action — no third-party
    service, so nothing here can break when someone else's server goes down.
  </sub>
</p>

<div align="center">

<a href="https://github.com/Takitxt">
  <img alt="Most used languages" height="150"
       src="https://github-readme-stats.vercel.app/api/top-langs/?username=Takitxt&layout=compact&langs_count=6&hide_border=true&bg_color=00000000&title_color=58a6ff&text_color=8b949e&hide_title=true">
</a>

</div>

<p align="center"><sub>Language mix across public repositories.</sub></p>

---

## Contact

| | |
| :-- | :-- |
| Website | [takitxt.vercel.app](https://takitxt.vercel.app/) |
| LinkedIn | [in/varuns347](https://linkedin.com/in/varuns347) |
| X | [@Varun_S_347](https://x.com/Varun_S_347) |
| GitHub | [@Takitxt](https://github.com/Takitxt) |

<!-- FILL: add an email if you want to be reachable by recruiters and maintainers.
     Right now there is no way to contact you off-platform. -->
