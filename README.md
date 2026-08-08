# MASTER PROMPT — Sriram M GitHub Profile README

Paste this entire prompt into Claude (or any capable AI) any time you want to regenerate, update, or rebuild your GitHub profile README from scratch. It is self-contained — no need to re-upload your resume.

---

## ROLE

You are building a GitHub profile README (the special `username/username` repo) for the person described below. Output ONE single `README.md` file, plus one profile photo file. Follow every rule in the "Hard Rules" section exactly — they exist because earlier versions broke.

---

## PERSON DATA (from resume — use exactly, don't invent extra facts)

**Name:** Sriram M
**Location:** Perambalur, Tamil Nadu, India
**Email:** kit29.am48@gmail.com
**Links:**
- LinkedIn: https://linkedin.com/in/srisriram
- GitHub: https://github.com/Sriram2214
- LeetCode: https://leetcode.com/u/SriramMuthaiya/ (handle: `SriramMuthaiya`)
- CodeChef: https://www.codechef.com/users/srirammuthaiya (handle: `srirammuthaiya`)
- Codeforces: https://codeforces.com/profile/kit29.am48 (handle: `kit29.am48`)
- Codolio: https://codolio.com/profile/SriramMuthaiya

**Summary:** First-year B.E. Computer Science (AI & ML) student at Kalaignar Karunanidhi Institute of Technology (CGPA 8.9/10.0), with hands-on experience across ML, DL, generative AI, agentic AI, and CNN-based models (Python, NumPy, Pandas). Completed AI/ML internships with V-DART and CodeAlpha. Comfortable with the full data-analyst workflow. Also builds full-stack + AI-assisted apps (Python, C, C++, Java, HTML, SQL, Cursor, Google AI Studio, Lovable). 1400+ CodeChef problems, 150+ LeetCode problems, 10+ GitHub projects. Submitted 10+ research paper proposals, 1 accepted for publication.

**Education:**
| Institution | Program | Duration | Score |
|---|---|---|---|
| Kalaignar Karunanidhi Institute of Technology, Coimbatore | B.E. CSE (AI & ML) | 2025–2029 | CGPA 8.9/10.0 |
| Jayaram Educational Trust | Full Stack Dev (Power BI, Python, HTML, SQL, C) | May–Aug 2025 | — |
| St. Mary's Matriculation HSS, Agaram | Class XII / X | — | 193.5/200 · 96.6% |

**Internships:**
- AI/ML Domain Intern — V-DART, Trichy (1 month): real-world AI/ML workflows; delivered a Time Table Management System
- AI/ML Virtual Intern — CodeAlpha (1 month): Medical Predictor, AI Loan Credit Predictor, Speech Emotion Analyser

**Projects:**
1. Hospital & Healthcare Locator Platform — hospital/doctor/X-ray directory + GPS comparison + govt scheme info
2. InternHub — internship discovery + résumé-to-requirement profile matching + qualification advisor
3. Ulavanin Ulaipalar — smart agriculture support system for farmers
4. VAANI AI — multilingual real-time voice assistant
5. Student Management System — C + file handling
6. Smart No Due System — automated clearance/dues tracking
7. Farm Plan Pro — intelligent crop planning tool (C, DSA, file handling)

**Skills:**
- Languages: C, C++, Java, Python
- Web/DB: HTML, CSS, SQL
- Data/ML libs: NumPy, Pandas
- AI/ML: Machine Learning, Deep Learning, Generative AI, Agentic AI, CNNs, 15+ ML algorithms
- Data Analytics: cleaning/preprocessing, visualization, statistics & probability, Power BI
- AI Tools: Google AI Studio (Gemini), Cursor, Lovable, Antigravity, Codeflying, Emergent
- Core: Data Structures, File Handling, AI Automation, Prompt Engineering, Workflow Design

**Certifications:** ML with Python (IBM) · Data Science Essentials (Cisco) · Advanced DSA in Java: BSTs (Infosys Springboard) · C Programming (Infosys Springboard) · Generative AI (Intellipaat) · AWS Skill Fest Badge · MongoDB (AI/ML) Certification · National Level Srinivasa Ramanujan Mathematics Competition (Participant)

**Achievements:** Ideathon @ GSSS Women's College, Mysore · Smart Hack 32-Hour Hackathon @ KIT, Coimbatore · 1 research paper published

**Competitive programming stats:** CodeChef 1400+ solved / rating 1182 (1★) · LeetCode 150+ solved / rating 1298 · Codeforces 20+ solved · GitHub 10+ projects

---

## HARD RULES (do not violate — these caused real breakage before)

1. **Zero GitHub Actions / workflows.** Do not use any service that requires a `.github/workflows/*.yml` file, a repo secret, or a scheduled job (this rules out `github-profile-3d-contrib` and `Platane/snk` snake animation). Every image must render from a plain public URL or a local file, nothing else.
2. **No slow/sleeping third-party servers.** Avoid `onrender.com`-style free-tier services that take 10+ seconds to wake up.
3. **Profile photo must be a LOCAL file**, referenced as `assets/profile.png` inside the same repo — never hotlinked. Local files never go down.
4. **Development Journey section = plain text arrow diagram** (```text``` block with `↓`), NOT a Mermaid flowchart and NOT a Gantt chart. This was explicitly requested — do not reintroduce graphs there.
5. **Mermaid is allowed elsewhere** (e.g., the Generative AI pipeline) since GitHub renders it natively — never breaks, no image hosting involved.
6. **No decorative chart-generator images** (e.g., QuickChart radar/doughnut) unless explicitly asked for again — they were removed by request.
7. Competitive-programming cards, in this exact order/layout, using the exact handles above:
   - LeetCode: `https://leetcard.jacoblin.cool/SriramMuthaiya?theme=unicorn&font=Fira%20Code`
   - CodeChef: `https://cp-logo.vercel.app/codechef/srirammuthaiya?logo=true`
   - Codeforces: `https://codeforces-readme-stats.vercel.app/api/card?username=kit29.am48`
   - Codolio: badge-only link (no public embeddable stats API exists for Codolio)
   - Lay these out as a side-by-side "global-style" split (HTML `<table>`: LeetCode left column, CodeChef+Codeforces stacked right column), followed by a small solved/rating summary table.
8. GitHub stats via `github-readme-stats.vercel.app`, `github-readme-streak-stats.herokuapp.com`, `github-profile-trophy.vercel.app`, theme `radical`, username `Sriram2214`.
9. Header banner: `capsule-render.vercel.app` waving type, dark-navy-to-purple-to-cyan AI gradient (`0:0F2027,25:2C5364,50:6A11CB,75:2575FC,100:00C6FF`), `animation=twinkling`.
10. Typing subtitle via `readme-typing-svg.demolab.com`, cyan/purple/pink/yellow gradient text color, rotating through key facts (first-year student, CodeChef/LeetCode counts, ML/DL/GenAI/Agentic AI, ex-intern, a `model.fit()` joke).
11. Everything in **ONE `README.md` file** unless the person explicitly asks for it split into multiple files again.
12. Keep it colorful/rainbow-gradient throughout (`#00E5FF`, `#B14EFF`, `#FF6EC7`, `#F9D423`, `#6A11CB` family) — this was requested repeatedly and should stay the default palette unless told otherwise.

---

## BANNER IMAGE PROMPT (for external AI image generators — ChatGPT/DALL·E/Ideogram/Midjourney)

Use this if a custom hero banner image (not just the capsule-render gradient) is wanted:

```
A wide 1920x480px dark navy/black futuristic tech banner for a GitHub developer profile, cinematic digital-art style.

LEFT SIDE: Bold white text "TURNING DATA INTO" in a thin sans-serif font, below it large bold text "INTELLIGENT SOLUTIONS" in a blue-to-purple neon gradient. Below that, a thin divider line with a tagline "Building AI for a Smarter Tomorrow" (the word "AI" in cyan, "Smarter Tomorrow" in purple). Below the tagline, a rounded rectangle outlined in purple neon containing 4 icon+label pairs separated by dots: a brain-circuit icon labeled "LEARN", a lightbulb icon labeled "BUILD", a rocket icon labeled "INNOVATE", a target icon labeled "IMPACT" — all icons in thin cyan/purple neon line-art style.

CENTER-RIGHT: A large glowing digital human brain made of connected blue-purple nodes and wireframe lines, next to a glowing isometric microchip/CPU with "AI" text engraved on it in cyan neon, circuit board traces glowing blue radiating outward, small icons floating nearby (cloud, code brackets, database cylinder, gear) in thin neon line-art.

RIGHT SIDE: A vertical stack of 4 small info rows, each with a small cyan/purple line-icon on the left and two lines of white/cyan text on the right:
1. Brain-chip icon — "AI & ML" — "Building intelligent models that solve real-world problems"
2. Bar-chart icon — "DATA DRIVEN" — "Transforming data into actionable insights"
3. Cloud icon — "CLOUD & IoT" — "Working with cloud platforms, IoT devices & real-time systems"
4. Code-brackets icon — "FULL STACK" — "Python, SQL, backend & web technologies"

Background: deep navy-black with a subtle glowing blue wave/mesh pattern in the bottom-left corner and scattered faint binary digits. Overall palette: black background, electric blue, violet/purple, and white text. High-tech, glassy, glowing, professional portfolio-banner aesthetic — no photorealistic people, no real logos, no watermarks.
```

---

## OUTPUT INSTRUCTIONS

1. Generate `README.md` following every Hard Rule above.
2. If a resume PDF is attached in the same session, extract the embedded photo (`pdfimages -png`), crop it to a circle with a rainbow-neon ring border, and save it as `assets/profile.png` for the header.
3. Deliver both files ready to drop into the `<github-username>/<github-username>` repo — `README.md` in the root, `profile.png` inside an `assets/` folder.
4. Do not require any GitHub Actions setup for anything to render.
