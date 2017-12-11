# 计算机程序设计A

- 主讲教师：[顾为兵老师](mailto:wbgu@ustc.edu.cn)
- 课堂：每周二07:50-09:25，每周四14:00-15:35，5202
- 实验：每周六14:30-17:30，东区机房
- 作业：每周二上课时收，迟交扣分，不接受超过一周迟交
- QQ群：`438448823`

## 助教

每位同学都有对应的助教负责作业和实验，如不清楚对应关系请咨询助教。

- 徐运坤 QQ:`3095405172` Tel:`17718139436`
- 董汉德 QQ:`734475868` Tel:`17737085538`
- 胡凯 QQ:`1556113800` Tel:`13083083846`
- 王啸天 QQ:`949488099` Tel:`18856021328`
- 王昱程 QQ:`1650317570` Tel:`15656587659`
- 王子博 QQ:`994571761` Tel:`17730222371`

助教一般都会到课旁听，坐在最后一排附近，如在学习过程中遇到疑问，欢迎咨询助教。

## 学生信息管理系统大作业要求

本次大作业网上提交，请大家认真完成并充分测试，提交没有问题的版本。另请注意以下要求：

- 只接受`.c`文件，都到学期末了，请不要还用`.cpp`写C程序
- 注意邮件礼节，至少在邮件中说明你的身份
- 必须真正用链表实现，而非数组或其他数据结构
- 每条学生信息包含整数类型学号、字符串类型姓名、整数或浮点数类型成绩
- 创建、插入等功能中需要输入学生信息时，每行输入一个学生，格式为`324 Zhang 90`
- 打印等功能中需要输出学生信息时，每行输出一个学生，格式同上
- 数组可以有头结点也可以没有，打印时应先打印链表头，再打印链表尾
- 保存的文件格式可以自行设计，但需保证导出再读入后，链表内容完全一致，追加模式导出再读入后，链表内容为两部分之和
- 程序不应该强制用户按某种顺序操作，以下所列出的功能应该可以以任意的顺序使用
- 如果暂未生成链表，或者刚刚销毁过，而选择打印或其它功能，不应当报错，而应当看作当前有一个空链表
- 不必进行错误处理，比如不用考虑按学号插入时如果学号不存在怎么办

功能要求如下：

- 退出
- 创建链表
  - 头插法逐行插入
  - 尾插法逐行插入
  - 有序逐行插入
  - 读文件
- 打印当前的链表
- 插入一行
  - 指定插入在第几条
  - 指定插入在某个学号后面
- 删除一行
  - 指定删除第几行
  - 指定删除某个学号
- 输入学号查询一行
- 统计人数、平均分、最高分、不及格人数（不要做子菜单，一次打印出来所有信息）
- 保存到文件
  - 追加
  - 重写
- 请空链表
- 排序（可选）
- 其他功能酌情加分

## 常见问题

### 我需要电脑吗？
强烈建议买一台电脑，对性能要求一般的同学可参考配置：CPU i7低压、8G内存、机械硬盘+SSD，5000元以内足够。

### 该装什么软件？
Windows用户推荐使用[Dev-C++](https://sourceforge.net/projects/orwelldevcpp/files/latest/download)练习编程，Mac用户推荐使用Xcode。

### 我的程序怎么闪退了？
程序运行太快了，一下子就退出，来不及看清。可以在开头加上`#include <stdlib.h>`，`return`前加上`system("pause");`。

### 为什么编译时报告和“ld”有关的错误？
编译前请先关闭正在运行的程序，否则新生成的编译结果无法覆盖掉旧的正在运行的程序。

### 为什么我的程序行为很奇怪？
请按下表解决：

1.  重新逐字阅读一遍程序，检查是否有打错字、误用中文标点、printf或scanf漏写参数
2.  scanf的格式串中除了`%d`或`%f`等符号不要放任何其他东西，如逗号、换行符等
3.  输入数据时用空格或回车分开各个数
4.  关掉编译器，重新打开并编译，重新运行
5.  若问题仍存在，且你使用的不是Windows操作系统，请直接咨询助教
6.  找到键盘上的“Print Screen”键，也可能叫“PrnSc”或类似名字
7.  确保你的程序和编译器的报错或程序错误清晰地显示在屏幕上，然后按一下那个键
8.  你的屏幕截图已经被复制了，可以粘贴发送到群里提问
9.  进一步描述你做了什么、你期待看到什么、为什么当前的情形不符合你的期望

---

作业和实验等信息总是来不及更新，感觉也没人看 XD 就不放了
