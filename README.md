## OVERVIEW

FLUX is a personal operating system and self-experimentation framework where I collect behavioral data and analyze productivity patterns.
By systematically applying these insights, I turn daily life into a controlled environment to experiment, learn, and improve my performance while developing practical skills in applied data science and behavioral analysis.

FLUX serves dual purposes: optimizing my performance through data-driven insights and building practical research skills through real-world behavioral experimentation.
Each tracked variable and tested intervention advances both goals forward — helping me work better every day while teaching me how to design studies, measure outcomes, and work with messy, longitudinal data.


## REPO STRUCTURE

```
FLUX/
├── README.md
├── core/               # System logic
├── configs/            # Tracking schemas
├── scripts/            # Logging scripts
├── database/           # SQLite storage
├── analysis/           # Data analysis files
└── research/           # Study documentation
    ├── 00_index.md         # Overview of all research documents
    ├── 01_foundations/     # Core principles and background
    ├── 02_methodology/     # Study design and variable definitions
    ├── 03_analysis/        # Data analysis fundamentals and correlation methods
    ├── 04_visualization/   # Charts and dashboard design
    ├── 05_case_studies/    # Reference examples and related work
    └── 06_experiments/     # Pilot studies and intervention results
```

## WHAT FLUX TRACKS

FLUX logs data twice a day—morning reflections and evening assessments—covering the variables demonstrated by research to influence focus, cognitive load, and daily performance.

### Morning Check-in

I record factors that set the baseline for the day:

- **Sleep:** hours, quality, restfulness, sleep-onset time  
- **Context:** caffeine timing, late meals, evening screen exposure—factors that may have influenced sleep quality  
- **Expected Cognitive Load:** planned tasks, anticipated mental demand, time pressure, and confidence in the day’s plan  

This captures how well the day starts and what conditions shape the first few hours.

### Evening Review

I document what actually happened:

- **Productivity:** tasks completed, effort, output quality, and satisfaction  
- **Study:** total hours, focus level, completion ratio, and study effectiveness  
- **Workout:** duration, intensity, exertion, and recovery signals  
- **Experienced Cognitive Load:** actual mental demand, time pressure, and fatigue—compared to what I expected  

Every variable is designed for long-term pattern recognition, grounded in behavioral science principles, and structured to reveal what consistently drives my best—and worst—performance days.

## PROJECT PHASES

FLUX progresses through five structured phases—from building consistent logging habits to extracting actionable insights and testing interventions. Each phase builds on the last, ensuring that analysis and experimentation rest on reliable data and rigorous methodology.

---

### Phase 1: Baseline Data Collection
**Purpose:** Build a consistent logging routine and generate the first 30 days of clean data.  
**Actions:**
- Record morning and evening logs every day  
- Maintain structured reflection with zero skipped entries  
- Flag early anomalies and repeating conditions  
- Keep the dataset organized for later integration  
**Status:** In Progress 

---

### Phase 1.5: Research & Methodology Foundation
**Purpose:** Establish the scientific and structural backbone of FLUX.  
**Actions:**
- Document behavioral-science principles (`01_foundations/`)  
- Finalize longitudinal study design (`02_methodology/`)  
- Set up analysis workflows (`03_analysis/`)  
- Define visualization logic (`04_visualization/`)  
- Collect case studies (`05_case_studies/`)  
- Outline experimentation protocols (`06_experiments/`)  
**Status:** Starting soon  

---

### Phase 2: Data Cleaning & Integration
**Purpose:** Convert raw logs into a validated, unified dataset.  
**Actions:**
- Merge morning and evening logs  
- Standardize formats and validate entries  
- Handle missing or inconsistent data  
- Document all cleaning decisions (`pilot_study_notes.md`)  
**Status:** Planned  

---

### Phase 3: Pattern Discovery & Correlation Analysis
**Purpose:** Identify variables that influence focus, mood, and productivity.  
**Actions:**
- Compute correlations across variables  
- Analyze long-term trends  
- Flag anomalies and unexpected patterns  
- Document insights for experimentation  
**Status:** Planned  

---

### Phase 4: Visualization & Dashboard Development
**Purpose:** Turn statistical findings into clear, actionable visual feedback.  
**Actions:**
- Build core charts (trends, correlations, distributions)  
- Design a simple dashboard interface  
- Explain chart decisions (`dashboard_design.md`)  
**Status:** Planned  

---

### Phase 5: Intervention Testing & Optimization
**Purpose:** Run targeted experiments based on discovered insights.  
**Actions:**
- Form hypotheses from correlations  
- Test routine or environmental interventions  
- Evaluate outcomes (`hypothesis_log.md`, `intervention_results.md`)  
**Status:** Future work


Phase 1 of data collection is underway; repository will expand as FLUX progresses through analysis, visualization, and experimentation phases.
