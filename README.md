# CRCI-Experiment-Dataset

This repository contains the experimental dataset and results from our academic study on the **Challenge-Responsive Code Instruction (CRCI)** method for code review effectiveness assessment.
The dataset is directly associated with the experiments described in our paper.

## 🧪 Experimental Context

This dataset was generated from an experimental study involving:
- **9 participants**: 3 undergraduate students, 3 graduate students, and 3 industry professionals  
- **85 code snippets**: drawn from both academic and industrial projects, across Java, C++, C#, and JavaScript  
- **303 injected errors**: balanced distribution of syntax, semantic, and logic errors  
- Reviews conducted under **controlled conditions** (IDE syntax checking disabled, no compilation allowed)  
- Supplementary experiment using **state-of-the-art LLM** for automated review

Full methodology and analysis are described in the associated paper.

## 🛠 CRCI Supporting Tool

The **CRCI Supporting Tool** is a prototype system developed based on the **Challenged Responsive Code Inspection (CRCI)** method proposed in our paper.  
In this system, the software itself takes on the role of the *Challenger*, guiding the reviewer through a structured, question-driven self-review process. The tool is designed to simulate the questioning strategy described in our methodology, prompting developers to reflect on their code’s structure, logic, and adherence to requirements.

**Key Features:**
- Automated challenger role to support structured self-review.
- Step-by-step guided questioning aligned with our CRCI checklist.
- Logging and exporting of detected issues for further quantitative analysis.


## 📜 License
This dataset is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).

You are free to:
- Share — copy and redistribute the material in any medium or format.

Under the following terms:
- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.
- **NoDerivatives** — If you remix, transform, or build upon the material, you may not distribute the modified material.

Full license text is available in the LICENSE file.
