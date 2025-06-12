# 📄 Applicant Tracking System (ATS)

The **Applicant Tracking System (ATS)** is an intelligent resume analysis tool that leverages natural language processing (NLP) and AI to evaluate resumes against job descriptions. It extracts key terms, highlights matching keywords, and identifies gaps, streamlining the hiring process for both candidates and recruiters.

---

## 🚀 Features

### 1. Soft Matching with Confidence Scores  
Utilizes **Large Language Models (LLMs)** to detect semantic similarity between resume and job description keywords. Each match includes a **confidence score** between 0.00 and 1.00 to help assess relevance.

> **Example:**  
> `"Visual Studio ↔ certifications"` → Confidence: **0.50** (likely ignored)  
> `"Product Roadmap Development ↔ product roadmap"` → Confidence: **0.88** (likely accepted)

---

### 2. Keyword Extraction  
- **Resumes:** Extracts and alphabetizes key resume terms.  
- **Job Descriptions:** Extracts and alphabetizes key job-related terms.  

---

### 3. Mechanical Matching  
Performs **exact, case-sensitive** keyword matching between resume and job description keywords for high-precision analysis.

---

### 4. Missing Keywords  
Highlights **keywords present in the job description** but **absent from the resume**, offering actionable insights for resume optimization.

---

## 🛠️ Future Enhancements

- Adjustable thresholds for soft match confidence levels  
- Support for additional document types (cover letters, pitch decks, etc.)  
- Paragraph-level evaluations for phrasing quality and alignment  
- Prioritized keyword weighting for impact analysis  
- Visual reports and charts for match/gap representation  

---

## 🗂️ Project Structure

