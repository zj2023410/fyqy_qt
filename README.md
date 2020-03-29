﻿1. **下载说明：由于可执行文件比较大，如有需要请到网盘下载（下面都给出了网盘地址）。**
2. **网店地址：https://shop244026315.taobao.com/**
3. **联系方式：QQ：517216493   微信：feiyangqingyun**

## 一、自定义控件大全
### （一）、控件介绍
 1. 超过160个精美控件，涵盖了各种仪表盘、进度条、进度球、指南针、曲线图、标尺、温度计、导航条、导航栏，flatui、高亮按钮、滑动选择器、农历等。远超qwt集成的控件数量。
 2. 每个类都可以独立成一个单独的控件，零耦合，每个控件一个头文件和一个实现文件，不依赖其他文件，方便单个控件以源码形式集成到项目中，较少代码量。qwt的控件类环环相扣，高度耦合，想要使用其中一个控件，必须包含所有的代码。
 3. 全部纯Qt编写，QWidget+QPainter绘制，支持Qt4.6到Qt5.13的任何Qt版本，支持mingw、msvc、gcc等编译器，支持任意操作系统比如windows+linux+mac+嵌入式linux等，不乱码，可直接集成到Qt  Creator中，和自带的控件一样使用，大部分效果只要设置几个属性即可，极为方便。
 4. 每个控件都有一个对应的单独的包含该控件源码的DEMO，方便参考使用。同时还提供一个所有控件使用的集成的DEMO。
 5. 每个控件的源代码都有详细中文注释，都按照统一设计规范编写，方便学习自定义控件的编写。
 6. 每个控件默认配色和demo对应的配色都非常精美。
 7. 超过130个可见控件，6个不可见控件。
 8. 部分控件提供多种样式风格选择，多种指示器样式选择。
 9. 所有控件自适应窗体拉伸变化。
 10.  集成自定义控件属性设计器，支持拖曳设计，所见即所得，支持导入导出xml格式。
 11. 自带activex控件demo，所有控件可以直接运行在ie浏览器中。
 12. 集成fontawesome图形字体+阿里巴巴iconfont收藏的几百个图形字体，享受图形字体带来的乐趣。
 13. 所有控件最后生成一个dll动态库文件，可以直接集成到qtcreator中拖曳设计使用。
 14. 目前已经有qml版本，后期会考虑出pyqt版本，如果用户需求量很大的话。
 
### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1A5Gd77kExm8Co5ckT51vvQ](https://pan.baidu.com/s/1A5Gd77kExm8Co5ckT51vvQ) 
2. 提取码：877p
3. 文件名：bin_quc.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_quc/000.gif)

## 二、输入法
### （一）、输入法V2018
1. 未采用Qt系统层输入法框架，独创输入切换机制。
2. 纯QWidget编写，支持任何目标平台（亲测windows、linux、嵌入式linux等），支持任意Qt版本（亲测Qt4.6.0到Qt5.11.2），支持任意编译器（亲测mingw、gcc、msvc等），支持任意控件输入包括网页中的输入控件。
3. 调用极为方便，pri文件调用形式，只要改成文件包含即可，例如pro文件中写 include($$PWD/inputnew/inputnew.pri)。
4. 界面清晰简洁，UI美观友好，非常适合触摸设备。
5. 支持实体键盘输入+鼠标单击输入+触摸输入。
6. Qt程序嵌入的浏览器中的网页中的文本框等控件的输入。
7. 迷你模式，界面大小随意设置，采用布局自使用任何分辨率。
8. 纯数字键盘模式，自由控制弹出完整输入法面板和数字键盘面板，只需要对控件设置属性即可。例如ui->txt->setProperty("flag", "number");
9. 控制需要显示输入法和不需要显示输入法，当某些控件不需要弹出输入法，只需要对应不需要弹出输入法的控件设置属性noinput为真即可。例如ui->txt->setProperty("noinput", true);
10. 自适应屏幕大小，输入法弹出位置为控件底部时，当超过桌面右边或者底部时，自动调整位置。
11. 实现了长按超过500毫秒重复执行按下的键的功能。例如长按退格键，不断删除。
12. shift键切换输入法，esc键隐藏输入法，空格选中第一个汉字，回车选中输入的拼音。和搜狗输入法处理一致。
13. 英文、中文、数字字母、大小写、特殊字符自由切换。
14. 支持单拼双拼词组输入，网上大部分只支持单个汉字输入。智能分页算法，可任意翻页查看汉字词组。
15. 默认自带5种皮肤颜色，可随意切换，用户也可用QSS自定义皮肤。
16. 字库文件可大可小，提供迷你版字库大小仅120KB，方便存储空间紧张的硬件，完整版字库25MB。
17. 可选谷歌内核的输入法引擎，字库文件1MB，不依赖数据库，资源占用低效率极高。支持模糊拼音，比如nh=你好。
18. 可选windows专有版本，支持外部程序输入，比如输入到记事本、QQ聊天窗口等。
19. 整个输入法代码行数1000行左右，非常小，不会对程序增加大小造成负担。
20. 代码结构极为清晰，注释详细，非常容易阅读和理解，同时也可以自行修改拓展自定义的需求。

### （二）、输入法V2019
1. 未采用Qt系统层输入法框架，独创输入切换机制。
2. 纯QWidget编写，支持任何目标平台（亲测windows、linux、嵌入式linux等），支持任意Qt版本（亲测Qt4.6.0到Qt5.13），支持任意编译器（亲测mingw、gcc、msvc等），支持任意控件输入包括网页中的输入控件。
3. 调用极为方便，pri文件调用形式，只要改成文件包含即可，例如pro文件中写 include($$PWD/input2019/input2019.pri)。
4. 界面清晰简洁，UI美观友好，高仿IOS输入法，非常适合触摸设备。
5. 顶部滑动选词+弹出汉字面板选词，支持滑动。
6. 具有记忆功能，之前选中过的词语首先显示，支持单个拼音多个汉字，自动调整优先级。
7. 具有造词功能，可以直接打开文件文件写入自定义词组，最高级别显示。
8. 支持Qt程序嵌入的浏览器中的网页中的文本框等控件的输入。
9. 界面大小随意设置，采用布局自使用任何分辨率。
10. 属性控制数字输入，例如需要文本框默认弹出的是数字则设置代码 ui->txt->setProperty("flag", "number");
11. 自由控制需要显示输入法和不需要显示输入法，当某些控件不需要弹出输入法，只需要对应不需要弹出输入法的控件设置属性noinput为真即可。例如ui->txt->setProperty("noinput", true);
12. 界面自适应屏幕大小，输入法弹出位置为控件底部时，当超过桌面右边或者底部时，自动调整位置。
13. 实现了长按超过500毫秒重复执行按下的键的功能。例如长按退格键，不断删除。
14. 英文、中文、数字字母、大小写、特殊字符自由切换。
15. 支持单拼、全拼、模糊拼音输入，智能分页算法，可任意翻页查看汉字词组。
16. 默认自带5种皮肤颜色，可随意切换，用户也可用QSS自定义皮肤。
17. 谷歌内核的输入法引擎，品质保证，字库文件1MB，不依赖数据库，资源占用低效率极高。支持模糊拼音，比如nh=你好。
18. 可选windows专有版本，支持外部程序输入，比如输入到记事本、QQ聊天窗口等。
19. 整个输入法代码行数1000行左右，非常小，不会对程序增加大小造成负担。
20. 代码结构极为清晰，注释详细，非常容易阅读和理解，同时也可以自行修改拓展自定义的需求。

### （三）、效果图
1. 网盘地：[https://pan.baidu.com/s/1vIyEdB4QGo5OvxLYj7kq5g](https://pan.baidu.com/s/1vIyEdB4QGo5OvxLYj7kq5g) 
2. 提取码：sysn
3. 文件名：bin_input.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_input/input2018.gif)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_input/input2019.gif)

## 三、气体安全管理系统
### （一）、功能特点
1. 采集数据端口，支持串口端口+网络端口，串口支持自由设置串口号+波特率，网络支持自由设置IP地址+通讯端口，每个端口支持采集周期，默认1秒钟一个地址，支持设置通讯超时次数，默认3次，支持最大重连时间，用于重新读取离线的设备。
2. 控制器信息，能够添加控制器名称，选择控制器地址+控制器型号，设置该控制器下面的探测器数量。
3. 探测器信息，能够添加位号，可自由选择探测器型号，气体种类，气体符号，高报值，低报值，缓冲值，清零值，是否启用，报警声音，背景地图，存储周期，数值换算小数点位数，报警延时时间，报警的类型（HH,LL,HL）等。
4. 控制器型号+探测器型号+气体种类+气体符号，均可自由配置。
5. 地图支持导入和删除，所有的探测器对应地图位置可自由拖动保存。
6. 端口信息+控制器信息+探测器信息，支持导入导出+导出到excel+打印。
7. 运行记录+报警记录+用户记录，支持多条件组合查询，比如时间段+控制器+探测器等，所有记录支持导出到excel+打印。
8. 导出到excel的记录支持所有excel+wps等表格文件版本，不依赖excel等软件。
9. 可删除指定时间范围内的数据，支持自动清理早期数据，设置最大保存记录数。
10. 支持报警短信转发，支持多个接收手机号码，可设定发送间隔，比如即时发送或者6个小时发送一次所有的报警信息，短信内容过长，自动拆分多条短信。
11. 支持报警邮件转发，支持多个接收邮箱，可设定发送间隔，比如即时发送或者6个小时发送一次所有的报警信息，支持附件发送。
12. 高报颜色+低报颜色+正常颜色+0值颜色+曲线背景+曲线颜色等，都可以自由选择。
13. 软件的中文标题+英文标题+logo路径+版权所有都可以自由设置。
14. 提供开关设置开机运行+报警声音+自动登录+记住密码等。
15. 报警声音可设置播放次数，界面提供17种皮肤文件选择。
16. 支持云端数据同步，可设置云端数据库的信息，比如数据库名称，用户名+密码等。
17. 支持网络转发和网络接收，网络接收开启后，软件从udp接收数据进行解析。网络转发支持多个目标IP，这样就实现了本地采集的软件，自由将数据转到客户端，随时查看探测器数据。
18. 自动记住用户最后停留的界面+其他信息，重启后自动应用。
19. 报警自动切换到对应的地图，探测器按钮闪烁。
20. 双击探测器图标，可以进行回控。
21. 支持用户权限管理，管理员+操作员两大类，用户登录+用户退出，可以记住密码和自动登录，超过三次报错提示并关闭程序。
22. 支持四种监控模式，设备面板监控+地图监控+表格数据监控+曲线数据监控，可自由切换，四种同步应用。
23. 支持报警继电器联动，一个位号可以跨串口联动多个模块和继电器号，支持多对多。
24. 本地数据存储支持sqlite+mysql，支持远程数据同步到云端数据库。自动重连。
25. 本地设备采集到的数据实时上传到云端，以便手机APP或者web等其他方式提取。
26. 支持两种数据源，一种是串口和网络通过协议采集设备数据，一种是数据库采集。数据库采集模式可以作为通用的系统使用。
27. 自带设备模拟工具，支持16个设备数据模拟，同时还带数据库数据模拟，以便在没有设备的时候测试数据。
28. 支持所有windows操作系统+linux操作系统和其他操作系统。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_sams.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_sams/sams.gif)

## 四、可视化大屏电子看板系统
### （一）、功能特点
1. 整体总共分三级界面，一级界面是整体布局，二级界面是单个功能模块，三级界面是单个控件。
2. 子控件包括饼图+圆环图+曲线图+柱状图+柱状分组图+横向柱状图+横向柱状分组图+合格率控件+百分比控件+进度控件+设备状态面板+表格数据+地图控件(包括动态闪烁点+迁徙图等)+视频控件+其他控件等。
3. 二级界面可以自由拖动悬浮，支持最小化最大化关闭，响应双击自定义标题栏。
4. 数据源支持数据库采集（默认）、网络通信、网络请求等，可自由设定每个子界面的采集间隔即数据刷新频率。
5. 采用纯QWidget编写，支持Qt4.6到Qt5.12.3任何版本，支持嵌入式linux比如树莓派、香橙派、全志、imx6等。
6. 提供三个内核版本，自定义控件版本+qchart版本+echart版本。
7. 内置多套配色风格样式，默认紫色，支持任何分辨率。
8. 可设置标题+目标分辨率+布局方案，启动立即应用。
9. 可设置主背景颜色+面板颜色+十字线游标颜色。
10. 可设置多条曲线颜色，没有设置颜色的情况下内置15套精美颜色随机应用。
11. 可设置标题栏背景颜色+文字颜色。
12. 可设置曲线图表背景颜色+文字颜色+网格颜色。
13. 可设置正常颜色+警戒颜色+报警颜色+禁用颜色+百分比进度颜色。
14. 可分别设置各种字体大小，比如全局+软件名称+标题栏+子标题栏+加粗标签等。
15. 可设置标题栏高度+表头高度+行高度。
16. 曲线支持游标+悬停高亮数据点和显示值，柱状图支持顶部（可设置顶端+上部+中间+底部）显示数据，全部自适应计算位置。
17. 主界面直接鼠标右键切换布局+配色方案+关闭开启某个二级窗体。
18. 自动记忆所有子窗口的大小和位置，下次启动立即应用。
19. 动态加载布局方案菜单，可以动态新建布局、恢复布局、保存布局、另存布局等，用户可以制造任意布局。
20. 二级窗体，双击从主窗体分离出来浮动，可以自由调整大小。再次双击标题栏最大化，再次双击还原。
21. 每个模块都可以自定义采集速度，如果是数据库采集会自动排队处理。
22. 提供系统设置窗口进行整体的配置参数设置。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1o97IGvZgTgDhlkuXQa4B0w](https://pan.baidu.com/s/1o97IGvZgTgDhlkuXQa4B0w) 
2. 提取码：r2bv
3. 文件名：bin_bigscreen.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_bigscreen/0.gif)

## 五、视频监控系统
### （一）、功能特点
1. 支持16画面切换，全屏切换等，包括1+4+6+8+9+13+16画面切换。
2. 支持alt+enter全屏，esc退出全屏。
3. 自定义信息框+错误框+询问框+右下角提示框。
4. 17套皮肤样式随意更换，所有样式全部统一，包括菜单等。
5. 云台仪表盘鼠标移上去高亮，八个方位精准识别。
6. 底部画面工具栏（画面分割切换+截图声音等设置）移上去高亮。
7. 可在配置文件更改左上角logo+中文软件名称+英文软件名称。
8. 封装了百度地图，三维切换，设备点位，鼠标按下获取经纬度等。
9. 堆栈窗体，每个窗体都是个单独的qwidget，方便编写自己的代码。
10. 顶部鼠标右键菜单，可动态控制时间CPU+左上角面板+左下角面板+右上角面板+右下角面板的显示和隐藏，支持恢复默认布局。
11. 工具栏可以放置多个小图标和关闭图标。
12. 左侧右侧可拖动拉伸，并自动记忆宽高位置，重启后恢复。
13. 双击摄像机节点自动播放视频，双击节点自动依次添加视频，会自动跳到下一个，双击父节点自动添加该节点下的所有视频。
14. 摄像机节点拖曳到对应窗体播放视频，同时支持拖曳本地文件直接播放。
15. 视频画面窗体支持拖曳交换，瞬间响应。
16. 双击节点+拖曳节点+拖曳窗体交换位置，均自动更新url.txt。
17. 支持从url.txt中加载16通道视频播放，自动记忆最后通道对应的视频，软件启动后自动打开播放。
18. 右下角音量条控件，失去焦点自动隐藏，音量条带静音图标。
19. 集成百度地图，可以添加设备对应位置，自动生成地图，支持缩放和三维地图，提供地图风格选择，共12种风格。
20. 视频拖动到通道窗体外自动删除视频。
21. 鼠标右键可删除当前+所有视频，截图当前+所有视频。
22. 录像机管理、摄像机管理，可添加删除修改导入导出打印信息，立即应用新的设备信息生成树状列表，不需重启。
23. 在pro文件中可以自由开启是否加载地图。
24. 视频播放可选四种内核自由切换，vlc+ffmpeg+easyplayer+海康sdk，均可在pro中设置。
25. 可设置1+4+9+16画面轮询，可设置轮询间隔以及轮询码流类型等，直接在主界面底部工具栏右侧单击启动轮询按钮即可，再次单击停止轮询。
26. 默认超过10秒钟未操作自动隐藏鼠标指针。
27. 高度可定制化，用户可以很方便的在此基础上衍生自己的功能，支持linux系统。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g](https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g) 
2. 提取码：zkeh
3. 文件名：bin_video_system.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_video_system/0.gif)

## 六、楼宇对讲管理平台
### （一）、功能特点
1. 同时集成了楼宇对讲、住户报警、门禁控制、公共报警、视频监控等模块。
2. 系统管理部分包括系统配置、对讲配置、住户配置、公共配置、监控配置、地图管理、视频联动、用户管理、区域管理。
3. 图形化的实时对讲、室内报警、门禁设备界面，非常大气美观。
4. 设备状态内置地图模式、面板模式两种方式展示，非常强大。
5. 楼宇对讲设备和报警设备都支持地图上拖曳到正确位置，保存立即应用。
6. 支持报警视频联动，设备报警对应弹出报警视频。
7. 各种设备信息支持添加、删除、修改、打印、导入、导出、查询等，支持多条件组合查询。
8. 各种日志信息支持多条件组合模糊查询，查询的记录可导出和打印。
9. 可直接在软件上授权发卡，支持多对多发卡，一个卡号可以发到多个门禁设备，支持通卡（卡号下发到所有设备），可连续自动制卡，自动选中下一个用户进行制卡。
10. 可直接远程读取选中设备的卡号集合信息，进行统一的管理。
11. 所有卡号支持本地备份，一旦远程设备更换，可以重新下发卡号信息。
12. 支持过期卡号自动清理，被清理的卡号可以查询，可以指定楼栋、单元、过期时间查询卡号。
13. 支持公共部位报警接入，默认DS7400主机，能够识别布防、撤防、报警等信息。
14. 视频监控默认支持16通道显示，可切换到4通道、6通道、8通道、9通道、13通道显示，支持全屏和轮询。
15. 首页背景图、左上角logo、右上角项目名称可自定义，支持恢复出厂设置。
16. 亿级别本地海量数据存储，自动清空早期数据，永远保持最新的数据记录。
17. 每个模块都有开关可以后台自由控制启用或者禁用。
18. 集成了秘钥控制功能，可以控制设备数量以及运行时间。
19. 内置最牛逼的豪华版的输入法，高仿苹果电脑输入法，体验一级棒。
20. 纯Qt编写，支持任意Qt版本+任意编译器+任意系统，可运行在windws XP、win7、win8、win10、linux、mac OS、嵌入式linux等系统。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_TB.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_TB/0.png)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_TB/1.png)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_TB/2.png)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_TB/3.png)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_TB/4.png)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_TB/5.png)

## 七、视频监控内核
### （一）、vlc内核
1. 多线程实时播放rtsp视频流。
2. 支持windows+linux+mac。
3. 多线程显示图像，不卡主界面。
4. 自动重连网络摄像头。
5. 可设置边框大小即偏移量和边框颜色。
6. 可设置是否绘制OSD标签即标签文本或图片和标签位置。
7. 可设置两种OSD位置和风格。
8. 可设置是否保存到文件以及文件名。
9. 可播放本地视频文件，支持设置帧率。
10. 支持h265视频流+rtmp等常见视频流。
11. 可暂停播放和继续播放。
12. 支持回调模式和句柄两种模式。
13. 自动将当前播放位置和音量大小是否静音以信号发出去。
14. 提供接口设置播放位置和音量及设置静音。
15. 支持定时存储视频文件。
16. 支持外部拖曳文件+拖曳节点数据进行播放。
17. 自定义顶部悬浮条，发送单击信号通知，可设置是否启用。

### （二）、ffmpeg内核
1. 多线程实时播放rtsp视频流。
2. 支持X86和嵌入式linux。
3. 多线程显示图像，不卡主界面。
4. 自动重连网络摄像头。
5. 可设置边框大小即偏移量和边框颜色。
6. 可设置是否绘制OSD标签即标签文本或图片和标签位置。
7. 可设置两种OSD位置和风格。
8. 可设置是否保存到文件以及文件名。
9. 可设置间隔时间段保存文件到指定目录。
10. 可播放本地视频文件，支持设置帧率。
11. 支持h265视频流+rtmp等常见视频流。
12. 可暂停播放和继续播放。
13. 支持定时存储文件,包括音频和视频。
14. 支持sdl播放音频。
15. 支持外部拖曳文件+拖曳节点数据进行播放。
16. 自定义顶部悬浮条,发送单击信号通知,可设置是否启用。
17. 支持qsv dxva d3d 硬解码。

### （三）、效果图
1. 网盘地：[https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g](https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g) 
2. 提取码：zkeh
3. 文件名：bin_video_vlc.zip bin_video_ffmpeg.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_video_ffmpeg/video_ffmpeg1.gif)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_video_vlc/video_vlc1.gif)

## 八、皮肤生成器+UIDemo
### （一）、功能特点
1. 自带17套精美皮肤样式，其中包括黑色、灰色、扁平等。
2. 皮肤生成器只需要简单几步就可以生成一套自定义的皮肤。
3. 自带了26种uidemo，非常漂亮美观，涵盖了主界面布局、菜单切换等各种效果，总有一款适合你。
4. 所有代码和demo注释都非常详细整齐整洁，非常适合初学者学习。
5. uidemo由简入难，可以一步步学习下去，从入门到熟悉。
6. uidemo从常规的客户端到app端到触摸端等都有，既有鼠标操作的也有触摸操作的。
7. 皮肤中的qss样式表内容，覆盖了几乎所有的控件，非常适合学习每个控件的qss样式如何设置，而且分门别类非常清晰。
8. 自带的quiwidget类，集大成之所长，超级牛逼，内置了无边框的消息框、错误框、询问框、右下角信息框、输入框、日期范围选择框等，支持倒计时关闭，集成图形字体设置方法及根据指定文字获取图片，集成CRC校验、获取应用程序文件名、文件路径、设置窗体居中显示、设置翻译文件、设置编码、设置延时、设置系统时间等各种静态方法，保你满意。
9. 支持任意Qt版本+任意编译器+任意系统，可运行在win、linux、mac OS、嵌入式linux等各种系统上。

### （二）、使用方法
1. 单击另存为按钮，可以将当前看到的界面的样式导出到一个样式表文件，包含自动生成的图片资源。
2. 右上角风格下拉菜单，可以切换17套皮肤，切换完成以后会自动应用。
3. 支持直接在右侧样式表编辑栏内直接修改样式表内容，修改完成立即应用。
4. 从左侧选择字体颜色+面板背景+渐变颜色等，只要选择8种颜色，就可以生成一套自己的皮肤。
5. 皮肤生成器只是用来生成统一风格的样式表，比如按钮+文本框+菜单等控件的风格，而不是生成ui界面文件。
6. 对应的uidemo是样式表+ui布局的整体综合应用，可以自行修改成自己想要的布局。
7. QChar图形字体的对照表在 图形字体对照表.png。

### （三）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_uidemo.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_uidemo/qui.gif)

## 九、Onvif搜索和云台控制工具
### （一）、功能特点
1. 广播搜索设备，支持IPC和NVR，依次返回，可选择不同的网卡IP。
2. 依次获取Onvif地址、Media地址、Profile文件、Rtsp地址。
3. 可对指定的Profile获取视频流Rtsp地址，比如主码流子码流地址。
4. 可对每个设备设置Onvif用户信息，用于认证获取详细信息。
5. 可实时预览摄像机图像。
6. 支持云台控制，可上下左右调节云台，支持绝对移动和相对移动，可放到和缩小图像远近。
7. 支持Qt4和Qt5任意Qt版本，亲测Qt4.7.0到Qt5.12.4。
8. 支持任意编译器，亲测mingw、msvc、gcc、clang。
9. 支持任意操作系统，亲测xp、win7、win10、linux、嵌入式linux、树莓派全志H3等。
10. 支持任意Onvif摄像机和NVR，亲测海康、大华、宇视、华为、海思芯片内核等，可定制开发。
11. 支持对指定IP地址进行单播搜索，比如跨网段情况下非常有用。
12. 纯Qt编写，超级小巧轻量，总共约2000行代码，不依赖任何第三方的库和组件，跨平台。
13. 封装好了通用的数据发送和接收解析的函数，可以非常方便的自行拓展其他Onvif处理比如修改IP等。
14. 工具上提供了收发数据文本框，显示收发的数据，方便查看和分析。
15. 支持所有Onvif设备，代码工整，接口友好，直接引入pri即可使用。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g](https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g) 
2. 提取码：zkeh
3. 文件名：bin_video_onvif.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_video_onvif/video_onvif.gif)

## 十、控件属性设计器
### （一）、功能特点
1. 自动加载插件文件中的所有控件生成列表，默认自带的控件超过120个。
2. 拖曳到画布自动生成对应的控件，所见即所得。
3. 右侧中文属性栏，改变对应的属性立即应用到对应选中控件，直观简洁，非常适合小白使用。
4. 独创属性栏文字翻译映射机制，效率极高，可以非常方便拓展其他语言的属性栏。
5. 所有控件的属性自动提取并显示在右侧属性栏，包括枚举值下拉框等。
6. 支持手动选择插件文件，外部导入插件文件。
7. 可以将当前画布的所有控件配置信息导出到xml文件。
8. 可以手动选择xml文件打开控件布局，自动根据xml文件加载控件。
9. 可拉动滑动条、勾选模拟数据复选框、文本框输入，三种方式来生成数据应用所有控件。
10. 控件支持八个方位拉动调整大小，自适应任意分辨率，可键盘上下左右微调位置。
11. 打通了串口采集、网络采集、数据库采集三种方式设置数据。
12. 代码极其精简，注释非常详细，可以作为组态的雏形，自行拓展更多的功能。
13. 纯Qt编写，支持任意Qt版本+任意编译器+任意系统。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1A5Gd77kExm8Co5ckT51vvQ](https://pan.baidu.com/s/1A5Gd77kExm8Co5ckT51vvQ) 
2. 提取码：877p
3. 文件名：bin_property.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_property/完整视频.gif)

## 十一、自定义曲线图柱状图
### （一）、功能特点
1. 可设置X轴Y轴范围值。
2. 可设置背景颜色+文本颜色+网格颜色。
3. 可设置三条曲线颜色+颜色集合。
4. 可设置是否显示定位十字线,可分别设置横向和纵向。
5. 可设置十字线的宽度和颜色。
6. 可设置是否显示数据点以及数据点的大小。
7. 可设置是否填充背景形成面积图。
8. 可设置模式-拖动+缩放等。
9. 可设置坐标轴间距+第二坐标系可见。
10. 提供接口setDataLine直接设置曲线,支持多条。
11. 提供接口setDataBar直接设置柱状图,支持多条形成堆积图。
12. 提供接口setLabs设置文本标签替代key,包括X轴和Y轴。
13. 提供清空数据+重绘图表+外部获取QCustomPlot对象,这样就可以进行更加详细的参数设置。
14. 提供函数start+stop来模拟正弦曲线。
15. 可设置柱状图的值的位置+精确度+颜色。
16. 支持鼠标移动到数据点高亮显示数据点以及显示数据提示信息。
17. 可设置提示信息位置 自动处理+顶部+右上角+右侧+右下角+底部+左下角+左侧+左上角。
18. 可设置是否校验数据产生不同的背景颜色,比如柱状图的每根柱子都可以根据数据生成不同背景颜色。
19. 可设置是否显示图例+图例位置+图例行数以及图例单行显示。
20. 支持多条曲线+柱状图+柱状分组图+横向柱状图+横向分组图+柱状堆积图。
21. 内置15套精美颜色,自动取颜色集合的颜色,省去配色的烦恼。
22. 每条柱状图都可以设置不同的颜色,分组柱状图可以设置颜色交替。
23. Y轴数值支持百分比显示,可拓展成其他格式。
24. 内置平滑曲线算法,支持平滑曲线绘制,传入点集合即可。
25. 同时支持 QCustomPlot 1.0 和 QCustomPlot 2.0。
26. 支持Qt4-Qt5任意Qt版本,支持任意编译器+任意操作系统。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_customplot.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_customplot/customplot.gif)

## 十二、 数据导出到Excel及Pdf和打印数据
### （一）、功能特点
1. 原创导出数据机制，不依赖任何office组件或者操作系统等第三方库，尤其是支持嵌入式linux。
2. 10万行数据9个字段只需要2秒钟完成。
3. 只需要四个步骤即可开始急速导出大量数据到Excel。
4. 同时提供直接写入数据接口和多线程写入数据接口，不卡主界面。
5. 可设置标题、副标题、表名。
6. 可设置字段名称、列宽度。
7. 可设置是否启用校验过滤数据、校验的列、校验规则、校验值，符合规则的特殊颜色显示。
8. 可设置随机背景颜色及需要随机背景色的列集合。
9. 支持分组输出数据，比如按照设备分组输出数据，方便查看。
10. 可自定义行内容分隔符。
11. 可追加数据形式写入数据，建议每次追加的数据小于10000条。
12. 灵活性超高，可自由更改源码设置对齐方式、文字颜色、背景颜色等。
13. 支持任意excel表格软件，包括但不限于excel2003/2007/2010/2013/2017/wps/openoffice等。
14. 除了提供导出到Excel类以外，还提供导出到Pdf文件以及打印数据的类。
15. 注释完善，详细完整的使用demo，支持QTableWidget、QTableView、数据库三种数据源。
16. 纯Qt编写，支持任意Qt版本+任意编译器+任意系统。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_dataout.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_dataout/dataout.gif)

## 十三、 数据库集成应用通用功能
### （一）、功能特点
1. 同时集成了远程数据实时同步、本地历史记录同步到云端、远程数据实时下载到本地、数据库通用翻页、本地数据库处理、批量执行sql语句线程、数据库表格自定义委托、自动清理早期数据等各种功能，每个功能都是大量的真实项目应用场景而来。
2. 具有数据库自动重连机制，开启以后再也不用担心数据库服务器挂掉后连不上的问题。
3. 支持数据库自动清理早期数据，可以自由设置对应的连接、对应的表、保留最近数据条数、自动清理的间隔等，多线程清理。
4. 自动清理数据类还支持指定文件夹清理，比如图片文件夹或者日志文件夹，设置好文件夹路径和保留的大小即可，超过设置的大小的早期文件都自动删除。
5. 既有本地数据库表实时同步到云端，也有本地数据库表定时上传到云端，还有远程数据库实时下载到本地，全部双向，这对于目前兴起的物联网+5G项目，非常实用。
6. 所有功能类都有打印消息日志，可以方便的查看运行过程中的各种处理，包括执行耗费的时间等。
7. 自定义委托类非常丰富强大，无需每次为新的表字段设置委托，一个类重复利用，支持文本框、下拉框、日期框等多种委托类型，文本框还支持密文显示，下拉框内容集合可设置，委托的控件内容更改发送对应的信号，比如根据该信号可以做出处理例如播放声音。
8. 通用的数据库翻页类，只需要传入表名、字段集合、每页行数等几个参数就可以自动处理，无需额外的代码，通用各种项目。
9. 示例中集成了数据发生器，可以指定数据库表随机产生新的数据，可以指定每次产生多少条，方便项目中用来做数据压力测试。
10. 远程数据下载采用了post请求的方式获取，自动解析请求的结果数据，这个通用性很高，服务器上只需要放一个最简单的PHP文件，可以自由设置对应的表名和字段名，此流程非常适合手机app端，为Qt编写对应的应用程序的手机app端提供了极大的便捷。
11. 每个功能类都对应有详细的使用demo，代码注释非常详细，demo非常完成，封装的类只需要传入对应参数即可，通用多种数据库和应用场景，大大节省了开发时间。
12. 封装成一个pri组件，方便调用，支持Qt4-Qt5任意版本，支持任意编译器和操作系统，尤其是嵌入式linux。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_dbtool.zip

## 十四、 图片及视频TCP/UDP网络传输
### （一）、功能特点
1. 多线程收发图片数据和解析图片数据，不卡主界面。
2. 同时支持TCP和UDP两种模式，封装了TCP模式以及UDP模式的客户端类和服务端类。
3. 图片传输客户端同时支持发送到多个服务端，可以作为一个教师机同屏发送到多个学生机的应用场景。
4. 同时支持多个客户端同时往服务端发送图片，服务端每个连接都会自动开辟线程收发和解析图片数据。
5. 自定义label控件信号槽机制绘制图片，不卡主界面。
6. 自带心跳机制判断离线，自动重连服务器，可设置超时时间。
7. 每个消息都有唯一的消息标识uuid，服务端收到以后会返回对应的uuid消息表示收到，客户端可以根据此返回消息判断服务端解析成功，不用再发，这样可以确保发出去的数据服务器接收到了并解析成功。
8. 每个消息都有唯一的图片标识flag，相当于ID号，根据此标识判断需要解析显示到哪个界面。
9. 图片以base64的字符串格式发送，接收端接收到base64字符串的图片数据解码后重新生成图片。
10. 所有数据的收发都有信号发出去，方便输出查看。
11. 都提供单例类，方便只有一个的时候直接使用无需new。
12. 采用自定义的xml协议，可以自由拓展其他属性字段比如带上图片内容等。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g](https://pan.baidu.com/s/1bbL2ZughZAgfIGrexyN-9g) 
2. 提取码：zkeh
3. 文件名：bin_video_image.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_video_image/video_image1.gif)

## 十五、 百度地图综合应用（在线+离线+区域+下载）
### （一）、省市区域地图封装类功能特点
1. 同时支持闪烁点图、迁徙图、区域地图、仪表盘等。
2. 可以设置标题、提示信息、背景颜色、文字颜色、线条颜色、区域颜色等各种颜色。
3. 可设置城市的名称、值、经纬度 集合。
4. 可设置地图的放大倍数、是否允许鼠标滚轮缩放。
5. 内置世界地图、全国地图、省份地图、地区地图，可以精确到县，所有地图全部离线使用。
6. 内置了各省市json数据文件转js文件功能，如有数据更新自行转换即可，支持单个文件转换和一键转换所有文件。
7. 内置了从json文件或者js文件获取该区域的所有名称和经纬度信息集合的功能，可以通过该方法获取到信息用来显示。
8. 依赖浏览器组件显示地图，提供的demo支持webkit、webengine、ie 三种方式加载网页。
9. 拓展性极强，可以依葫芦画瓢自行增加各种精美的echarts组件，做出牛逼的效果。
10. 内置的仪表盘组件提供交互功能，demo演示中包含了对应的代码。
11. 函数接口友好和统一，使用简单方便，就一个类。
12. 支持任意Qt版本、任意系统、任意编译器。

### （二）、百度地图封装类功能特点
1. 同时支持在线地图和离线地图两种模式。
2. 同时支持webkit内核、webengine内核、IE内核。
3. 支持设置多个标注点，信息包括名称、地址、经纬度。
4. 可设置地图是否可单击、拖动、鼠标滚轮缩放。
5. 可设置协议版本、秘钥、主题样式、中心坐标、中心城市、地理编码位置等。
6. 可设置地图缩放比例和级别，缩略图、比例尺、路况信息等控件的可见。
7. 支持地图交互，比如鼠标按下获取对应位置的经纬度。
8. 支持查询路线，可设置起点位置、终点位置、路线模式、路线方式、路线方案（最少时间、最少换乘、最少步行、不乘地铁、最短距离、避开高速）。
9. 可显示点线面工具，可直接在地图上划线、点、矩形、圆形等。
10. 可设置行政区划，指定某个城市区域绘制图层，在线地图自动输出行政区划边界点集合到js文件给离线地图使用。
11. 可静态或者动态添加多个覆盖物。支持点、折线、多边形、矩形、圆形、弧线、点聚合等。
12. 函数接口友好和统一，使用简单方便，就一个类。
13：支持js动态交互添加点、删除点、清空点、重置点，不需要刷新页面。
14. 支持任意Qt版本、任意系统、任意编译器。

### （三）、离线地图下载类功能特点
1. 多线程同步下载多级别瓦片地图，不卡界面。
2. 内置多个离线地图下载请求地址，自动随机选择一个发送请求。
3. 下载地图类型同时支持街道图和卫星图。
4. 自动计算可视区域或者行政区域的下载瓦片数量。
5. 下载的级别可以自定义范围和选择。
6. 每个瓦片下载完成都发送信号通知，参数包括下载用时。
7. 可设置下载最大超时时间，超过了则丢弃跳到下一个下载任务。
8. 实时显示下载进度，以及当前级别已经下载的瓦片数和总瓦片数。
9. 下载过程中可以停止下载，下载完成自动统计总用时。
10. 内置经纬度和屏幕坐标互相转换函数。
11. 目前支持百度地图，其他地图比如谷歌地图、腾讯地图、高德地图可以定制。
12. 函数接口友好和统一，使用简单方便，就一个类。
13. 支持任意Qt版本、任意系统、任意编译器。

### （四）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_map.zip
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_map/map_echart_win.gif)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_map/map_baidu_win.gif)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_map/map_download_win.gif)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_map/map_echart_ubuntu.gif)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_map/map_baidu_ubuntu.gif)
![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_map/map_download_ubuntu.gif)

## 十六、 网络请求客户端/服务器
### （一）、功能特点
1. 支持多个客户端连接并发同时处理，
2. 可设置http请求是长连接还是短连接，默认长连接。
3. 支持多种回复数据格式，其中包括网页内容、json数据等。
4. 服务端示例中同时包含读取文件回复、读取数据库回复。
5. 支持8种配色方案（暗黑、灰黑、深绿、浅黄、深蓝、深黑、暗蓝、默认）。
6. 客户端可指定请求地址，服务端可指定网卡和端口进行监听。
7. 所有请求和连接都有计数，所有在线请求的IP和端口都显示在表格中。
8. 可自由拓展增加权限校验等，作为一个http请求服务器。
9. 代码框架整洁，注释完整，支持任意Qt版本、任意编译器、任意操作系统。

### （二）、效果图
1. 网盘地：[https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ](https://pan.baidu.com/s/1uQsDQO5E5crUBN2J-nPeLQ) 
2. 提取码：1jkp
3. 文件名：bin_httpserver.zip

![avatar](https://github.com/feiyangqingyun/QWidgetExe/raw/master/snap_httpserver/httpserver.gif)