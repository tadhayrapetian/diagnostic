# diagnostic

**English Diagnostic** — single-page tool for running a first-lesson English diagnostic
(learner profile, question log, grammar, vocabulary, speaking, pronunciation, writing,
errors, summary) and exporting the results as a PDF report.

Open `index.html` in a browser. Data is saved automatically: to the user's account when
running as a claude.ai artifact (`db` capability), otherwise to the browser's localStorage.
PDF export uses jsPDF + jspdf-autotable (loaded from cdnjs) with embedded fonts that
cover Latin, Cyrillic and Armenian.
