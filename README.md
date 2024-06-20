# Zhejiang Lab LLM Trace Program
[中文版说明](./README-CN.md)
## Overview
The *Zhejiang Lab LLM Trace Program*, published by Zhejiang Lab, offers large language model (LLM) training traces derived from our large-scale clusters, along with traffic data from the cluster network. This program is designed to facilitate a comprehensive comprehension of communication behavior during LLM training, with a specific emphasis on analyzing traffic information within the cluster network. It aims to benefit researchers, students, and individuals seeking to enhance their understanding in this domain.

The program will progressively release LLM training logs and traffic information from multiple large-scale clusters. Currently, the following traces have been made accessible:

- `cluster_2000_A100` includes LLM tasks' training logs and cluster network traffic data.The cluster consists of 2000 A100 GPUs and a lossless Ethernet with a Spine-Leaf architecture with a bandwidth of 200Gbps. To see more about this trace, see related documents ([cluster_2000_A100](./cluster_2000_A100/cluster_2000_A100.md)).  Download link is available after a short survey ([survey link](https://forms.gle/2K66hHB4ZovQ5Cjn7)).


We encourage everyone to use the logs and traces for study or research purposes. If you have any questions while using the trace data, please feel free to contact us via email at [Zhejiang Lab](mailto:zhejianglab-clustertrace@zhejianglab.com) or [Tongyu](mailto:tongyusong@zhejianglab.com)  (Tongyu is responsible for maintaining this repository and is affiliated with Zhejiang Lab's research center for high-efficiency computing systems). Alternatively, you can submit an issue on GitHub. Submitting an issue is recommended as it benefits the entire community through open discussion.

If you use this traces in your research, please cite it as follows:
```latex
@misc{ZJ2024traces,
 author = {Zhejiang Lab},
 title = {Zhejiang Lab LLM Trace Program},
 year = {2024},
 howpublished = {\url{https://github.com/zhejianglab/Zhejiang-Lab-Cluster-Traces}},
 note = {Accessed: 2024-06-20}
}
```

We kindly request that you inform us when any publications utilizing our trace data are published. We maintain a list of related publications to enhance communication among researchers. As the construction of the cluster progresses, more data will be released. If you require specific data from the cluster, please let us know. 

## License

![Creative Commons CC-BY license](https://i.creativecommons.org/l/by/4.0/88x31.png)
The data and trace documentation are made available under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Downloading and using the data from this repository implies your agreement to our [Terms of Access](./Terms%20of%20Access%20使用条款.pdf).
