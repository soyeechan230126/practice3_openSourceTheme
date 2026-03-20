# Practice 3: using an Open-Source Theme

1. cloned jekyll-serif-theme from jamstackthemes.dev to local repository
2. initialised commit and pushed to remote repository

- To do: modify `_config.yml` and `Gemfile` for GitHub Page

  > #### bummer: had to reset the remote origin
  > `git init` , could not execute `git add` ; current branch `master`, remote branch `main`\
  > \
  > Actions take:  
  > `git remote remove origin`\
  > `git remote add origin <url>` \
  > `git checkout -b main` \
  > create `main` locally 
  > `git checkout master` \
  > `git push -u origin master` \
  > `git pull master main` \
  > `git checkout main` \
  > `git pull origin master` \
  > `git reset --hard origin/master` \
  > `git push -f origin main`  
  > \
  > Status: 
  > - still not able to commit despite of cloning `master` to `main`
  > - fail to deploy: `jekyll` and `github-pages` dependencies?

