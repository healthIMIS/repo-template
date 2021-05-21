# repo-template
A template to be used for all our future repositories. 

## After repo creation checklist

- [ ] Go to [gitignore.io](https://www.toptal.com/developers/gitignore) and pick the language, IDE and tools you are using. Update `.gitignore` accordingly, commit, and push.
- [ ] Create `development` branch: `git checkout -b development` and `git push --set-upstream origin development`. We are using `development` as default branch and `main` for stable releases only.
- [ ] Go to `Settings` tabs:
    - [ ] Enable Discussions under `Options` tab.
    - [ ] Only allow `squash merging` under the `Merge button` section.
- [ ] Under `Manage access` tab, give access to dev teams. Please add outside collaborators one by one and only add them to teams if you really want them to show up in the GitHub organization.
- [ ] Under `Security & analysis` tab, double check that all features are enabled. This should happen by default but better save than sorry.
- [ ] Under `Branches` tab 
    - [ ] switch the default branch to `development`.
    - [ ] Set the following branch protection rules for `development` and `main`:
        * `Require pull request reviews before merging` to 1 for `development` and 2 for `main`.
        * Tick `Dismiss stale pull request approvals when new commits are pushed `.
  
- [ ] In the repo view, edit the about section and add tags. Leave the website empty for now.
