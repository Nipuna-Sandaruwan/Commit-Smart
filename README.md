Commit-Smart
A simple and effective guide to writing semantic commit messages ✍️ for better Git history and collaboration. Improve your workflow with clear and structured commit messages!

Using semantic commit messages keeps your Git history clear and structured. It helps you and your team understand changes at a glance and makes collaboration easier.

Format
Copy
1
2
3
4
5
<type>(<scope>): <short description>

[optional body]

[optional footer(s)]
Example:
feat(auth): add JWT authentication
fix(ui): resolve button alignment issue
docs(readme): update installation instructions
Commit Types
feat
Introduces a new feature.
fix
Fixes a bug.
docs
Documentation updates (e.g., README, comments).
style
Code style changes (formatting, missing semicolons, etc.).
refactor
Code restructuring without changing behavior.
perf
Performance improvements.
test
Adds or modifies tests.
chore
Maintenance tasks (e.g., build process, dependencies).
ci
Changes to continuous integration configuration (e.g., GitHub Actions).
build
Changes related to the build system or external dependencies.
revert
Reverts a previous commit.
wip
Marks work-in-progress commits.
merge
Explicitly marks a merge commit.
release
Marks a new version release.
config
Changes to configuration files (e.g.,
.eslintrc
,
.prettierrc
).
security
Addresses security vulnerabilities or implements security improvements.
i18n
Internationalization (i18n) or localization (l10n) updates.

Examples
Adding a Feature:
feat(search): add vehicle model search functionality
Fixing a Bug:
fix(backend): correct database query for vehicle prices
Refactoring Code:
refactor(api): optimize database connection handling
Updating Documentation:
docs(README): update setup instructions for Next.js frontend
Performance Improvements:
perf(images): implement lazy loading for faster page load
Work in Progress:
wip(auth): partially implement user login flow
Reverting a Commit:
revert: undo commit abc123 due to regression
Best Practices
✅ Use the imperative mood (e.g., "add" instead of "added").
✅ Keep your messages concise but informative .
✅ Include a body if additional explanation is needed.
✅ Use the scope (in parentheses) to specify the affected part of the project.

By following semantic commit messages, you’ll maintain a clean and understandable Git history, making collaboration and project management much smoother. 🚀

Troubleshooting Tip
If you ever face this error after pushing to master or any other branch which is not main:

"There isn’t anything to compare. main and master are entirely different commit histories." 
