## 上周工作总结
1. 最近把手头的科研工作放一放，好好准备下GRE考试，目前正在刷OG。
2. 前几周准备Camera Ready时发现了一个Embedded Fonts（即嵌入字体）的问题。


维基百科的定义是Font embedding is the inclusion of font files inside an electronic document。

我用自己的理解说一下。

举个栗子，比如我们在网上下载了一个非常漂亮的字体，叫做“我很漂亮体”，然后安装到了你的电脑系统里。这时你在word里编辑文件的时候就可以把文字的字体设置成这个“我很漂亮体”。当然自己的杰作需要去炫耀一番才能满足自己的虚荣心嘛！你把这个word文档发送给了你的好友B，但是B的电脑里没有安装“我很漂亮体”啊，所以原来你设置成“我很漂亮体”的文字都变成了很naive的字体，也就是word默认的宋体，是不是很生气？这种问题在前几年很让人头疼，因为设计界的人士经常需要给客户发设计作品嘛，字体原因就是很头疼的事情。那个时候的解决方案就是把这个文档截个图发过去，很low对不对？



几年前呢，为了解决这个问题，字体嵌入技术Font Embedding应运而生。你编辑word文件的时候，可以直接把你用到的“我很漂亮体”嵌入到这个文档中，这样等你把Word文档发送给其他没有安装这个字体的人时，他们也能看到“我很漂亮体”啦，因为这个字体文件被嵌入到文档中了嘛，系统可以直接从word文件中读取字体然后渲染显示咯。注意这个只是例子啦，word能不能做字体嵌入我还没弄过，但是PDF是绝对可以做的啦，你把文档转换成PDF发送给好友是绝对没问题滴。



不过这个技术也存在不少争议啦，毕竟有些字体是设计者花费很多心血设计出来的，一些人的共享精神值得赞扬啦，设计出好字体给大家免费用，比如微软。另一些人就没那么好心咯，想用我好看的字体你就得掏钱买我的产品，比如小米出的“小米兰亭体”，名字记不清啦，大家看看就好。你说你要是花钱买个“小米兰亭体”，然后把带字体嵌入的文档免费发送给其他人，那其他人不花钱就可以拥有带小米兰亭体的文档啦，那小米岂不是很生气？一人掏钱大家沾光，这样是不对的！就像前几年P2P技术引起的版权争议一样。

吧啦吧啦说了一堆废话，更多细节欢迎大家光临我的个人博客：

[http://blog.sina.com.cn/s/blog_d8f783c90102xf7s.html](http://blog.sina.com.cn/s/blog_d8f783c90102xf7s.html)
