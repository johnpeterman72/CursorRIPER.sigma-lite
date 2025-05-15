# CursorRIPER♦Σ Lite

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/version-1.0.0-green)

> A streamlined, ultra-efficient AI prompt framework for software development assistance. Lite version without context references, permissions, or code protection.

## 📚 Overview

CursorRIPER♦Σ Lite is a simplified version of the [CursorRIPER♦Σ framework](https://github.com/johnpeterman72/CursorRIPER.sigma) that maintains the core RIPER workflow while removing several advanced features for simplicity and efficiency.

The lite version excludes:
- Context reference system (@files functionality)
- CRUD permission enforcement
- Code protection system

This results in a more lightweight framework that's easier to use while still providing structured guidance for AI-assisted development.

## 🌟 Key Features

- **Symbolic Notation**: Uses Greek letters (Ω, Π, Σ, Δ), subscripts, and emoji for extreme conciseness
- **RIPER Workflow Modes**: Research, Innovate, Plan, Execute, Review (🔍R, 💡I, 📝P, ⚙️E, 🔎RV)
- **Structured Memory System**: Standardized file templates
- **Phase-based Project Management**: Tracks project progress from initialization to maintenance
- **Automatic Memory**: Creates and maintains a structured memory bank for project context

## 🧠 Framework Structure

### Modes (Ω)

```
Ω₁ = 🔍R ⟶ Research: Gather information and document findings
Ω₂ = 💡I ⟶ Innovate: Explore options and suggest ideas
Ω₃ = 📝P ⟶ Plan: Create specifications and sequence steps
Ω₄ = ⚙️E ⟶ Execute: Implement code according to plan
Ω₅ = 🔎RV ⟶ Review: Validate output against requirements
```

### Phases (Π)

```
Π₁ = 🌱UNINITIATED ⟶ Framework installed but not started
Π₂ = 🚧INITIALIZING ⟶ Setup in progress
Π₃ = 🏗️DEVELOPMENT ⟶ Main development work
Π₄ = 🔧MAINTENANCE ⟶ Long-term support
```

### Memory Files (σ)

```
σ₁ = 📋projectbrief.md ⟶ Requirements, scope, criteria
σ₂ = 🏛️systemPatterns.md ⟶ Architecture, components, decisions
σ₃ = 💻techContext.md ⟶ Stack, environment, dependencies
σ₄ = 🔮activeContext.md ⟶ Focus, changes, next steps
σ₅ = 📊progress.md ⟶ Status, milestones, issues
```

## 🚀 Getting Started

### Installation

1. Create a memory bank directory in your project:

```bash
mkdir -p /memory-bank/backups
```

2. Copy the CursorRIPER♦Σ Lite framework `.mdc` file to your project rules folder: `.cursor/rules/`

3. Initialize the framework with the AI assistant:

```
/start
```

### Usage

Change modes by using the following commands with your AI assistant:

```
/research (or /r) - Research mode
/innovate (or /i) - Innovate mode
/plan (or /p) - Plan mode
/execute (or /e) - Execute mode
/review (or /rev) - Review mode
```

## 📑 Memory System

The framework automatically maintains five key memory files:

1. **Project Brief** (σ₁): Defines requirements, success criteria, and scope
2. **System Patterns** (σ₂): Captures architecture, components, and design decisions
3. **Technical Context** (σ₃): Records technology stack, environment, and dependencies
4. **Active Context** (σ₄): Tracks current focus, recent changes, and next steps
5. **Progress Tracker** (σ₅): Monitors project status, features, issues, and milestones

## ⚠️ Safety Features

- Automatic backups before destructive operations
- Confirmation prompts for critical actions
- Phase transition verification
- Error recovery suggestions

## 🔣 Symbol Reference

See the [Symbol Reference Guide](./docs/symbol-reference-guide.md) for a complete list of symbols and notation used in the framework.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*CursorRIPER♦Σ Lite: Streamlined symbolic efficiency for AI-assisted development.*
