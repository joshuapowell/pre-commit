# Execute Python Tests on Commit

Add the `pre-commit` file in this directory to you GIT repositories `.git/hooks` directory.

After adding the `pre-commit` file, make sure that the `git commit` command can access it.

```
chmod +x .git/hooks/pre-commit
```

From there you can test that it works by executing:
```
git commit
```
