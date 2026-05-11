# 📘 Mini Contribution Guide

### Project Contribution Rules & Workflow

Welcome to the project! 🚀
Please follow these rules carefully to keep the code clean and stable.

---

# 🔒 Important Rule

🚫 **Do NOT push directly to the `master` branch.**
All changes must go through a Pull Request.

The `master` branch is protected and only the main maintainer can merge changes.

---

# 🛠 Contribution Workflow (Step-by-Step)

## 1️⃣ Clone the Repository

```bash
git clone <repository-url>
```

---

## 2️⃣ Create a New Branch

Always create a new branch before starting work.

```bash
git checkout -b feature-branch-name
```

Example:

```bash
git checkout -b feature-login
```

Branch naming examples:

* `feature-navbar`
* `bugfix-header`
* `update-footer`
* `refactor-auth`

---

## 3️⃣ Make Your Changes

* Write clean and readable code
* Follow project structure
* Test your code before pushing

---

## 4️⃣ Commit Properly

Write meaningful commit messages.

```bash
git add .
git commit -m "Add login form validation"
```

✅ Good:

```
Fix navbar alignment issue
Add responsive design for homepage
```

❌ Bad:

```
update
changes
fix
```

---

## 5️⃣ Push Your Branch

```bash
git push origin feature-branch-name
```

---

## 6️⃣ Create a Pull Request (PR)

After pushing:

1. Go to GitHub
2. Click "Compare & pull request"
3. Add a clear description
4. Submit PR

---

# 🔍 Pull Request Rules

Before your PR can be merged:

* It must be reviewed
* It must be approved
* All discussions must be resolved
* Code should not break existing features

Only the project maintainer will merge into `master`.

---

# 🧼 Code Standards

✔ Use proper indentation
✔ Keep code clean and readable
✔ Remove unused code
✔ Use meaningful variable names
✔ Comment complex logic

---

# 🚫 What NOT To Do

* ❌ Do not push directly to `master`
* ❌ Do not merge your own PR
* ❌ Do not force push
* ❌ Do not upload unnecessary files
* ❌ Do not change unrelated files

---

# 💬 Communication

If you are:

* Confused about a task
* Facing merge conflicts
* Unsure about implementation

👉 Ask before making major changes.

---

# 🌳 Branch Structure Example

```
master (protected)
│
├── feature-login
├── feature-navbar
├── bugfix-footer
```

---

# 🎯 Goal

Keep the project:

* Stable
* Clean
* Professional
* Easy to maintain

---
