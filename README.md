# crawler-beauty
</p>应舍友要求，帮其爬取某个图片分享网站的小黄图</p>
<br/>
<B>目前有1、正则版本   2、bs4版本
#正则版本
<B>1.运行前操作</B>
<p>请在E盘创建一个目录Photo，即路径为：E:\Photo</p>
<p>当然路径可以修改，具体修改方式在程序的注释中已说明</p>
<p>为什么不在程序中自动生成文件夹？------- 我只是怕你不知道哪个是你要的小黄图而已，自己新建的文件夹你总会记得吧</p>
<br/>
<B>2.程序完善时间列表</B>
<p>[16.02.23]  发现程序xiuren_useful.py爬到第十五个秀人图片时产生错误，正在研究为什么会有这样的错误产生</p>
<p>[16.03.13]  修正了正则表达式上的错误，实现了全部的爬取，正在验证是否还存在问题</p>
<p>[16.05.02]  添加了bs4版本，可以将全部图片完整的爬取下来</p>
#bs4版本
<p>1.操作指南</p>
<p>直接运行xiuren_bs4_version.py,默认的下载目录为E:/beauty/需要修改直接在文件中修改即可</p>
<br/>
<B>3.下载完后的目录情况（其中****视网站更新情况有所不同）</B>
<div class="cnblogs_Highlighter">
<pre class="brush:html;gutter:true;">E:
  /Photo
    /[秀人网]********
           _1.jpg
           _2.jpg
           ......
           10.jpg
           ......
           n.jpg
    /[秀人网]********
           _1.jpg
           _2.jpg
           ......
           10.jpg
           ......
           n.jpg
    .................
</pre>
</div>
<p>　　</p>

##re版本
###1.怎么工作
* 请在E盘创建一个目录Photo，即路径为：`E:\Photo`,当然路径可以修改，具体修改方式在程序的注释中已说明
* 为什么不在程序中自动生成文件夹？------- 我只是怕你不知道哪个是你要的小黄图而已，自己新建的文件夹你总会记得吧
###2.程序完善时间列表
* [ 16/02/23 ]  发现程序`xiuren_useful.py`爬到第十五个秀人图片时产生错误，正在研究为什么会有这样的错误产生
* [ 16/03/13 ]  修正了正则表达式上的错误，实现了全部的爬取，正在验证是否还存在问题
* [ 16/05/02 ]  添加了**bs4版本**，可以将全部图片完整的爬取下来


##bs4版本
###1.怎么工作
* 运行`xiuren_bs4_version.py`就可以对网站进行爬取，其中默认的下载目录为`E:/beauty/`需要修改可在Python程序*对应位置进行修改*
###2.程序完善时间列表
* [ 16/05/02 ]  添加了bs4版本，可以将全部图片完整的爬取下来

##爬取结果
###1.下载完后的目录情况
*  /Photo
 * /[秀人网]********
      * _1.jpg
      * _2.jpg
      * ......
      * 10.jpg
      * ......
      * n.jpg
 * /[秀人网]********
      * _1.jpg
      * _2.jpg
      * ......
      * 10.jpg
      * ......
      * n.jpg
 * ......

###2.截图目录如下
![image](https://github.com/zhongjiajie/crawler-beauty/raw/master/SampleResult.jpg)
