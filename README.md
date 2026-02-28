## Terms of Service & Privacy Notice

DySec is a research-oriented tool. This document explains how submissions are handled and how machine learning (ML) results should be interpreted.

---

### ⚠️ Analysis Scope & Limitations

DySec analyzes **only packages with existing install-time and post-installation traces** available in the dataset.

Real-time analysis of newly submitted packages is **not supported** in this version.

- The ML model relies on pre-captured dynamic behavioral traces  
- Newly uploaded packages are **not dynamically executed on-demand**

---

### 🛡️ Privacy Principles

DySec is designed for academic research and security analysis. We aim to minimize data collection and avoid unnecessary storage of uploaded artifacts.

- We **do not sell** uploaded files or data  
- We **do not intentionally collect** personal information  
- Users are strongly advised **not to submit sensitive or personal data**

Submissions are processed strictly for analysis purposes.

---

### 🔒 Data Handling & Usage

DySec primarily relies on **pre-collected dynamic traces** (e.g., install-time and post-installation behaviors).

The platform supports research evaluation and demonstration. It is **not intended as a real-time malware detection service**.

- ML inference uses **derived behavioral features**  
- Temporary processing data may be cached for performance  
- Long-term retention is avoided unless required for research reproducibility

---

### 🧠 Machine Learning Model Accuracy

Accuracy values displayed in DySec reflect **controlled experimental evaluations**.

They **do not guarantee** real-world detection performance.

---

### ⚠️ Important Notice

Machine learning predictions are **probabilistic**.

False positives and false negatives may occur due to:

- Feature set variations  
- Trace quality differences  
- Behavioral diversity

---

### ✅ Responsible Interpretation

DySec outputs should be treated as **supporting analytical evidence**, not a final security verdict.

For operational or security-critical decisions, results should be combined with:

- Static analysis  
- Dependency inspection  
- Sandboxing  
- Expert review

---

**DySec is intended for research, educational, and experimental purposes only.**
