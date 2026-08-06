---
# ============================================================
#  MEMBER PROFILE TEMPLATE  —  _members/
#  1. Copy this file to _members/<name>.md
#  2. Fill in the front matter below.
#  3. In the body, KEEP ONLY the sections you have content for —
#     delete the rest so no empty headings render.
#  This file itself is never published (published: false).
# ============================================================
published: false

layout: profiles
inline: false

# --- Team grouping (controls placement on /team/) ---
group: Undergraduate students        # Master students | Undergraduate students | Alumni
group_rank: 100                      # smaller number = listed higher within the group
order: 1                             # ordering within the group
team_frontpage: true                 # show in the home-page "People" grid

# --- Identity ---
title: English Name                  # H1 title + English name shown in the team list
description: Profile of English Name, Student Researcher at KHU-SysSec.
lastname: Surname                    # keep this matching how your name appears in your papers
publications: 'author^=*Surname'

# --- One or two sentences, shown on the team card ---
teaser: >
  One or two sentences: who I am and what I research.

# --- Sidebar profile. Social icons render in THIS fixed order:
#     email · linkedin · orcid · scholar · twitter · github · website · cv · phone
#     Use a square headshot; keep a consistent background across members. ---
profile:
  name: 한글이름
  align: right
  image: <name>-profile.jpg          # square headshot in assets/img/
  image_orig: <name>-profile-orig.jpg
  role: Student Researcher           # Student Researcher | Alumni
  # alumni_note: Former Undergraduate Researcher   # Alumni only
  email: id@khu.ac.kr
  # linkedin:
  # scholar:
  # github:
  # website:
  # cv:
---

<!-- ============================================================
  BODY

  This follows the same format as Prof. CheolJun Park's page
  (_members/cheoljun.md) — look there for a filled-in example.

  Keep only the sections you have content for and delete the
  rest; an empty heading still renders on the site.

  WRITING RULES — please follow these exactly so every profile
  on the site reads the same.

  1. Every entry LEADS with the bold part: the title, the award,
     the role, the patent number.
  2. Supporting detail goes on a SECOND line, indented 3 spaces,
     with the place and date in *italics*. To make the line break
     work you must leave TWO SPACES at the end of the first line.
         - **Talk title**··                  <- two trailing spaces
            Venue, *City, Mon. Year*
  3. Dates: "Mon. Year", no parentheses, at the END.
     Months are 3 letters + a period — Jan. Feb. Mar. Apr. Jun.
     Jul. Aug. Sep. Oct. Nov. Dec. — EXCEPT May, no period.
  4. Date ranges use "~", never "-" or "–".
         (Sep. 2024 ~)      Mar. 2022 ~ Mar. 2025
     EXCEPT a year range glued to a name inside a comma-separated
     inline list — there a tight en dash reads better, because
     "2024 ~ 2026" is heavy enough to break up the list:
         ASIACCS 2026, ACSAC 2026, KIISC CISC 2024–2026
  5. Newest first in every list.
  6. English, except Korean-only titles (patents, domestic award
     names) that have no official English name.
============================================================ -->

<!-- CORE: intro block, as bullets. First bullet = your position,
     where, and since when. The date is when you JOINED KHU-SysSec. -->

- **Bachelor's Student** (Mar. 2023 ~) in the [Dept. of Computer Science & Engineering](https://ce.khu.ac.kr) @ [Kyung Hee University](https://khu.ac.kr)
- One sentence on what you research and what you are working on now.
- Previously, I was a **research intern at Some Lab** in 2024. <!-- optional -->

---

**Email**: id@khu.ac.kr

---

<!-- CORE -->
## Research Interests

- Cellular / wireless security
- Second interest, if any

<!-- Prior or additional degrees. Skip if the intro covers it. -->
## Education

- **B.S. in Information Security** (Mar. 2020 ~ Feb. 2025)  
   [Prior University](https://example.ac.kr), *graduated summa cum laude*

<!-- Papers, posters, domestic-conference talks. -->
## Publications & Presentations

- **Paper or poster title**  
   KIISC CISC-S, *Seoul, Jun. 2025*

<!-- Prizes, scholarships, paper awards. Numbered list, newest first. -->
## Honors & awards

1. **Grand Prize**, Cyber Security Hackathon, Korea Internet & Security Agency, Aug. 2024
2. **Excellence Award**, SW Education Donation Corps, Code Club Korea, 2022

<!-- Internships, programs, labs, student orgs, military service. -->
## Experience & Activities

- **Research Intern**, KAIST System Security Lab  
   *Jul. 2025 ~ Sep. 2025*
- **Team Leader**, SWING Information Security Club  
   *Mar. 2022 ~ Mar. 2025*

<!-- ===== Optional sections — add only if relevant =====

## Patents
- **KR 10-2022-0182441** (Filed)
   *Title of the patent*

## Service
- **Reviewer**: Venue, Venue, Venue
-->
