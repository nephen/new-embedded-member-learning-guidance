前言
=======

######此教程为长沙理工大学嵌入式基地内部资料，由学习部负责起草，嵌入式资深成员维护，旨在为嵌入式新成员提供更好更快的学习指导，访问地址：[emb.nephen.com](http://emb.nephen.com/)。

>####`怎么参与维护`

1、**加入合作者**

如果你有时间、并且有兴趣，请给我发邮件<a href=mailto:995168694@qq.com>995168694@qq.com</a>，我将给你发送加入合作者的链接，如果没有github帐号就注册[github](https://github.com/login)，然后使用github帐号登录邮箱里的链接，然后再在个人设置里面加入你发我的邮箱。如下：
<img src="blob:https%3A//www.gitbook.com/19ee451b-284a-4561-af15-1dedbd2864a7">

2、**编辑方法**

- *网页端编辑*

    如果你没有安装任何环境，你也可以在[网页](https://www.gitbook.com/book/nephen/bluetoothlamp/details)上进行编辑。

- *本地编辑*

    1. 如果你习惯于使用git（[教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/)），那么具体的方法如下：

    ```bash
    touch README.md SUMMARY.md
    git init
    git add README.md SUMMARY.md
    git commit -m "first commit"
    git remote add gitbook https://git.gitbook.com/nephen/new-embedded-member-learning-guidance.git
    git push -u gitbook master
    ```
    2. 或者下载[GitBook Editor](https://www.gitbook.com/editor)客户端操作，如果是在64位Linux环境下
    
    ```
    ~ $ sudo dpkg -i gitbook-editor-4.2.2-linux-x64.deb
    ```

>####`参考资料`

1. 关于gitbook，可查看[www.gitbook.com](https://www.gitbook.com)。

2. gitbook的官方使用，可查看[www.help.gitbook.com](https://help.gitbook.com/)。