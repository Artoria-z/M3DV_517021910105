# M3DV_517021910105
这是我的机器学习大作业的代码。为防止数据集的二次传播，数据没有存放在这里（详见“注意事项”）。

# 代码说明
直接运行test.py 可在本目录下生成最终的提交文件"submission.csv"。

test.py中有大段注释的内容即为训练模型所用的代码。

所用的DenseNet模型参考自https://github.com/titu1994/DenseNet/

# 注意事项

数据存放要求：将名为"train_val"和"test"的两个文件夹直接存储于此目录下，其中分别存放465个训练数据和117个测试数据。（或者可以修改main.py文件中第14行、第17行的数据存放目录地址）

另外，"train_val.csv"(表头为"Id"和"label")和"sampleSubmission.csv"(表头为"Id"和"Predicted")也应直接存放于此目录下。
