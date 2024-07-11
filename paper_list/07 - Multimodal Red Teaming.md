# Multimodal Red Teaming
## Table of Contents
- Multimodal Red Teaming
	 - [Attack Strategies](#attack-strategies)
		 - [Completion Compliance](#completion-compliance)
		 - [Instruction Indirection](#instruction-indirection)
	 - [Attack Searchers](#attack-searchers)
		 - [Image Searchers](#image-searchers)
		 - [Cross Modality Searchers](#cross-modality-searchers)
		 - [Others](#others)
	 - [Defense](#defense)
		 - [Guardrail Defenses](#guardrail-defenses)
		 - [Other Defenses](#other-defenses)
	 - [Application](#application)
		 - [Agents](#agents)
	 - [Benchmarks](#benchmarks)
## Attack Strategies
### Completion Compliance
### Instruction Indirection
- **On the Robustness of Large Multimodal Models Against Image Adversarial Attacks** \[[Paper](https://arxiv.org/abs/2312.03777)\] <br />
Xuanming Cui,  Alejandro Aparcedo,  Young Kyun Jang,  Ser-Nam Lim (2023)<br />
- **Visual Adversarial Examples Jailbreak Aligned Large Language Models** \[[Paper](https://arxiv.org/abs/2306.13213)\] <br />
Xiangyu Qi,  Kaixuan Huang,  Ashwinee Panda,  Peter Henderson,  Mengdi Wang,  Prateek Mittal (2023)<br />
- **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** \[[Paper](https://arxiv.org/abs/2307.14539)\] <br />
Erfan Shayegani,  Yue Dong,  Nael Abu-Ghazaleh (2023)<br />
- **Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs** \[[Paper](https://arxiv.org/abs/2307.1049)\] <br />
Eugene Bagdasaryan,  Tsung-Yin Hsieh,  Ben Nassi,  Vitaly Shmatikov (2023)<br />
- **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** \[[Paper](https://arxiv.org/abs/2311.05608)\] <br />
Yichen Gong,  Delong Ran,  Jinyuan Liu,  Conglei Wang,  Tianshuo Cong,  Anyu Wang,  Sisi Duan,  Xiaoyun Wang (2023)<br />
- **Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks** \[[Paper](https://arxiv.org/abs/2402.00626)\] <br />
Maan Qraitem,  Nazia Tasnim,  Piotr Teterwak,  Kate Saenko,  Bryan A. Plummer (2024)<br />
- **Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2403.09792)\] <br />
Yifan Li,  Hangyu Guo,  Kun Zhou,  Wayne Xin Zhao,  Ji-Rong Wen (2024)<br />
- **From LLMs to MLLMs: Exploring the Landscape of Multimodal Jailbreaking** \[[Paper](https://arxiv.org/abs/2406.14859
   )\] <br />
Siyuan Wang,  Zhuohan Long,  Zhihao Fan,  Zhongyu Wei (2024)<br />
- **Unveiling the Safety of GPT-4o: An Empirical Study using Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2406.06302
   )\] <br />
Zonghao Ying,  Aishan Liu,  Xianglong Liu,  Dacheng Tao (2024)<br />
- **Image-to-Text Logic Jailbreak: Your Imagination can Help You Do Anything** \[[Paper](https://arxiv.org/abs/2407.02534
   )\] <br />
Xiaotian Zou,  Yongkang Chen (2024)<br />
- **Cross-Modality Jailbreak and Mismatched Attacks on Medical Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2405.20775
   )\] <br />
Xijie Huang,  Xinyuan Wang,  Hantao Zhang,  Jiawen Xi,  Jingkun An,  Hao Wang,  Chengwei Pan (2024)<br />
- **InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models** \[[Paper](https://arxiv.org/abs/2312.01886)\] <br />
Xunguang Wang,  Zhenlan Ji,  Pingchuan Ma,  Zongjie Li,  Shuai Wang (2023)<br />
- **Voice Jailbreak Attacks Against GPT-4o** \[[Paper](https://arxiv.org/abs/2405.19103
   )\] <br />
Xinyue Shen,  Yixin Wu,  Michael Backes,  Yang Zhang (2024)<br />
## Attack Searchers
### Image Searchers
- **Diffusion Attack: Leveraging Stable Diffusion for Naturalistic Image Attacking** \[[Paper](https://arxiv.org/abs/2403.14778)\] <br />
Qianyu Guo,  Jiaming Fu,  Yawen Lu,  Dongming Gan (2024)<br />
- **On the Adversarial Robustness of Multi-Modal Foundation Models** \[[Paper](https://arxiv.org/abs/2308.10741)\] <br />
Christian Schlarmann,  Matthias Hein (2023)<br />
- **How Robust is Google's Bard to Adversarial Image Attacks?** \[[Paper](https://arxiv.org/abs/2309.11751)\] <br />
Yinpeng Dong,  Huanran Chen,  Jiawei Chen,  Zhengwei Fang,  Xiao Yang,  Yichi Zhang,  Yu Tian,  Hang Su,  Jun Zhu (2023)<br />
- **Test-Time Backdoor Attacks on Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2402.08577)\] <br />
Dong Lu,  Tianyu Pang,  Chao Du,  Qian Liu,  Xianjun Yang,  Min Lin (2024)<br />
### Cross Modality Searchers
- **MMA-Diffusion: MultiModal Attack on Diffusion Models** \[[Paper](https://arxiv.org/abs/2311.17516)\] <br />
Yijun Yang,  Ruiyuan Gao,  Xiaosen Wang,  Tsung-Yi Ho,  Nan Xu,  Qiang Xu (2023)<br />
- **SA-Attack: Improving Adversarial Transferability of Vision-Language Pre-training Models via Self-Augmentation** \[[Paper](https://arxiv.org/abs/2312.04913)\] <br />
Bangyan He,  Xiaojun Jia,  Siyuan Liang,  Tianrui Lou,  Yang Liu,  Xiaochun Cao (2023)<br />
- **Improving Adversarial Transferability of Visual-Language Pre-training Models through Collaborative Multimodal Interaction** \[[Paper](https://arxiv.org/abs/2403.10883)\] <br />
Jiyuan Fu,  Zhaoyu Chen,  Kaixun Jiang,  Haijing Guo,  Jiafeng Wang,  Shuyong Gao,  Wenqiang Zhang (2024)<br />
- **An Image Is Worth 1000 Lies: Transferability of Adversarial Images across Prompts on Vision-Language Models** \[[Paper](https://openreview.net/forum?id=nc5GgFAvtk)\] <br />
Haochen Luo,  Jindong Gu,  Fengyuan Liu,  Philip Torr (2024)<br />
### Others
- **Prompting4Debugging: Red-Teaming Text-to-Image Diffusion Models by Finding Problematic Prompts** \[[Paper](https://arxiv.org/abs/2309.06135)\] <br />
Zhi-Yi Chin,  Chieh-Ming Jiang,  Ching-Chun Huang,  Pin-Yu Chen,  Wei-Chen Chiu (2023)<br />
- **SneakyPrompt: Jailbreaking Text-to-image Generative Models** \[[Paper](https://arxiv.org/abs/2305.12082)\] <br />
Yuchen Yang,  Bo Hui,  Haolin Yuan,  Neil Gong,  Yinzhi Cao (2023)<br />
- **White-box Multimodal Jailbreaks Against Large Vision-Language Models** \[[Paper](https://arxiv.org/abs/2405.17894
   )\] <br />
Ruofan Wang,  Xingjun Ma,  Hanxu Zhou,  Chuanjun Ji,  Guangnan Ye,  Yu-Gang Jiang (2024)<br />
## Defense
### Guardrail Defenses
- **Universal Prompt Optimizer for Safe Text-to-Image Generation** \[[Paper](https://arxiv.org/abs/2402.10882)\] <br />
Zongyu Wu,  Hongcheng Gao,  Yueze Wang,  Xiang Zhang,  Suhang Wang (2024)<br />
- **UFID: A Unified Framework for Input-level Backdoor Detection on Diffusion Models** \[[Paper](https://arxiv.org/abs/2404.01101)\] <br />
Zihan Guan,  Mengxuan Hu,  Sheng Li,  Anil Vullikanti (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou,  Kai Chen,  Zhili Liu,  Lanqing Hong,  Hang Xu,  Zhenguo Li,  Dit-Yan Yeung,  James T. Kwok,  Yu Zhang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou,  Kai Chen,  Zhili Liu,  Lanqing Hong,  Hang Xu,  Zhenguo Li,  Dit-Yan Yeung,  James T. Kwok,  Yu Zhang (2024)<br />
- **A Mutation-Based Method for Multi-Modal Jailbreaking Attack Detection** \[[Paper](https://arxiv.org/abs/2312.10766)\] <br />
Xiaoyu Zhang,  Cen Zhang,  Tianlin Li,  Yihao Huang,  Xiaojun Jia,  Ming Hu,  Jie Zhang,  Yang Liu,  Shiqing Ma,  Chao Shen (2023)<br />
- **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** \[[Paper](https://arxiv.org/abs/2401.02906)\] <br />
Renjie Pi,  Tianyang Han,  Jianshu Zhang,  Yueqi Xie,  Rui Pan,  Qing Lian,  Hanze Dong,  Jipeng Zhang,  Tong Zhang (2024)<br />
- **Added Toxicity Mitigation at Inference Time for Multimodal and Massively Multilingual Translation** \[[Paper](https://arxiv.org/abs/2311.06532)\] <br />
Marta R. Costa-jussà,  David Dale,  Maha Elbayad,  Bokai Yu (2023)<br />
### Other Defenses
- **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models** \[[Paper](https://arxiv.org/abs/2404.06666
   )\] <br />
Xinfeng Li,  Yuchen Yang,  Jiangyi Deng,  Chen Yan,  Yanjiao Chen,  Xiaoyu Ji,  Wenyuan Xu (2024)<br />
- **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models** \[[Paper](https://arxiv.org/abs/2404.06666)\] <br />
Xinfeng Li,  Yuchen Yang,  Jiangyi Deng,  Chen Yan,  Yanjiao Chen,  Xiaoyu Ji,  Wenyuan Xu (2024)<br />
- **Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models** \[[Paper](https://arxiv.org/abs/2402.02207)\] <br />
Yongshuo Zong,  Ondrej Bohdal,  Tingyang Yu,  Yongxin Yang,  Timothy Hospedales (2024)<br />
- **Cross-Modality Safety Alignment** \[[Paper](https://arxiv.org/abs/2406.15279
   )\] <br />
Siyin Wang,  Xingsong Ye,  Qinyuan Cheng,  Junwen Duan,  Shimin Li,  Jinlan Fu,  Xipeng Qiu,  Xuanjing Huang (2024)<br />
- **Safety Alignment for Vision Language Models** \[[Paper](https://arxiv.org/abs/2405.13581
   )\] <br />
Zhendong Liu,  Yuanbi Nie,  Yingshui Tan,  Xiangyu Yue,  Qiushi Cui,  Chongjun Wang,  Xiaoyong Zhu,  Bo Zheng (2024)<br />
- **AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting** \[[Paper](https://arxiv.org/abs/2403.09513)\] <br />
Yu Wang,  Xiaogeng Liu,  Yu Li,  Muhao Chen,  Chaowei Xiao (2024)<br />
- **Safeguarding Vision-Language Models Against Patched Visual Prompt Injectors** \[[Paper](https://arxiv.org/abs/2405.10529
   )\] <br />
Jiachen Sun,  Changsheng Wang,  Jiongxiao Wang,  Yiwei Zhang,  Chaowei Xiao (2024)<br />
## Application
### Agents
- **MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2311.176)\] <br />
Xin Liu,  Yichen Zhu,  Jindong Gu,  Yunshi Lan,  Chao Yang,  Yu Qiao (2023)<br />
- **How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs** \[[Paper](https://arxiv.org/abs/2311.16101)\] <br />
Haoqin Tu,  Chenhang Cui,  Zijun Wang,  Yiyang Zhou,  Bingchen Zhao,  Junlin Han,  Wangchunshu Zhou,  Huaxiu Yao,  Cihang Xie (2023)<br />
- **Towards Red Teaming in Multimodal and Multilingual Translation** \[[Paper](https://arxiv.org/abs/2401.16247)\] <br />
Christophe Ropers,  David Dale,  Prangthip Hansanti,  Gabriel Mejia Gonzalez,  Ivan Evtimov,  Corinne Wong,  Christophe Touret,  Kristina Pereyra,  Seohyun Sonia Kim,  Cristian Canton Ferrer,  Pierre Andrews,  Marta R. Costa-jussà (2024)<br />
- **Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast** \[[Paper](https://arxiv.org/abs/2402.08567)\] <br />
Xiangming Gu,  Xiaosen Zheng,  Tianyu Pang,  Chao Du,  Qian Liu,  Ye Wang,  Jing Jiang,  Min Lin (2024)<br />
- **JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2404.03027)\] <br />
Weidi Luo,  Siyuan Ma,  Xiaogeng Liu,  Xiaoyu Guo,  Chaowei Xiao (2024)<br />
- **Adversarial Attacks on Multimodal Agents** \[[Paper](https://arxiv.org/abs/2406.12814
   )\] <br />
Chen Henry Wu,  Jing Yu Koh,  Ruslan Salakhutdinov,  Daniel Fried,  Aditi Raghunathan (2024)<br />
- **Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks?** \[[Paper](https://arxiv.org/abs/2404.03411)\] <br />
Shuo Chen,  Zhen Han,  Bailan He,  Zifeng Ding,  Wenqian Yu,  Philip Torr,  Volker Tresp,  Jindong Gu (2024)<br />
## Benchmarks
- **Adversarial Nibbler: An Open Red-Teaming Method for Identifying Diverse Harms in Text-to-Image Generation** \[[Paper](https://arxiv.org/abs/2403.12075)\] <br />
Jessica Quaye,  Alicia Parrish,  Oana Inel,  Charvi Rastogi,  Hannah Rose Kirk,  Minsuk Kahng,  Erin van Liemt,  Max Bartolo,  Jess Tsang,  Justin White,  Nathan Clement,  Rafael Mosquera,  Juan Ciro,  Vijay Janapa Reddi,  Lora Aroyo (2024)<br />
- **Red Teaming Visual Language Models** \[[Paper](https://arxiv.org/abs/2401.12915)\] <br />
Mukai Li,  Lei Li,  Yuwei Yin,  Masood Ahmed,  Zhenguang Liu,  Qi Liu (2024)<br />