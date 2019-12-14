---
url: 01-readme
public: 1
---

# 前言

[![HitCount](http://hits.dwyl.io/XSLiuLab/XSLab-docs.svg)](http://hits.dwyl.io/XSLiuLab/XSLab-docs)

**放宽眼界，摆低姿态。认真学习，踏实研究**。

在语雀阅读：<https://www.yuque.com/shixiangwang/gucm2q>

***

在正式做研究之前，读一读理查德·汉明[《你和你的研究》](http://www.ruanyifeng.com/blog/2016/04/you-and-your-research.html)。

在提问之前，读一读[《提问的艺术》](https://www.oschina.net/question/124879_45870)。

***

生物信息学作为一门交叉学科，所需要掌握的知识呈现多、乱、杂的状态。为增强知识的系统性学习和检索，由Liulab分析成员一起编辑本仓库，提供入门建议和分类知识的Roadmap，帮助初学者快速入门，同时也帮助自身记录和分享知识。

***


## 入门建议

生物信息学学习有4块核心：

* Linux操作系统知识
* 数据处理编程语言
* 统计学
* 研究背景

研究背景是工作的方向，但对于一个研究生而言课题常常由导师指定，因此该部分的学习一般是通过阅读文献和自己对于课题的探索而逐步深入的。

统计学在生物信息学乃至生物学中都是极为核心的一部分，不过当前科学界普遍存在p值的滥用和缺乏一些深厚的统计学素养，因此学习时应当额外注意对统计基本概念的理解，应当掌握**假设检验**、**p值**、**置信区间**、**参数检验与非参数检验**、**多重校正**等知识。这些知识可以通过大学本科的概率论与数理统计教材以及生物统计学教材获得，另可参考[生物统计学与R手册](https://github.com/ShixiangWang/Handbook_of_biostatistic_R)。

Linux操作系统知识可以分为两块：一是基本的Linux操作与管理，可参考[《鸟哥的私房菜-基础篇》](http://cn.linux.vbird.org/linux_basic/linux_basic.php)进行学习；二是Linux Shell编程，用以处理文本数据流，可参考《[优雅的Linux>>Shell笔记与探索](https://www.jianshu.com/nb/13897796)》进行学习。《[Linux数据处理命令工具](https://www.shixiangwang.top/post/2017-09-03-linux-data-analysis-tools/)》一文有一些重要Linux命令的讲解。

最后，学习和使用数据处理编程语言一般是工作的核心。目前主流有2门用于生信领域的语言：Python和R。学习应以其中一门为主，下面列出一些参考书目。

Python:

* [《利用Python进行数据分析》](https://www.jianshu.com/nb/19743417)
* 《Bioinformatics with Python Cookbook》
* [《Python for Bioinformatics》](https://github.com/XSLiuLab/Py4Bio)

R:

* [《R for Data Science》](http://r4ds.had.co.nz/)（不推荐看中文，翻译的不好）
* 《R实战》第二版
* 《R语言编程艺术》

最后推荐一些资源仓库：

* [Unix, R and python tools for genomics and data science](https://github.com/XSLiuLab/getting-started-with-genomics-tools-and-resources)
* [Bioinformatics one-liners](https://github.com/XSLiuLab/oneliners)

## Roadmap

* [操作系统](OS/README.md) - 操作系统知识与问题的方案
* [工具包与数据库](Tools/README.md) - 科研与生信分析软件（工具包）、数据库
* [Markdown与Notebook](Markdown/README.md) - 如何进行知识的记录与分享
* [癌症研究](Cancer-research/README.md) - 癌症研究知识、分析流程汇总
* [awesome列表](Awesome-list/README.md) - awesome以及其他的资源合集
* [线上图书](Online-books/README.md) - 图书学习汇总与推荐
* [填坑笔记](Diary/README.md) - Liulab分析工作的填坑日常


## 云资源

- **生信入门资料集合** - 分享自生信技能树公众号，已转至百度云，链接: <https://pan.baidu.com/s/1mhHd8aG> 密码: vjxa
- Github入门与实战（中文版） - 链接: <https://pan.baidu.com/s/1nvgJWIP> 密码: ne2w
- RNA-seq Data Analysis-A Practical Approach - 链接: <https://pan.baidu.com/s/1eSPD4hs> 密码: y79f
- Python for Data Analysis(2nd Edition, Early Release) - 链接: <https://pan.baidu.com/s/1c1UleXq> 密码: s692
- 小张聊科研修炼手册 - 链接: <https://pan.baidu.com/s/1jIiRXhO> 密码: zu4n
- MySQL视频（尚观云） - 链接: <https://pan.baidu.com/s/1pLJV7b9> 密码: e6fg
- NIH的TCGA-topic大全 - 链接: <https://pan.baidu.com/s/1i4CzYoH> 密码: w9q4
- TCGA大文章 - 链接: <https://pan.baidu.com/s/1qXY6wI4> 密码: de2q
- sed与awk（修订第三版） - 链接: <https://pan.baidu.com/s/1qYqPz5a> 密码: 4ei4
- **北大生科院基因组学数据分析课程** - 链接：<https://share.weiyun.com/5UGqR2i>
- **StatQuest生物统计学** - 链接:<https://pan.baidu.com/s/1uOIfcsGdkTgddqzZ0-W6jQ>  密码:rabg

## Github仓库

### 基础学习

- [中国科学技术大学计算机学院课程资源](https://github.com/USTC-Resource/USTC-Course)
- [Unix, R and python tools for genomics and data science](https://github.com/XSLiuLab/getting-started-with-genomics-tools-and-resources)
- [Row-oriented workflows in R with the tidyverse](https://github.com/XSLiuLab/row-oriented-workflows)
- [Bioinformatics one-liners](https://github.com/XSLiuLab/oneliners)
- [bioconda教程中文版](https://github.com/XSLiuLab/bioconda-tutorial) - https://github.com/XSLiuLab/bioconda-tutorial
- [Data Analysis for the Life Sciences](https://github.com/XSLiuLab/labs) - I am reading. Online link <https://genomicsclass.github.io/book/>
- ["Python for Data Analysis" by Wes McKinney, published by O'Reilly Media](https://github.com/XSLiuLab/pydata-book)
- [Public data for the book Python for Bioinformatics](https://github.com/XSLiuLab/Py4Bio)
- [The lecture slides for Coursera's Data Analysis class](https://github.com/XSLiuLab/dataanalysis)
- [Statistical Rethinking: A Bayesian Course Using R and Stan](https://github.com/XSLiuLab/statrethinking_winter2019) - Statistical Rethinking course at MPI-EVA from Dec 2018 through Feb 2019
- [Modern Statistics for Modern Biology](https://www.huber.embl.de/msmb/) - by Susan Holmes, Wolfgang Huber


### 数据分析

- [RNA-seq-analysis](https://github.com/XSLiuLab/RNA-seq-analysis) - RNAseq analysis notes from Ming Tang
- [Informatics for RNA-seq: A web resource for analysis on the cloud](https://github.com/XSLiuLab/rnaseq_tutorial) 
- [A repository for setting up a RNAseq workflow](https://github.com/XSLiuLab/RNAseq-workflow)
- [DNA-seq-analysis](https://github.com/XSLiuLab/DNA-seq-analysis) - DNAseq analysis notes from Ming Tang
- [ChIP-seq-analysis](https://github.com/XSLiuLab/ChIP-seq-analysis) - ChIPseq analysis notes from Ming Tang

### Pipeline

- [NGS Pipeline](https://github.com/XSLiuLab/NGS-pipeline)

## 贡献

本仓库只允许 Xuesong Liu 课题组组内人员编辑与修改，其他人员可以提交 issue 或合并请求进行报告，经过审核后报告人将加入 Contributors。

> Please open an issue or pull request to contribute. Any suggestion is welcome.

## 许可协议

[Academic Free License version 3.0](https://opensource.org/licenses/AFL-3.0)

**非 Liulab 成员的研究工作如果使用到该仓库的文档或代码，请在文章中引用 Liulab 最新发表文章或致谢，谢谢。**

> If you feel this repository useful for your academic project, please cite our recent publications or acknowledge us.

## Contributors

