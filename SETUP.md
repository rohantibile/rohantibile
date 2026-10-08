# GitHub profile setup

## 1. Install the README (2 minutes)
Your profile README lives in the repository `rohantibile/rohantibile` (it already exists).
1. Open that repo, click **Add file → Upload files**, drag in `README.md` and the whole `assets/` folder, and commit to `main`.
2. Open `README.md` and search for `YOUR-PORTFOLIO-URL`. Replace both with your public portfolio link.
   The portfolio is private until you share it from the page's Share menu, so recruiters cannot open it yet.

## 2. Profile settings (Settings → Public profile)
| Field | Value |
|---|---|
| Name | Rohan Tibile |
| Bio | Java Developer · Spring Boot, Kafka, Microservices · 4 yrs on high-transaction insurance-tech · Pune · Open to work |
| Location | Pune, India |
| Website | your portfolio link |
| LinkedIn | https://www.linkedin.com/in/rohantibile |
| Timezone | Set it to India Standard Time, or turn off "Display current local time". Your profile currently shows UTC-12. |

Use the same portrait on GitHub as in the portfolio video so people recognise you on both.

## 3. Keep one story across resume, portfolio and GitHub
- **LinkedIn link:** your old GitHub README linked `in/rohan-tibile1997`. Your resume says `in/rohantibile`. Pick one and use it everywhere.
- **Stack claims:** the old README listed Oracle, SQL Server, Node.js and Jira. They are not on your resume. Either add them to the resume or leave them off GitHub. A recruiter who sees different stacks will trust neither.
- **Title:** use "Java Developer" everywhere. The old bio said "Full Stack Developer".
- **Instagram:** remove it from the profile README if this profile is for hiring.

## 4. Repositories
Your popular repositories are forks of tutorial repos (java-basics, nodejs-basics, azure-basics, react-basics, javascript-basics). Forks signal "learning", not "builder".
- Unpin all of them. Keep the forks if you like, but they should not be the first thing a visitor sees.
- Pin 2 to 3 original repos instead. Your client code is private, so build small public demos of the same ideas. Suggested names:
  - `kafka-order-events`: 3 small Spring Boot services talking through Kafka topics, with a dead-letter topic
  - `policy-premium-engine`: a premium calculation engine on Spring Data JPA with a JUnit 5 and Mockito suite
  - `observability-starter`: a Spring Boot service wired to Grafana and Loki with Docker Compose
- Give each repo a one-line description, topics (`java`, `spring-boot`, `kafka`, `microservices`) and a README that opens with the same `GET /route → 200 OK` style as this profile.

## 5. Design tokens (for social preview images and future repos)
| Token | Dark | Light |
|---|---|---|
| Background | #0B0D12 | #F4F2EE |
| Panel | #12161E | #FFFFFF |
| Text | #E8EAF0 | #12151C |
| Muted | #8A92A3 | #5B6372 |
| Accent (amber) | #FFA31A | #C25E00 |
| Secondary (steel) | #6FA8D6 | #2F6A99 |
| Success | #4ADE80 | #15803D |

Display type is Syne (800) with IBM Plex Mono for labels. GitHub images cannot load web fonts, so the SVGs use system fonts.
