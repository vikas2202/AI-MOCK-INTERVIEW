
# AI Mock Interviewer (Python + Streamlit)

This web app analyzes a candidate's resume and conducts a mock interview with **10–15 questions**, progressing from **beginner to advanced** and tailored to the skills found in the resume.

## Features
- Upload resume (PDF/DOCX/TXT)
- Resume analysis to detect skills and estimate seniority
- Auto-generated questions from beginner → advanced
- Interactive, question-by-question interface
- Optional lightweight, keyword-based feedback
- Summary view of all Q&A

## Quick Start

1. Create and activate a virtual environment (recommended).
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```
4. Open the local URL shown in the terminal.

## Notes
- If text extraction fails (scanned PDFs), convert your resume to text or DOCX.
- The feedback is **not** a full AI evaluation—it's a gentle keyword checker for practice.
- Extend `SKILL_KEYWORDS` and `QUESTION_BANK` in `app.py` to tailor for your domain.


API KEY         


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