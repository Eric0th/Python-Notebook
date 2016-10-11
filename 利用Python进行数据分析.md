#利用Python进行数据分析

#####chp1 准备工作

重要的库
- Numpy 
是Python科学计算包的基础，为Python提供快速的数组处理能力，还可以作为在算法之间传递数据的容器
- pandas
提供处理结构化数据的大量数据结构和函数，和适用于金融数据的高性能时间序列功能和工具
- matplotlib
用于绘制图标的Python库
- SciPy
专门解决科学计算中各种标准问题域的包的集合
---

####chp附录A Python语言精要
1. Python通过空白符（制表符或空格）来组织代码，不同于其他语言使用大括号，例如
```Python
  for x in array:
    if x < pivot:
      less.append(x)
    else:
      greater.append(x)
```
2. 任何前缀为井号（#）的文本都会被Python解释器忽略掉，通常用于添加注释。有时想排除不运行某些代码而不像删除，也可以注释掉那些代码
3. 函数需要用圆括号
4. 在Python中对变量赋值时，其实是在创建等号右侧对象的一个引用
