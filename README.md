# blablablahoyo.github.io

学号：2200921845
姓名：洪巧芸

# 第一次课程作业
发布时间: 2023年3月22日    截止时间：2023.4.5  23：59
## 题目一
### 题目要求：
   * 词频统计图，选择自己熟悉领域的某一长篇文本进行某一类词的词频分析（也可选科研著作）
   * 将结果可视化，可使用柱状图或词云，也可用课上未讲到的其他图表形式
### 故事背景：
   1. 统计毛语录中不同人名出现的次数（步驟2-4）
   2. 生成柱状图 （步驟5-6）
   3. 生成词云（步驟7）
### 解题思路：
   1. 从网上下载毛语录的txt档案
   2. 利用flag先进行初步判读，找出可能为人名的字词
   3. 手动输入ignore list，将错误的人名塞选进行排除
   4. 生成人名与出现次数的统计图表，并储存为csv档
   5. 读取步骤4.所生成的csv档案，生成柱状图  
      标题为人物词频统计，并以人物为x座标，出现次数为y座标
   6. 调整图片大小及标签大小，让图片中的人名标签不会相互重叠影响判读
   7. 生成词云
### 代码链接：
   1. 主架构 <http://blablablahoyo.github.io/01.py>
   2. 主架构中引用到的Data资料
      1. [world_cointry.jason](http://blablablahoyo.github.io/data/world_country.json "link")
      2. [毛语录.txt](http://blablablahoyo.github.io/data/毛语录.txt "link")
   3. 生成图片
      1. [毛语录-人物词频.csv](http://blablablahoyo.github.io/毛语录-人物词频.csv "link")
      2. [毛语录-人物词频.png](http://blablablahoyo.github.io/毛语录-人物词频.png "link")
      3. [毛语录-人物词云.html](http://blablablahoyo.github.io/毛语录-人物词云.html "link")

## 题目二
### 题目要求：
   中国地图、世界地图（自己设定故事背景）
### 故事背景：
   1. 中国地图 -> 各个省份录取清北人数
   2. 挑选几个城市拉线至清北所在省份
   3. 世界地图 -> 台湾人喜欢到哪里去读书
   4. 找出前20个国家 标记数量
### 代码链接：
   1. 主架构 <http://blablablahoyo.github.io/02.py>
   2. 主架构中引用到的Data资料
      1. [world_cointry.jason](http://blablablahoyo.github.io/data/world_country.json "link")
      2. [台湾学生出国流向.csv](http://blablablahoyo.github.io/data/台湾学生出国流向.csv "link")
   3. 生成图片
      1. [清华北大招生人数.html](http://blablablahoyo.github.io/清华北大招生人数.html "link")
      2. [台湾学生出国留学数据地图.html](http://blablablahoyo.github.io/台湾学生出国留学数据地图_geo.html "link")
   4. 参考资料：
      1. <https://shirley.tw/2021y-study-abroad/>
      2. <https://new.qq.com/rain/a/20210719A0EBFG00>

## 题目三
### 题目要求：
   组合图表（自己设定故事背景）
### 故事背景：
   1. 比较去年每个月的花销 (NTD)
   2. 分为饮食、交通、总和
### 代码链接：
   1. 主架构 <http://blablablahoyo.github.io/03.py>
   2. 生成圖片
      [2022年每月花销.html](http://blablablahoyo.github.io/2022年每月花销.html "link")

# 第二次课程作业
发布时间: 2023年4月3日   截止时间：2023.4.23  23：59
## 题目一
### 题目要求：
   完成课上实现的某个搜索引擎的搜索功能
### 作业说明：
面对问题时习惯以Google进行搜索，所以决定选择制作Google Search的小视窗，自己也重新将Google标志颜色做了一些更动。
### 代码链接：
   [Google搜寻](http://blablablahoyo.github.io/search_engine.html "link")

## 题目二
### 题目要求：
选一部著作，可以是之前分析词频的作品，分析人物（或其他关键词）“共现”，生成关系图；用本次课学到的网页设计技术，设计一个简单的网页，放置关系图和相关说明
### 作业说明：
来到北京后一直很想去“大观园”因此在制作人物关系图时选择分析红楼梦。
### 代码链接：
   [Web_红楼梦](http://blablablahoyo.github.io/web.html "link")

## 遇到问题&解决办法
    1. 点开html时，跳出的网页页面是乱码
       -> 更改Safari中显示方式的文字编码，选择UTF-8
    2. 题目二中的人物关系图一直无法显现，但在编码中插入的连结能够正常运作
       -> 在网页中嵌入网页要用<iframe>而不是<img>
