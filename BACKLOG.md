# Backlog: <project name>

This file is the **human-readable mirror** of the [GitHub Projects (v2) Iterative Development board](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) for this repo. Every row here is also a GitHub issue, added to the board, tagged with a milestone label, and sized.

## Conventions

- Each item has: id, title, hypothesis or user story, **Create / Observe / Analyze** triple, milestone tag, size.
- Items are ordered top to bottom by **priority**.
- Milestone tags: `M1-proposal`, `M2-data-summary`, `M3-poster-draft`, `M4-writeup-draft`, `M5-final`, `infra`, `ethics`.
- Sizes: seed, flower, tree, forest.
- The board has five columns: `Backlog` → `Create` → `Observe` → `Analyze` → `Done`. Each column is the *phase of work happening on a single PBI right now*, not a work type. See the [Iterative Development board explainer](https://courses.lpcordova.phd/data510/project-framework/#github-projects-board-per-project-iterative-development-board) for what each column means and when to advance a card.
- WIP cap: `Create + Observe + Analyze` ≤ `owners + 1` at any time.
- Definition of Ready and Definition of Done live in [`CHARTER.md`](CHARTER.md).

## Items

### PBI-001

- **Title:** Acquire and document data
- **Hypothesis:** data is accessible, license-compatible, and large enough to answer the research question.
- **Create:** download all available data and complete `data/README.md` section describing schema.
- **Observe:** row counts, missingness, key uniqueness, distribution sanity checks.
- **Analyze:** decide whether the dataset survives feasibility; document in the next Iteration Review.
- **Tag:** `M1-proposal`
- **Size:** Flower
- **GitHub issue:** [(https://github.com/b-l-proctor/Natural-Resources-Project/issues/1)]

### PBI-002

- **Title:** Draft research question and frame as a testable claim
- **Hypothesis:** We can state the project's research question in one sentence that names the population, the predictor or treatment, and the outcome.
- **Create:** RQ statement in `CHARTER.md` Mission section; one-paragraph framing in the proposal draft.
- **Observe:** can a peer PO who has never seen the project repeat the question back accurately?
- **Analyze:** revise based on Studio Brief feedback.
- **Tag:** `M1-proposal`
- **Size:** Flower
- **GitHub issue:** [https://github.com/b-l-proctor/Natural-Resources-Project/issues/2]

### PBI-003

- **Title:** Draft Methods section
- **Hypothesis:** We can write out the methods section in two to four paragraphs, including the data cleaning and more.
- **Create:** A document with rough drafts includes minimally two paragraph for the methods section.
- **Observe:** Can a peer easily understand what is written.
- **Analyze:** revise based on feedback.
- **Tag:** `M2-data-summary`
- **Size:** Flower
- **GitHub issue:** [https://github.com/b-l-proctor/Natural-Resources-Project/issues/3]

### PBI-004

- **Title:** Do a literature review
- **Hypothesis:** We can find literature that is answering similar questions to our research question, without being identical.
- **Create:** A written literature review around 1 page.
- **Observe:** Can a peer easily understand what is written.
- **Analyze:** revise based on feedback.
- **Tag:** `M1-proposal`
- **Size:** Flower
- **GitHub issue:** 

### PBI-005

- **Title:** Document a plan for data engineering
- **Hypothesis:** We can assemble different data sources into one database.
- **Create:** A 1 to 2 page written plan for data engineering, including a database schema and ERD.
- **Observe:** Can a peer understand what the connections are between the ERD.
- **Analyze:** revise based on feedback.
- **Tag:** `M1-proposal`
- **Size:** Flower
- **GitHub issue:** 

### PBI-006

- **Title:** Program integration plan
- **Hypothesis:** We can write a plan to reasonably use all five pillars of the data science curriculum to tell a story about the research question.
- **Create:** A 1 page written plan about integrating each part of data science into the project in alignment with the research question.
- **Observe:** Can a peer feasibly see each pillar happening in alignment with the project and research questions.
- **Analyze:** revise based on feedback.
- **Tag:** `M1-proposal`
- **Size:** Seed
- **GitHub issue:**

### PBI-007

- **Title:** Timeline documentation
- **Hypothesis:** We can write a timeline to help plan out the remainder of the semester.
- **Create:** A brief timeline incorporating all of the milestone due dates and brief/critique deadlines.
- **Observe:** Do my peer POs understand and think the timeline is functional.
- **Analyze:** revise based on feedback.
- **Tag:** `M1-proposal`
- **Size:** Seed
- **GitHub issue:** [https://github.com/b-l-proctor/Natural-Resources-Project/issues/4]
