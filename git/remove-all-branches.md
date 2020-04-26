## Remove all branches except master

When working on a project with a team is normal that your local and remote repository fill with unused branches making it hard to find the branches that you're currently working on. To purge the branches in your local machine you can run this command:

```bash
git branch | grep -v "master" | xargs git branch -D 
```

If you'd checkout in your development branch all branches except `master` and `development` are going to be removed.
