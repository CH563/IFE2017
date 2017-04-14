# 2017百度前端技术学院任务

前端学习与任务完成进度

## 斌斌学院

### 任务一：零基础JavaScript编码（一）

在输入框中输入任何内容，点击“确认填写”按钮后，用户输入的内容会显示在“您输入的值是”文字的右边

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task01/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task01/index.html)


### 任务二：零基础JavaScript编码（二）

页面加载后，将提供的空气质量数据数组，按照某种逻辑（比如空气质量大于60）进行过滤筛选，最后将符合条件的数据按照一定的格式要求显示在网页上

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task02/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task02/index.html)


### 任务三：零基础JavaScript编码（三）

读取页面上已有的source列表，从中提取出城市以及对应的空气质量
将数据按照某种顺序排序后，在resort列表中按照顺序显示出来

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task03/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task03/index.html)


### 任务四：基础JavaScript练习（一）

有一个input输入框，以及4个操作按钮

- 点击"左侧入"，将input中输入的数字从左侧插入队列中；
- 点击"右侧入"，将input中输入的数字从右侧插入队列中；
- 点击"左侧出"，读取并删除队列左侧第一个元素，并弹窗显示元素中数值；
- 点击"右侧出"，读取并删除队列又侧第一个元素，并弹窗显示元素中数值；

点击队列中任何一个元素，则该元素会被从队列中删除

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task04/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task04/index.html)


### 任务五：基础JavaScript练习（二）

有一个input输入框，以及4个操作按钮

- 基于上一任务
- 限制输入的数字在10-100
- 队列元素数量最多限制为60个
- 队列展现方式变化，直接用高度表示数字大小
- 实现冒泡排序用可视化的方法表达出来

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task05/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task05/index.html)

### 任务六：基础JavaScript练习（三）

有一个input输入框，以及4个操作按钮

- 基于任务四进行升级
- 将新元素输入框从input改为textarea
- 一次批量输入多个内容，格式可以为数字、中文、英文等，可以通过用回车，逗号（全角半角均可），顿号，空格（全角半角、Tab等均可）等符号作为不同内容的间隔
- 添加查询词在各个元素内容中模糊匹配，匹配到的内容标红，不匹配暂时隐藏
- 一个都匹配不到时，提示

** 遇到问题：大小时匹配时，分别对大小写相应标红，替换不成功 **

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task06/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task06/index.html)

### 任务七：JavaScript和树（一）

- 在页面中展现一颗二叉树的结构
- 点击按钮显示开始遍历，点击后，以动画的形式呈现遍历的过程和禁用按钮
- 利用递归实现前序中序后序的二叉树的遍历算法
- 当前被遍历到的节点变化背景色
- 每隔500ms再遍历下一个节点

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task07/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task07/index.html)


### 任务八：JavaScript和树（二）

- 基于任务七，将二叉树变成了多叉树，并且每一个节点中带有内容
- 提供一个按钮，显示开始遍历，点击后，以动画的形式呈现遍历的过程
- 当前被遍历到的节点做一个特殊显示
- 每隔一段时间（500ms，1s等时间自定）再遍历下一个节点
- 增加一个输入框及一个“查询”按钮，点击按钮时，开始在树中以动画形式查找节点内容和输入框中内容一致的节点，找到后以特殊样式显示该节点，找不到的话给出找不到的提示。查询过程中的展示过程和遍历过程保持一致

[任务完成效果](http://chenliwen.tech/IFE2017/binbin/task08/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/binbin/task08/index.html)



## 耀耀学院

### 任务一：表单（一）单个表单项的检验

校验规则：
- 1.字符数为4~16位
- 2.每个英文字母、数字、英文符号长度为1
- 3.每个汉字，中文符号长度为2

[任务完成效果](http://chenliwen.tech/IFE2017/yaoyao/task01/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/yaoyao/task01/index.html)


### 任务二：表单（二）多个表单项的动态校验

校验规则：
- 表单获得焦点时，下方显示表单填写规则
- 表单失去焦点时校验表单内容
- 校验结果正确时，表单边框显示绿色，并在下方显示验证通过的描述文字
- 校验结果错误时，表单边框显示红色，并在下方显示验证错误的描述文字
- 点击提交按钮时，对页面中所有输入进行校验，校验结果显示方式同上。若所有表单校验通过，弹窗显示“提交成功”，否则显示“提交失败”

[任务完成效果](http://chenliwen.tech/IFE2017/yaoyao/task02/index.html)   |   [源码查看](https://github.com/CH563/IFE2017/blob/master/yaoyao/task02/index.html)