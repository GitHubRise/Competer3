Readme测试

父目录必须有仓库名

#####

pwd        显示当前目录
cd xx      进入目录
mkdiir     创建文件夹
git init   把这个目录变成Git可以管理的仓库

ls -ah     查看所有文件，包括隐藏文件
dir -ah    同上

#####

git add    添加文件到仓库
git commit 文件提交到仓库
git commit -m "提交说明，即可以理解为注释"

git commit命令执行成功后会告诉你，1 file changed：1个文件被改动（我们新添加的readme.txt文件）；2 insertions：插入了两行内容（readme.txt有两行内容）

添加文件到Git仓库，分两步：

使用命令git add <file>，注意，可反复多次使用，添加多个文件；
使用命令git commit -m <message>，完成。

git clone http 克隆到本地

git remote -v 用于查看远程仓库的地址

#####

https://git-scm.com/book/zh/v2/Git-%E5%9F%BA%E7%A1%80-%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%93%E7%9A%84%E4%BD%BF%E7%94%A8

https://www.liaoxuefeng.com/wiki/896043488029600