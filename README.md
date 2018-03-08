# git_command
It's git commands.

# master 브랜치의 마지막 커밋을 가리키던 HEAD를 그 이전으로 이동시켜서 commit 내용을 없앰
```
git reset --hard HEAD^
```

# commit은 취소하고 commit 했던 내용은 남기고 staged 상태로 만들기
```
git reset --soft HEAD^
```

# commit은 취소하고 commit 했던 내용은 남기고 unstaged 상태로 만들기
```
git reset HEAD^ (revert the previous commit)
```

# 강제푸시
```
git push origin +master   (forced update)
```

# if I wanna delete the commit which I push.
```
git reset HEAD^   (revert the previous commit)
git push origin +master (forced update)
```

# add 한 파일들 unstaged 상태로 되돌리고 싶을때  
```
git reset (unstaged)
```

# delete untracked files
```
git clean -fdx
```
