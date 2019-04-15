# 评价
# Siamese region proposal network (Siamese-RPN)
---
## *Abstract*
- Siamese subnetwork  
- RPN subnetwork  
- discard traditional multi-scale test and online fine-tuning

---
## *Introduction*
- 追踪算法主要分两大派：相关滤波类和深度学习类  
- 相关滤波主要在频域进行追踪，采用了FFT，并且可以在线更新追踪器，效率十分高  
- 深度学习的算法由于提取了深度特征精确度高，但是速度慢  
- 本文提出了SiamRPN，依然保留Siam的两支


## *Related Work*