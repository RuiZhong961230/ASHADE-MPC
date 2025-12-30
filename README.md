# ASHADE-MPC
Adaptive success history adaptive differential evolution with multi-agent participated competition mechanism

## Abstract
This paper proposes an efficient and improved variant of the success history adaptive differential evolution (SHADE), termed Adaptive SHADE with Multi-agent Participated Competition Mechanism (ASHADE-MPC). The proposed ASHADE-MPC incorporates two key components: (1) a Multi-agent Participated Competition (MPC) mechanism and (2) an adaptive mutation probability. The incorporated MPC mechanism enhances search efficiency and stability by integrating two powerful mutation strategies: DE/cur-to-/1 and DE/cur-to-/1. Additionally, ASHADE-MPC dynamically adjusts the implementation of DE/best/1 and the multi-agent competition mechanism through a switching probability P to balance local exploitation and global exploration at different optimization stages effectively. Extensive experiments in CEC2017, CEC2020, CEC2022, and seven engineering problems against eleven state-of-the-art optimizers demonstrate the superiority and domination of ASHADE-MPC in different optimization challenges. Furthermore, we apply ASHADE-MPC to the ensemble learning domain to detect the coffee leaf disease, where three high-accuracy deep learning models are fused using an ASHADE-MPC-optimized soft voting scheme. Experimental results confirm that the proposed ASHADE-MPC-Ensemble approach improves the accuracy of 0.952% in accuracy, 0.938% in precision, 0.952% in recall, and 0.952% in F1-score compared to the second-best model, Swin Transformer, which highlights the effectiveness and applicability of ASHADE-MPC in real-world scenarios. The source code of this research can be found at https://github.com/RuiZhong961230/ASHADE-MPC.

## Citation

@article{Wang:26,
title={Adaptive success history adaptive differential evolution with multi-agent participated competition mechanism},
author={Zhongmin Wang and Qifang Luo and Chuan Zhang and Shiwei Chen and Jun Yu and Mahmoud Abdel-Salam and Rui Zhong and Daihong Li},
journal={Cluster Computing},
pages={1-43},
year={2026},
volume={29},
publisher={Springer},
doi={https://doi.org/10.1007/s10586-024-04988-1}  
}

## Datasets and Libraries
CEC benchmarks are provided by opfunu==1.0.0, engineering problems are provided by enoppy==0.1.1, and the dataset of the coffee leaf disease can be downloaded at https://www.kaggle.com/datasets/gauravduttakiit/coffee-leaf-diseases.

## Contact
If you have any questions, please don't hesitate to contact zhongminwang@ynau.edu.cn or zhongrui[at]iic.hokudai.ac.jp
