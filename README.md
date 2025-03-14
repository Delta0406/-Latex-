# 西北工业大学专业硕士学位论文Latex模板
本仓库主要基于开源库[Yet-Another-LaTeX-Template-for-NPU-Thesis](https://github.com/NWPUMetaphysicsOffice/Yet-Another-LaTeX-Template-for-NPU-Thesis)进行修改，旨在修改专业硕士学位论文模板存在的一些问题。此外，还对学术学位硕士模板和专业硕士学位论文模板存在的共性问题进行了修改。具体修改说明如下：
## 一、学术学位硕士论文和专业学位硕士论文存在的共性问题
### 1.中文内封“题目：xxx”，“：”出现在横线上方
<img src="Yet-Another-LaTeX-Template-for-NPU-Thesis-master/preview/中文内封题目.png" width="60%">


### 2，英文封面“Title”缺失、加粗和日期格式问题
<img src="Yet-Another-LaTeX-Template-for-NPU-Thesis-master/preview/英文封面.png" width="60%">


## 二、专业学位硕士论文存在的问题
### 1.专业名前面是“专业领域”而非“学科专业”
<img src="Yet-Another-LaTeX-Template-for-NPU-Thesis-master/preview/中文外封.png" width="60%">
<img src="Yet-Another-LaTeX-Template-for-NPU-Thesis-master/preview/中文内封专业领域.png" width="60%">

## 三、其他建议
### 1.不生成图表目录
学校指南没有图表目录的要求，如想要生成这两个目录，需要注意图表命名的统一，例如“示例”和“示例图”。
### 2.摘要关键词写五个
### 3.尽量不要在.tex文件中引入.cls文件中已经引入的包
如果在.tex文件中引入.cls文件中已经引入的包，可能导致图表的格式与模板原格式不一致，尤其是行间距、表字体和横线粗细。
### 4.总结和展望放在一章
这两个分别写一章篇幅不够，不够美观。
## 四、参考模板
```
@software{NWPUThesisLaTeXTemplate,
    title       = {Yet Another {{\LaTeX}} Template for NPU Thesis},
    author      = {Shangkun Shen and Zhihe Wang and Jiduo Zhang and Weijia Zhang},
    month       = {11},
    year        = {2019},
    publisher   = {Zenodo},
    journal     = {GitHub repository},
    doi         = {10.5281/zenodo.4159248},
    url         = {https://doi.org/10.5281/zenodo.4159248}
}
```



