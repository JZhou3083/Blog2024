# Blog

Personal blog [Seanote](https://jzhou3083.github.io/Blog2024/) powered with [Hexo](https://hexo.io/zh-cn/).  


**Log - 18 Aug, 2024**

因为硬盘烧了加上没有备份好， 之前的文章的源markdown文件全部丢失。只剩下了publish里面的index文件， 这些只要我一推送publish就会被刷新掉。
解决思路：https://github.com/hexojs/hexo/issues/3676
- stage 1： 用Typora之类的工具把index文件反过来生成md文件放回去
- stage 2： 恢复完以后建立一个私人branch， 每次push完记得把md源文件push上去

**25 Aug, 2024**
现在把cactus主题弄了回去，建立了master和dev的branch，之后不会有丢失的问题了。 以后用feature 分支来加东西， dev来更新。 master用来push
下一步：
- 把搜索框加回去
- 把主页回复成一模一样
- 把算法的文章都恢复回去
