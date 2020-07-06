- [Cherry Pick Range of Commits](#cherry-pick-range-of-commits)
- [Remotes](#remotes)
  - [List Remote](#list-remote)
  - [Change Remote URL](#change-remote-url)
  - [Remove files from staging area](#remove-files-from-staging-area)

# Cherry Pick Range of Commits

Lower-bound is exclusive

```
git cherry-pick B^..D
```


# Remotes

## List Remote
```
git remote -v
```

## Change Remote URL
```
git remote set-url origin <remote url>
```

## Remove files from staging area
```
git rm -r --cached .
```