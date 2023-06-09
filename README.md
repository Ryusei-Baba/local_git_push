# local_git_push
普通は，remoteでrepositoryを作成してから，git cloneして，作業という流れ．<br>
ここではある程度localで作業してからremoteにpushしたいという場合の手順について説明する．

## 手順例
1. cd ~/ws/src/packege名
2. git init
3. git add -A
4. git commit -m "add"
5. (git push)
6. GitHubに同名のリポジトリを作成
7. git remote add origin <sshでcloneできるURL（git clone は除外）> 
8. cat .git/config
9. git branch
10. git switch -c main
11. git branch
12. git branch -d master
13. git branch
14. (git pull)
15. git branch --set-upstream-to=origin/main main
16. git pull --allow-unrelated-histories
17. vimが立ち上がるが Esc : q で抜ける
18. git push
