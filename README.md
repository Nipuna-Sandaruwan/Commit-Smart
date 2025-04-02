

---

# Commit-Smart ✍️  
A simple and effective guide to writing **semantic commit messages** for better Git history and collaboration. Improve your workflow with **clear and structured commit messages**!  

Using semantic commit messages keeps your Git history **clear and structured**. It helps you and your team understand changes at a glance and makes collaboration easier.  

## ✅ Format  

```bash
<type>(<scope>): <short description>

[optional body]

[optional footer(s)]
```

### Example:  

```bash
feat(auth): add JWT authentication  
fix(ui): resolve button alignment issue  
docs(readme): update installation instructions  
```

---

## 🚀 Commit Types  

| Type      | Description                                               |
|-----------|-----------------------------------------------------------|
| `feat`    | Introduces a new feature.                                 |
| `fix`     | Fixes a bug.                                              |
| `docs`    | Documentation updates (e.g., README, comments).           |
| `style`   | Code style changes (formatting, missing semicolons, etc.).|
| `refactor`| Code restructuring without changing behavior.             |
| `perf`    | Performance improvements.                                 |
| `test`    | Adds or modifies tests.                                   |
| `chore`   | Maintenance tasks (e.g., build process, dependencies).    |
| `ci`      | Changes to continuous integration (e.g., GitHub Actions). |
| `build`   | Changes related to build system or external dependencies. |
| `revert`  | Reverts a previous commit.                                |
| `wip`     | Marks work-in-progress commits.                           |
| `merge`   | Explicitly marks a merge commit.                          |
| `release` | Marks a new version release.                              |
| `config`  | Changes to configuration files (e.g., `.eslintrc`, `.prettierrc`). |
| `security`| Addresses security vulnerabilities or improvements.       |
| `i18n`    | Internationalization (i18n) or localization (l10n) updates.|

---

## 💡 Examples  

- **Adding a Feature:**  
  ```bash
  feat(search): add vehicle model search functionality
  ```  

- **Fixing a Bug:**  
  ```bash
  fix(backend): correct database query for vehicle prices
  ```  

- **Refactoring Code:**  
  ```bash
  refactor(api): optimize database connection handling
  ```  

- **Updating Documentation:**  
  ```bash
  docs(README): update setup instructions for Next.js frontend
  ```  

- **Performance Improvements:**  
  ```bash
  perf(images): implement lazy loading for faster page load
  ```  

- **Work in Progress:**  
  ```bash
  wip(auth): partially implement user login flow
  ```  

- **Reverting a Commit:**  
  ```bash
  revert: undo commit abc123 due to regression
  ```  

---

## 🌟 Best Practices  

✅ **Use the imperative mood** (e.g., "add" instead of "added").  
✅ **Keep messages concise but informative**.  
✅ **Include a body** if additional explanation is needed.  
✅ **Use the scope (in parentheses)** to specify the affected part of the project..  

---

By following semantic commit messages, you’ll maintain a **clean and understandable Git history**, making collaboration and project management much smoother. 🚀  

---

