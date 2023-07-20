# asuka-memo
a memo of a singing little bird

### 贡献代码和 PR
- 请 fork 本仓库到您的个人空间。如果本仓库代码更新了，同样需要同步最新修订到本地
  * 将本仓库的远程分支追加为 fork 仓库的上游：```git remote add upstream https://github.com/nayurin/asuka-memo.git```
  * 同步上游的修订：```git fetch upstream```
  * 如果和本地内容出现冲突，需要在本地解决冲突
- 如果需要在新的分支上来调试代码，请使用```git checkout -b {分支名}```来创建新的分支
- ```{分支名}```请避免使用无意义的名字
  * 如果这是单模块内部的功能优化，建议使用```{模块名或接口名}-{优化内容}```来命名分支
  * 如果这是新功能的开发或是跨模块的功能优化，建议使用```feat-{特性名}```来命名分支
  * 如果这是对现存 Bug 的修复，则建议使用```fix-{bug名}```来命名分支
- 合并上游的修订：```git merge upstream/main```
- 在提交之前请仔细检查提交记录，尽量避免将个人环境的调试用代码提交到新分支。之后请使用```git push --set-upstream origin {您的本地分支名}```将本地分支推送到代码仓库的远程分支
- 每次提交 PR 之前**强烈建议**同步远端的仓库，以免遇到合并冲突的困扰
- 最后，请移步至代码仓库的 [Pull Request](https://github.com/nayurin/asuka-memo/pulls) 页创建新的 PR 请求，CR 通过后新代码会合入主分支
