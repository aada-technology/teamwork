# teamwork

## Workflow

START<br>
&nbsp;&nbsp;&nbsp;&nbsp; |<br>
  v<br>
[Fork Repo]<br>
  |<br>
  v<br>
[Create Branch]<br>
  |<br>
  v<br>
Make Changes<br>
  |<br>
  v<br>
Switch to Main & Update<br>
  git checkout main<br>
  git pull origin main<br>
  |<br>
  v<br>
Return to Branch & Merge Main<br>
  git checkout your-branch<br>
  git merge main<br>
  |<br>
  v<br>
Push Branch<br>
  git push origin your-branch<br>
  |<br>
  v<br>
Create Pull Request<br>
  (Reference issues in description)<br>
  |<br>
  v<br>
DONE 🎉<br>

## When Conflicts Happen

Two PRs exist without each other's changes<br>
        |<br>
        v<br>
One PR is merged<br>
        |<br>
        v<br>
Other person runs:<br>
  git fetch origin<br>
  git merge origin/main<br>
        |<br>
        v<br>
Resolve conflicts in VS Code<br>
        |<br>
        v<br>
Commit changes<br>
        |<br>
        v<br>
Push branch again<br>
        |<br>
        v<br>
Update PR<br>
