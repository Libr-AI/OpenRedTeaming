# Defenses
## Table of Contents
- Defenses
	 - [Training Time Defenses](#training-time-defenses)
		 - [RLHF](#rlhf)
		 - [Fine-tuning](#fine-tuning)
	 - [Inference Time Defenses](#inference-time-defenses)
		 - [Prompting](#prompting)
		 - [Ensemble](#ensemble)
		 - [Guardrails](#guardrails)
			 - [Input Guardrails](#input-guardrails)
			 - [Output Guardrails](#output-guardrails)
			 - [Input & Output Guardrails](#input-&-output-guardrails)
		 - [Adversarial Suffix Defenses](#adversarial-suffix-defenses)
		 - [Decoding Defenses](#decoding-defenses)
## Training Time Defenses
### RLHF
- **Configurable Safety Tuning of Language Models with Synthetic Preference Data**\[[Paper](https://arxiv.org/abs/2404.00495)\] <br />
Victor Gallego (2024)<br />
- **Enhancing LLM Safety via Constrained Direct Preference Optimization**\[[Paper](https://arxiv.org/abs/2403.02475)\] <br />
Zixuan Liu, Xiaolin Sun, Zizhan Zheng (2024)<br />
- **Safe RLHF: Safe Reinforcement Learning from Human Feedback**\[[Paper](https://arxiv.org/abs/2310.12773)\] <br />
Josef Dai, Xuehai Pan, Ruiyang Sun, Jiaming Ji, Xinbo Xu, Mickel Liu, Yizhou Wang, Yaodong Yang (2023)<br />
- **BeaverTails: Towards Improved Safety Alignment of LLM via a Human-Preference Dataset**\[[Paper](https://arxiv.org/abs/2307.04657)\] <br />
Jiaming Ji, Mickel Liu, Juntao Dai, Xuehai Pan, Chi Zhang, Ce Bian, Chi Zhang, Ruiyang Sun, Yizhou Wang, Yaodong Yang (2023)<br />
- **Safer-Instruct: Aligning Language Models with Automated Preference Data**\[[Paper](https://arxiv.org/abs/2311.08685)\] <br />
Taiwei Shi, Kai Chen, Jieyu Zhao (2023)<br />
### Fine-tuning
- **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models**\[[Paper](https://arxiv.org/abs/2404.06666)\] <br />
Xinfeng Li, Yuchen Yang, Jiangyi Deng, Chen Yan, Yanjiao Chen, Xiaoyu Ji, Wenyuan Xu (2024)<br />
- **Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models**\[[Paper](https://arxiv.org/abs/2402.02207)\] <br />
Yongshuo Zong, Ondrej Bohdal, Tingyang Yu, Yongxin Yang, Timothy Hospedales (2024)<br />
- **Developing Safe and Responsible Large Language Models -- A Comprehensive Framework**\[[Paper](https://arxiv.org/abs/2404.01399)\] <br />
Shaina Raza, Oluwanifemi Bamgbose, Shardul Ghuge, Fatemeh Tavakoli, Deepak John Reji (2024)<br />
- **Immunization against harmful fine-tuning attacks**\[[Paper](https://arxiv.org/abs/2402.16382)\] <br />
Domenic Rosati, Jan Wehner, Kai Williams, Łukasz Bartoszcze, Jan Batzner, Hassan Sajjad, Frank Rudzicz (2024)<br />
- **Mitigating Fine-tuning Jailbreak Attack with Backdoor Enhanced Alignment**\[[Paper](https://arxiv.org/abs/2402.14968)\] <br />
Jiongxiao Wang, Jiazhao Li, Yiquan Li, Xiangyu Qi, Junjie Hu, Yixuan Li, Patrick McDaniel, Muhao Chen, Bo Li, Chaowei Xiao (2024)<br />
- **Dialectical Alignment: Resolving the Tension of 3H and Security Threats of LLMs**\[[Paper](https://arxiv.org/abs/2404.00486)\] <br />
Shu Yang, Jiayuan Su, Han Jiang, Mengdi Li, Keyuan Cheng, Muhammad Asif Ali, Lijie Hu, Di Wang (2024)<br />
- **Pruning for Protection: Increasing Jailbreak Resistance in Aligned LLMs Without Fine-Tuning**\[[Paper](https://arxiv.org/abs/2401.10862)\] <br />
Adib Hasan, Ileana Rugina, Alex Wang (2024)<br />
- **Eraser: Jailbreaking Defense in Large Language Models via Unlearning Harmful Knowledge**\[[Paper](https://arxiv.org/abs/2404.0588)\] <br />
Weikai Lu, Ziqian Zeng, Jianwei Wang, Zhengdong Lu, Zelin Chen, Huiping Zhuang, Cen Chen (2024)<br />
- **Two Heads are Better than One: Nested PoE for Robust Defense Against Multi-Backdoors**\[[Paper](https://arxiv.org/abs/2404.02356)\] <br />
Victoria Graf, Qin Liu, Muhao Chen (2024)<br />
- **Defending Against Weight-Poisoning Backdoor Attacks for Parameter-Efficient Fine-Tuning**\[[Paper](https://arxiv.org/abs/2402.12168)\] <br />
Shuai Zhao, Leilei Gan, Luu Anh Tuan, Jie Fu, Lingjuan Lyu, Meihuizi Jia, Jinming Wen (2024)<br />
- **Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions**\[[Paper](https://arxiv.org/abs/2309.07875)\] <br />
Federico Bianchi, Mirac Suzgun, Giuseppe Attanasio, Paul Röttger, Dan Jurafsky, Tatsunori Hashimoto, James Zou (2023)<br />
- **Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM**\[[Paper](https://arxiv.org/abs/2309.14348)\] <br />
Bochuan Cao, Yuanpu Cao, Lu Lin, Jinghui Chen (2023)<br />
- **Learn What NOT to Learn: Towards Generative Safety in Chatbots**\[[Paper](https://arxiv.org/abs/2304.1122)\] <br />
Leila Khalatbari, Yejin Bang, Dan Su, Willy Chung, Saeed Ghadimi, Hossein Sameti, Pascale Fung (2023)<br />
- **Jatmo: Prompt Injection Defense by Task-Specific Finetuning**\[[Paper](https://arxiv.org/abs/2312.17673)\] <br />
Julien Piet, Maha Alrashed, Chawin Sitawarin, Sizhe Chen, Zeming Wei, Elizabeth Sun, Basel Alomair, David Wagner (2023)<br />
## Inference Time Defenses
### Prompting
- **AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting**\[[Paper](https://arxiv.org/abs/2403.09513)\] <br />
Yu Wang, Xiaogeng Liu, Yu Li, Muhao Chen, Chaowei Xiao (2024)<br />
- **Break the Breakout: Reinventing LM Defense Against Jailbreak Attacks with Self-Refinement**\[[Paper](https://arxiv.org/abs/2402.1518)\] <br />
Heegyu Kim, Sehyun Yuk, Hyunsouk Cho (2024)<br />
- **On Prompt-Driven Safeguarding for Large Language Models**\[[Paper](https://arxiv.org/abs/2401.18018)\] <br />
Chujie Zheng, Fan Yin, Hao Zhou, Fandong Meng, Jie Zhou, Kai-Wei Chang, Minlie Huang, Nanyun Peng (2024)<br />
- **Signed-Prompt: A New Approach to Prevent Prompt Injection Attacks Against LLM-Integrated Applications**\[[Paper](https://arxiv.org/abs/2401.07612)\] <br />
Xuchen Suo (2024)<br />
- **Intention Analysis Makes LLMs A Good Jailbreak Defender**\[[Paper](https://arxiv.org/abs/2401.06561)\] <br />
Yuqi Zhang, Liang Ding, Lefei Zhang, Dacheng Tao (2024)<br />
- **Defending Against Indirect Prompt Injection Attacks With Spotlighting**\[[Paper](https://arxiv.org/abs/2403.1472)\] <br />
Keegan Hines, Gary Lopez, Matthew Hall, Federico Zarfati, Yonatan Zunger, Emre Kiciman (2024)<br />
- **Ensuring Safe and High-Quality Outputs: A Guideline Library Approach for Language Models**\[[Paper](https://arxiv.org/abs/2403.11838)\] <br />
Yi Luo, Zhenghao Lin, Yuhao Zhang, Jiashuo Sun, Chen Lin, Chengjin Xu, Xiangdong Su, Yelong Shen, Jian Guo, Yeyun Gong (2024)<br />
- **Goal-guided Generative Prompt Injection Attack on Large Language Models**\[[Paper](https://arxiv.org/abs/2404.07234)\] <br />
Chong Zhang, Mingyu Jin, Qinkai Yu, Chengzhi Liu, Haochen Xue, Xiaobo Jin (2024)<br />
- **StruQ: Defending Against Prompt Injection with Structured Queries**\[[Paper](https://arxiv.org/abs/2402.06363)\] <br />
Sizhe Chen, Julien Piet, Chawin Sitawarin, David Wagner (2024)<br />
- **Studious Bob Fight Back Against Jailbreaking via Prompt Adversarial Tuning**\[[Paper](https://arxiv.org/abs/2402.06255)\] <br />
Yichuan Mo, Yuji Wang, Zeming Wei, Yisen Wang (2024)<br />
- **Self-Guard: Empower the LLM to Safeguard Itself**\[[Paper](https://arxiv.org/abs/2310.15851)\] <br />
Zezhong Wang, Fangkai Yang, Lu Wang, Pu Zhao, Hongru Wang, Liang Chen, Qingwei Lin, Kam-Fai Wong (2023)<br />
- **Using In-Context Learning to Improve Dialogue Safety**\[[Paper](https://arxiv.org/abs/2302.00871)\] <br />
Nicholas Meade, Spandana Gella, Devamanyu Hazarika, Prakhar Gupta, Di Jin, Siva Reddy, Yang Liu, Dilek Hakkani-Tür (2023)<br />
- **Defending Large Language Models Against Jailbreaking Attacks Through Goal Prioritization**\[[Paper](https://arxiv.org/abs/2311.09096)\] <br />
Zhexin Zhang, Junxiao Yang, Pei Ke, Minlie Huang (2023)<br />
- **Bergeron: Combating Adversarial Attacks through a Conscience-Based Alignment Framework**\[[Paper](https://arxiv.org/abs/2312.00029)\] <br />
Matthew Pisano, Peter Ly, Abraham Sanders, Bingsheng Yao, Dakuo Wang, Tomek Strzalkowski, Mei Si (2023)<br />
### Ensemble
- **Combating Adversarial Attacks with Multi-Agent Debate**\[[Paper](https://arxiv.org/abs/2401.05998)\] <br />
Steffi Chern, Zhen Fan, Andy Liu (2024)<br />
- **TrustAgent: Towards Safe and Trustworthy LLM-based Agents through Agent Constitution**\[[Paper](https://arxiv.org/abs/2402.01586)\] <br />
Wenyue Hua, Xianjun Yang, Zelong Li, Wei Cheng, Yongfeng Zhang (2024)<br />
- **AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks**\[[Paper](https://arxiv.org/abs/2403.04783)\] <br />
Yifan Zeng, Yiran Wu, Xiao Zhang, Huazheng Wang, Qingyun Wu (2024)<br />
- **Learn to Disguise: Avoid Refusal Responses in LLM's Defense via a Multi-agent Attacker-Disguiser Game**\[[Paper](https://arxiv.org/abs/2404.02532)\] <br />
Qianqiao Xu, Zhiliang Tian, Hongyan Wu, Zhen Huang, Yiping Song, Feng Liu, Dongsheng Li (2024)<br />
- **Jailbreaker in Jail: Moving Target Defense for Large Language Models**\[[Paper](https://arxiv.org/abs/2310.02417)\] <br />
Bocheng Chen, Advait Paliwal, Qiben Yan (2023)<br />
### Guardrails
#### Input Guardrails
- **UFID: A Unified Framework for Input-level Backdoor Detection on Diffusion Models**\[[Paper](https://arxiv.org/abs/2404.01101)\] <br />
Zihan Guan, Mengxuan Hu, Sheng Li, Anil Vullikanti (2024)<br />
- **Universal Prompt Optimizer for Safe Text-to-Image Generation**\[[Paper](https://arxiv.org/abs/2402.10882)\] <br />
Zongyu Wu, Hongcheng Gao, Yueze Wang, Xiang Zhang, Suhang Wang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation**\[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation**\[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang (2024)<br />
- **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance**\[[Paper](https://arxiv.org/abs/2401.02906)\] <br />
Renjie Pi, Tianyang Han, Yueqi Xie, Rui Pan, Qing Lian, Hanze Dong, Jipeng Zhang, Tong Zhang (2024)<br />
- **Added Toxicity Mitigation at Inference Time for Multimodal and Massively Multilingual Translation**\[[Paper](https://arxiv.org/abs/2311.06532)\] <br />
Marta R. Costa-jussà, David Dale, Maha Elbayad, Bokai Yu (2023)<br />
- **A Mutation-Based Method for Multi-Modal Jailbreaking Attack Detection**\[[Paper](https://arxiv.org/abs/2312.10766)\] <br />
Xiaoyu Zhang, Cen Zhang, Tianlin Li, Yihao Huang, Xiaojun Jia, Xiaofei Xie, Yang Liu, Chao Shen (2023)<br />
- **Detection and Defense Against Prominent Attacks on Preconditioned LLM-Integrated Virtual Assistants**\[[Paper](https://arxiv.org/abs/2401.00994)\] <br />
Chun Fai Chan, Daniel Wankit Yip, Aysan Esmradi (2024)<br />
- **ShieldLM: Empowering LLMs as Aligned,Customizable and Explainable Safety Detectors**\[[Paper](https://arxiv.org/abs/2402.16444)\] <br />
Zhexin Zhang, Yida Lu, Jingyuan Ma, Di Zhang, Rui Li, Pei Ke, Hao Sun, Lei Sha, Zhifang Sui, Hongning Wang, Minlie Huang (2024)<br />
- **Round Trip Translation Defence against Large Language Model Jailbreaking Attacks**\[[Paper](https://arxiv.org/abs/2402.13517)\] <br />
Canaan Yung, Hadi Mohaghegh Dolatabadi, Sarah Erfani, Christopher Leckie (2024)<br />
- **Gradient Cuff: Detecting Jailbreak Attacks on Large Language Models by Exploring Refusal Loss Landscapes**\[[Paper](https://arxiv.org/abs/2403.00867)\] <br />
Xiaomeng Hu, Pin-Yu Chen, Tsung-Yi Ho (2024)<br />
- **Defending Jailbreak Prompts via In-Context Adversarial Game**\[[Paper](https://arxiv.org/abs/2402.13148)\] <br />
Yujun Zhou, Yufei Han, Haomin Zhuang, Taicheng Guo, Kehan Guo, Zhenwen Liang, Hongyan Bao, Xiangliang Zhang (2024)<br />
- **SPML: A DSL for Defending Language Models Against Prompt Attacks**\[[Paper](https://arxiv.org/abs/2402.11755)\] <br />
Reshabh K Sharma, Vinayak Gupta, Dan Grossman (2024)<br />
- **Robust Safety Classifier for Large Language Models: Adversarial Prompt Shield**\[[Paper](https://arxiv.org/abs/2311.00172)\] <br />
Jinhwa Kim, Ali Derakhshan, Ian G. Harris (2023)<br />
- **AI Control: Improving Safety Despite Intentional Subversion**\[[Paper](https://arxiv.org/abs/2312.06942)\] <br />
Ryan Greenblatt, Buck Shlegeris, Kshitij Sachan, Fabien Roger (2023)<br />
- **Maatphor: Automated Variant Analysis for Prompt Injection Attacks**\[[Paper](https://arxiv.org/abs/2312.11513)\] <br />
Ahmed Salem, Andrew Paverd, Boris Köpf (2023)<br />
#### Output Guardrails
- **Defending LLMs against Jailbreaking Attacks via Backtranslation**\[[Paper](https://arxiv.org/abs/2402.16459)\] <br />
Yihan Wang, Zhouxing Shi, Andrew Bai, Cho-Jui Hsieh (2024)<br />
- **Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks**\[[Paper](https://arxiv.org/abs/2401.17263)\] <br />
Andy Zhou, Bo Li, Haohan Wang (2024)<br />
- **Jailbreaking is Best Solved by Definition**\[[Paper](https://arxiv.org/abs/2403.14725)\] <br />
Taeyoun Kim, Suhas Kotha, Aditi Raghunathan (2024)<br />
- **LLM Self Defense: By Self Examination,LLMs Know They Are Being Tricked**\[[Paper](https://arxiv.org/abs/2308.07308)\] <br />
Mansi Phute, Alec Helbling, Matthew Hull, ShengYun Peng, Sebastian Szyller, Cory Cornelius, Duen Horng Chau (2023)<br />
#### Input & Output Guardrails
- **RigorLLM: Resilient Guardrails for Large Language Models against Undesired Content**\[[Paper](https://arxiv.org/abs/2403.13031)\] <br />
Zhuowen Yuan, Zidi Xiong, Yi Zeng, Ning Yu, Ruoxi Jia, Dawn Song, Bo Li (2024)<br />
- **NeMo Guardrails: A Toolkit for Controllable and Safe LLM Applications with Programmable Rails**\[[Paper](https://arxiv.org/abs/2310.10501)\] <br />
Traian Rebedea, Razvan Dinu, Makesh Sreedhar, Christopher Parisien, Jonathan Cohen (2023)<br />
- **Llama Guard: LLM-based Input-Output Safeguard for Human-AI Conversations**\[[Paper](https://arxiv.org/abs/2312.06674)\] <br />
Hakan Inan, Kartikeya Upasani, Jianfeng Chi, Rashi Rungta, Krithika Iyer, Yuning Mao, Michael Tontchev, Qing Hu, Brian Fuller, Davide Testuggine, Madian Khabsa (2023)<br />
### Adversarial Suffix Defenses
- **Defending Large Language Models against Jailbreak Attacks via Semantic Smoothing**\[[Paper](https://arxiv.org/abs/2402.16192)\] <br />
Jiabao Ji, Bairu Hou, Alexander Robey, George J. Pappas, Hamed Hassani, Yang Zhang, Eric Wong, Shiyu Chang (2024)<br />
- **Certifying LLM Safety against Adversarial Prompting**\[[Paper](https://arxiv.org/abs/2309.02705)\] <br />
Aounon Kumar, Chirag Agarwal, Suraj Srinivas, Aaron Jiaxun Li, Soheil Feizi, Himabindu Lakkaraju (2023)<br />
- **Baseline Defenses for Adversarial Attacks Against Aligned Language Models**\[[Paper](https://arxiv.org/abs/2309.00614)\] <br />
Neel Jain, Avi Schwarzschild, Yuxin Wen, Gowthami Somepalli, John Kirchenbauer, Ping-yeh Chiang, Micah Goldblum, Aniruddha Saha, Jonas Geiping, Tom Goldstein (2023)<br />
- **Detecting Language Model Attacks with Perplexity**\[[Paper](https://arxiv.org/abs/2308.14132)\] <br />
Gabriel Alon, Michael Kamfonas (2023)<br />
- **SmoothLLM: Defending Large Language Models Against Jailbreaking Attacks**\[[Paper](https://arxiv.org/abs/2310.03684)\] <br />
Alexander Robey, Eric Wong, Hamed Hassani, George J. Pappas (2023)<br />
- **Token-Level Adversarial Prompt Detection Based on Perplexity Measures and Contextual Information**\[[Paper](https://arxiv.org/abs/2311.11509)\] <br />
Zhengmian Hu, Gang Wu, Saayan Mitra, Ruiyi Zhang, Tong Sun, Heng Huang, Viswanathan Swaminathan (2023)<br />
### Decoding Defenses
- **Towards Safety and Helpfulness Balanced Responses via Controllable Large Language Models**\[[Paper](https://arxiv.org/abs/2404.01295)\] <br />
Yi-Lin Tuan, Xilun Chen, Eric Michael Smith, Louis Martin, Soumya Batra, Asli Celikyilmaz, William Yang Wang, Daniel M. Bikel (2024)<br />
- **SafeDecoding: Defending against Jailbreak Attacks via Safety-Aware Decoding**\[[Paper](https://arxiv.org/abs/2402.08983)\] <br />
Zhangchen Xu, Fengqing Jiang, Luyao Niu, Jinyuan Jia, Bill Yuchen Lin, Radha Poovendran (2024)<br />