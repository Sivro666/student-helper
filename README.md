# Student Helper

Lab Sheet 7: Git and Collaborative Development.

## Run each independent program

```sh
python welcome.py
python calculator.py
python grade.py
```

The calculator accepts integers. A mark of 50 or above passes.

## Git history

The initial commit creates three empty Python files. Three branches start at that
commit: `member-a-welcome`, `member-b-calculator`, and `member-c-grade`.
Each adds one program and is merged into `main` with a separate merge commit.

```sh
git status
git branch -a
git log --oneline --graph --all
```

## Collaboration status

This is a single-user demonstration prepared for Ding Sibo (Sybolt0921).
Branch names follow the worksheet's suggested roles; they do not represent three
different contributors. Actual team formation, collaborator access, teammate
clones and teammate pulls still require the real students. No teammate activity
is claimed. The optional merge-conflict exercise has not been performed.

## Verification

Six terminal runs passed: welcome text, positive and negative integer addition,
and marks 49, 50 and 100. See `verification.json` for captured outputs.
