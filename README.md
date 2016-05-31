## Add Remote
```bash
git remote add origin /Remote/Project/Path/
git remote update
git remote -v
```
## Diff
```bash
git diff --cached  # 目前修改檔案的 diff,檔案要先 add 到 statge 中才可 diff
```
## Reset
```bash
git reset --hard HEAD # 全部復原
git reset FileName    # 檔案從 staged 中移到 unstaged 
```

## Show
```bash
git show -p -1/sha    # show 更改內容
```

## Checkout
```bash
git checkout FileName # Discard unstaged file change
```

## Error
```bash
Q: ....git/index.lock': File exists.
A: rm -f .git/index.lock
```
