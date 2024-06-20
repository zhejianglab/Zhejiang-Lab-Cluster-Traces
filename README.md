# Zhejiang Lab LLM Trace Program
[中文版说明](./README-CN.md)
## Overview
The *Zhejiang Lab LLM Trace Program*, published by Zhejiang Lab, offers large language model (LLM) training traces from our large-scale clusters and the traffic data of the cluster network. This program aims to help researchers, students, and people gain a deeper understanding of communication behavior during LLM training, particularly focusing on traffic information within the cluster network.

The program will gradually release LLM training logs and traffic information from several large-scale clusters. So far, the following traces have been made available:

- `cluster_2000_A100` includes LLM tasks' training logs and cluster network traffic data.The cluster consists of 2000 A100 GPUs and a lossless Ethernet with a Spine-Leaf architecture with a bandwidth of 200Gbps. To see more about this trace, see related documents ([cluster_2000_A100](./cluster_2000_A100/cluster_2000_A100.md)).  Download link is available after a short survey ([survey link](https://forms.gle/2K66hHB4ZovQ5Cjn7)).


We encourage everyone to use the logs and traces for study or research purposes. If you have any questions while using the trace data, please contact us via email at [Zhejiang Lab](mailto:zhejianglab-clustertrace@zhejianglab.com) or [Tongyu](mailto:tongyusong@zhejianglab.com) (Tongyu maintains this repository and works for zhejianglab's research center for high efficiency computing system), or submit an issue on GitHub. Submitting an issue is recommended as it benefits the entire community through open discussion.

If you use this traces in your research, please cite it as follows:
```latex
@misc{ZJ2024traces,
 author = {Zhejiang Lab},
 title = {Zhejiang Lab LLM Trace Program},
 year = {2024},
 howpublished = {\url{实际项目链接}},
 note = {Accessed: 2024-06-20}
}
```

We kindly request that you inform us when any publications utilizing our trace data become available. We maintain a list of related publications to facilitate better communication among researchers.  As the lab cluster construction progresses, more data will be released. If you need specific data from the cluster, please let us know. 

## License

![Creative Commons CC-BY license](https://i.creativecommons.org/l/by/4.0/88x31.png)
The data and trace documentation are made available under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Downloading and using the data from this repository implies your agreement to our [Terms of Access](./Terms%20of%20Access%20使用条款.pdf).