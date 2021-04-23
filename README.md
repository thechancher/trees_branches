# Markdown

[cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[emojis](https://gist.github.com/rxaviers/7360908)

# trees_branches
experiments with commands

> v0.1 (1) initial version
>
> v0.2 (2) more modifications
>
> v1.0 (3) final version
>
> v1.1 **release** (4) Documented, tested, verified
>
>>
>> v1.1.1 **release v1.1.1** fix (7) {git log --online} {git checkout ####} {git branch v1.1.1} {git log --oneline --all} extra details
>>
>> v1.1.2 **release** fix (9) {git log --oneline --all --graph} last extra
>>
>
> v2.0 (5) Stronger
>
> v2.1 (6) More Stronger {git checkout main}
>
> ...
>
> v2.2 (8) More Stranger but without old details
>
>...
>
> v2.3 (10) Merge
> 
> v2.4 (11) stash {git stash} {git stash list} {git checkout ####} {git checkout main} {git stash pop}
> 
> v2.5 (12) {git tag v1.1 ####} {git tag v1.1 -d}
> 
> v2.5.1 (13) {git revert ####} {git revert --continue}
> 

# history
> git log --oneline --all --graph
> 
> git stash
>  
> git log --oneline --all --graph
> 
> git checkout ####
>
> git restore .
> 
> git status
> 
> git checkout main
> 
> git stash pop  
> 
> git log --oneline --all
> 
> git status

# undo changes
> git add .
> 
> git reset .\xxx.yyy
> 
> git reset .
> 
> git add .
> 
> git commit -m "..." -m "..."
> 
> git push

# upload
> git init
> 
> *git add .
> 
> git remote add origin xxx.com
> 
> git pull xxx.com master
> 
> *fix
> *commit
> 
> git push --set-upstream origin master
> 
> ...
> 
> git push