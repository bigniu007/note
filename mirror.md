# mirror

### 2017年7月7号

**做事不要太武断**  

​	测试发现部分手机出现首页内容和状态栏重叠（沉浸式效果），项目中有改变状态栏的需求（个人中心），自己也看过类似代码，直接给出判断是这部分代码引起的问题。
​	其实仔细想想，报告中出现的机型都是4.4.x（level 15）的手机，而那部分代码是有（level >= 21）的前置条件的。
​	更有趣的是当我给出了不要做改变状态栏的需求时，有人提出应该添加前置条件的时候，我还知道反驳说这个前置条件是有的（成吉思汗）。

