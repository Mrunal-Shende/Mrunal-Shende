from pathlib import Path

path = Path("/mnt/data/README.md")
text = path.read_text(encoding="utf-8")

old = """**Current Role:** Working with React.js, Node.js, Express.js, and Supabase on client-facing applications across travel, logistics, real estate, and financial domains.

**AI & ML Internship:** Completed a 10-week virtual internship focused on AI/ML concepts and practical AI-based solutions."""

new = """**Current Role:**
- Developing and maintaining full-stack client-facing applications using **React.js, Node.js, Express.js, and Supabase**.
- Contributing to projects across **travel, logistics, real estate, and financial domains**.
- Building frontend interfaces, backend REST APIs, authentication flows, dashboards, and database integrations.
- Working with Git-based development workflows and supporting application deployment and production updates.

**AI & ML Internship:**
- Completed a **10-week virtual internship** focused on Artificial Intelligence and Machine Learning.
- Worked with practical AI/ML concepts and explored how AI capabilities can be integrated into software applications.
- Gained hands-on exposure to AI-based workflows, problem-solving, and technology-driven solutions."""

if old not in text:
    raise ValueError("Target experience section not found")

path.write_text(text.replace(old, new), encoding="utf-8")
print("Updated:", path)
