# Precourse Materials Schedule

## Git Workflow Instructions

To complete these materials, you'll practice using Git by following these steps:

1. Create a personal branch:
   ```bash
   git checkout -b your-name/precourse
   ```

2. For each section:
   - Create a new branch from your personal branch
   - Complete the exercises and documentation
   - Commit your changes with clear messages
   - Push to your personal branch
   - Create a pull request against the main branch

3. Example workflow for a section:
   ```bash
   git checkout your-name/precourse
   git checkout -b your-name/terminal-basics
   # Complete the terminal section
   git add .
   git commit -m "Complete terminal basics section"
   git push origin your-name/terminal-basics
   # Create PR on GitHub
   git checkout your-name/precourse
   ```

4. Keep your personal branch up to date:
   ```bash
   git checkout your-name/precourse
   git pull origin main
   ```

This approach helps you practice Git workflows while maintaining a clean history of your progress.

---

This table provides a recommended sequence for working through the precourse study materials, with links to each section and brief descriptions.

| Section | Topic | Description |
|---------|-------|-------------|
| **Getting Started** |
| 1 | [Terminal Basics](terminal/README.md) | Learn essential terminal commands and navigation |
| 2 | [Git Fundamentals](git/README.md) | Master version control with Git |
| **Basics** |
| 1 | [Computer Science Basics](computer-science/basics/README.md) | Core computing concepts and fundamentals |
| 2 | [Programming Languages](computer-science/languages/README.md) | Overview of different programming languages |
| 3 | [General Concepts](computer-science/general-concepts/README.md) | Key programming and computing concepts |
| 4 | [TypeScript](computer-science/typescript/README.md) | TypeScript fundamentals and best practices |
| **Frontend** |
| 1 | [Browser Fundamentals](frontend/browser/README.md) | Understanding how browsers work |
| 2 | [CSS & Styling](frontend/css/README.md) | Modern CSS techniques and best practices |
| 3 | [React](frontend/react/README.md) | React fundamentals and advanced concepts |
| 4 | [State Management](frontend/state-management/README.md) | Managing application state effectively |
| **Backend** |
| 1 | [Backend Overview](backend/OVERVIEW.md) | Introduction to backend development |
| 2 | [Database Concepts](backend/database/README.md) | Database design and management |
| 3 | [Controllers](backend/controller/README.md) | Understanding backend controllers |
| 4 | [Services](backend/service/README.md) | Building backend services |
| **Advanced Computer Science** |
| 1 | [Light Computing](computer-science/light-computing/README.md) | Advanced computing concepts |
| 2 | [Light CS](computer-science/light-cs/README.md) | Additional computer science topics |
| 3 | [Light Networking](computer-science/light-networking/README.md) | Networking fundamentals and concepts |


