# 📁 Projects Folder

> This folder contains **project-specific instances** of the Sonnet 4.5 Governance Kit.

---

## Purpose

Each subfolder represents a real project that applies the governance framework defined in the root of this repository.
Project folders contain their own customized versions of roles, templates, documents, and prompts — tailored to the
specific context, stakeholders, and scope of that project.

---

## Structure

```
projects/
├── README.md              ← You are here
└── <project-folder>/
    ├── README.md
    ├── roles/
    │   └── <role>/SKILL.md
    ├── templates/
    │   ├── whatsapp/
    │   └── trello/
    └── docs/
        └── governance-reference.md
```

Each project folder mirrors the root kit structure but contains **project-specific governance content**.

---

## Privacy

Project folders prefixed with `.` (dot) are **private by default** and excluded from version control via `.gitignore`:

```gitignore
/projects/.*
```

To make a project folder tracked by Git, use a name **without** the leading dot (e.g., `projects/my-project/`).

---

## How to Create a New Project

1. Create a new folder under `projects/` (use a `.` prefix for private projects)
2. Copy the root-level structure (`roles/`, `templates/`, `docs/`) into your project folder
3. Customize each `SKILL.md`, template, and reference document for your project's context
4. Add a `README.md` to your project folder describing scope, phases, and stakeholders

---

## Existing Projects

| Project                  | Folder |
|--------------------------|--------|
| *No public projects yet* | —      |

> Only **public** (non-dot-prefixed) projects are listed here. Private projects (dot-prefixed) are excluded from version
> control and not listed.

---

*Part of the [Sonnet 4.5 — AI-Assisted Project Governance Kit](../README.md)*
