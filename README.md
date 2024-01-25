# Git


## branch
```sh
git branch --list
# rename current branch as main
git branch -M main
# copy branch::main to branch::test
git branch --copy main test
# switch branch
git checkout test
```

## add remote

```sh
# show all the remote urls
git remote -v
# alias repository as origin
git remote add origin git@github.com:xuewenm/test.git
```

## push

```sh
# push local:main to origin:master
git push origin main:master
```
