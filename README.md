# css-
学习搭建前端框架
1.文件名用下划线“_”连接单词，文件包括js、css、html、图片、声音等文件，如alert_contain.html

2.类名、id名用横线“-”连接单词，允许使用英文大写，（尽量使用横线，遇到要区分层级，整齐命名的情况下可以使用驼峰加下划线的方式命名sideBar-tool）

3.变量、方法名用匈牙利命名法，类型+驼峰的方法，如bSubmitBtn     b代表是布尔型，后面表示按钮时提交按钮，用驼峰命名法，如a表示数组，s表示字符串，n表示数字型，o表示对象，j表示json（区别于其他对象），   如：jAlert，oBj，方法前面没有前缀，只需要使用驼峰命名即可如 function openSwitchMeter（）{ }
定时器前面全部加上前缀timer   如timerArrow，表示箭头动画的定时器

4.命名尽量使用英文翻译的方法，请勿使用中文拼音或数字（特殊情况下可以加入数字），英文翻译推荐使用谷歌翻译（有些名称使用公司公共的，比如诊断仪是obdscan，仪表是dashboard等）

5、样式 注释使用/**/,不要使用// (//在sass中不能编译到css文件中，)
