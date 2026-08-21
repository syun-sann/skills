
# Agent Skills Repository

A curated collection of custom skills for Google Antigravity, Claude Code, and agentic coding/writing assistants. 

---

## Included Skills (will continuously update)
| Skill Name | Target Domain & Application | Documentation |
| :--- | :--- | :--- |
| **cas-writer** | IB DP CAS (Creativity, Activity, Service) experience entries, ManageBac logs, and Gibbs/Kolb deep reflections (Dual-language input, Standard English output). | [cas-writer/README.md](cas-writer/README.md) |
| **paper1-drafter** | IB DP Chinese A Paper 1 guided textual analysis (三维互斥分论点、六段式学术评论与辩证深化，对标 Level 7 官方标准). | [paper1-drafter/README.md](paper1-drafter/README.md) |
| **nus-essay-revision** | National University of Singapore (NUS) application essays, personal statements, and scholarship prompts (Standard British English, strict character limit discipline). | [nus-essay-revision/README.md](nus-essay-revision/README.md) |

---

## Skill Overviews

### 1. `cas-writer` (IB CAS Reflection Generator)
- **Key Features**:
  - Dual-language input (supports rough Chinese/English notes, voice transcripts, or bullet points).
  - Produces complete 3-part packages: Part 1 Activity Overview (100–180 words), Part 2 Deep Reflection (200–350 words), Part 3 Portfolio Evidence suggestions.
  - Strict anti-slop filter to eliminate corporate jargon and artificial AI clichés.
  - See [`cas-writer/README.md`](./cas-writer/README.md) for full instructions and examples.

### 2. `nus-essay-revision` (NUS Admissions Essay Revision)
- **Key Features**:
  - Enforces the official NUS character reply limits: **Max 600 characters** for Questions 1–3, **Max 1,100 characters** for Question 4.
  - Seamlessly integrates the **Five NUS Core Values** (Innovation, Resilience, Excellence, Respect, Integrity) in Question 4.
  - Enforces Standard British English spelling and Commonwealth academic conventions.
  - High information density and minimal-invasive editing to preserve authentic student voice.
  - See [`nus-essay-revision/README.md`](./nus-essay-revision/README.md) for full instructions and prompt breakdowns.

### 3. `paper1-drafter` (IB Chinese A Paper 1 Drafter)
- **Key Features**:
  - Strict 3-step workflow: Step 1 (3D Mutually Exclusive Sub-Arguments), Step 2 (Full 6-Paragraph Commentary with Dialectical Limitation), Step 3 (Targeted Refinement).
  - Strictly aligned with IB Chinese A Level 7 (20/20 Marks) Assessment Criteria A, B, C, and D.
  - Academic metalanguage and PEEL micro-structural evidence analysis.
  - See [`paper1-drafter/README.md`](./paper1-drafter/README.md) for templates and full exemplar commentaries.

---

## Installation & Usage

To install these skills in your local AI agent configuration:

1. Clone this repository:
   ```bash
   git clone https://github.com/syun-sann/skills.git
   ```

2. Copy the desired skill directories into your environment's skills folder:
   - **Google Antigravity**: `~/.gemini/config/skills/`
   - **Claude Code**: `~/.claude/skills/` (or `.claude/skills/` within a project)

