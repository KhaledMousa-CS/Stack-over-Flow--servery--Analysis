# 📊 The 2025 Global Tech Ecosystem: A SAS Visual Analytics Deep Dive

> **Course:** Business Intelligence | **Platform:** SAS Visual Analytics on SAS Viya 4  
> **Institution:** University of Sadat City — Faculty of Computers and Artificial Intelligence  
> **Department:** Information Systems

---

## 👥 Project Team

| Role | Name |
|------|------|
| **Team Member** | Khaled Mousa Ali |
| **Team Member** | Ahmed Srour |
| **Team Member** | Ebrahim Zaghlol |
| **Supervisor** | Dr. Ahmed Lamey |
| **Supervisor** | Eng. Aya Al-Malah |

---

## 📌 Project Overview

This project delivers a professional-grade tech market analysis built on the **Stack Overflow Developer Survey** dataset, visualized using **SAS Visual Analytics on SAS Viya 4**. The report focuses on the Middle East and Arabic-speaking countries while also contextualizing findings within the global developer ecosystem.

The core research questions driving this project:
- How is **Generative AI** reshaping the day-to-day work of developers?
- What does the shift in **remote work culture** mean for talent and organizations?
- Which **technologies, tools, and frameworks** dominate the modern stack?
- What is the **demographic and geographic profile** of today's tech workforce?

---

## 🗂️ Dashboard Structure

The report is organized into **4 analytical parts** across **7 dashboard pages**:

### Part 1 — Demographics & Global Geography
| Page | Visualization | Key Insight |
|------|--------------|-------------|
| Page 1 | Geo Map (Country × Frequency) | Global developer footprint; emerging hubs in MENA |
| Page 1 | Bar Chart — Age × Frequency | 25–34 age group dominates ("engine room" of the industry) |
| Page 1 | Donut Chart — EdLevel | Bachelor's is baseline; non-traditional paths on the rise |
| Page 1 | Pie Chart — RemoteWork | Remote vs. Hybrid distribution reveals workforce flexibility trends |

### Part 2 — Professional Landscape & Industry Sectors
| Page | Visualization | Key Insight |
|------|--------------|-------------|
| Page 2 | Horizontal Bar Chart — DevType | Full-stack dominance; generalist skills increasingly valued |
| Page 2 | Donut Chart — Industry | Financial Services, Healthcare & Manufacturing are top tech employers |

### Part 3 — The Modern Technology Stack
| Page | Visualization | Key Insight |
|------|--------------|-------------|
| Page 3 | Word Cloud — LanguageHaveWorkedWith | Bash/Shell & HTML/CSS prominent; Python's AI dominance visible |
| Page 3 | Treemap — DatabaseHaveWorkedWith | PostgreSQL leads; shift toward open-source relational DBs |
| Page 4 | Bar Chart — OfficeStackAsyncHaveWorkedWith | GitHub leads async collaboration tools |
| Page 4 | Bar Chart — DevEnvsHaveWorkedWith | Android Studio top; Claude Code & Cursor emerging strongly |
| Page 4 | Treemap — CommPlatformHaveWorkedWith | Stack Overflow dominant; GitHub, Reddit, Discord follow |
| Page 5 | Treemap — WebframeHaveWorkedWith | Angular & ASP.NET lead; React, Django, Express strong presence |
| Page 5 | Bar Chart — SOTagsHaveWorkedWith | Tailwind CSS leads trending tags; LLM/AI tools rising |

### Part 4 — The AI Revolution & Future Sentiment
| Page | Visualization | Key Insight |
|------|--------------|-------------|
| Page 6 | Bar Chart — AIAgentExternal | ChatGPT far ahead; Claude Code & GitHub Copilot are strong competitors |
| Page 6 | Treemap — AIToolCurrentlyMostlyAI | Project planning & search are top AI use contexts |
| Page 6 | Line Chart — AIAgent_Uses | Software development tasks overwhelmingly dominate AI agent usage |
| Page 7 | Treemap — AgentUsesGeneral | Language processing & multi-platform search are primary uses |
| Page 7 | Pie Chart — AIThreat | Majority are not concerned about AI as a personal career threat |
| Page 7 | Donut Chart — AIComplex | Mixed sentiment on AI handling complex tasks |
| Page 7 | Bar Chart — AILearnHow | AI CodeGen is the #1 way developers learn AI; technical docs follow |

---

## 🔍 Key Findings

### 🌍 Demographics
- The **25–34 age group** is the largest segment — cloud-native developers at peak productivity
- **Bachelor's degree** remains the norm, but "Some College" and "Secondary" segments reflect growing non-traditional entry paths
- A significant **hybrid and remote workforce** in the MENA region suggests companies must offer flexibility to attract talent

### 💻 Technology Stack
- **Bash/Shell** and **HTML/CSS** are highly prevalent in the regional survey
- **Angular** and **ASP.NET** dominate the web framework landscape in this dataset
- **Tailwind CSS** tops the trending Stack Overflow tags, signaling rapid frontend tooling adoption
- **PostgreSQL** is gaining ground as the preferred open-source relational database

### 🤖 AI Adoption
- **ChatGPT** leads AI tool adoption by a wide margin; **Claude Code** and **GitHub Copilot** are the next tier
- Primary AI use cases: **debugging**, **writing boilerplate**, **project planning**, and **learning**
- Developers are mostly using AI as a **"Tireless Junior Partner"** — handling repetitive tasks while humans focus on architecture
- Most developers do **not** view AI as a direct personal threat, but worry about displacement of **entry-level roles**
- **AI CodeGen tools** are the top method for learning AI among developers in this cohort

### 🏢 Industry
- The tech workforce is no longer concentrated in "pure tech" companies
- **Banking/Financial Services, Higher Education, Computer Systems** are top employers alongside Software Development
- **Stack Overflow** remains the primary community platform, followed by **GitHub** and **Discord**

---

## 🛠️ Tools & Technologies Used

| Category | Tool |
|----------|------|
| **BI Platform** | SAS Visual Analytics on SAS Viya 4 |
| **Data Source** | Stack Overflow Developer Survey 2024 |
| **Chart Types** | Geo Map, Bar/Horizontal Bar, Donut, Pie, Treemap, Word Cloud, Line Chart |
| **Advanced Features** | Geographic mapping, data brush-linking, multi-response category analysis |

---

## 📁 Project Files

```
📦 Project Root
├── README.md                          ← This file
├── The_State_of_the_Tech_Market_      ← Full project report (PDF)
│   Stack_Overflow_Survey_Analysis.pdf
├── Screenshots/
│   ├── Page_1_Demographics.png        ← Geo map, age, EdLevel, remote work
│   ├── Page_4_DevTools.png            ← Office stack, dev environments, comm platforms
│   ├── Page_5_Frameworks.png          ← Web frameworks, SO tags, LearnCode
│   ├── Page_6_AI_Tools.png            ← AI agents, tool usage, agent uses
│   └── Page_7_AI_Sentiment.png        ← AgentUsesGeneral, AIThreat, AILearnHow
```

---

## 🚀 How to Reproduce

1. **Access SAS Viya 4** via your institution's SAS Viya for Learners portal
2. **Import the dataset**: Download the Stack Overflow Developer Survey from [survey.stackoverflow.co](https://survey.stackoverflow.co)
3. **Upload to SAS Visual Analytics**: Use SAS Information Catalog to register the dataset
4. **Build the dashboards** following the page-by-page visualization guide in the project PDF
5. **Apply filters** for MENA/Arabic countries on Page 1 to focus on the regional perspective

### Visualization Quick Reference

```
Part 1 → Geo Map + 3× Bar/Donut Charts
Part 2 → Horizontal Bar (DevType) + Donut (Industry)
Part 3 → Word Cloud + 2× Treemap + Bar Charts
Part 4 → Bar (AIAgentExternal) + Treemap + Bar (AILearnHow, AIThreat)
```

---

## 📚 Resources & Further Learning

- [SAS Viya for Learners](https://www.sas.com/en_us/software/viya-for-learners.html) — Advanced predictive modeling tutorials
- [SAS Skill Builder for Students](https://www.sas.com/en_us/learn/academic-programs/resources/free-sas-e-learning.html) — Visual Analytics 1 & 2 e-learning paths
- [Stack Overflow Survey Data](https://survey.stackoverflow.co) — Full raw dataset

---

## 📄 License & Academic Integrity

This project was completed as part of the **Business Intelligence** course at the University of Sadat City. All data originates from the publicly available Stack Overflow Developer Survey. Visualizations and analysis are original academic work.

---

*Faculty of Computers and Artificial Intelligence — Information Systems Department*  
*University of Sadat City, Egypt*
