# deploy

## Split

```sh
❯ git subtree split --prefix deploy --branch split/deploy
❯ git remote add split-deploy git@github.com:yujunz/git-subtree-split.git
❯ git push split-deploy split/deploy:main
```

## Push

```sh
❯ git subtree push --prefix deploy split-deploy main
```
