# <center>scikit-learn (sklearn) 官方文档中文版</center>

<center><img src="img/logo/scikit-learn-logo.png" alt="logo" /></center>

<br/>
<table>
    <tr align="center">
        <td><a title="sklearn 0.21.3[master] 中文文档" href="https://sklearn.apachecn.org/" target="_blank"><font size="5">sklearn 0.21.3 中文文档</font></a></td>
        <td><a title="sklearn 0.21.3[master] 中文示例" href="https://sklearn.apachecn.org/docs/examples" target="_blank"><font size="5">sklearn 0.21.3 中文示例</font></a></td>
        <td><a title="sklearn 英文官网" href="https://scikit-learn.org" target="_blank"><font size="5">sklearn 英文官网</font></a></td>
    </tr>
</table>
<br/>

---

## 介绍

sklearn (scikit-learn) 是基于 Python 语言的机器学习工具

1. 简单高效的数据挖掘和数据分析工具
2. 可供大家在各种环境中重复使用
3. 建立在 NumPy ，SciPy 和 matplotlib 上
4. 开源，可商业使用 - BSD许可证

## 目录

*   [安装 scikit-learn](docs/master/62.md)
*   用户指南
    *   [1. 监督学习](docs/master/1.md)
        * [1.1. 广义线性模型](docs/master/2.md)
        * [1.2. 线性和二次判别分析](docs/master/3.md)
        * [1.3. 内核岭回归](docs/master/4.md)
        * [1.4. 支持向量机](docs/master/5.md)
        * [1.5. 随机梯度下降](docs/master/6.md)
        * [1.6. 最近邻](docs/master/7.md)
        * [1.7. 高斯过程](docs/master/8.md)
        * [1.8. 交叉分解](docs/master/9.md)
        * [1.9. 朴素贝叶斯](docs/master/10.md)
        * [1.10. 决策树](docs/master/11.md)
        * [1.11. 集成方法](docs/master/12.md)
        * [1.12. 多类和多标签算法](docs/master/13.md)
        * [1.13. 特征选择](docs/master/14.md)
        * [1.14. 半监督学习](docs/master/15.md)
        * [1.15. 等式回归](docs/master/16.md)
        * [1.16. 概率校准](docs/master/17.md)
        * [1.17. 神经网络模型（有监督）](docs/master/18.md)
    *   [2. 无监督学习](docs/master/19.md)
        * [2.1. 高斯混合模型](docs/master/20.md)
        * [2.2. 流形学习](docs/master/21.md)
        * [2.3. 聚类](docs/master/22.md)
        * [2.4. 双聚类](docs/master/23.md)
        * [2.5. 分解成分中的信号（矩阵分解问题）](docs/master/24.md)
        * [2.6. 协方差估计](docs/master/25.md)
        * [2.7. 新奇和异常值检测](docs/master/26.md)
        * [2.8. 密度估计](docs/master/27.md)
        * [2.9. 神经网络模型（无监督）](docs/master/28.md)
    * [3. 模型选择和评估](docs/master/29.md)
        * [3.1. 交叉验证：评估估算器的表现](docs/master/30.md)
        * [3.2. 调整估计器的超参数](docs/master/31.md)
        * [3.3. 模型评估: 量化预测的质量](docs/master/32.md)
        * [3.4. 模型持久化](docs/master/33.md)
        * [3.5. 验证曲线: 绘制分数以评估模型](docs/master/34.md)
    * [4.  检验](docs/master/35.md)
        * [4.1. 部分依赖图](docs/master/36.md)
    * [5. 数据集转换](docs/master/37.md)
        * [5.1. Pipeline（管道）和 FeatureUnion（特征联合）: 合并的评估器](docs/master/38.md)
        * [5.2. 特征提取](docs/master/39.md)
        * [5.3 预处理数据](docs/master/40.md)
        * [5.4 缺失值插补](docs/master/41.md)
        * [5.5. 无监督降维](docs/master/42.md)
        * [5.6. 随机投影](docs/master/43.md)
        * [5.7. 内核近似](docs/master/44.md)
        * [5.8. 成对的矩阵, 类别和核函数](docs/master/45.md)
        * [5.9. 预测目标 (`y`) 的转换](docs/master/46.md)
    * [6. 数据集加载工具](docs/master/47.md)
        * [6.1. 通用数据集 API](docs/master/47.md)
        * [6.2. 玩具数据集](docs/master/47.md)
        * [6.3 真实世界中的数据集](docs/master/47.md)
        * [6.4. 样本生成器](docs/master/47.md)
        * [6.5. 加载其他数据集](docs/master/47.md)
    * [7. 使用scikit-learn计算](docs/master/48.md)
        * [7.1. 大规模计算的策略: 更大量的数据](docs/master/48.md)
        * [7.2. 计算性能](docs/master/48.md)
        * [7.3. 并行性、资源管理和配置](docs/master/48.md)
*   [教程](docs/master/50.md)
    *   [使用 scikit-learn 介绍机器学习](docs/master/51.md)
    *   [关于科学数据处理的统计学习教程](docs/master/52.md)
        *   [机器学习: scikit-learn 中的设置以及预估对象](docs/master/53.md)
        *   [监督学习：从高维观察预测输出变量](docs/master/54.md)
        *   [模型选择：选择估计量及其参数](docs/master/55.md)
        *   [无监督学习: 寻求数据表示](docs/master/56.md)
        *   [把它们放在一起](docs/master/57.md)
        *   [寻求帮助](docs/master/58.md)
    *   [处理文本数据](docs/master/59.md)
    *   [选择正确的评估器(estimator.md)](docs/master/60.md)
    *   [外部资源，视频和谈话](docs/master/61.md)
*   [API 参考](https://scikit-learn.org/stable/modules/classes.html)
*   [常见问题](docs/master/63.md)
*   [时光轴](docs/master/64.md)
