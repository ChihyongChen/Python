# Python学习整理
核心思想：“以用为主”、“站在巨人的肩膀上”。
### 常用网站
- [pip 清华源](https://mirrors.tuna.tsinghua.edu.cn/help/pypi/)。使用pip清华源安装库更快，比如安装 `jieba` 库：pip install -i https://mirrors.tuna.tsinghua.edu.cn/pypi/web/simple jieba。要安装其他库，就把 jieba 替换成相应的库名。
- [Anaconda 官网](https://www.anaconda.com/download)。下载安装包的时候，在右侧需要输入邮箱，便可以下载了。安装好的 `Anaconda` 默认安装了我们需要的 Spyder 软件。
## 一、基础知识
### 1. 程序设计语言
- 机器语言
- 汇编语言
- 高级语言
- **注意:** 自然语言不是程序设计语言，我们的课程经常遇到
### 2. `Python`模块
#### Python模块（Module），是一个 Python 文件
- `Python` 默认安装仅包含基本模块
- `Spyder` 仅加载基本模块
- 需要时再导入和加载标准库和第三方扩展库
#### 库是具有相关功能模块的集合
- `Python` 具有强大的标准库、第三方库、自定义模块
  - 标准库：下载安装的`python`里那些自带的模块
  - 第三方库：是由第三方机构发布的具有特定功能的模块，也叫扩展库 
  - 自定义模块：是用户自己可以自行编写并使用的模块
#### 3. 模块导入
```python
#示例
import pandas as pd
from pandas import DataFrame as DF
#pandas 是一个模块名
#DataFrame 是一个方法
#导入模块
import （模块名）
#使用了别名，就不能用原名
import （模块名） as （别名） 
#导入模块中的方法（函数）
from （模块名） import （方法）
#使用了别名，就不能用原名
from （模块名） import （方法） as （方法别名） 
```
## 三、数据类型