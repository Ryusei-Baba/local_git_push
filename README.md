# local_git_push
普通は，remoteでrepositoryを作成してから，git cloneして，作業という流れだが，ここではある程度localで作業してからremoteにpushしたいという場合の手順について説明する．

## 手順例
1. cd ~/ws/src/packege名
2. (git add -A)
3. (git commit -m "add")
4. (git push)
5. git init
6. GitHubに同名のリポジトリを作成
7. git remote add origin <リポジトリ名> 
8. cat .git/config
9. git branch
10. git switch -c main
11. git branch
12. git branch -d master
13. git branch
14. (git pull)
15. 
