# Codex

**Codex** is the central workspace for Patricia Liden’s digital projects powered by OpenAI technologies.

This repository brings together exploratory scripts, automation tools, documentation assets, and AI-driven solutions used across various initiatives, including:

- 🚀 AI integration in project management
- 🧠 Knowledge product development (eBooks, templates, tutorials)
- 🛠️ Application modernization frameworks
- 💡 Experiments and POCs involving OpenAI Codex, Python, and Java

## 📁 Structure (coming soon)

/scripts # Python, Java, or AI utilities
  - `build_project_status_db.py` creates a SQLite database from PPTX status reports

/docs # Project documentation or internal guides

/templates # Project or content templates for reuse

/experiments # AI prototypes, models, and test files

## ⚖️ License

This repository is licensed under the [MIT License](LICENSE).
Feel free to use, fork, and contribute with credit.

## Building a Project Status Database

`scripts/build_project_status_db.py` scans a directory of `.pptx` files and
stores slide text in a SQLite database. You can also export the data as CSV.

Usage:

```bash
python scripts/build_project_status_db.py --pptx_dir path/to/pptx_files \
    --db project_status.db --csv project_status.csv
```

---

### About

Created and maintained by [Patricia Liden](https://www.linkedin.com/in/patliden),  
Project, Portfolio, PMO Expert | AI Explorer | Digital Creator @PMInsight
