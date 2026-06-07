[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

# ⚖️ Sixth Amendment IAC Assessment Tool




An interactive, interview-style legal utility designed to conduct initial **Cronic–Strickland Ineffective Assistance of Counsel (IAC)** assessments. By guiding users through the constitutional continuum, this tool helps defense attorneys, legal clinics, and researchers evaluate potential Sixth Amendment violations.


## 🏛️ What is the Cronic–Strickland Continuum?

When assessing whether a criminal defendant received constitutionally inadequate legal representation, courts look at two major frameworks established by the U.S. Supreme Court on the exact same day in 1984:

1. **The *Cronic* Threshold (*United States v. Cronic*):** Evaluates structural or systemic errors (e.g., complete denial of counsel, severe funding limits, crushing caseloads) where a trial is so fundamentally flawed that constitutional prejudice is **presumed**.
2. **The *Strickland* Test (*Strickland v. Washington*):** If no structural defect exists, the tool shifts to an individualized two-prong inquiry: evaluating if counsel's performance fell below an **objective standard of reasonableness** (*deficiency*), and if there is a reasonable probability it affected the case outcome (*prejudice*).


## ✨ Features

* **Guided Legal Assessment:** Formulates interview-style questions mapped directly to Supreme Court precedents (*Gideon, Cronic, Strickland, Cuyler*, etc.).
* **Dynamic Logic Traversal:** Moves systematically through *Cronic threshold* questions, *Cronic systemic* defects, and *Strickland* prongs based on historical user input.
* **Local State Persistence:** Uses `localStorage` so assessors can pause, back up to previous questions, save case notes, and resume without losing data.
* **Print & PDF Export:** Custom CSS formatting prints beautifully or generates clean PDF case files (`window.print()`) for offline documentation and case files.
* **Zero Dependencies:** A single, lightweight HTML file containing semantic markup, clean typography, and vanilla JavaScript. No complex build tools required.


## 🚀 Getting Started

Because this is a completely static, vanilla web application, running it locally takes less than 10 seconds.

### Prerequisites

You only need a modern web browser (Chrome, Firefox, Safari, Edge). No local server, Node.js, or Python environment is required.

### How to Run Locally

1. **Clone the repository:**
```bash
git clone https://github.com/castle-bravo-project/IAC-Assessment-Tool.git
```


2. **Navigate into the directory:**
```bash
cd IAC-Assessment-Tool
```

3. **Launch the application:**
Simply double-click the `index.html` file to open it in your default web browser, or run:
```bash
# On macOS
open index.html
```
```
# On Linux
xdg-open index.html
```


## 📋 Assessment Workflow

1. **Case Metadata:** Optionally input the Assessor Name and Case Reference Number.
2. **Interview Interface:** Cycle through questions detailing compliant vs. non-compliant real-world legal scenarios.
3. **Case Notes:** Jot down case-specific facts directly below each constitutional question.
4. **Review Panel:** Verify answers before triggering the final verdict generation.
5. **Risk Summary & Export:** Review the generated exposure bars (Constitutional Risk) and print the comprehensive decision trail to a PDF.


## ⚖️ Legal Peer Review & Collaboration

This tool aims to accurately bridge the gap between systemic indigent defense data and actionable constitutional analysis. We are actively seeking **legal peer review, academic validation, and non-profit collaboration** to refine the question weights, logic gates, and legal citations.

### 🎯 Strategic Alignment: The Sixth Amendment Center (6AC)
We heavily respect and draw inspiration from the **[Sixth Amendment Center (6AC)](https://6ac.org/)**, the nation’s leading non-partisan, non-profit organization dedicated exclusively to uncovering and fixing the root causes of America's indigent defense crisis. 

Because 6AC focuses extensively on structural and constructive denials of counsel—the exact framework evaluated in our *Cronic* logic modules—we specifically welcome feedback from 6AC staff, researchers, and network members to ensure this utility aligns with rigorous national research standards.

*   **Public Defenders & Jurisdictions:** If you have local state court precedents or unique caseload limitations you'd like represented in the framework, please open an issue.
*   **Legal Academics:** Review our interpretation of the *Cronic/Strickland* continuum boundaries to ensure maximum pedagogical accuracy.


## 🤝 Contributing

Contributions to sharpen the legal examples, expand citations, or improve accessibility (a11y) are highly encouraged.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/RefineCitations`)
3. Commit your Changes (`git commit -m 'Add supporting state court citations'`)
4. Push to the Branch (`git push origin feature/RefineCitations`)
5. Open a Pull Request


## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📬 Contact & Affiliation

**Castle Bravo Project** - [GitHub Organization](https://github.com/castle-bravo-project)  
Project Repository: [https://github.com/castle-bravo-project/IAC-Assessment-Tool](https://github.com/castle-bravo-project/IAC-Assessment-Tool)

*Disclaimer: This tool is independent, open-source, and is not officially partnered with or endorsed by the Sixth Amendment Center (6AC). It is intended for educational, research, and initial assessment assistance for legal professionals and does not constitute formal legal advice.*
