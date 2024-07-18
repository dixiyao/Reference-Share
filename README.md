# Reference-Share

## Privacy-Preserving ML
### Private Inference
#### Protocol Optimization
|Index|Paper | Link |
|:-----|:-----|:-----|
|1| Garimella, Karthik, Zahra Ghodsi, Nandan Kumar Jha, Siddharth Garg, and Brandon Reagen. **"Characterizing and optimizing end-to-end systems for private inference."** In Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 3, pp. 89-104. 2023. | https://arxiv.org/pdf/2207.07177|
|4 | Srinivasan, Wenting Zheng, P. M. R. L. Akshayaram, and Popa Raluca Ada. **"DELPHI: A cryptographic inference service for neural networks."** In Proc. 29th USENIX secur. symp, vol. 3. 2019.| |
|5 | Lou, Qian, Yilin Shen, Hongxia Jin, and Lei Jiang. **"Safenet: A secure, accurate and fast neural network inference."** In International Conference on Learning Representations. 2021. | https://openreview.net/pdf?id=Cz3dbFm5u-|
|6 | Jha, Nandan Kumar, Zahra Ghodsi, Siddharth Garg, and Brandon Reagen. **"Deepreduce: Relu reduction for fast private inference."** In International Conference on Machine Learning, pp. 4839-4849. PMLR, 2021.|
https://arxiv.org/pdf/2103.01396|
|7 |Cho, Minsu, Ameya Joshi, Brandon Reagen, Siddharth Garg, and Chinmay Hegde. **"Selective network linearization for efficient private inference."** In International Conference on Machine Learning, pp. 3947-3961. PMLR, 2022.|https://arxiv.org/pdf/2202.02340|
#### Neural Network Design
|Index|Paper | Link | Category|
|:-----|:-----|:-----|:-------|
|2|Cho, Minsu, Zahra Ghodsi, Brandon Reagen, Siddharth Garg, and Chinmay Hegde. **"Sphynx: A deep neural network design for private inference."** IEEE Security & Privacy 20, no. 5 (2022): 22-34.|https://arxiv.org/pdf/2106.11755|NAS|
|3|Ghodsi, Zahra, Akshaj Kumar Veldanda, Brandon Reagen, and Siddharth Garg. **"CryptoNAS: Private inference on a relu budget."** Advances in Neural Information Processing Systems 33 (2020): 16961-16971. | https://arxiv.org/abs/2006.08733|NAS|
|9|Jha, Nandan Kumar, and Brandon Reagen. **"Deepreshape: Redesigning neural networks for efficient private inference."** arXiv preprint arXiv:2304.10593 (2023). |https://openreview.net/pdf?id=iwCBWULItx| pruning|
#### Hardware Optimization
|Index|Paper | Link | Category|
|:-----|:-----|:-----|:----|
| 8 | Reagen, Brandon, Woo-Seok Choi, Yeongil Ko, Vincent T. Lee, Hsien-Hsin S. Lee, Gu-Yeon Wei, and David Brooks. "Cheetah: Optimizing and accelerating homomorphic encryption for private inference." In 2021 IEEE International Symposium on High-Performance Computer Architecture (HPCA), pp. 26-39. IEEE, 2021.|https://hsienhsinlee.github.io/MARS/pub/hpca2021-cheetah.pdf | HE |

## Efficient Machine Learning

### Neural Network Design
|Index|Paper | Link | Category|
|:-----|:-----|:-----|:-------|
|1| Shen, Maying, Hongxu Yin, Pavlo Molchanov, Lei Mao, Jianna Liu, and Jose M. Alvarez. **"Halp: hardware-aware latency pruning."** arXiv preprint arXiv:2110.10811 (2021).| https://arxiv.org/pdf/2110.10811| Pruning|

## General Large Models
### Large Language Models

#### Controllable Text Generation
|Index|Paper | Link | Note|
|:-----|:-----|:-----|:----|
|1|Dekoninck, Jasper, Marc Fischer, Luca Beurer-Kellner, and Martin Vechev. "Controlled text generation via language model arithmetic." arXiv preprint arXiv:2311.14479 (2023). |https://openreview.net/pdf?id=SLw9fp4yI6|Only inference needed|
|2|Chen, Yihan, Benfeng Xu, Quan Wang, Yi Liu, and Zhendong Mao. "Benchmarking large language models on controllable generation under diversified instructions." In Proceedings of the AAAI Conference on Artificial Intelligence, vol. 38, no. 16, pp. 17808-17816. 2024. |https://arxiv.org/pdf/2401.00690 | Large benchmark|
|3|Sun, Jiao, Yufei Tian, Wangchunshu Zhou, Nan Xu, Qian Hu, Rahul Gupta, John Wieting, Nanyun Peng, and Xuezhe Ma. "Evaluating Large Language Models on Controlled Generation Tasks." In Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing, pp. 3155-3168. 2023. |https://arxiv.org/pdf/2310.14542 | Evaluation metrics, benchmark|

#### Alignment
|Index|Paper | Link | Note|
|:-----|:-----|:-----|:----|
|4|Wang, Xinyuan, Chenxi Li, Zhen Wang, Fan Bai, Haotian Luo, Jiayou Zhang, Nebojsa Jojic, Eric Xing, and Zhiting Hu. "PromptAgent: Strategic Planning with Language Models Enables Expert-level Prompt Optimization." In The Twelfth International Conference on Learning Representations. |https://arxiv.org/pdf/2310.16427|Prompt Optimization|
|5|Liang, Tian, Zhiwei He, Wenxiang Jiao, Xing Wang, Yan Wang, Rui Wang, Yujiu Yang, Zhaopeng Tu, and Shuming Shi. "Encouraging divergent thinking in large language models through multi-agent debate." arXiv preprint arXiv:2305.19118 (2023). |https://arxiv.org/pdf/2305.19118 | Multi-agent debate, data synthesis|
|6|Deng, Yang, Lizi Liao, Liang Chen, Hongru Wang, Wenqiang Lei, and Tat-Seng Chua. "Prompting and evaluating large language models for proactive dialogues: Clarification, target-guided, and non-collaboration." arXiv preprint arXiv:2305.13626 (2023).|https://arxiv.org/pdf/2305.13626 | Proactive dialogues, survey|
|7|Abramson, Josh, Arun Ahuja, Federico Carnevale, Petko Georgiev, Alex Goldin, Alden Hung, Jessica Landon et al. "Evaluating multimodal interactive agents." arXiv preprint arXiv:2205.13274 (2022). |https://arxiv.org/pdf/2205.13274 | Evaluation, Multi-modal, Benchmark|

#### Long Context LM
|Index|Paper | Link | Note|
|:-----|:-----|:-----|:----|
|8 |Dong, Qingxiu, Lei Li, Damai Dai, Ce Zheng, Zhiyong Wu, Baobao Chang, Xu Sun, Jingjing Xu, and Zhifang Sui. "A survey on in-context learning." arXiv preprint arXiv:2301.00234 (2022). |https://arxiv.org/pdf/2301.00234 | ICL, survey|
|9 |Dong, Zican, Tianyi Tang, Lunyi Li, and Wayne Xin Zhao. "A survey on long text modeling with transformers." arXiv preprint arXiv:2302.14502 (2023).|https://arxiv.org/pdf/2302.14502| Long-context modeling, survey|
|10|Dong, Zican, Tianyi Tang, Lunyi Li, and Wayne Xin Zhao. "A survey on long text modeling with transformers." arXiv preprint arXiv:2302.14502 (2023). |https://arxiv.org/pdf/2405.07437 | RAG, survey|