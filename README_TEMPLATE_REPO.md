# Python Package Template

> A comprehensive, production-ready template for creating Python packages with modern best practices, AI-assisted development, and automated CI/CD.

## 🎯 Purpose

This is a **template repository** designed to be used with `auto-package-framework` or as a standalone starting point for Python package development.

## ✨ Features

- **Complete Project Structure**: Pre-configured with best practices
- **CI/CD Ready**: GitHub Actions workflows for testing and releasing
- **AI-Assisted Development**: Includes `AI_CONTEXT.md` and `llms.txt` for AI assistants
- **Code Quality**: Pre-configured with ruff, mypy, pytest, and pre-commit
- **Documentation**: Comprehensive documentation templates
- **Release Automation**: Release-please for automated versioning and changelog

## 🚀 Quick Start

### Using with auto-package-framework

```bash
# Install auto-package-framework
pip install auto-package-framework

# Create a new package from this template
auto-package --project-name "my-package" --idea "My package description"
```

### Using as a Template

1. **Use this template** on GitHub (click "Use this template")
2. **Clone** your new repository
3. **Customize** the placeholders:
   - Replace `[Project Name]` with your project name
   - Replace `[package-name]` with your package name
   - Replace `[USERNAME]` with your GitHub username
   - Update `PROJECT_IDEA.md` with your project vision
   - Customize `AI_CONTEXT.md` with your technical standards

## 📁 What's Included

```
.
├── .github/              # GitHub workflows and templates
│   ├── workflows/       # CI/CD automation
│   └── ISSUE_TEMPLATE/  # Issue templates
├── src/                  # Source code directory
├── tests/                 # Test files
├── docs/                  # Documentation
├── AI_CONTEXT.md         # AI assistant guide
├── PROJECT_IDEA.md       # Project planning document
├── llms.txt.template      # LLM context template
├── pyproject.toml        # Project configuration
└── README.md             # This file
```

## 📚 Key Files

- **PROJECT_IDEA.md**: Project vision and requirements (start here!)
- **AI_CONTEXT.md**: Technical context for AI assistants
- **START_HERE.md**: Navigation guide for new contributors
- **QUICK_START.md**: Quick setup guide
- **llms.txt.template**: Template for AI context documentation

## 🔧 Development

### Setup

```bash
# Install dependencies
pip install -e ".[dev]"

# Install pre-commit hooks
pre-commit install
```

### Code Quality

```bash
# Format code
ruff format .

# Lint code
ruff check .

# Type check
mypy src/

# Run tests
pytest
```

## 📝 License

MIT License - feel free to use this template for your projects!

## 🔗 Related Projects

- **[auto-package-framework](https://github.com/flashpoint493/auto-package-framework)**: Automated Python package creation and publishing framework

## 🤝 Contributing

This is a template repository. If you have suggestions for improvements:

1. Use this template for your project
2. Make improvements
3. Share your enhancements with the community

---

**Note**: This is a template repository. When you use it, remember to:
- Replace all placeholders (`[Project Name]`, `[package-name]`, etc.)
- Update `PROJECT_IDEA.md` with your project vision
- Customize `AI_CONTEXT.md` for your needs
- Update badges and links in `README.md`

