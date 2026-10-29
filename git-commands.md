\# Git Commands Record



This document lists the Git commands used during the assignment and explains their purposes.



| Command | Purpose |

|---|---|

| `git init` | Initializes a local Git repository. |

| `git clone <url>` | Copies a remote repository to the computer. |

| `git status` | Displays the current repository status. |

| `git add .` | Stages changes in the current directory. |

| `git add README.md` | Stages a specific file. |

| `git commit -m "message"` | Saves staged changes as a commit. |

| `git log --oneline` | Displays a compact commit history. |

| `git branch` | Lists local branches. |

| `git switch -c feature/exercise-01` | Creates and switches to a new branch. |

| `git switch main` | Switches to the main branch. |

| `git remote -v` | Displays configured remote repositories. |

| `git pull origin main` | Fetches and integrates changes from the remote main branch. |

| `git push -u origin main` | Pushes the main branch to GitHub and sets its upstream. |

| `git diff` | Displays unstaged changes. |

| `git merge feature/exercise-01` | Merges the specified branch into the current branch. |

| `git switch -c feature/update-documentation` | Creates and switches to the documentation feature branch. |
| `git push -u origin feature/update-documentation` | Pushes the feature branch to GitHub and sets its upstream. |
| `git switch main` | Switches back to the main branch. |



\## Commit History



Use meaningful commit messages that describe the changes made.



Examples:

\- Add assignment README

\- Add Exercise 01 source code

\- Add sample input and output

\- Add Git commands record

\- Fix input validation

\- Update exercise documentation



\## Merge Conflict



Record the actual merge conflict encountered during the assignment.



If a conflict occurs:

1\. Run `git status` to identify the conflicting files.

2\. Open each conflicting file.

3\. Examine the conflict markers: `<<<<<<<`, `=======`, and `>>>>>>>`.

4\. Edit the file to retain the correct content and remove the conflict markers.

5\. Stage the resolved file using `git add <filename>`.

6\. Complete the merge commit if Git requires one.

7\. Verify the result using `git status` and `git log --oneline`.


**Conflict encountered:** No content merge conflict was encountered while creating Pull Request #5. GitHub confirmed that the feature branch could be merged into the main branch without conflicts.

**Resolution:** No conflict resolution was required for this pull request. The documentation changes were reviewed and merged into the main branch through GitHub.



If no conflict occurred, state that no merge conflict was encountered during the assignment. Do not claim to have resolved a conflict unless you actually did so.

