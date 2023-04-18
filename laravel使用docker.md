安装laravel版本要根据机器上的php版本选择

### #步骤

1. composer install
2. php artisan sail:install // 初始化 sail
3. php artisan sail:publish

NPM运行
```shell
npm run watch-poll
```



Linux命令

> 设置别名
>
> alias sail='bash vendor/bin/sail'
>
> asias up



挂载项目文件

![image-20230412123059499](/Users/nansongx/Library/Application Support/typora-user-images/image-20230412123059499.png)





# 启动

> 生成appkey
>
> php artisan key:generate --show
>
> // 创建模型的同时，创建迁移文件
> php artisan make:model Article -m
>
>
>
>

## git
```shell
撤销“已经提交到本地仓库的文件”的追踪
当一个文件（例如hello.txt）已经提交到本地仓库时。后续你再往.gitignore添加它，也不会起作用。怎么解除这种追踪呢？最常见的做法是直接删除这个文件，流程是：本地删除，提交删除这个commit到仓库。

但这样本地的也会被删除。有时我们只是想删除仓库的副本，可以使用git rm --cached。git rm经常被用来删除工作区和暂存区的文件。它可以携带一个cache参数，作用如下（摘自文档）：

git rm --cached
  
Use this option to unstage and remove paths only from the index. Working tree files, whether modified or not, will be left alone.
  
使用这个项来解除暂存区的缓存，工作区的文件将保持不动。
意思就是不会在实际上删掉这个文件，只是解除它的追踪关系。
```

```shell
执行 clean 命令，放弃所有文件修改：
git merge filling-layout-stylegit clean -df
```








