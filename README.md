# CodeSnippets
Xcode 开发常用代码片段管理

###下载代码片段

~~~
git clone https://github.com/LengYi/CodeSnippets.git
~~~

###让Xcode同步使用下载的代码片段
进入下载的代码目录然后执行脚本

~~~
./snap.sh
~~~

大功告成

原理：脚本建立了Xcode使用CodeSnippets文件的链接，通过软链接直接使用了git clone下来的CodeSnippets文件，从而实现了代码片段的管理使用同步
