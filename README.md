<h1>github使用</h1>
<h5>基本概念</h5>
<h6>仓库用来存放项目代码，每个项目对应一个仓库</h6>
<h6>star表示收藏项目的人数</h6>
<h6>fork克隆仓库</h6>
<h6>note：git bash中，Linux的命令基本可以使用</h6>
<h4>git的使用</h4>
<h6>git安装完成后，需要进行一些基本信息设置</h6>
<h6>设置用户名：git config --global user.name'用户名称'</h6>
<h6>设置用户邮箱：git config --global user.email'邮箱'</h6>
<h6>查看设置：git config --list</h6>
<h6>初始化仓库：git init</h6>
<h6>向仓库添加文件：git add 文件名</h6>
<h6>查看当前仓库状态：git status</h6>
<h6>从暂存器提交到仓库：git commit -m ' 文件描述 '</h6>
<h6>删除仓库文件：git rm  '文件'</h6>
<h4>将本地仓库同步到git远程仓库</h4>
<h6>先将远程仓库复制到本地：git clone 仓库地址</h6>
<h6>git push origin 分支名称</h6>
<h6>如果加上-f表示强制覆盖</h6>
<h6>这里如果因为代理报错，可以使用如下两行命令</h6>
<h6>git config --global --unset http.proxy</h6>
<h6>git config --global --unset https.proxy</h6>
<h6>修改分支名称 ：git branch -m 旧分支名称  新分支名称</h6>
<h6>查看本地分支 git branch</h6>
<h6>git pull origin main --allow-unrelated-histories 拉取远程 main 分支并与本地分支合并</h6>
