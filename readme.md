# Github Actions Tutorial

.github/workflows/hello.ymlに設定を書く．  

https://seijikojima.github.io/github_actions_tutorial/ に公開されている．

## 行いたいことリスト

* vpsにssh経由でvue.js,node.js,flask-appなどのapplicationをdeploy
  * vps内のrepositoryに入って，pull (できた)
* dockerを利用してdeployß
  * server側でgit clone, docker build & run 
  * docker hubを利用してdeploy
* kubernetesを利用
  * 正直まだ何もわかっていない
