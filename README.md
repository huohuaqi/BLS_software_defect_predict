# BLS_software_defect_predict
用宽度学习在promise数据集的软件度量上面实现二分类


BLS Code
the related introduction could be find at https://blog.csdn.net/Liangjun_Feng/article/details/80541689
the code is according to the paper "Broad Learning System: An Effective and Efficient Incremental Learning System Without the Need for Deep Architecture"


PROMISE数据集
https://github.com/feiwww/PROMISE-backup

本项目的结构
promise_dataset 数据集

bug_*.py  四种方法的对比lr svm nn bls

tool_*.py  一些工具，例如读取数据 计算f1 等

实验环境：python3.6， tensorflow-2.3

