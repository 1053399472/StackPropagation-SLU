# NOTICE

本仓库基于原论文作者的代码pytorch实现进行修改.利用该模型在CAIS数据集以及重新划分好的SMP数据集进行了训练。相关模型已经保存在save目录下，训练的参数同原作者保持一致。

相关结果如下：

| detasets | Slot(F1) | Intent(Acc) | Overall(Acc) |
| :------: | :------: | :---------: | :----------: |
|   CAIS   |  87.65   |    94.57    |    84.68     |
| SMP2019  |  78.91   |    94.44    |    72.59     |
| SMP2020  |  82.50   |    94.03    |    76.15     |