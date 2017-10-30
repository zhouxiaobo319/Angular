# Angular
```js
    // git clone 仓库地址 代表你要将这个仓库克隆下来
    // 100% done 之后 会有一个 .git 文件(隐藏文件夹) 代表这个文件夹的范围是你的仓库范围
    // 仓库会默认有一个 主干(master) 也就是说如果你什么都不做 那么将默认在主干上开发 (当然你也可以新建分支)

    git status //这个命令用于查看仓库的状态   红色文件在 工作区 绿色文件在缓存区 不显示的文件在版本库。

    //工作区  将工作区的代码提交到缓存区 使用 git add 文件名/文件夹名   : git add README.md  git add . 来匹配所有  git add *.css 来添加所有的 css文件
    //缓存区 就是即将被添加到版本库 但没被添加到版本库的文件所在的区  如何添加 git commit -m "我写好了主页"
    //版本库 这区分为 本地版本库 和远端版本库  那么如何将本地版本库上的代码上传呢 使用 git push 
    //下载使用  git clone / git pull / git fetch 
    // git clone  就是把整个仓库克隆下来
    // git fetch  就是在已有仓库的前提下更新远端的代码 把远端的新代码下载下来
    // git pull  = git fetch + git merge  //git merge 就是合并的意思。
    //
```