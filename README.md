如何删除git拉去下来的本地项目仓库？

git branch  #显示所有本地分支 （初始化时只有一个master分支）
git init   #初始化本地版本库（这里重新初始化了一下，这一步可以忽略）
ls -a    #找到目录下.git
rm -rf  .git   #删除
可以看到master分支已经删除（test中隐藏的.git文件夹已经删除）
