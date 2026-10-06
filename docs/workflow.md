# Git Workflow Documentation

## Project Objective

This project demonstrates Git and GitHub best practices for managing a DevOps project.

## Branching Strategy

The project uses three types of branches:

- `main` - Production-ready code
- `dev` - Development and integration
- `feature/*` - Individual feature development

## Workflow

```text
feature branch
      ↓
     dev
      ↓
 Pull Request
      ↓
    main
      ↓
   Git Tag