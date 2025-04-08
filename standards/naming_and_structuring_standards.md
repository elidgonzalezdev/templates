# 🛡️ Naming and Structuring Standards (v1.0)

> **"Order is the foundation upon which empires endure."**

This document defines the official naming, structuring, and operational standards across all code, repos, labs, notes, and artifacts.

---

## 1. Repository Naming (GitHub, GitLab, etc.)

- Use `kebab-case` (all lowercase, hyphens between words).
- Keep names tactical, clear, purpose-driven.

**Examples:**
- `private-infrastructure-consulting`
- `labs-automation`
- `learning-journal`
- `templates-repo`

---

## 2. Folder/Directory Naming

- Use `kebab-case`.
- Reflect modular functional structure inside repos.
- Never use spaces.

**Examples:**
- `ansible-playbooks/`
- `bash-scripts/`
- `lab-reports/`
- `case-studies/`

---

## 3. File Naming

- Use `snake_case`.
- Reflect purpose clearly.
- Match file extension appropriately.

**Examples:**
- `deploy_server.sh`
- `automated_backup.py`
- `nextcloud_setup.md`
- `learning_note_wireguard.md`

---

## 4. Code Naming Standards

| Element              | Standard               |
|----------------------|-------------------------|
| Variables             | `snake_case` (Python, Rust, C) |
| Constants             | `UPPER_SNAKE_CASE` |
| Functions/Methods     | `snake_case` |
| Classes/Structs       | `PascalCase` |
| Bash Variables        | `UPPER_SNAKE_CASE` |
| Bash Functions        | `snake_case` (lowercase preferred) |

✅ **No Hungarian Notation.**  
✅ **No meaningless names (`foo`, `bar`, `temp123`).**  
✅ **Semantic clarity above all.**

---

## 5. Branch Naming Standards (Git)

- Use `type/short-description`.
- All lowercase, hyphens for spaces.

**Branch Types:**
- `feature/` → New functionality
- `bugfix/` → Fixes to existing functionality
- `chore/` → Maintenance tasks (non-functional)
- `doc/` → Documentation updates
- `refactor/` → Code improvements without functional change

**Examples:**
- `feature/add-private-vpn-automation`
- `bugfix/resolve-nextcloud-ssl-issue`
- `chore/update-bash-scripts`
- `doc/improve-readme`

---

## 6. Commit Message Standards

- Format: `type(scope): short message`
- Keep message under ~72 characters when possible.

**Commit Types:**
- `feat` → New feature
- `fix` → Bug fix
- `docs` → Documentation only changes
- `style` → Code style changes (formatting, missing semi-colons, etc.)
- `refactor` → Code refactoring
- `test` → Adding missing tests
- `chore` → Maintenance

**Examples:**
- `feat(deploy): add WireGuard multi-node mesh setup`
- `fix(backup): patch SSH key permission error`
- `docs(readme): update services list for consulting`
- `chore(lab): archive finished SIEM project`

---

## 7. Documentation Requirements

- Every repo must have a `README.md` at root.
- Optional `/docs/` folder for complex repositories.
- Templates from `/templates-repo/` must be used when applicable.

---

## 8. Licensing Standards

- Default license: **MIT License** for public-facing code unless otherwise specified.
- Private client work: Licensing customized per contract.

---

## 9. Tagging and Versioning (if applicable)

- Use Semantic Versioning: `vX.Y.Z`
  - `X` → Major breaking changes
  - `Y` → Feature additions, backward compatible
  - `Z` → Bug fixes and patches

**Examples:**
- `v1.0.0`
- `v1.1.0`
- `v1.1.1`

---

✅ **Deviation from these standards requires explicit strategic justification.**  
✅ **Otherwise, discipline wins. Always.**

🛡️ Version 1.0 — Code of Standards
