---
widget: blank  # See https://wowchemy.com/docs/page-builder/
headless: true  # This file represents a page section.
weight: 10  # Order that this section will appear.

title: Shared Task on Readability-Controlled Text Simplification

design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: "1"
---

We invite participation in the TSAR 2025 Shared Task on Readability-Controlled Text Simplification, aimed at generating simplifications of texts that conform to a specified target readability level, balancing reduced linguistic complexity with meaning preservation and fluency.

### Announcements

- 17 July 2025: Trial data and evaluation scripts will now be released on July 18th.
- 07 July 2025: Shared task announced

### Description

The task targets English-language paragraphs written at upper-intermediate or advanced levels and requires participants to simplify them according to a specified target readability level, defined using the Common European Framework of Reference for Languages (CEFR). Specifically, participants will be asked to simplify texts originally at B2 level or above to target levels of A1, A2, or B1.

Participants are expected to adjust linguistic complexity while preserving the core meaning and coherence of the original paragraph.

### Important Dates

All dates are 11:59PM UTC-12:00 (“anywhere on Earth”).

- <del>16 July 2025</del> <span style="color:red">(NEW) 18 July 2025</span> – Trial data and evaluation scripts released  
- **15 August 2025** – Test data released  
- **26 August 2025** – System outputs due  
- **2 September 2025** – Evaluation results published  
- **23 September 2025** – System description papers due  
- **30 September 2025** – Reviews and notifications sent  
- **7 October 2025** – Camera-ready papers due  

### Data

This is a **fully open** task in terms of system development. Participants are free to use any publicly-available data or resources. **No training data will be provided.**

#### Trial Data

We will release a trial dataset including:

- Input paragraphs with associated target CEFR levels
- One or more reference simplifications
- Official evaluation scripts

This release is intended to help participants understand the data format, expected output, and evaluation process.

#### Test Data

The final test set will consist of:

- Paragraphs with target CEFR levels
- No references will be provided

Participants must submit their outputs strictly following a prespecified format for official evaluation.

### Evaluation

Submissions will be evaluated using the following metrics:

1. **CEFR Compliance:** A CEFR-level classifier will verify whether the simplified paragraph meets the specified target level.

2. **Meaning Preservation:** Semantic similarity between the source paragraph and the system output.

3. **Similarity to References:**  Semantic similarity between the system output and references.

The official evaluation scripts will be released together with the trial data.

### Participation

All participants must register in advance using the following form:

👉 [[Registration Form](https://forms.gle/p9rg7FjxaNFWcPVS7)]

Registered participants will receive announcements, updates, and submission instructions.

### Submission Format

Submissions must follow a specific JSON format (details will be provided with the trial data). Each entry should include:

- A paragraph ID
- The simplified paragraph
- The target CEFR level

Each team may submit **up to three runs** for evaluation.

### Publication

Participants are invited to submit a system description paper to the TSAR 2025 Workshop. All papers will undergo peer review and accepted papers will appear in the workshop proceedings.

### Organizers

- Fernando Alva-Manchego (Cardiff University, UK)  
- Regina Stodden (University of Bielefeld, Germany)  
- Kai North (Cambium Assessment, USA)  
- Joseph Marvin Imperial (National University Philippines and University of Bath, UK)  
- Abdullah Barayan (Cardiff University, UK)  
- Harish Tayyar Madabushi (University of Bath, UK)

### Contact

For questions, please contact us at: tsarworkshop@googlegroups.com adding **[Shared Task]** to the email subject.

### Useful Resources

- [UniversalCEFR: Enabling Open Multilingual Research on Language Proficiency Assessment](https://universalcefr.github.io/) (Imperial et al., 2025)
- [Analysing Zero-Shot Readability-Controlled Sentence Simplification](https://aclanthology.org/2025.coling-main.452/) (Barayan et al., COLING 2025)
- [Is It Possible to Modify Text to a Target Readability Level? An Initial Investigation Using Zero-Shot Large Language Models](https://aclanthology.org/2024.lrec-main.815/) (Farajidizaji et al., LREC-COLING 2024)
- [Controlling Pre-trained Language Models for Grade-Specific Text Simplification](https://aclanthology.org/2023.emnlp-main.790/) (Agrawal & Carpuat, EMNLP 2023)
- [Flesch or Fumble? Evaluating Readability Standard Alignment of Instruction-Tuned Language Models](https://aclanthology.org/2023.gem-1.18/) (Imperial & Tayyar Madabushi, GEM 2023)
- [Learning to Paraphrase Sentences to Different Complexity Levels](https://aclanthology.org/2023.tacl-1.76/) (Chi et al., TACL 2023)
