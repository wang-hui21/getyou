懂你
===
# 一．项目介绍<br> 
    一款懂你的陌生人社交APP<br> 
# 二. 项目内容<br> 
## 1.产品使用流程：<br> 
   ![image](https://raw.githubusercontent.com/fwdhz998/getyou/master/imgfolder/%E5%9B%BE%E7%89%871.png)
## 2.前端框架：
   ![image](https://raw.githubusercontent.com/fwdhz998/getyou/master/imgfolder/%E5%9B%BE%E7%89%872.png)
## 3.后端框架
   ![image](https://raw.githubusercontent.com/fwdhz998/getyou/master/imgfolder/%E5%9B%BE%E7%89%873.png)
## 4.算法框架：
   本项目算法框架由两部分构成，分别是用户标签过滤算法与情感分析算法，其中本项目主要完成用户标签过滤算法，情感分析算法由BosonNLP的API提供。<br> 
### 4.1标签过滤：
   用户的标签分为长期标签与短期标签，长期标签由引导页设置(共10类)，短期标签由用户的输入获得。通过长期标签的匹配与短期标签的匹配综合得出最“可能”的陌生人。<br>
### 4.2情感分析：
 情感分析算法的大体由基于Word2Vec的目标分类算法实现，本项目出于时间考虑直接选用API直接调用。在此基础上，做了进一步细致根据情感因子划分的匹配算法。<br>
