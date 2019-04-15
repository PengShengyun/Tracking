# 统一的测试平台与标准
# OTB (Object Tracking Benchmark)
---
## *Abstract*
- the set of sequences is often not sufficient or is biased
- construct a large dateset with groundtruth object positions and introduce the sequence attributes  
- integrate most of the trackers into one code library  
- evaluate 31 algorithms on 100 sequences, identify effective approaches

---
## *Introduction*
- 大部分已有的trackers评判的指标不同，评判使用的视频也不同，追踪器的输入也不同，视频的groundtruth(gt)标注的结果也不一样，因此无法对比追踪器的优劣
- 由于追踪算法都是给定第一帧的目标gt，后续帧通过追踪器给出，因此第一帧尤为重要，为了减少算法对于第一帧的敏感程度，我们提出了在时间上和空间上重新初始化第一帧
- 全文贡献：  
1.标注了100个视频，适合单目标追踪  
2.编写了代码仓库，提供了统一的视频评价接口  
3.提出了新的评价指标  

## *Brief review of object tracking*
