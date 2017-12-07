# 实现代码
脚本我放在了script，需要看详细代码并优化的算法工程师同学，可以去查阅

# package
为了方便大数据工程师同学快速使用，我打包上传到了[pypi](https://pypi.python.org/pypi?:action=display&name=fast_risk_control&version=0.0.1)，直接使用`pip install fast_risk_control`下载即可
```
#加载包
from fast_risk_control import fast_risk_control

#使用方法
fast_risk_control.transform(data)
```


# example
快速上手的case，我写在了example文件夹下，需要的可以对照尝试，包括一些error和warning的解释

# 前置需要安装的包库要求
## [isolation forest地址](https://github.com/scikit-learn/scikit-learn/blob/master/sklearn/ensemble/iforest.py)
## [pandas、numpy下载地址](http://www.lfd.uci.edu/~gohlke/pythonlibs/)

# 理论文档：
论文在doc文件夹下，我之前个人分析过一两次，在我的博客地址：
[数据预处理-异常值识别](http://shataowei.com/2017/08/09/数据预处理-异常值识别/)
[多算法识别撞库刷券等异常用户](http://shataowei.com/2017/12/01/多算法识别撞库刷券等异常用户/)

# Release
#### 0.0.2 新增了保存信息提示
#### 0.0.3 当用户提供数据**量过小且差异不大**的时候提供了距离衡量判别方法