# staticWeb
基于github发布个人静态网站

对于一些想弄自己网站/博客，想给同学朋友展示下自己的页面，但有没有服务器的小伙伴，可以用这个方法发布出去。这样人家直接访问地址就能看到了，
不过这只能发布纯静态网站哦。

第一步：创建一个新仓库

第二步：在仓库选择“Settings”页，找到下面的“GitHub Pages”，点进去随便选一个主题

第三步：选择主题后，可以看到一个博客地址。

地址格式：https://用户名.github.io/仓库名/

当放入自己文件上传后，访问该地址就能看到页面了。默认是访问index.html的，如果你文件叫abc.html，就需要访问：https://用户名.github.io/仓库名/abc.html

1 先项目下载到本地：git clone+代码地址
2 把你的文件都放到项目文件夹中
3 上传到github即可，访问链接就能看到了
git add -A
git commit -m'更新代码'
git push origin master
