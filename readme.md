# Github Actions Tutorial

.github/workflows/hello.ymlに設定を書く．  

https://seijikojima.github.io/github_actions_tutorial/ に公開されている．

## 行いたいことリスト

* vpsにssh越しにvue.js,node.js,flask-appをdeploy
 * 定期的に各アプリのrepositoryをcloneしてrestart
 * webhookを利用して，pushされたらserver側でdeploy起動．
* dockerを利用してdeploy
 * server側でgit clone, docker build & run 
 * docker hubを利用してdeploy
* kubernetesを利用
 * 正直まだ何もわかっていない
