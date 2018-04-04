## Algorithm    :   KNN
**Description** ：k近邻算法采用测量不同特征值之间的距离方法进行分类。

## Appendix 1: NumPy
    
### sum函数

    原型：
    sum(a, axis=None, dtype=None, out=None, keepdims=<class 'numpy._globals._NoValue'>)

**axis**: 维度轴

    eg:
    numpy.array : c(2,3,4) shape: (2,3,4)
    axis=0:在第一个dimension上进行求和，计算后shape:(3,4),计算方法: s[j,k]=∑i(c[i,j,k])

    axis=1:在第二个dimension上进行求和，计算后shape:(2,4),计算方法：s[i,k]=sumj(c[i,j,k])

    axis=2，在第三个dimension上进行求和，计算后shape:(2,3)，计算方法： s[i,j]=sumk(c[i,j,k])

    高维数据以此类推
