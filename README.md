#简单说明

### Hadoop任务分配

#### 整个系统的结构层次

****

1. org.apache.hadoop.fs包总述
2. Hadoop文件系统概述(类层次结构, 输入输出流 )
3. FileSystem深入分析(fs中的接口, FileSystem, FilterFileSystem, ChecksumFileSystem, LocalFileSystem)
4. 输入输出流分析(FSInputStream抽象类, 输出流, FSInputChecker, FSOutputSummer, FSDataInputStream, FSDataOutputStream)
5. AbstractFileSystem分析(AbstractFileSystem抽象类, FilterFs抽象类, ChecksumFs抽象类, LocalFs类, DelegateToFileSystem抽象类, FileContext类)
6. 其它类(Hadoop Shell命令, 杂类)

目前的新的任务分配

- org.apache.hadoop.fs包总述     我
- Hadoop文件系统概述             我
- FileSystem深入分析             刘培新 陈广欣
- 输入输出流分析                 李冬冬
- AbstractFileSystem分析         郭庆 任雅丽
- 其它类                         黄逸斌 陈鹏（同时最后画出UML）

**该划分是按照随代码给的PDF得出的，所以可以根据PDF的内容进行分析，具体每个部分需要看哪些文件就自己去找了**

****
第一阶段的时间可以持续到
**5月25日** 
