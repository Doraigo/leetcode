# LeetCode Solutions in Go

This repository contains my solutions to [LeetCode](https://leetcode.com/) problems, written in **Go**.  
The goal is to improve my problem-solving skills while following good coding practices and keeping a clean, testable structure.

---

## 📂 Folder Structure
Each problem has its own folder, named using:

```<problem-number>-<problem-slug>```/

Inside each folder:
- `main.go` → A manual runner with sample inputs for quick testing.
- `solution_test.go` → Unit tests for verifying multiple cases.

Example:
```
0001-two-sum/
├── main.go
└── solution_test.go
```
---

## 🚀 How to Run Locally
Clone the repository:
```bash
git clone https://github.com/Doraigo/leetcode.git
cd leetcode
```

Run a specific problem manually:
```bash
cd 0001-two-sum
go run .
```

Run tests for a specific problem:
```bash
cd 0001-two-sum
go test
```

Run all tests in the repo:
```bash
go test ./...
```

---

## 📜 Naming Conventions
Problem numbers are zero-padded to 4 digits (0001, 0015, 0100, etc.).

Folder names follow:
```bash
<problem-number>-<problem-title-in-kebab-case>
```
Commit messages use:
```bash
Add solution for <problem-number> <problem-title>
```

Example:
```bash
git commit -m "Add solution for 0003 Longest Substring Without Repeating Characters"
```

---

## 🎯 Goals
- Practice solving problems without relying on autocomplete.

- Write unit tests for each solution.

- Keep solutions simple, readable, and idiomatic in Go.

- Track progress publicly for accountability.