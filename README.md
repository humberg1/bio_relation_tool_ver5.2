"# bio_annotate_tools" 



#================加了行标的版本是888触发菜单版本.py. 加了行标.但是wordwrap时候滑动滚轮有行号bug,还不会改.




English readme: just run 777触发菜单版本.py the six version of my software. update new trie search substrings algorithm
 100x faster than 5.xversion. 
 basic use method. 

#===============经过打印时间发现. 卡在了kmp算法上. 涂色速度还行.

#===========开发了正则匹配加速算法.目前最新版本代码运行777触发菜单版本.py 即可.



#===============第6个版本, 使用trie树加速. 加速算法在:https://github.com/zhangbo2008/searching_in_trie_in_microseconds_1000wdata_python










#==========666.py:59行添加了护眼色作为文本默认颜色.
#========tkinter开发说明书:
http://c.biancheng.net/tkinter/text-widget.html

#===========关于正则卡性能的问题.
#分析之后发现是涂色慢. 正则匹配速度还可以,python的库包本身就是用C加速度的底层.


#5.2版本
增加保存ner文件.现在按保存文件.bio和txt按钮之后生成output.ner文件. 注意里面的区间是左右都闭的意思.
举例子:入你要处  per  1  4   表示的是这一行文本入你要处是per.他所在行的第1个到第四个的闭区间这4个字符对应的
是入你要处这4个字.
#输出样式: ner1_text  ner1_label ner1_locationhead  ner1_locationtail ner2_text ner2_label ner2_locationhead ner2tail.....########正文的该行.


#5.1版本.
#=========常用正则匹配:
#最小匹配法律:《.*?法》
#最大匹配法律:《.*法》
#匹配月份:  re.findall(r"-(\d+)-",'2015-8-7')    # 8




#所有颜色的表:
http://color.liminba.com/c/ffb6c1/



#5.0版本=====================================
重大更新.目前主文件改名为666触发菜单版本.py
目前使用方式是支持无限个标签,只要你屏幕能放下按钮就行.100个没问题. 颜色表在代码最下面有.可以查看.
还是修改19行文件.注意我已经把white 无标签写死到其他地方.所以现在19行只需要根据你要的类别写入即可.不用
关心空白标签了.
使用方式:目前一行按钮10个. 然后折叠排布.
        每个按钮左键点击就是正常的标注.
        右键点击每个按钮会弹出全标注和正则标注选项卡.跟之前效果一样.为了更好的节省按钮空间而已.

后续打算按照888.py做一个行号.但是没研究太明白, 怕直接贴入会触发不可预知bug.所以就暂缓开发了.








4.1版本.-------------------------------------------------------------------------------------------
目前功能:
目前模式是,英文按照每个字母,标点,空格,汉字这些单位都是一个标注基本单位来看.这种模式很适合中英文混合的预料.
保存bio txt文件按钮: 按下后编辑器里面的文本自动保存为output.txt  , 标注保存为output.bio
读取bio txt文件按钮: 按下后编辑器里面的文本设置为output.txt, 标注设置为output.bio
颜色类别数量最大十个.可以在1.py:19 设置. 目前主要是因为屏幕按钮太多会不容易排列,所以最大设置10个类别.
                                      代码目前默认6个类别.不同任务时候需要自己修改.
支持三种标注方式. 第一排单独标注:选择一块文本后点按钮会涂色
                第二排全体标注:会全文搜索跟选中的相同文本一样的都读图一样色
                第三排是正则标注:框里面写入正则然后点右边的按钮会正则匹配全部符合的文本进行涂色.

加入了各种标注的颜色提醒.
正则输入框里面写了默认的例子.
都是些小改动就不录讲解视频了.有问题的童鞋可以github上提issue
支持2种格式标注: bio和bioes 加入一个选项卡来在界面切换模式2种.
这两种模式互相不影响,加入你读取bio格式的.然后标注为bioes再保存都是互通的.都会按照你最后的保存时候的
    选项卡为准.


bio和bioes的定义:https://blog.csdn.net/kevinjin2011/article/details/113939817









3.0版本:-------------------------------------------------------------------------------------------
#================一个bug, 比如 aaa 然后我要把aa标注为红色.那么就会图2次.所以这里面我们强制让他只图最前面的aa,后的aa忽略#==============3.0版本修复了这个bug#================一个bug, 比如 aaa 然后我要把aa标注为红色.那么就会图2次.所以这里面我们强制让他只图最前面的aa,后的aa忽略#==============3.0版本修复了这个bug



2.0版本:-------------------------------------------------------------------------------------------
2022-01-29,17点11

更新了,全文匹配全部标注.

2022-01-29,10点58

网上的bio软件太垃圾了.
所以自己手撸一个.
基于tkinter开发. 只要你装了python3就可以直接运行1.py
使用方法.
1.贴入自己的文本.
2.鼠标选择一段文字然后点击下面1-5标注按钮
3.点击生成文件,就会在1.py同级目录生成ouput.bio文件.
#注意这个标注是任意字符都标注.空格也会一般标注为O.
#以为我的理解是这样会支持中英文以及名字里面带空格的情况,是最好的标注方式.
#至于标注按钮不够多,颜色不够明显,可以根据自己要求修改1.py里面的文件.




#==========bio标注: NER任务. 命名实体识别,信息抽取.


经典工具是 精灵标注助手



















"# bio_tool_version3" 
"# bio_tool_vesion4" 
"# bio_tool_vesion5" 
"# bio_relation_tool_ver5.2" 
