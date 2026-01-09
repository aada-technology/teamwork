# teamwork

## Workflow
<pre>
START
  |
  v
[Fork Repo]
  |
  v
[Create Branch]
  |
  v
Make Changes, stage and commit
  |
  v
Switch to Main & Update <---- Makes sure you have all the most recent changes from AADA
  git checkout main
  git pull origin main
  |
  v
Return to Branch & Merge Main 
  git checkout your-branch
  git merge main
  |
  v
Push Branch
  git push origin your-branch
  |
  v
Create Pull Request
  (Reference issues in description)
  |
  v
DONE 🎉
</pre>
## When Conflicts Happen
<pre>
Two PRs exist without each other's changes
        |
        v
One PR is merged
        |
        v
Other person runs:
  git fetch origin
  git merge origin/main
        |
        v
Resolve conflicts in VS Code
        |
        v
Commit changes
        |
        v
Push branch again
        |
        v
Update PR
  </pre>
