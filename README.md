# Lab 10 · Refactor to functions

**Week 10 · Functions**  
**Theme:** Name the process  
**Type:** Lesson week


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

**Your demo:** _add your link here_


## Scenario
A function is a named block you call from main. Take last week’s sweep (or a small score list) and split compute from print.

## Goals
- One helper that **returns** a number (`average`, or similar)
- One helper that **prints** (`printSummary`, or similar)
- `main` declares data, calls, returns — a table of contents
- Push + short demo + Canvas

## Starter
Use `main.cpp`. Put your name in the file-top comment. Prototypes are sketched.

## Environment
VS 2022 · **GitHub Codespaces** · Replit · library machines

## Procedure
1. Keep a small array in `main`
2. Write `average` so it returns a `double`
3. Write `printSummary` so it only talks
4. Call them from `main`. Don’t leave the math in `main`
5. Commit, push, short demo, Canvas

## Sample output
```
Average: 85.2
```

## Definition of done
- Two helpers besides `main`
- At least one `return` value
- `main` is thin
- Repo + short demo + Canvas

## Rubric (100)
| Criterion | Pts |
|-----------|----:|
| Runs correctly on a supported path | 40 |
| Meets prompt requirements | 30 |
| Helpers have one job each | 15 |
| GitHub + short demo video | 15 |

## Scope fence
No classes. No globals. Guard a zero `n` if you can.

## Tips
- Define above `main`, or declare a prototype and define below — pick one style
- A function that prints *and* computes is two jobs
- `const int a[]` means read the row; don’t rewrite it

## Help (`/ring`)
After a real try, include: goal · what you tried · exact error · screenshot/repo · OS + tool.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, and a real run.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
