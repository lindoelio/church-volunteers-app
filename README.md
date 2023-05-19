# app_church_volunteers

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)


### iOS Config

Check if the file GoogleService-Info.plist (from Firebase project) exists into ...ios/Runner.

## Folder Structure

## Git Branching

We deliver continuosly combining Feature Branch Workflow and [Trunk Based Strategy](https://trunkbaseddevelopment.com)
for git branching.

### Branch Naming Convention
- main
- feature/*
- bugfix/*
- hotfix/*

### Commit Message Convention

We use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) for commit messages.

Examples:
```sh
git commit -m 'feat: add login button; add user message after login'
```

```sh
git commit -m 'refactor: rewrite logout button'
```

```sh
git commit -m 'chore: update README.md'
```

## CI/CD

### GitHub Actions