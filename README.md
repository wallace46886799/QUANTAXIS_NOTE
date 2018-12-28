# QUANTAXIS_NOTE
QUANTAXIS的探险笔记

## Github的操作
### Fork项目的同步更新
https://blog.csdn.net/zhongzunfa/article/details/80344585  
https://blog.csdn.net/qq1332479771/article/details/56087333  
https://www.jianshu.com/p/840ea273f25a

## QUANTAXIS
### 行情服务
#### 交易行情
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/DataFetch.md
#### 财务数据
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/financial_means.md
#### 自定义数据源的数据
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/crawler.md
https://github.com/QUANTAXIS/QUANTAXIS/tree/774acf8650891da78653702069a52243b4fd524e/QUANTAXIS_CRAWLY


### 分析服务
#### 股票数据结构
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/DataStruct.md
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/analysis.md

#### 指标系统
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/indicators.md

### 事件框架
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/about_event.md

### 回测服务
在Jupyter中显示图片，输入 %matplotlib inline

### 实盘交易
http://www.iguuu.com/

### REST服务
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/backendapi.md

### 开发计划
https://github.com/QUANTAXIS/QUANTAXIS/blob/master/job_list.md


## QUANTAXIS应用
### 切换Python环境
source activate quantaxis

### 启动QUANTAXIS_WEBSERVER
cd $WORK/Frameworks/Python/QuantAxis/QUANTAXIS_WEBSERVER
quantaxis_webserver --port=8010

### 启动QADESKTOP
cd $WORK/Frameworks/Python/QuantAxis/QADESKTOP
npm run dev
