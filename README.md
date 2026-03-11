# GitQuest — Terminal Adventures 🚀

An interactive, VS Code–themed browser game that teaches Git through hands-on terminal missions. Type real Git commands, earn XP, level up, and unlock a completion certificate — all inside a single HTML file.

![HTML](https://img.shields.io/badge/Built%20With-HTML%2FCSS%2FJS-orange)
![Missions](https://img.shields.io/badge/Missions-22-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

- **VS Code look & feel** — Titlebar, activity bar, sidebar, tabs, integrated terminal, and status bar recreated in the browser.
- **22 guided missions** covering the full Git workflow:

  | # | Mission | Commands |
  |---|---------|----------|
  | 1 | Repo Banao | `git init` |
  | 2 | Status Check | `git status` |
  | 3 | Stage Karo | `git add` |
  | 4 | Commit Karo | `git commit` |
  | 5 | History Dekho | `git log` |
  | 6 | Diff Dekho | `git diff` |
  | 7 | Undo Karo | `git restore` |
  | 8 | File Ops | `git rm` / `git mv` |
  | 9 | Branching | `git checkout` / `git switch` |
  | 10 | Merge Karo | `git merge` |
  | 11 | Remote & Sync | `git remote` / `git push` / `git pull` |
  | 12 | Clone Karo | `git clone` |
  | 13 | Reset Karo | `git reset` |
  | 14 | Revert Karo | `git revert` |
  | 15 | Amend Karo | `git commit --amend` |
  | 16 | Stash Karo | `git stash` |
  | 17 | Cherry Pick | `git cherry-pick` |
  | 18 | Rebase Karo | `git rebase` |
  | 19 | Tag Karo | `git tag` |
  | 20 | Reflog | `git reflog` |
  | 21 | Bisect | `git bisect` |
  | 22 | Blame & Show | `git blame` / `git show` |

- **XP & leveling system** — Earn experience points for each completed mission and watch your level grow.
- **Hinglish flavor** — Explanations mix Hindi and English for a fun, conversational learning style.
- **Certificate of Completion** — Finish all missions to unlock a printable certificate ([gitquest-certificate.html](gitquest-certificate.html)).
- **Zero dependencies** — Pure HTML, CSS, and vanilla JavaScript. No build tools, no frameworks.

## Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/<your-username>/GitByBit.git
   cd GitByBit
   ```
2. **Open the game** — Double-click `gitquest.html` or serve it with any static server:
   ```bash
   npx serve .
   ```
3. **Play** — Follow the mission instructions in the editor pane and type Git commands in the terminal.

## Project Structure

```
GitByBit/
├── gitquest.html              # Main game (single-file app)
├── gitquest-certificate.html  # Printable completion certificate
└── README.md
```

## How It Works

- The sidebar lists all missions grouped by chapter. Completing a mission unlocks the next one.
- The editor pane displays lesson content, syntax examples, and tips for each mission.
- The integrated terminal accepts Git commands — the game engine validates them against the current mission's requirements.
- XP is awarded on completion; accumulate enough to level up and earn new titles.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for:
- New missions or Git topics
- UI improvements
- Bug fixes
- Translations

## License

This project is available under the [MIT License](LICENSE).
