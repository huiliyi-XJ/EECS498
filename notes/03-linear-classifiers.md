# Lecture 3: Linear Classifiers

> 📅 日期:  

## 📌 本节要点
- Algebraic / Visual / Geometric viewpoints
- Softmax classifier
- SVM classifier

## 📝 笔记

### 1. 线性分类器的三种视角
代数角度/视觉角度/几何角度

### 2. SVM 分类器
正确类别的分数应该比所有错误类别的分数高出一个安全间隔（margin）
如果正确类别的分数已经足够高（比其他类高出至少 margin），则损失为 0；否则就产生惩罚。

但是很可能对于不同的权重矩阵，有一样的 loss
所以不能很好的表达对这些权重的偏好

### 3. Softmax 分类器
L2正则化：惩罚大的权重值，防止模型过拟合（over fitting）
更像是一种对模型的提示，我们喜欢什么样的矩阵。
有很多不同类型的正则化。

### 4. 交叉熵损失 cross-entropy loss
正确标签：小概率-->大损失

## ❓ 疑问与思考


## 📖 补充阅读
- [ ] [CS231n Linear Classification](https://cs231n.github.io/linear-classify/)
