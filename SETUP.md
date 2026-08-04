# Setup & Workflow Guide

## Initial Setup (Do this once)

```bash
# Navigate to your repo
cd Circular_Tectonic

# Stage all new folders and files
git add .

# Commit the repository structure
git commit -m "docs: initialize research repository structure with weekly tasks, project info, resources, material research, and precedent research folders"

# Push to GitHub
git push origin main
```

---

## Weekly Workflow

Each week, follow this pattern:

### 1. Planning (Monday)
- Update `01_Weekly_Tasks/README.md` with weekly objectives
- Review previous week's progress notes

### 2. Documentation (Throughout week)
- Add sketches → `04_Pictures/Sketches/`
- Add renders → `04_Pictures/Renders/`
- Add material test results → `05_Material_Research/`
- Add photos/photography → `04_Pictures/Photography/`

### 3. Synthesis (Friday)
- Update relevant README files
- Add preliminary findings
- Document blockers and next steps

### 4. Commit & Push (End of week)
```bash
git add .
git commit -m "docs: week [N] progress - [brief summary]"
git push origin main
```

---

## File Naming Convention

To keep things organized:

- **Images:** `YYYY-MM-DD_description.jpg` (e.g., `2026-10-26_gfrc-sample-001.jpg`)
- **Sketches:** `SKETCH_[date]_[concept].jpg`
- **Renders:** `RENDER_[iteration]_[name].jpg`
- **Documents:** `[Folder]_[Date]_[Description].md`
- **Tests:** `TEST_[Material]_[Date]_Results.md`

---

## Tips for Effective Documentation

✅ **Do:**
- Take photos with consistent lighting/scale
- Write clear method descriptions for tests
- Link related files and folders
- Update README files regularly
- Commit often with descriptive messages

❌ **Don't:**
- Leave large Rhino files (.3dm) — use .gitignore (already set up)
- Add render sequences — instead add 1-2 key frames
- Neglect notes/metadata — future you will need context
- Let the repo sit without updates

---

## Useful Git Commands

```bash
# Check status
git status

# Stage specific folder
git add 05_Material_Research/

# Commit with message
git commit -m "docs: GFRC testing week 1 results"

# Push
git push origin main

# View commit history
git log --oneline
```

---

## Folder Quick Reference

| Folder | Use For |
|--------|---------|
| `01_Weekly_Tasks/` | Track progress, milestones, deliverables |
| `02_Project_Info/` | Brief, scope, learning outcomes |
| `03_Resources/` | References, tools, code, CAD files |
| `04_Pictures/` | All visual documentation |
| `05_Material_Research/` | Tests, specs, fabrication learnings |
| `06_Precedent_Research/` | Case studies, analogues, practices |

---

*Happy researching! Update this guide as workflow evolves.*
