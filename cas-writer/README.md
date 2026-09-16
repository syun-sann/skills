# CAS Experience & Reflection Writer (cas-writer)

A specialized skill for the International Baccalaureate (IB) Diploma Programme that generates, structures, and polishes authentic, high-scoring CAS (Creativity, Activity, Service) activity entries and in-depth reflections.

The skill seamlessly accepts user input in either Mandarin (Chinese) or English (including rough bullet points, voice transcription notes, or conversational drafts) and produces standard English outputs suitable for ManageBac and school coordinator reviews.

---

## Humanizer & Stop-Slop Integration

This skill deeply integrates the anti-AI writing frameworks of **Humanizer** and **Stop-Slop** to ensure all generated reflections read like genuine, articulate 17-year-old student writing:

1. **Zero Em-Dashes (`—`)**: Eliminates journalistic / sales-like em-dashes and replaces them with standard punctuation or restructured clauses.
2. **No Binary Negation Contrasts**: Eliminates artificial pivots (*"It wasn't about X, it was about Y"*) in favor of direct, honest statements.
3. **No Manufactured Aphorisms**: Cuts pull-quote slogans (*"athletic progress is an interdependent ecosystem"*) in favor of tangible operational habits and numbers.
4. **No Filler Adverbs & Intensifiers**: Cuts `-ly` intensifiers (`genuinely`, `fundamentally`, `deeply`, `actually`, `truly`, `acutely`).
5. **No Inanimate False Agency**: Ensures human actors (I, we, our coach) drive every sentence rather than abstract concepts (*"the session taught me"*).
6. **No Dangling `-ing` Participle Tails**: Removes superficial participle clauses tacked onto sentence endings.
7. **Rhythmic Variety & Concrete Micro-Details**: Pairs varied sentence lengths with physical, procedural, and sensory specifics.

---

## How to Use

### 1. Basic Invocation
Trigger this skill at any time by mentioning CAS reflections, CAS logs, ManageBac, or specific CAS activities in your prompt.

### 2. Input Formats Supported
You do not need to format your raw notes in any special way. You can provide:
- **Mandarin (Chinese) or English bullet points**: Raw notes of what you did, difficulties faced, and how things went.
- **Voice memo transcripts**: Conversational speech-to-text transcripts with pauses or informal phrasing.
- **Draft reflections**: Existing entries that you want to polish, deepen, or align with specific Learning Outcomes.

### 3. Example Prompts

#### Example A: Generating a Reflection from Chinese Notes
```
帮我写这周的 CAS 反思。
- 活动：学校文学杂志 (Literary Magazine) 的排版与封面插画 (Creativity)
- 时间：本周共花了 6 小时
- 过程与挑战：第一次用 Adobe InDesign 编排 32 页的册子，一开始没设好 3mm 出血位导致打印样张边缘被裁切，花了两晚看教程调整段落样式和 CMYK 分色。
- 感受与收获：发现出版工程量远超预期，提高了排版技术，也学会了预印前检查清单。
- 目标 LO：LO 1 和 LO 2
```

#### Example B: Generating a Reflection from English Notes
```
Write a CAS log and reflection for my 16km half-marathon training run.
- Strand: Activity
- Weather: 28C, very humid
- Challenge: Right hamstring tightened at km 11, wanted to give up, slowed pace to 6:15/km, focused on cadence and hydration.
- Reflection: Realized I had been skipping post-run stretching and recovery because of IA deadlines. Need better discipline for recovery.
```

#### Example C: Polishing an Existing Draft
```
Here is my current CAS reflection for tutoring at the local primary school. Please review it, remove any robotic or generic language, add realistic micro-details, and make sure it strongly hits LO 5 (Collaboration) and LO 7 (Ethics).
```

### 4. What the Skill Returns
Every generation produces a complete 3-part package in Standard English:
1. **Part 1: CAS Activity Entry**: A concise 100–180 word operational log ready for the ManageBac activity description.
2. **Part 2: In-Depth CAS Reflection**: A 200–350 word reflective journal following the Gibbs/Rolfe reflective model, embedding 1–2 target Learning Outcomes with concrete behavioral evidence.
3. **Part 3: Recommended Portfolio Evidence & Next Steps**: Practical suggestions for portfolio artifacts (photos, GPS logs, supervisor notes) and next session goals.

---

## The 7 IB CAS Learning Outcomes (LO 1 to 7)

The skill maps your experiences to the official IB CAS Learning Outcomes:
- **LO 1**: Identify own strengths and develop areas for growth
- **LO 2**: Demonstrate that challenges have been undertaken, developing new skills in the process
- **LO 3**: Demonstrate how to initiate and plan a CAS experience
- **LO 4**: Show commitment to and perseverance in CAS experiences
- **LO 5**: Demonstrate the skills and recognize the benefits of working collaboratively
- **LO 6**: Demonstrate engagement with issues of global significance
- **LO 7**: Recognize and consider the ethics of choices and actions

---

## Directory Structure

```
cas-writer/
├── SKILL.md                               # Main agent instructions, core principles, and pre-flight checks
├── README.md                              # User guide and anti-slop principles
└── references/
    ├── writing_style_and_vocabulary.md    # Comprehensive guide on authentic voice, stop-slop rules, and LO formulas
    ├── exemplars.md                       # High-scoring full exemplars for Creativity, Activity, Service, and CAS Projects
    ├── learning_outcomes_guide.md         # Full criteria, rubrics, and phrasing formulas for LO 1–7
    └── reflection_frameworks.md           # 5 CAS Stages, Gibbs Cycle, Rolfe Model, and Kolb Cycle
```
