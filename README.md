# npm-package

## Branches

```sh
┌───────────────────────┐       ┌────────────────────────────────┐       ┌───────────┐       ┌──────────┐
|                       |       |                                |       |           |       |          |
|  @langnang-temp/node  | ====> |   @langnang-temp/npm-package   | ====> |  develop  | ====> |  master  |
|  Sync from template   |       |         Sync to remote         |       |           |       |          |
└───────────────────────┘       └────────────────────────────────┘       └───────────┘       └──────────┘

```

### Sync to remote

```sh
# add remote url
git remote set-url --add origin [url]
# checkout the branch for sync
git checkout @langnang-temp/npm-package

git pull
# force push
git push -f
```
