Need to set up the following when creating a new dev project (in no particular order, yet):

- Create folder
- If a Python project, create virtual environment (ie. `python -m venv venv --prompt="project_name"`)
- `git init`
- Rename initial git branch from master to main (unless already set using `git config --global init.defaultBranch main`)
- Create remote project on Github (no .gitignore, README or license)
- Add .gitignore file
- ssh-add relevant ssh key
- set remote repos (git remote add origin git@github.com:[your GitHub username]/[Repo name].git)
- Run git add. and git commit
- `git push -u origin main`

If you need to see your git config settings when setting a project folder up run `git config --list --show-origin`
If you need to set the global configs use:
- `git config --global user.name "John Doe"` and 
- `git config --global user.email johndoe@example.com`
