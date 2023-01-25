# 工具的下载与安装

## R语言的安装
### https://cran.rstudio.com/ ，安装适用于电脑系统的R语言，安装镜像一般使用清华大学镜像
## Rstudio安装
### 在安装R之后安装Rstudio，Rstudio是广泛使用的R语言IDE，网址：https://posit.co/download/rstudio-desktop/
## Jupyter notebook/Jupyter Lab
### Jupyter是数据科学领域常用的IDE，支持多种语言，能直观地显示输出结果，一般通过Anaconda安装 https://www.anaconda.com/
### Jupyter 配置R环境：参考教程 https://blog.csdn.net/ccgcccccc/article/details/90273238

# 包的下载：
## 心理学中的绝大部分数据分析操作都可以找到对应的包，对于我们这种计算机菜鸡来说，调用包和使用包的功能，足以满足大部分的需求
## 一般可以直接使用install.packages("包名")进行安装
## 对于未在scan上发布的包或者下载失败的包可以手动下载，再通过Rstudio中的安装本地包的功能进行安装,建议在安装前先安装依赖的包
## 除此之外，还可以使用git工具从GitHub上下载相关的R语言包



# 不得不推荐的神包，非常值得学习：
## bruceR  
描述性统计分析，相关分析，ANOVA，中介....涵盖的功能很多，而且输出的结果非常清晰，比如相关分析，只需要导入数据集，就可以直接输出两两变量之间的相关系数、p值、置信区间和相关矩阵，非常省心

## lavaan
结构方程模型的不二之选,语法简单，功能强大，一个包等于Mplus.

## ggplot
绘图包

## psych 
描述性统计分析、相关分析、主成分分析等

## Dplyr、tidyr、tidyverse
数据清洗

## 其他的包可以根据自己的需求在R语言官网或者github上搜索，例如混合效应模型常用包lme4、文本分析包jieba等


# 好用的资料
## 公众号：荷兰心理统计联盟，老俊俊的生信笔记，萜心话 ，Rstata
## 网站：
https://r-graph-gallery.com/
https://rweekly.org/
CSDN,Github


# <font color=Red>多使用help函数</font> 
