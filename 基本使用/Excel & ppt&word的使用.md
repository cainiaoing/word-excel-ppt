# Excel 使用

### 1、工作表中的输入数据

文本型数据的输入：当输入身份证号，电话号码，编号，学号，等长的数字或者字符，用文本型输入，当长度不够时可以调

2. 数值型数据：除了有数字（0 ~ 9）外，还有各种运算符号，

​                        对于==分数==的输入：为了与日期区分，比如输入 1 / 2，在这样输入 “0  1/2”就会得到对应的值

3. 日期型的输入：输入日期 ：mm/dd/yy,或者 dd-mm-y  

​                             输入时间：hh:mm(AM/PM)  例如：8：30 AM(am与时间之间要有空格)

4. 自动填充（利用规律，自动填充）：1、填充相同的数据（复制数据）

​                                                                 2、填充序列数据 （按等差等比，日期） 开始 -> “编辑”组 ——填充——序列

​                                                                 3、用户自定义序列数据：文件 ——选项——Excel选项——高级——自定义对话 

> 需要注意的是：要先把需要填充的表格，拖出来到一定单元格——在通过填充——系列——来设置填充方式——此时才会填充更新                               

框 ——在“输入序列”列表框中直接输入 ——导入

5. 是用公式和函数来计算公式

   在单元格中输入公式“=A1 + A2 + A3 +A4"再按回车键，形成结果将自动计算在单元格格内部

   以上的相当于函数“=SUM(A1:A4)"

   EXCEL的五种基本函数：SUM(求和)，AVERAGE(求平均值),COUNT(有数值型的数据被计数),MAX(最大值),MIN(最小值);

   函数的输入方法：公式——函数库——插入函数——fx按钮——插入函数

6. 函数单元格的引用地址 1、相对引用地址：“=E2 + E3 + E4”,在拖拽到时候会自动更新行标，和列号

   ​                                          2、绝对引用地址：在行标和列号前都加入‘$’表示该地址始终不变如“$B$3”,

   ​                                           3、混合引用地址：“$B1”百事列号不变，但是行号会自动更新
   
   

### 2、格式化工作表

1. 单元格的行列的插入和删除

​           开始——单元格——插入

2. 设置数据格式：小数位数，百分号，货币符号，是否使用千位分隔符表示同一个数

   开始——数字——对话框启动器——设置单元格格式——数字选项卡

3. 对数据进行字符格式化：（文字的美化，下划线之类的）

​          开始——字体——对话框启动器——设置单元格格式——字体

4. 调整工作表的行宽和列高：

   开始——单元格——格式

5. 设置对齐方式：

   开始——对齐方式——更高的要求的话，在其对话框启动器中去完成

6. 添加边框和底纹：

   选择对应的单元格区域——右击——设置单元格格式——边框选项卡中实现

   底纹（添加背景颜色和图案）：在填充即可完成


---

### 3、制作图表

1. 插入三维图表

​          选定所有选择的三列——插入——图表——柱形图

2. 为图标插入标题，x轴，y轴标题，

   选中图标——图表工具——布局——标签——选择相应的标题

3. 给图标标题设置图表快速样式，和改变绘图区的背景

   点击图表标题——图表工具——格式——形状样式——

   单击绘图区——双击打开绘图区格式——填充——图片或纹理填充做选择

### 4、数据排序和筛选

1、==排序==针对一个或者一个以上进行升序或者讲序

数据 —— 排序和筛选——排序按钮来实现（最多科弄三个关键字）

2、筛选：选定单元格——数据——排序和筛选——筛选——（自定义设置筛选类型）

### 5、简单汇总

选定要汇总的列，——单机”数据“选项卡——分级显示——分类汇总——进行相应的汇总方式

### 6、数据透视表

当对多字段进行汇总是，数据透视表更有力的显示数据

单机数据清单中的任一单元格——插入——表格——数据透视下拉按钮——

### 7、sheet

它是表示页数，当前有几页。（缺陷，删除后，不能恢复）

工作簿中有工作表，工作表就是sheet,

1. 可以对工作表 进行重命名， 改颜色，该顺序等一系列操作。通常右击就可以完成各项操作。
2. 可以对工作表进行隐藏，和取消隐藏
3. 可以实现跨工表进行复制。方式，；首先新建一个工作簿（该工作簿必须为打开的状态），然后对此工作簿右击，移动或复制工作表，确定即可
4. 对工作簿进行加密；文件 -> 信息 -> 保护工作簿
5. 保护工作表；对工作表右击-> 保护工作表 -> 设置权限 -> 添加密码；当在对工作表进行编辑，需要加密码才能编辑

### 8、对数据增加线框

选中框， 点击田字格， 选则所有线框，所有线框都被加进去了。

### 9、数据自动填充与单元格复制粘贴

1. 单元格的复制粘贴，粘贴，粘贴改单元格所有操作，，二粘贴值，值粘贴文字
2. 双击单元格，编辑单元格各个文字，单机，编辑整体文字

3. ctrl键 配个右下角拖动，看看是自动填充的是相同的还是等差的
4. 自动填充类型；关于列和行的自动填充；首先，在单元格输入一个数据 -> 然后框选所要填充的单元格 -> 在开始 ->  编辑 -> 填充 -> 选则（日期 时间 等差 等比） -> 之间差值 ，可移动完成填充（横向和列向都可以填充） 

### 10、数字格式

增加货币格式，日期格式，百分比格式，小数点位，等一系列格式。

### 11、条件格式

1. 把满足某些值的单元格跳出来，并让其与其他单元格不同，框选所要单元格， 条件格式 -> 其他进行设置、

2. 查找某人的信息，可以直接查找。比如查找孔德华的信息，ctrl + F5,在输入信息即可。

   

### 12、冻结工作表

1. 冻结窗格就是；冻结某一单元格或者行列的位置，让其一直显示，方便查找信息
2. 操作步骤；选则行或列的单元格，视图 -> 冻结窗格

### 13、排序

1. 在排序和筛选那块，进行主要和次要关键字进行排序



### 14、数据验证

1. 主要作用；快速添加所需数据，并进行验证，里面有多种分类比如（男，女），男和女之间要必须以英文状态下的符号进行输入。

2. 举例；在性别那列；框选范围，-> 数据 选项卡 -> 数据验证 -> 设置 -> 序列（相当于添加条件） -> 来源 （输入男,女）-> 确定即可 ，此时在性别那列，通过下拉三角符号，进行选项输入，且只能输入男，女

   输入错误会报错

   还有相似的，包括日期验证（设定范围，只能输入在这个范围内的日期）

### 15、半角符号全角符号区别

英文状态下的符号即使半角符号，中文状态下的符号是全角符号

### 16、分类汇总

1. 选中单元格不能有合并到单元格.
2. 选中分类字段，（把相同的排在一起）；选中所有需要单元格，排序，关键字，
3. 排好序后，在次框选，分类汇总，选则分类字段，汇总方式，选定汇总量（列名）

### 17、选中单元格的方式

点击所要的左上方的单元格，在按shift 在单机右下方的单元格。

### 18、打印预览

1. 作用；可以让自己直到，自己在打印时候，会不会出现明明打印到两张纸上的现象，方式；
2. 方式一 、打印预览，后，工作表会自动出现虚线，自己要把单元格间距缩时期放到一张纸上，
3. 方式二；文件 ，打印 ， 无缩放下拉按钮，将工作表调整到一页，，页实现自动缩放字体。

### 19、打印设置

1. 为了让打印出来的文件，水平居中，需要对页面进行设置，包括页数；
2. 打印，页面设置，包括（页面，页边距（居中），页眉页脚，工作表）

#  PPT

### 1、工作环境

1. 普通视图：（1）“幻灯片”标签，可以在单张幻灯片中添加图形，影片，声音，并创立超链接，并向其中添加动画

   ​                       （2）“大纲”标签，显示演示文稿的文本内容，全部幻灯片的编号，标题，和主题中的文本。

2. 幻灯片浏览视图：可以在幻灯片试图下，可以同时对多张幻灯片显示，方便对幻灯片进行移动，复制，删除，等操作

3. 阅读模式，

4. 幻灯片放映模式

### 2、编辑演示文稿

1、编辑幻灯片中的对象

​      （1）插入音频和视频

​                 单击插入——媒体

​      （2）插入超链接1、下划线表示超链接，单击“插入”——链接——超链接

​                                    2、插入——插图——形状——动作按钮——来实现各种动作

​        在幻灯片中对对象进行缩放，修该，移动，复制，删除，等操作，方法与word相同

2、例子：对第一张幻灯片插入图片，视频，和音频，第二张图片第一行文字是以下划线表示超链接，右下角的按钮（播放按钮），是以动作按钮表示超链接，（均是链接到下一张幻灯片），同时该幻灯片还插入了图片

​      做法：单击插入——图像——图片——插入图片——调整到小（插入图片）

​                   单击插入——媒体——视频下拉按钮——文件中的视频——找到视频文件——调整大小

​                   单击插入——媒体——音频下拉按钮——文件中的音频——找到音频文件——幻灯片上会出现声音图标

​      超链接：输入相应的内容后，——选定第一行文字——单击插入——链接——超链接——选定到连接到的位置

​    动作按钮超链接：插入——插图——形状下拉按钮——动作按钮——选定播放图标——把它画在右下角适合位置——“动作设置对话框”——超链接到——下一张幻灯片

### 3、美化幻灯片&统一设置幻灯片外观

1、设置字体和段落格式

​       开始——“字体”和“段落”——相应的按钮来实现

2、对文本框，图片，自选图形，表格，图表，等其他对象进行操作化，

​          只要单击这些对象，在打开相应的选项卡中设置即可

3、设置幻灯片主题和背景

​        单击“设计”——主题和背景——相应的按钮来操作

4、统一设置幻灯片外观

“幻灯片母版”讲义母版“”“备注母版”

幻灯片母版最常用，同意输入标题，和文本格式，视图——母版视图——幻灯片母版

母版通常由五个占位符，标题，文本，日期，页脚，和幻灯片标号，

插入——文本——页眉和页脚

视图——母版模式——幻灯片母版——选择对应的母版——设置页眉和页脚以及相应的字

### 4、设置演示文稿的播放效果

1、设置动画效果

1. 对幻灯片的对象进行动画效果：（分别对他们进行进入，强调，退出，以及动作的路径进行设置）

   ==添加动画==单击动画选项卡——动画  / 高级动画——添加动画下拉按钮

   ==编辑动画==可以对动画的运行方式，顺序，声音，动画长度，进行编辑  动画选项卡——动画组——效果选项下拉按钮。

2. 设置幻灯片之间的动画效果：

​         切换——切换到次幻灯片  组  和  “计时”组 相应的按钮来实现

### 5、播放演示文稿

1. 隐藏幻灯片：在普通视图的 “幻灯片标签中，选定幻灯片，右击——选择隐藏幻灯片   命令

   ​                                                  或者选定幻灯片——幻灯片放映  选项卡——设置组 ——隐藏幻灯片

2. 排练计时：对幻灯片的放映进行排练，对每个动画进行时间的控制：

​           幻灯片放映 选项卡——设置——排练计时

3. 设置幻灯片的放映方式：



​       幻灯片放映 选项卡——设置组——设置幻灯片放映——在打开的对话框进行实现

演讲者放映：以全屏幕的形式，演讲者可以控制放映进程，可以用绘图笔构画，适用于大屏幕投影仪的会议，讲课

观众自行浏览：以窗口的形式显示

在站台浏览：（以全屏）以实现排练的顺序和次序进行放映，不允许现场进行控制放映进程

### 6、PPT视图编辑

在新建幻灯片时，可以通过，选则复制幻灯片，以谁为母版，或者直接复制空白ppt.

节；作用是，帮做ppt分章节。

### 7、文字设置

1. 点击字体，在文本框中，对文字去进行编辑

2. 但是在编辑文字时，不会出现上下标，这就需要在字体下拉按钮，去勾选上下标了

3. 通过快速样式，可以快速对文本框和文字达到一个好看的效果（都是电脑预设好的）。形状填充；针对于所选文字的文本框的底色；  形状轮廓；针对于文本框的轮廓设置；   形状效果；文本框和文字都会出现的效果。

### 8、段落设置

1. 选中字体，才能激活各种命令；首先选中文本框，才进行对操作选项卡里东西进行使用
2. 段落的对齐方式；是字体针对于文本框的。
3. 可以有段落前的标题样式，有黑点，有数字等
4. 文字方向的设置，对齐文本
5. 在弄好段落层级关机的前提下，可以把文字转成smartArt图。改图是流程图了，关系图了，美观而已
6. 关于怎样弄好段落层级关系；可以在段落那里，有缩进关系，可以缩进，这样很方便弄好层级关系。

### 9、插入图片

1. 插入图片，根据路径，插入图片。对，插入图片后，还可以删除背景，但不是很完美的，会把主题部分保留出来，然后保留更改，这样就会在ppt界面出现插入后的主题图片
2. 在图片工具中，像校正，颜色，艺术效果，就是对图片进行p图而已，；更改图片；会让自己重新选定图片。  重设图片；会让图片恢复到改掉之前的样子。
3. 图片样式；调整的是图片的边和效果，使之能看起来更加立体。
4. 图片版式；会让图片出现层次结构图，还会有对应输入文字的地方，也能使其看起来更加好看。
5. 排列是对于多个图片的谁先显示，谁后显示问题。对齐；是图片针对于ppt大小对齐的。
6. 裁剪还可以设置图片的大小，
7. 插入相册；这样会批量插入图片，使之每张图片成为了ppt的一页。

### 10、插入表格

1. 插入选项卡；表格，选则表格，自定义行列数目

2. 在表格样式里，可以看到各种表格样式，供自己使用。前面的表格样式选项，有标题行，汇总行可以勾选，让其该行更加醒目。

3. 还可以对表格进行设置底纹，边框，和效果等一系列效果。

4. 当然在表格输入文字，还可以对文字进行设置，

5. 对输入完后的表格还可以对表格进行设置大小。

6. 绘制边框工具；绘制表格，在表格内绘制，起到分栏作用，在表格外进行绘制，相当于创建了文本框了。

7. 橡皮檫；在表格内擦格与格之间的分界线，会让其边界消失，但是对单个单元格没有用。

### 11.插入插图

1. 插入形状，自行设置大小，，还可以在各种形状中编辑文字。

2. 插入smartArt图；会让组织结构图出现，

3. 插入图表；会有很多图形（条状，折现等图形的模板）插入后，看不清，可以在图表样式里选则一张可以看的清的样式，通过改变自带的Excel表，填写数据，可以更改图标中的数据。  还可以添加图标元素，在图中增加许多值，比如xy轴里，各块的值，什么先，趋势线等一系列现。   快速布局，可以对图表，有更多的显示（对比参数会更详细一些）

   更改颜色，会更改图中的柱形图柱子颜色。

### 12、插入文本及视频

1. 插入文本；插入选项卡 -> 文本 -> 文本框 -> 托选范围。输入文字
2. 插入视频；插入好视频，也可以对视频范围调增大小
3. 对于视频的一系列操作；更正；   是为了让视频更改色调，颜色，就是该视频颜色，  海报框架；就是把视频某一帧，当成视频界面，否则就是视频第一帧，操作是；选中到视频某一帧 -> 选则海报框架 -> 当前帧即可
4. 还可以调整视频框的效果，以及视频效果。视频形状。
5. 插入音频和是视频都是一样的

### 13、进入动画

1. 在单个ppt页内，对文本框，选中，进行动画设置。（文本框带动文字一起按照某种格式进入ppt来）

2. 在ppt内的动画，所有文本框进入都是由顺序的，要更改顺序的话，需要点击文本框前面的数字，在选项卡最后一列选则向前移动或是向后移动。
3. 多个文本框时，如何快速对文本框进行添加进入的动画；方式；  动画选项卡， 高级动画选项卡 ， 动画窗格，  可以快速调整动画进入ppt的顺序。

### 14、强调动画

1. 强调动画于进入动画操作一样，只不过强调动画的重点在于强调对象，而进入动画针对的对对象的进入效果；
2. 效果可以叠加，不过需要从添加动画的按钮里进行添加。（意思时先选中进入的动画， 在 添加动画里选则别的强调动画，在从添加动画里选其他动画，这就达到了动画叠加效果）
3. 效果选项，可以对文本框的内容进行动画展示。
4. 也可以对文本框中的文字框选，进行设置动画，但是此时要在对次文本框设置动画，就会让，文字动画小时。

### 15、动作路径

1. 会让某个文本框在动画，中的动作路径，沿着某条路径进行移动，而且还可以弄移动时间。

2. 还可以让，通过改变移动后的位置，进行拖拽，进而确定其最终位置。
3. 自定义路径；第一；点击文本框，选则起点。 第二；在移动鼠标，到某一位置，点击，创建拐点  第三；双击左键，确定终点。

### 16、触发按钮

1. 除法按钮的前提首先要有一个动画，然后在添加一个按钮
2. 触发按钮可以有多个触发功能，比如触发链接（在ppt中的任意一个元素）
3. 比较好的按钮；插入 -> 形状
4. 将按钮和动画链接起来，选中动画，触发 ， 找到按钮即可
5. 触发超链接，最后一页，视频的操作；选中某文本框，或者某个按钮，  - >  插入 -> 动作 ->  进行触发内容。

### 17、换灯片切换

1. 切换幻灯片的效果
2. 切换选项卡， 通过预设，来设置切换动画，
3. 同时还可以设置切换时间， 声音，并将此应用于全部幻灯片。
4. 切换方式；最好用  单机鼠标时； 进行切换。

---

# word的使用

### 1、标尺&网格线

这两个是对排版的时候，起辅助作用，还有网格线，也是对排版起辅助作用（在 视图 ，显示里）

### 2、字体格式（字符）

有下划线，下标，上标，更改英文转态下字母大小写，删除线，背景颜色，前景颜色。

字体颜色的底纹和边框，与段落的低温和边框是针对范围不一样的，前者这对是字体，后者针对单元格，大范围的。

删除线，一般不容易弄成双下划线，想弄成双下划线的方式是在字体选项卡中去勾选，

字符加宽，就是字体间的间距加宽，也是在字体选项卡中去找。

字符缩放：在段落中，某标志可以找见。

### 3、格式刷的应用

先选中原字体，然后单击格式刷，然去框选要更改的字体，

如果要多次应用格式刷，先选中原字体，双击格式化，可以不断框选要更改的字体，达到格式相同的效果。按Esc键结束。

### 4、项目编号和格式

项目标号，主要是对段落与段落间，前面有标号（1，2、3、……，一、二、……）等，应用主要是，通过框选各段落，减少缩进量，增加缩进量，来达到分层级的效果，在通过更改项目编号的格式，来让各段之间有层级感。

### 5、分栏，首行缩进，文字方向

分栏：在布局，栏上，具体格式可以自行设计

首行下沉;框选索要首行缩进的段落，在插入-首字下沉，中，具体格式可以自己设计。

问题方向，主要应用在表格内，对文字方向横的占格比较多，可以用纵的方向。具体使用方法；选中更改的子，布局- 文字方向。

### 6、页面背景，格式

在设计-页面背景可以找到，可以增加水印，可以弄背景颜色，但是弄好背景颜色的时候，需要在打印的时候，必须勾选打印页面颜色。

### 7、插入符号

1、插入页码；

2、插入时间和日期；在插入出，弄日期和时间选项卡，勾选自动更新时间。等

3、插入文本框；可以弄出一个文本框，设置不同的样式，且插入文字等。

4、插入SmartArt图，组织结构图，主要是流程图，，组织结构图等，一系列的关系的制作。

### 8、组合与拆分

1、选中对象   ctrl + 拖动 = 复制

2、把零散对象弄成一个整体，整体放大与缩小，操作；shift + 选则对象 + 右击 - > 组合（也可以取消组合）

### 9、叠放次序

当我们用word做图时（用插入里的图形，点击，shift + 拖动=等比列出现图），想把外面的图放到里层，可以右击图片，选则叠放次序来实现

### 10、图片对齐

多个图片不齐，且间距不一样，

操作方式；选中对象，布局，对齐，间距调整等

### 11、对文本添加背景

插入文本框，添加背景。右击，编辑文本等操作。

### 12、页眉，页码小技巧

1、单独的调整中文字体和英文字体；选中所有文字，改成宋体，在全选中，tiems new roman，这样，中文时宋体，英文和阿拉伯数字时不一样的字体。

2、如何实现多种页码的格式；

1. 找到要求页码不同的张页（没有页数，和要求有页数的分界页，在要求不让有页码的最有一页，单机  布局 -> 分隔符 -> 分节符 - > 下一页，此时要求有页码的最上边有一个回车键，在把那个回车键删除，删除办法；实在该页有文字的开头按住backspace），此时，上下时两个不同的部分，对要求有页码的部分，可以选择的页码 下拉按钮 -> 页码格式 -> 页码编号 -> 起始编号为1 -> 确定 ； 此时上方就是没有页码，下方就是从一开始有的页码。 
2. 当第一页，第二页，删除页码，所有的页码都会消失；这是解决办法是；点击到，分界线出，就是有页码的那页，点击页码，在页眉和页脚处，把   链接到上一节，给去掉，在去删除开始章节的页码即可。
3. 链接到前一页的前提是；没有页码和有页码处，之间必须有分隔符。才能激活链接到前一页的复选框

### 13、目录的自动生成

1、对一级标题，弄成标题一，且更改学校要求的个格式，二级标题弄成标题二，更改要求的格式，下面一系列三四即标题，都是如此。

目录标题下，顶格，回车键哪里，引用-> 目录 -> 自定义目录 -> 格式（正式）-> 显示级别（显示多少级，就会有多少级的小标题）-> 确定（目录会自动生成）

，目录格式自己调整。

2、当弄完时，发现有些内容进行更改，或者，有些东西没有用标题（标题1，2，3，……）弄，可以弄完后，在引用出，更新目录 -> 更新整个目录。来实现。然后，在用相同的操作，更新整个页码就好了。

### 14、参考文献怎么写

百度学术，随便点开一个论文，引用，就会出现很规范的参考文献引用格式。。

### 15、一键删除页眉页脚水印

文件 -> 信息 -> 检查文档 -> 检查文档 -> 在文档检查器中 -> 把所有勾都去掉，只留下页眉页脚，水印 ->  检查 -> 点击全部删除

### 16、word版手写签名，可重复使用

准备一张白纸 -> 写上自己的姓名 -> 手机拍下来 -> 插入到文档里面 -> 调整合适的大小 -> 环绕文字 -> 浮于文字上方 -> 点击颜色 -> 重新着色 ->黑白50% -> 再次点击颜色 -> 设置透明色 ->  把变成笔的光标点击字体的白色背景 -> 在把白色背景删除掉 -> 手写签名就做好了 -> 再把它拖动到签名栏，进行适当的调整 

为了保存图片供下次使用 -> 点击图片 -> 点击文件菜单 -> 选项 -> 校对 -> 自动更正选项 -> 替换栏里输入签名 ->选则带格式文本 -> 点击添加 -> 的点击确定 -> 以后在输入签名 -> 签名图片就自动出现了

### 17、制作输入不受影响的下划线，且可以随意调整长度

很多人在制作班级，姓名，院系了，这样的下划线的时候，

1、很多人的制作方法；敲一堆空格，然后添加下划线制作的

2、这里用插入表格制作，方法；

插入 -> 表格 -> 选则要制作的行数，列数是2 -> 在每行的第一列输入信息 -> 选中那几行的信息 -> 开始选项卡 -> 段落 -> 调整宽度 -> 字节的宽度是跟输入信息的最长的信息的宽度 从而达到对其的效果 -> 选中整个表格 -> 设计选项卡 -> 边框 -> 无边框  -> 在选则消除边框的表格的右部分区域（没有信息的部分，虽说看不见了，但是还是可以框选的） -> 再次在边框设置 -> 下框线和内部框线 -> 再在下划线上输入文字会发现下划线跟文字有间距 ->选则所有的部分 -> 开始选项卡 -> 字体下拉按钮 -> 高级选项卡 -> 位置   上选则下降 -> 对应的磅值越高就会与下划线的间距越下，但是会有临界值，这个临界值需要自己根据字体的大小去找（一般情况下是26磅） -> 再利用网格去调整下划线的宽度 -> 中间的文字也要调整居中对齐 -> 就完成了

### 18、如何删除空白页

方法有三种；

1、在空白页上按住backspace,和delete，直至空白页消失，但是这种方法比较局限，不适用所有的情况

2、方法二；在空白页的第一行 -> 右击段落 -> 间距 -> 行距选为固定值 -> 设置值改为1

3、删除分节符；针对分节符产生的空白页 -> 视图 -> 大纲视图 -> 把分节符给删除掉 -> 在利用方法1，或者2，把空白页给删除掉。

### 19、word实用技巧

1、大规模框选（首位选取，框选）；将光标放置在框选的开始，按住shift,再去点击结束的位置，可以进行有效的框选。适合多页的跨页选取文字

2、单击、双击，三击； 当光标置于段落中，双击选则一个单词，三级选则该整个段落； 当光标置于页边距左侧，单机选则一行，双击选则一段，三击选则整篇

3、word文档内置翻译器；选则翻译文字 -> 审阅选项卡 -> 翻译 -> 翻译所选内容 -> 在右侧对话框中选则插入（也可以翻译为其他国家的语言）

4、快速输入勾叉；打勾；输入2611 再按住alt + x

打叉；输入2612 再按住alt + x

5、快速输入当前日期或时间；输入当前日期；shift + alt + d,输入当前时间；shift + alt + t;     如果输入的日期时间格式要改，对其框选 -> 右击 > 编辑域 ->选则自己想要的版式

6、快速输入间隔线；输入3个-，再按住回车，出现一条间隔线； 双间隔线；输入3个=，再按回车 ； 虚线间隔线；输入三个*，再按回车键；  输入粗间隔线；输入三个#，再按住回车键， 输入一条波浪线；输入三个~，再按回车键

7、excel表格复制到word文档中，不变形；选中excel表格 -> 将光标置于边界线，等到出现十字时，拖到word文档中即可。excel想要复原，直接撤销即可。

8、快速统一图片大小；找到一个合适的图片 -> 右击 -> 大小和位置 -> 绝对值找到合适的数值 -> 在选中其他的图片 -> 按住快捷键F4,即可调整到一样的图片大小。