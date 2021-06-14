# 第四章 shell脚本编程实验

## 一、实验目的

熟悉shell编程的基本语法

完成所给任务

## 二、实验环境

Ubuntu 20.04

vscode

## 三、实验内容

### · 任务一：用bash编写一个图片批处理脚本，实现以下功能

支持命令行参数方式使用不同功能  √

支持对指定目录下所有支持格式的图片文件进行批处理 √

支持以下常见图片批处理功能的单独使用和组合使用 √

​    支持对jpeg格式图片进行图片质量压缩 √

​    支持对jpeg/png/svg格式图片在保持原始宽高比的前提下压缩分辨率 √

​    支持对图片批量添加自定义文本水印 √

​    支持批量重命名（统一添加文件名前缀或后缀，不影响原始文件拓展名）√

​    支持将png/svg图片统一转换为jpg格式图片 √

#### ·任务二：用bash编写一个文本批处理脚本，对以下附件分别进行批处理完成相应的数据统计任务

2014世界杯运动员数据

​    统计不同年龄区间范围（20岁以下、[20-30]、30岁以上的球员数量、百分比 √

​    统计不同场上位置的球员数量、百分比 √

​    名字最长的球员是谁？名字最短的球员是谁？√

​    年龄最大的球员是谁？年龄最小的球员是谁？√

#### ·任务三：用bash编写一个文本批处理脚本，对以下附件分别进行批处理完成对应的数据统计任务

web服务器访问日志

​    统计访问来源主机TOP100 和分别对应出现的总次数 √

​    统计访问来源主机TOP100 IP和分别对应出现的总次数 √

​    统计最频繁被访问的URL TOP100 √

​    分别统计不同响应状态码的出现次数和对应百分比 √

​    分别统计不同4XX状态码对应的TOP 10 URL和对应出现的总次数 √

​    给定URL输出TOP 100访问来源主机 √

## 四、实验步骤

### ·任务一

1、安装imagemagick和shellcheck

```
sudo apt-get update
sudo apt-get install -y shellcheck
sudo apt-get install imagemagick
```

2、上传照片

3、编写脚本

4、完成测试任务

### ·任务二

1、下载所需文件

 [数据文件]( https://c4pr1c3.gitee.io/linuxsysadmin/exp/chap0x04/worldcupplayerinfo.tsv)

2、编写脚本

3、完成测试任务 【任务二.md】

### ·任务三

1、安装 p7zip-full

```
sudo apt-get install p7zip-full
```

2、下载所需文件

[数据文件](https://c4pr1c3.gitee.io/linuxsysadmin/exp/chap0x04/worldcupplayerinfo.tsv)

3、编写脚本

4、完成测试任务【任务三.md】

## 五、参考文献

[CUCCS/linux-2020-LyuLumos](https://github.com/CUCCS/linux-2020-LyuLumos)

[awk官方文档](https://www.gnu.org/software/gawk/manual/html_node/History.html#History)

[shell编程](https://www.runoob.com/linux/linux-shell.html)

[linux sort 命令](https://www.runoob.com/linux/linux-comm-sort.html)

