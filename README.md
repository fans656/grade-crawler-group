# 考研分数统计

考研结束后会有很多晒分群，一般而言会要求成员在自己的群名片中备注上分数
这个chrome插件通过访问群空间来获取成员名片，继而统计每个群的分数

## 用法
(安装方式请查阅chrome文档)
在main.js的groups中添加群信息(名称和群号)，注意必须是你已经加入的群
在main.js的me中添加你的信息(分数、组名和你的qq号)
注意必须保证浏览器中留有qq的登录cookie，即你可以无需登录访问群空间
点击扩展按钮，程序会自动弹出多个tab来获取分数信息，获取完成后这些tab自动关闭
扩展页面显示分数统计

## 说明
程序自动剔除无有效成绩或名片中含有“围观”的成员
有效成绩根据群名片来判定，方式为名称中包含三位数，且大于等于200小于500

## 统计内容
- 所有群的汇总信息：最高分/最低分/平均分，总人数，你的排名
- 群信息：组名，组排名(最高分)，组排名(平均分)，最高分/最低分/平均分，人数，你的排名
- 群成员信息：排名、分数、姓名、qq