# Contributing Guide

First of all, thank you for considering contributing to this project! We welcome all kinds of contributions — whether it's a bug report, a suggestion, a fix, or a feature.

## 📦 How to Contribute

### 1. Fork the Repository

Click the **Fork** button at the top right of this page to create your own copy of the repo.

### 2. Clone Your Fork

```bash
git clone https://github.com/your-username/your-forked-repo.git
cd your-forked-repo
```

### 3. Create a Branch

Use a descriptive branch name:

```bash
git checkout -b fix/typo-in-readme
```

### 4. Make Your Changes

Please follow the existing code style. If you're unsure, check `.editorconfig` or existing files.

### 5. Commit Your Work

```bash
git add .
git commit -m "fix(docs): correct typo in README"
```

Use conventional commits if possible:
- `fix`: bug fixes
- `feat`: new features
- `docs`: documentation changes
- `refactor`: code refactoring
- `chore`: tooling, dependencies, cleanup

### 6. Push and Open a Pull Request

```bash
git push origin fix/typo-in-readme
```

Then go to the GitHub repo and open a Pull Request (PR) from your branch.

---

## ✅ Pull Request Checklist

Before opening a PR:

- [ ] The code builds and passes tests
- [ ] Linting and formatting have been applied
- [ ] The PR has a clear title and description
- [ ] Related issues are referenced (e.g. `Closes #123`)
- [ ] Documentation was updated (if needed)

---

## 🐛 Bug Reports & Feature Requests

If you're not submitting code, feel free to [open an issue](../issues/new/choose) using the appropriate template:
- Bug report: please include steps to reproduce, logs, and your environment.
- Feature request: describe the use case and what problem it solves.

---

## 🤝 Code of Conduct

Please read and follow our [Code of Conduct](./CODE_OF_CONDUCT.md) to keep this community respectful and inclusive.

---

Thanks again for helping make this project better! 🙌
