# yolio-git-practice

Practice repository for the free **Git & GitHub** course by [Yolio Career](https://github.com/yoliocompany).

This repo is public on purpose. Use it to practice `fork`, `clone`, branches, commits, `push`, and pull requests.

## How to practice

1. **Fork** this repo (the Fork button at the top right of this page).
2. **Clone** your fork to your computer:
   ```
   git clone https://github.com/<your-username>/yolio-git-practice.git
   ```
3. Create a branch:
   ```
   git switch -c add-<your-username>
   ```
4. Copy `contributors/example.md` to `contributors/<your-username>.md` and edit it.
5. Save your work:
   ```
   git add contributors/<your-username>.md
   git commit -m "Add <your-username> to contributors"
   git push -u origin add-<your-username>
   ```
6. Open a **pull request** from your fork to this repo.

## Folders

| Folder | What it is for |
|---|---|
| `contributors/` | Your pull request adds one file here, named after your GitHub username |
| `practice/` | `notes.md` is used for the fork-sync exercise (course lesson 6.7) |

## Rules

- Add only **one file** named after your own GitHub username.
- Do not write personal data: no email, no phone number, no home address.
- Pull requests here are for practice. They may not be merged, and that is fine.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the short guide.
