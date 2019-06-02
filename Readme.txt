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

#####