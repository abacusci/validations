# AbacusCI – Validations Repository

This repository stores public validations related to students' progress, certifications, objectives, and achievements within Abacus Computing Institute.

All validations are recorded as GitHub Issues using standardized formats, labels, and structures. Each issue represents a unique event in a student's learning path.

---

## 📂 Structure

- Each issue represents one validation event
- Issues are labeled by type (e.g., `certificate`, `objective`)
- Issues are assigned to students (GitHub username) if available
- The title and body follow defined templates

---

## 🏷️ Labels

Standard labels include:

- `certificate` – Formal certification after completing a module
- `enrollment` – Learning milestone or practical achievement
- `objective` – Learning milestone or practical achievement

---

## 🧪 Example Queries

- All validations by student:
  `https://github.com/abacusci/validations/issues?q=assignee:studentusername`

- All certificates:
  `label:certificate`

- All objectives completed in a project:
  `label:objective project:abacusci/4`

---

## 🛠️ Templates

Templates for issue creation are provided in the `.github/ISSUE_TEMPLATE` directory (to be added).

---

## 🔐 Privacy

All validations are public. If a student does not have a GitHub account, validations can still be created without assignment, using name and student ID.

---

## 🌐 Integration

This repository is referenced from the AbacusCI portal. Each student profile or enrollment may link to corresponding validation entries here.

---

## ✅ Maintainer

This repository is maintained by Divengine Software Solutions as part of the AbacusCI infrastructure.
