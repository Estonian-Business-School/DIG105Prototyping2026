# 🚀 [Add Here Your Digital Product Name]

**Course:** DIG105 Digital Product Development and Prototyping (Autumn 2026)  
**Lecturer:** Marko Rillo  
**Team Members:** 
* [Add Here Student 1 Name] – [Email/LinkedIn]
* [Add Here Student 2 Name] – [Email/LinkedIn]

## 📌 Executive Summary
[Write a 2-3 sentence elevator pitch for your app. What specific user problem does it solve, and what is the core value proposition?]

## 🔗 Quick Links
* 🌐 **Live Application:** [URL once deployed via Lovable.ai/Vercel]
* 🎨 **Figma Prototype:** [URL to High-Fidelity Design]
* 🧠 **FigJam/Miro Empathy Map:** [URL to Discovery Board]
* 📹 **Final Pitch Video:** [URL to final recorded demo]

## 📂 Repository Navigation

### 1. User Research & Design (`/01_discovery_and_design`)
This section documents our transition from raw user empathy to structured product architecture. Create new directory for every 2 weeks when you complete your tasks in this course. In case you change something, then update it here, too.
* [Functional Requirements](./01_discovery_and_design/functional_requirements.md): Translating user needs into actionable app features.
* [Architecture & User Flows](./01_discovery_and_design/architecture_flows.md): How our users move from "Login" to "Value".
* [Prototyping Journey](./01_discovery_and_design/visual_prototypes.md): Our evolution from paper sketches to high-fidelity Figma components.
* ... add here your future documentation as we progress in the course.

### 2. Sprint Progress & Video Diaries (`/02_video_diaries`)
We are operating in bi-weekly sprints. Each diary includes a 3–5 minute video demonstrating what we built, footage of a user testing it, and our reflections/pivots based on their struggles.
| Sprint | Focus Area | Video Link | Pivot / Key Insight |
| :--- | :--- | :--- | :--- |
| **Sprint 1** | Empathy & User Mapping | [▶️ Watch Diary 1](./02_video_diaries/sprint_01_diary.md) | *E.g., Users cared more about time than cost.* |
| **Sprint 2** | Needs to Requirements | [▶️ Watch Diary 2](./02_video_diaries/sprint_02_diary.md) | *Pending* |
| **Sprint 3** | User Flows & Architecture | [▶️ Watch Diary 3](./02_video_diaries/sprint_03_diary.md) | *Pending* |
| **Sprint 4** | Low-Fi Paper Prototyping | [▶️ Watch Diary 4](./02_video_diaries/sprint_04_diary.md) | *Pending* |
| **Sprint 5** | High-Fi Figma Design | [▶️ Watch Diary 5](./02_video_diaries/sprint_05_diary.md) | *Pending* |
| **Sprint 6** | Vibe Coding & Functional App | [▶️ Watch Diary 6](./02_video_diaries/sprint_06_diary.md) | *Pending* |

### 3. Business Strategy (`/03_business_and_pitch`)
* [Go-To-Market Plan](./03_business_and_pitch/go_to_market_plan.md): Our strategic roadmap for acquiring our first users and ensuring business viability.
* [Final Pitch Deck](./03_business_and_pitch/final_pitch_deck.pdf): Slides used for the Session 7 Grand Demo.

### 4. Codebase (`/src`)
Our functional prototype was generated using "Vibe Coding" principles. We utilized **Lovable.ai**, **Claude 3.5 Sonnet**, and **Cursor** to translate our visual designs into a functional React/Tailwind codebase without manual programming. The code resides in the `/src` directory.

**NB!NB!NB! Never add your personal credentials, API keys, .env files to the repository!**

### 5. Summary posible folder structure for your repository:
```
DIG105-your-project/
│
├── README.md                      # Main project hub (course info, quick links, overview)
├── .gitignore                     # To keep AI-generated code clean (e.g., Node.js template)
│
├── 📁 01_discovery_and_design/    # Empathy, Requirements, and Figma links
│   ├── functional_requirements.md # Translated from messy interviews (S1 & S2)
│   ├── architecture_flows.md      # User flows mapping "Login to Value" (S3)
│   └── visual_prototypes.md       # Links to Paper (Low-Fi) and Figma (High-Fi) designs (S4 & S5)
│
├── 📁 02_video_diaries/           # 6 bi-weekly sprint reflection videos
│   ├── sprint_01_diary.md         # Contains embedded YouTube links and written pivot notes
│   ├── sprint_02_diary.md
│   ├── sprint_03_diary.md
│   ├── sprint_04_diary.md
│   ├── sprint_05_diary.md
│   └── sprint_06_diary.md
│
├── 📁 03_business_and_pitch/      # 30% of grade - Go-To-Market and final presentation
│   ├── go_to_market_plan.md       # Strategy to acquire users
│   └── final_pitch_deck.pdf       # Exported slides for the Grand Demo (S7)
│
└── 📁 src/                        # 30% of grade - The codebase
    └── (This folder will be auto-populated by Lovable.ai and Cursor during S6)
```
