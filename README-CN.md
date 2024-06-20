# 之江实验室大语言模型训练日志项目
## 概述
由之江实验室发布的**之江实验室大语言模型训练日志项目**，提供了从之江实验室大规模智算集群中所获取的LLM训练日志信息和集群网络数据，旨在帮助研究人员、学生、各人开发者等更深入地理解LLM训练过程中的通信行为，特别是集群网络内部的流量信息。

目前，该项目已发布若干大规模集群的LLM训练日志和流量信息。已提供的日志信息包括：
- `cluster-2000-A100`：包含了大语言模型（LLM）任务的训练日志和集群网络流量数据。该集群包含2000个A100 GPU和带宽为 200Gbps 的 Spine-Leaf 架构无损以太网。关于这部分数据的详细介绍，请查看相关文档（[cluster_2000_A100](./cluster_2000_A100/cluster_2000_A100.md)）。在完成简短的问卷后即可下载该数据集（[问卷链接](https://forms.gle/2K66hHB4ZovQ5Cjn7)）。


## 引用
如果您在研究中使用了该数据，请按照以下格式引用：
```latex
@misc{ZJ2024traces,
 author = {Zhejiang Lab},
 title = {Zhejiang Lab LLM Trace Program},
 year = {2024},
 howpublished = {\url{https://github.com/zhejianglab/Zhejiang-Lab-Cluster-Traces}},
 note = {Accessed: 2024-06-20}
}
```

如果您使用这些数据发表了研究成果，请告知我们，我们会维护一个相关出版物的列表，以促进研究人员更好的沟通。随着之江实验室万卡规模智算集群的建设，我们将会发布更多的数据。如果您需要特定集群的数据，请告知我们。

## 许可证 

![Creative Commons CC-BY license](https://i.creativecommons.org/l/by/4.0/88x31.png) 本仓库的数据在[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh-hans)许可下提供。从该仓库下载并使用数据意味着您同意我们的[使用条款](./Terms%20of%20Access%20使用条款.pdf)。

## 联系我们
我们鼓励每个人使用这些数据进行学习或研究。如果您在使用数据时有任何问题，请通过电子邮件与我们联系，邮箱地址为[Zhejiang Lab](mailto:zhejianglab-clustertrace@zhejianglab.com) 或 [Tongyu](mailto:tongyusong@zhejianglab.com)（Tongyu 为之江实验室高效能计算系统研究中心工作人员，负责维护此存储库）。
