🔹 1. git diff

What: Shows changes between files/commits
How: git diff
Why: To see what you changed before committing

👉 Example: shows added/removed lines

⸻

🔹 2. git stash

What: Temporarily saves your changes
How: git stash
Why: When you want to switch branch without committing

👉 Think: “save for later”

⸻

🔹 3. Git Strategies (merge strategies)

What: Ways Git merges branches
Types: recursive, ours, theirs
Why: To handle conflicts during merge

⸻

🔹 4. git restore

What: Restores files to previous state
How: git restore file.txt
Why: Undo changes in working directory

⸻

🔹 5. git reset

What: Moves HEAD (undo commits)
Types:
	•	--soft → keeps changes
	•	--hard → deletes changes

Why: To undo commits

⸻

🔹 6. git revert

What: Creates new commit to undo old commit
How: git revert <commit>
Why: Safe undo (doesn’t delete history)

⸻

🔹 7. git fork

What: Copy of someone else’s repo (GitHub concept)
Why: To work on others’ projects

⸻

🔹 8. git rebase

What: Moves your commits to another base
Why: Keeps history clean (no merge commits)

👉 Think: “rewrite history”

⸻

🔹 9. git squash

What: Combines multiple commits into one
Why: Clean commit history

⸻

🔹 10. git tag

What: Marks a specific commit
How: git tag v1.0
Why: Used for versions/releases

⸻

🔹 11. git amend

What: Modify last commit
How: git commit --amend
Why: Fix message or add files

⸻

🔹 12. git blob

What: Basic file data stored in Git
Why: Git stores files as blobs internally

⸻

🔹 13. git workflows

What: Ways teams use Git
Examples:
	•	Feature branch workflow
	•	Gitflow

Why: To manage team collaboration

⸻

🔹 14. git gc (garbage collection)

What: Cleans unnecessary files
How: git gc
Why: Improves performance

⸻

🚀 Simple Summary
	•	diff → see changes
	•	stash → save temporarily
	•	restore/reset/revert → undo things
	•	rebase/squash → clean history
	•	tag → mark version
	•	gc → clean repo
