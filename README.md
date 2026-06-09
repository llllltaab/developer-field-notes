# Developer Field Notes

## Description

A small personal reference site for Git commands, workflow habits, and reminders during bootcamp.

## Deployed Site

Live site: https://llllltaab.github.io/developer-field-notes/

## Features

- Git vs GitHub explanation
- Daily Git workflow notes
- Git command reference
- Safety notes about files not to commit

## One Thing I Learned About Git

I learned that Git only commits staged changes, not automatically everything in the folder.


git log --oneline
4ef61bc (HEAD -> main, origin/main) Merge pull request #6 from llllltaab/feature/responsive-styling
9f96326 (origin/feature/responsive-styling, feature/responsive-styling) Improve responsive styling
b5a40c9 Merge pull request #5 from llllltaab/feature/do-not-commit-safety
fdec4f4 (origin/feature/do-not-commit-safety, feature/do-not-commit-safety) Add do not commit safety section
1b80ca0 Merge pull request #4 from llllltaab/feature/command-reference
52ee3a7 (origin/feature/command-reference, feature/command-reference) Add Git command reference section
95f751a Add initial page styling
c424470 Add initial site content and README
5e75689 Add gitignore for local and sensitive files
git log --oneline --graph --all
*   4ef61bc (HEAD -> main, origin/main) Merge pull request #6 from llllltaab/feature/responsive-styling
|\  
| * 9f96326 (origin/feature/responsive-styling, feature/responsive-styling) Improve responsive styling
|/  
*   b5a40c9 Merge pull request #5 from llllltaab/feature/do-not-commit-safety
|\  
| * fdec4f4 (origin/feature/do-not-commit-safety, feature/do-not-commit-safety) Add do not commit safety section
|/  
*   1b80ca0 Merge pull request #4 from llllltaab/feature/command-reference
|\  
| * 52ee3a7 (origin/feature/command-reference, feature/command-reference) Add Git command reference section
|/  
* 95f751a Add initial page styling
* c424470 Add initial site content and README
* 5e75689 Add gitignore for local and sensitive files
git branch --all
  feature/command-reference
  feature/do-not-commit-safety
  feature/responsive-styling
* main
  remotes/origin/feature/command-reference
  remotes/origin/feature/do-not-commit-safety
  remotes/origin/feature/responsive-styling
  remotes/origin/main