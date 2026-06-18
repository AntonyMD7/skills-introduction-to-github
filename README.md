# GitHub Learning Path

Use this repository as a guided practice space to go from complete beginner to confident GitHub user.

## How to use this syllabus

1. Work through the phases in order.
2. Check off each lesson as you complete it.
3. Do the hands-on tasks directly in this repository whenever possible.
4. Repeat exercises until the workflow feels natural.

## Phase 1: Beginner

Goal: Learn the basic GitHub workflow and become comfortable making simple changes safely.

### Concepts and practice

#### Repositories and files
- [ ] Understand what a repository is, what the default branch does, and how files are organized.
- [ ] Practice: explore the root folder, `.github/steps`, and `.github/workflows`.
- [ ] Practice: explain in your own words what this repository is for.

#### Branches
- [ ] Understand why branches are used for isolated work.
- [ ] Practice: create a branch named `beginner/my-first-change`.
- [ ] Practice: switch between your branch and `main` in the GitHub UI.

#### Commits
- [ ] Understand that a commit is a saved snapshot of changes.
- [ ] Practice: edit this README or create a small notes file with one new sentence.
- [ ] Practice: commit with a message like `docs: add first GitHub notes`.

#### Pull requests
- [ ] Understand how a pull request proposes changes from one branch into another.
- [ ] Practice: open a pull request from `beginner/my-first-change` into `main`.
- [ ] Practice: write a short description that explains what changed and why.

#### Reviews and feedback
- [ ] Understand that review comments help improve changes before merging.
- [ ] Practice: leave yourself a checklist in the pull request description.
- [ ] Practice: respond to at least one comment or suggestion before merging.

#### Merging
- [ ] Understand what happens when a pull request is merged.
- [ ] Practice: merge your pull request after review is complete and, if checks are configured, after they pass.
- [ ] Practice: delete the branch after merging.

### Beginner mini-project
- [ ] Create a new branch.
- [ ] Add a short profile-style Markdown file such as `PROFILE.md` or `NOTES.md`.
- [ ] Commit the file with a clear message.
- [ ] Open and merge a pull request.

---

## Phase 2: Intermediate

Goal: Work more independently with Git, collaboration features, and repository maintenance.

### Concepts and practice

#### Branching strategy
- [ ] Understand feature branches, naming conventions, and keeping work focused.
- [ ] Practice: create branches like `feature/update-readme` and `fix/typo`.
- [ ] Practice: keep one topic per branch and one logical change per pull request.

#### Syncing with the main branch
- [ ] Understand why branches can fall behind `main`.
- [ ] Practice: fetch the latest changes and update your branch locally.
- [ ] Practice: compare your branch against `main` before opening a pull request.

#### Merge conflicts
- [ ] Understand why conflicts happen when two changes edit the same lines.
- [ ] Practice: create two branches that edit the same section of a file.
- [ ] Practice: merge one branch first, then resolve the conflict in the second branch.

#### Issues and project planning
- [ ] Understand how issues track bugs, ideas, and tasks.
- [ ] Practice: create an issue describing a small improvement for this repository.
- [ ] Practice: reference the issue in a pull request description.

#### Pull request quality
- [ ] Understand how small, well-described pull requests are easier to review.
- [ ] Practice: open a pull request with a summary, testing notes, and a checklist.
- [ ] Practice: review the file diff before requesting review.

#### Markdown and documentation
- [ ] Understand headings, lists, links, code blocks, tables, and checkboxes.
- [ ] Practice: improve this README with one extra tip, section, or example.
- [ ] Practice: add a checklist to track your own learning progress.

### Intermediate mini-project
- [ ] Open an issue for a README improvement.
- [ ] Create a feature branch linked to that issue.
- [ ] Make the change in one or two commits.
- [ ] Open a pull request that references the issue.
- [ ] Resolve any conflict or review feedback.

---

## Phase 3: Advanced

Goal: Become productive with automation, collaboration at scale, and advanced repository workflows.

### Concepts and practice

#### GitHub Actions
- [ ] Understand workflows, jobs, steps, triggers, and runners.
- [ ] Practice: inspect the files in `.github/workflows`.
- [ ] Practice: identify what event triggers each workflow in this repository.
- [ ] Practice: explain the difference between a successful run, a failed run, and a queued or in-progress run.

#### CI/CD basics
- [ ] Understand how continuous integration checks code automatically.
- [ ] Practice: open the Actions tab and inspect recent workflow runs.
- [ ] Practice: read logs from one run and summarize what happened.
- [ ] Practice: identify where a test, build, or deployment step would fit in a workflow.

#### Repository settings and permissions
- [ ] Understand branch protection, required reviews, and repository roles.
- [ ] Practice: read GitHub Docs about branch protection rules.
- [ ] Practice: list which protections you would enable for a team project and why.

#### Advanced pull request workflows
- [ ] Understand draft pull requests, stacked work, and review iterations.
- [ ] Practice: open a draft pull request for work that is not ready to merge.
- [ ] Practice: convert it to ready for review when your checklist is complete.

#### Releases and tags
- [ ] Understand semantic versioning, releases, and annotated history.
- [ ] Practice: inspect release and tag features in GitHub Docs.
- [ ] Practice: write a sample release note for a pretend `v1.0.0`.

#### Open source collaboration
- [ ] Understand forks, upstream repositories, discussions, and contribution guidelines.
- [ ] Practice: review an open-source repository and identify its README, issue templates, and contribution guidance.
- [ ] Practice: write a short plan for how you would contribute a documentation fix.

### Advanced mini-project
- [ ] Review one workflow in `.github/workflows` and explain it step by step.
- [ ] Draft a pull request that improves documentation and includes testing notes.
- [ ] Write sample release notes for the documentation update.
- [ ] Summarize how CI and code review would help protect the default branch.

---

## GitHub cheat sheets

### Everyday workflow cheat sheet

1. Create or update an issue.
2. Create a branch for one focused change.
3. Make the change.
4. Commit with a clear message.
5. Push the branch.
6. Open a pull request.
7. Review the diff and checks.
8. Address feedback.
9. Merge.
10. Delete the branch.

### Pull request checklist

- [ ] My branch has one clear purpose.
- [ ] My title explains the change.
- [ ] My description explains what changed and why.
- [ ] I reviewed the diff before requesting review.
- [ ] I noted how I tested the change.
- [ ] I merged only after checks and feedback were complete.

### Commit message best practices

- Start with a short summary line.
- Use the imperative mood: `add`, `fix`, `update`, `remove`.
- Keep the subject focused on one change.
- Add a body when the reason is not obvious.
- Prefer consistency.

Examples:

```text
docs: add beginner GitHub checklist
fix: correct pull request instructions
chore: reorganize workflow references
```

Simple template:

```text
type: short summary

Why:
- reason 1
- reason 2
```

Common types:

- `docs` for documentation changes
- `feat` for new functionality
- `fix` for bug fixes
- `test` for test updates
- `chore` for maintenance work

---

## Common commands

### Basic Git commands

```bash
git status
git branch
git switch -c beginner/my-first-change
git add README.md
git commit -m "docs: update learning checklist"
git pull
git push -u origin beginner/my-first-change
```

### Useful comparison commands

```bash
git diff
git diff main...HEAD
git log --oneline --graph --decorate --all
```

### Helpful GitHub actions in the UI

- Open the **Code** tab to browse files.
- Use the branch selector to switch branches.
- Open **Pull requests** to propose and review changes.
- Open **Issues** to plan work.
- Open **Actions** to inspect workflow runs and logs.

---

## Suggested study rhythm

- [ ] Day 1: Finish the Beginner phase.
- [ ] Day 2: Repeat the branch, commit, and pull request flow without help.
- [ ] Day 3: Practice an Intermediate mini-project.
- [ ] Day 4: Resolve a merge conflict on purpose.
- [ ] Day 5: Inspect workflows and summarize a CI run.
- [ ] Day 6: Write a high-quality pull request description from scratch.
- [ ] Day 7: Review everything and teach the workflow back to someone else.

## Definition of success

You are becoming an advanced GitHub user when you can:

- [ ] Explain repositories, branches, commits, and pull requests clearly.
- [ ] Create focused branches and clean commits confidently.
- [ ] Open clear pull requests and respond well to review feedback.
- [ ] Resolve basic merge conflicts without panic.
- [ ] Read GitHub Actions runs and understand what failed.
- [ ] Use GitHub as both a coding tool and a collaboration platform.

---

## Repository notes

- [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md)
- [MIT License](./LICENSE)
