# Git and GitHub Workflow

## Once in the shellgit

> git init # -- create a repo (once per project) <br>
> don't forget to add a .gitignore file <br>
> git remote add origin "ssh-path-to-github"

## For each feature in the shell

> git switch -c "branchname" # create and switch to new branch <br>
> git add "file" # add a file to the stage <br>
> git status # check, if everything is ok <br>
> git commit -m "message" # commit your changes <br>
> git push -u origin "branchname" # push to GitHub <br>
> continue on GitHub

## On GitHub

- Create a pull request for that branch (to merge it into main) <br>
- Send a link to the changed files to your team <br>
- Get a code review <br>
- Optional: implement changes, push again to update pull request <br>
- Merge and delete the branch on GitHub <br>
- Continue in the shell <br>

## Again in the shell <br>git

> git switch main <br>
> git pull # get the merged commits in your local main <br>
> git branch -d "oldbranchname" # delete the merged branch <br>

---

## Source

> https://neuefische-students.slack.com/archives/C081PGSM0GK/p1732723285669959
