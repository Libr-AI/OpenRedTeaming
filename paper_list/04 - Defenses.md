# Defenses
## Table of Contents
- Defenses
	 - [Overkill](#overkill)
	 - [Training Time Defenses](#training-time-defenses)
		 - [RLHF](#rlhf)
		 - [Fine-tuning](#fine-tuning)
		 - [Unlearning](#unlearning)
	 - [Inference Time Defenses](#inference-time-defenses)
		 - [Prompting](#prompting)
		 - [Ensemble](#ensemble)
		 - [Guardrails](#guardrails)
			 - [Input Guardrails](#input-guardrails)
			 - [Output Guardrails](#output-guardrails)
			 - [Input & Output Guardrails](#input-&-output-guardrails)
		 - [Defenses against Adversarial Suffix](#defenses-against-adversarial-suffix)
		 - [Decoding Defenses](#decoding-defenses)
## Overkill
- **MOSSBench: Is Your Multimodal Language Model Oversensitive to Safe Queries?** \[[Paper](https://arxiv.org/abs/2406.17806
   )\] <br />
Xirui Li,  Hengguang Zhou,  Ruochen Wang,  Tianyi Zhou,  Minhao Cheng,  Cho-Jui Hsieh (2024)<br />
- **Mitigating Exaggerated Safety in Large Language Models** \[[Paper](https://arxiv.org/abs/2405.05418
   )\] <br />
Ruchi Bhalani,  Ruchira Ray (2024)<br />
- **XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models** \[[Paper](https://arxiv.org/abs/2308.01263)\] <br />
Paul Röttger,  Hannah Rose Kirk,  Bertie Vidgen,  Giuseppe Attanasio,  Federico Bianchi,  Dirk Hovy (2023)<br />
## Training Time Defenses
### RLHF
- **SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model** \[[Paper](https://arxiv.org/abs/2406.12030)\] <br />
Yongting Zhang,  Lu Chen,  Guodong Zheng,  Yifeng Gao,  Rui Zheng,  Jinlan Fu,  Zhenfei Yin,  Senjie Jin,  Yu Qiao,  Xuanjing Huang,  Feng Zhao,  Tao Gui,  Jing Shao (2024)<br />
- **BeaverTails: Towards Improved Safety Alignment of LLM via a Human-Preference Dataset** \[[Paper](https://arxiv.org/abs/2307.04657)\] <br />
Jiaming Ji,  Mickel Liu,  Juntao Dai,  Xuehai Pan,  Chi Zhang,  Ce Bian,  Chi Zhang,  Ruiyang Sun,  Yizhou Wang,  Yaodong Yang (2023)<br />
- **Adversarial DPO: Harnessing Harmful Data for Reducing Toxicity with Minimal Impact on Coherence and Evasiveness in Dialogue Agents** \[[Paper](https://arxiv.org/abs/2405.12900
   )\] <br />
San Kim,  Gary Geunbae Lee (2024)<br />
- **One-Shot Safety Alignment for Large Language Models via Optimal Dualization** \[[Paper](https://arxiv.org/abs/2405.19544
   )\] <br />
Xinmeng Huang,  Shuo Li,  Edgar Dobriban,  Osbert Bastani,  Hamed Hassani,  Dongsheng Ding (2024)<br />
- **PKU-SafeRLHF: A Safety Alignment Preference Dataset for Llama Family Models** \[[Paper](https://arxiv.org/abs/2406.15513
   )\] <br />
Jiaming Ji,  Donghai Hong,  Borong Zhang,  Boyuan Chen,  Josef Dai,  Boren Zheng,  Tianyi Qiu,  Boxun Li,  Yaodong Yang (2024)<br />
- **Robustifying Safety-Aligned Large Language Models through Clean Data Curation** \[[Paper](https://arxiv.org/abs/2405.19358)\] <br />
Xiaoqun Liu,  Jiacheng Liang,  Muchao Ye,  Zhaohan Xi (2024)<br />
- **Configurable Safety Tuning of Language Models with Synthetic Preference Data** \[[Paper](https://arxiv.org/abs/2404.00495)\] <br />
Victor Gallego (2024)<br />
- **Enhancing LLM Safety via Constrained Direct Preference Optimization** \[[Paper](https://arxiv.org/abs/2403.02475)\] <br />
Zixuan Liu,  Xiaolin Sun,  Zizhan Zheng (2024)<br />
- **Safer-Instruct: Aligning Language Models with Automated Preference Data** \[[Paper](https://arxiv.org/abs/2311.08685)\] <br />
Taiwei Shi,  Kai Chen,  Jieyu Zhao (2023)<br />
- **Safe RLHF: Safe Reinforcement Learning from Human Feedback** \[[Paper](https://arxiv.org/abs/2310.12773)\] <br />
Josef Dai,  Xuehai Pan,  Ruiyang Sun,  Jiaming Ji,  Xinbo Xu,  Mickel Liu,  Yizhou Wang,  Yaodong Yang (2023)<br />
### Fine-tuning
- **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models** \[[Paper](https://arxiv.org/abs/2404.06666)\] <br />
Xinfeng Li,  Yuchen Yang,  Jiangyi Deng,  Chen Yan,  Yanjiao Chen,  Xiaoyu Ji,  Wenyuan Xu (2024)<br />
- **Cross-Modality Safety Alignment** \[[Paper](https://arxiv.org/abs/2406.15279
   )\] <br />
Siyin Wang,  Xingsong Ye,  Qinyuan Cheng,  Junwen Duan,  Shimin Li,  Jinlan Fu,  Xipeng Qiu,  Xuanjing Huang (2024)<br />
- **Safety Alignment for Vision Language Models** \[[Paper](https://arxiv.org/abs/2405.13581
   )\] <br />
Zhendong Liu,  Yuanbi Nie,  Yingshui Tan,  Xiangyu Yue,  Qiushi Cui,  Chongjun Wang,  Xiaoyong Zhu,  Bo Zheng (2024)<br />
- **Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models** \[[Paper](https://arxiv.org/abs/2402.02207)\] <br />
Yongshuo Zong,  Ondrej Bohdal,  Tingyang Yu,  Yongxin Yang,  Timothy Hospedales (2024)<br />
- **Efficient Adversarial Training in LLMs with Continuous Attacks** \[[Paper](https://arxiv.org/abs/2405.15589
   )\] <br />
Sophie Xhonneux,  Alessandro Sordoni,  Stephan Günnemann,  Gauthier Gidel,  Leo Schwinn (2024)<br />
- **PromptFix: Few-shot Backdoor Removal via Adversarial Prompt Tuning** \[[Paper](https://arxiv.org/abs/2406.04478
   )\] <br />
Tianrong Zhang,  Zhaohan Xi,  Ting Wang,  Prasenjit Mitra,  Jinghui Chen (2024)<br />
- **Adversarial Tuning: Defending Against Jailbreak Attacks for LLMs** \[[Paper](https://arxiv.org/abs/2406.06622
   )\] <br />
Fan Liu,  Zhao Xu,  Hao Liu (2024)<br />
- **On Trojans in Refined Language Models** \[[Paper](https://arxiv.org/abs/2406.07778
   )\] <br />
Jayaram Raghuram,  George Kesidis,  David J. Miller (2024)<br />
- **Lazy Safety Alignment for Large Language Models against Harmful Fine-tuning** \[[Paper](https://arxiv.org/abs/2405.18641
   )\] <br />
Tiansheng Huang,  Sihao Hu,  Fatih Ilhan,  Selim Furkan Tekin,  Ling Liu (2024)<br />
- **Beyond Perplexity: Multi-dimensional Safety Evaluation of LLM Compression** \[[Paper](https://arxiv.org/abs/2407.04965
   )\] <br />
Zhichao Xu,  Ashim Gupta,  Tao Li,  Oliver Bentham,  Vivek Srikumar (2024)<br />
- **The Instruction Hierarchy: Training LLMs to Prioritize Privileged Instructions** \[[Paper](https://arxiv.org/abs/2404.13208
   )\] <br />
Eric Wallace,  Kai Xiao,  Reimar Leike,  Lilian Weng,  Johannes Heidecke,  Alex Beutel (2024)<br />
- **Navigating the Safety Landscape: Measuring Risks in Finetuning Large Language Models** \[[Paper](https://arxiv.org/abs/2405.17374
   )\] <br />
ShengYun Peng,  Pin-Yu Chen,  Matthew Hull,  Duen Horng Chau (2024)<br />
- **Model Merging and Safety Alignment: One Bad Model Spoils the Bunch** \[[Paper](https://arxiv.org/abs/2406.14563
   )\] <br />
Hasan Abed Al Kader Hammoud,  Umberto Michieli,  Fabio Pizzati,  Philip Torr,  Adel Bibi,  Bernard Ghanem,  Mete Ozay (2024)<br />
- **Safe LoRA: the Silver Lining of Reducing Safety Risks when Fine-tuning Large Language Models** \[[Paper](https://arxiv.org/abs/2405.16833
   )\] <br />
Chia-Yi Hsu,  Yu-Lin Tsai,  Chih-Hsun Lin,  Pin-Yu Chen,  Chia-Mu Yu,  Chun-Ying Huang (2024)<br />
- **Dialectical Alignment: Resolving the Tension of 3H and Security Threats of LLMs** \[[Paper](https://arxiv.org/abs/2404.00486)\] <br />
Shu Yang,  Jiayuan Su,  Han Jiang,  Mengdi Li,  Keyuan Cheng,  Muhammad Asif Ali,  Lijie Hu,  Di Wang (2024)<br />
- **Developing Safe and Responsible Large Language Models -- A Comprehensive Framework** \[[Paper](https://arxiv.org/abs/2404.01399)\] <br />
Shaina Raza,  Oluwanifemi Bamgbose,  Shardul Ghuge,  Fatemeh Tavakol,  Deepak John Reji,  Syed Raza Bashir (2024)<br />
- **Two Heads are Better than One: Nested PoE for Robust Defense Against Multi-Backdoors** \[[Paper](https://arxiv.org/abs/2404.02356)\] <br />
Victoria Graf,  Qin Liu,  Muhao Chen (2024)<br />
- **Defending Against Weight-Poisoning Backdoor Attacks for Parameter-Efficient Fine-Tuning** \[[Paper](https://arxiv.org/abs/2402.12168)\] <br />
Shuai Zhao,  Leilei Gan,  Luu Anh Tuan,  Jie Fu,  Lingjuan Lyu,  Meihuizi Jia,  Jinming Wen (2024)<br />
- **Mitigating Fine-tuning Jailbreak Attack with Backdoor Enhanced Alignment** \[[Paper](https://arxiv.org/abs/2402.14968)\] <br />
Jiongxiao Wang,  Jiazhao Li,  Yiquan Li,  Xiangyu Qi,  Junjie Hu,  Yixuan Li,  Patrick McDaniel,  Muhao Chen,  Bo Li,  Chaowei Xiao (2024)<br />
- **Immunization against harmful fine-tuning attacks** \[[Paper](https://arxiv.org/abs/2402.16382)\] <br />
Domenic Rosati,  Jan Wehner,  Kai Williams,  Łukasz Bartoszcze,  Jan Batzner,  Hassan Sajjad,  Frank Rudzicz (2024)<br />
- **Pruning for Protection: Increasing Jailbreak Resistance in Aligned LLMs Without Fine-Tuning** \[[Paper](https://arxiv.org/abs/2401.10862)\] <br />
Adib Hasan,  Ileana Rugina,  Alex Wang (2024)<br />
- **Jatmo: Prompt Injection Defense by Task-Specific Finetuning** \[[Paper](https://arxiv.org/abs/2312.17673)\] <br />
Julien Piet,  Maha Alrashed,  Chawin Sitawarin,  Sizhe Chen,  Zeming Wei,  Elizabeth Sun,  Basel Alomair,  David Wagner (2023)<br />
- **Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions** \[[Paper](https://arxiv.org/abs/2309.07875)\] <br />
Federico Bianchi,  Mirac Suzgun,  Giuseppe Attanasio,  Paul Röttger,  Dan Jurafsky,  Tatsunori Hashimoto,  James Zou (2023)<br />
- **Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM** \[[Paper](https://arxiv.org/abs/2309.14348)\] <br />
Bochuan Cao,  Yuanpu Cao,  Lu Lin,  Jinghui Chen (2023)<br />
- **Learn What NOT to Learn: Towards Generative Safety in Chatbots** \[[Paper](https://arxiv.org/abs/2304.1122)\] <br />
Leila Khalatbari,  Yejin Bang,  Dan Su,  Willy Chung,  Saeed Ghadimi,  Hossein Sameti,  Pascale Fung (2023)<br />
- **Emerging Safety Attack and Defense in Federated Instruction Tuning of Large Language Models** \[[Paper](https://arxiv.org/abs/2406.10630
   )\] <br />
Rui Ye,  Jingyi Chai,  Xiangrui Liu,  Yaodong Yang,  Yanfeng Wang,  Siheng Chen (2024)<br />
- **Merging Improves Self-Critique Against Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2406.07188
   )\] <br />
Victor Gallego (2024)<br />
- **Self and Cross-Model Distillation for LLMs: Effective Methods for Refusal Pattern Alignment** \[[Paper](https://arxiv.org/abs/2406.11285
   )\] <br />
Jie Li,  Yi Liu,  Chongyang Liu,  Xiaoning Ren,  Ling Shi,  Weisong Sun,  Yinxing Xue (2024)<br />
- **Learning diverse attacks on large language models for robust red-teaming and safety tuning** \[[Paper](https://arxiv.org/abs/2405.18540
   )\] <br />
Seanie Lee,  Minsu Kim,  Lynn Cherif,  David Dobre,  Juho Lee,  Sung Ju Hwang,  Kenji Kawaguchi,  Gauthier Gidel,  Yoshua Bengio,  Nikolay Malkin,  Moksh Jain (2024)<br />
- **Defending Large Language Models Against Jailbreak Attacks via Layer-specific Editing** \[[Paper](https://arxiv.org/abs/2405.18166
   )\] <br />
Wei Zhao,  Zhe Li,  Yige Li,  Ye Zhang,  Jun Sun (2024)<br />
### Unlearning
## Inference Time Defenses
### Prompting
- **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models** \[[Paper](https://arxiv.org/abs/2404.06666
   )\] <br />
Xinfeng Li,  Yuchen Yang,  Jiangyi Deng,  Chen Yan,  Yanjiao Chen,  Xiaoyu Ji,  Wenyuan Xu (2024)<br />
- **Safeguarding Vision-Language Models Against Patched Visual Prompt Injectors** \[[Paper](https://arxiv.org/abs/2405.10529
   )\] <br />
Jiachen Sun,  Changsheng Wang,  Jiongxiao Wang,  Yiwei Zhang,  Chaowei Xiao (2024)<br />
- **AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting** \[[Paper](https://arxiv.org/abs/2403.09513)\] <br />
Yu Wang,  Xiaogeng Liu,  Yu Li,  Muhao Chen,  Chaowei Xiao (2024)<br />
- **PARDEN, Can You Repeat That? Defending against Jailbreaks via Repetition** \[[Paper](https://arxiv.org/abs/2405.07932
   )\] <br />
Ziyang Zhang,  Qizhen Zhang,  Jakob Foerster (2024)<br />
- **Defensive Prompt Patch: A Robust and Interpretable Defense of LLMs against Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2405.20099
   )\] <br />
Chen Xiong,  Xiangyu Qi,  Pin-Yu Chen,  Tsung-Yi Ho (2024)<br />
- **Self-Evaluation as a Defense Against Adversarial Attacks on LLMs** \[[Paper](https://arxiv.org/abs/2407.03234
   )\] <br />
Hannah Brown,  Leon Lin,  Kenji Kawaguchi,  Michael Shieh (2024)<br />
- **Goal-guided Generative Prompt Injection Attack on Large Language Models** \[[Paper](https://arxiv.org/abs/2404.07234)\] <br />
Chong Zhang,  Mingyu Jin,  Qinkai Yu,  Chengzhi Liu,  Haochen Xue,  Xiaobo Jin (2024)<br />
- **Ensuring Safe and High-Quality Outputs: A Guideline Library Approach for Language Models** \[[Paper](https://arxiv.org/abs/2403.11838)\] <br />
Yi Luo,  Zhenghao Lin,  Yuhao Zhang,  Jiashuo Sun,  Chen Lin,  Chengjin Xu,  Xiangdong Su,  Yelong Shen,  Jian Guo,  Yeyun Gong (2024)<br />
- **Defending Against Indirect Prompt Injection Attacks With Spotlighting** \[[Paper](https://arxiv.org/abs/2403.1472)\] <br />
Keegan Hines,  Gary Lopez,  Matthew Hall,  Federico Zarfati,  Yonatan Zunger,  Emre Kiciman (2024)<br />
- **Studious Bob Fight Back Against Jailbreaking via Prompt Adversarial Tuning** \[[Paper](https://arxiv.org/abs/2402.06255)\] <br />
Yichuan Mo,  Yuji Wang,  Zeming Wei,  Yisen Wang (2024)<br />
- **StruQ: Defending Against Prompt Injection with Structured Queries** \[[Paper](https://arxiv.org/abs/2402.06363)\] <br />
Sizhe Chen,  Julien Piet,  Chawin Sitawarin,  David Wagner (2024)<br />
- **Break the Breakout: Reinventing LM Defense Against Jailbreak Attacks with Self-Refinement** \[[Paper](https://arxiv.org/abs/2402.1518)\] <br />
Heegyu Kim,  Sehyun Yuk,  Hyunsouk Cho (2024)<br />
- **Intention Analysis Makes LLMs A Good Jailbreak Defender** \[[Paper](https://arxiv.org/abs/2401.06561)\] <br />
Yuqi Zhang,  Liang Ding,  Lefei Zhang,  Dacheng Tao (2024)<br />
- **Signed-Prompt: A New Approach to Prevent Prompt Injection Attacks Against LLM-Integrated Applications** \[[Paper](https://arxiv.org/abs/2401.07612)\] <br />
Xuchen Suo (2024)<br />
- **Defending Large Language Models Against Jailbreaking Attacks Through Goal Prioritization** \[[Paper](https://arxiv.org/abs/2311.09096)\] <br />
Zhexin Zhang,  Junxiao Yang,  Pei Ke,  Fei Mi,  Hongning Wang,  Minlie Huang (2023)<br />
- **Bergeron: Combating Adversarial Attacks through a Conscience-Based Alignment Framework** \[[Paper](https://arxiv.org/abs/2312.00029)\] <br />
Matthew Pisano,  Peter Ly,  Abraham Sanders,  Bingsheng Yao,  Dakuo Wang,  Tomek Strzalkowski,  Mei Si (2023)<br />
- **Self-Guard: Empower the LLM to Safeguard Itself** \[[Paper](https://arxiv.org/abs/2310.15851)\] <br />
Zezhong Wang,  Fangkai Yang,  Lu Wang,  Pu Zhao,  Hongru Wang,  Liang Chen,  Qingwei Lin,  Kam-Fai Wong (2023)<br />
- **Using In-Context Learning to Improve Dialogue Safety** \[[Paper](https://arxiv.org/abs/2302.00871)\] <br />
Nicholas Meade,  Spandana Gella,  Devamanyu Hazarika,  Prakhar Gupta,  Di Jin,  Siva Reddy,  Yang Liu,  Dilek Hakkani-Tür (2023)<br />
- **On Prompt-Driven Safeguarding for Large Language Models** \[[Paper](https://arxiv.org/abs/2401.18018)\] <br />
Chujie Zheng,  Fan Yin,  Hao Zhou,  Fandong Meng,  Jie Zhou,  Kai-Wei Chang,  Minlie Huang,  Nanyun Peng (2024)<br />
### Ensemble
- **AutoJailbreak: Exploring Jailbreak Attacks and Defenses through a Dependency Lens** \[[Paper](https://arxiv.org/abs/2406.03805
   )\] <br />
Lin Lu,  Hai Yan,  Zenghui Yuan,  Jiawen Shi,  Wenqi Wei,  Pin-Yu Chen,  Pan Zhou (2024)<br />
- **Learn to Disguise: Avoid Refusal Responses in LLM's Defense via a Multi-agent Attacker-Disguiser Game** \[[Paper](https://arxiv.org/abs/2404.02532)\] <br />
Qianqiao Xu,  Zhiliang Tian,  Hongyan Wu,  Zhen Huang,  Yiping Song,  Feng Liu,  Dongsheng Li (2024)<br />
- **AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2403.04783)\] <br />
Yifan Zeng,  Yiran Wu,  Xiao Zhang,  Huazheng Wang,  Qingyun Wu (2024)<br />
- **Combating Adversarial Attacks with Multi-Agent Debate** \[[Paper](https://arxiv.org/abs/2401.05998)\] <br />
Steffi Chern,  Zhen Fan,  Andy Liu (2024)<br />
- **Jailbreaker in Jail: Moving Target Defense for Large Language Models** \[[Paper](https://arxiv.org/abs/2310.02417)\] <br />
Bocheng Chen,  Advait Paliwal,  Qiben Yan (2023)<br />
- **TrustAgent: Towards Safe and Trustworthy LLM-based Agents through Agent Constitution** \[[Paper](https://arxiv.org/abs/2402.01586)\] <br />
Wenyue Hua,  Xianjun Yang,  Zelong Li,  Wei Cheng,  Yongfeng Zhang (2024)<br />
### Guardrails
#### Input Guardrails
- **UFID: A Unified Framework for Input-level Backdoor Detection on Diffusion Models** \[[Paper](https://arxiv.org/abs/2404.01101)\] <br />
Zihan Guan,  Mengxuan Hu,  Sheng Li,  Anil Vullikanti (2024)<br />
- **Universal Prompt Optimizer for Safe Text-to-Image Generation** \[[Paper](https://arxiv.org/abs/2402.10882)\] <br />
Zongyu Wu,  Hongcheng Gao,  Yueze Wang,  Xiang Zhang,  Suhang Wang (2024)<br />
- **Added Toxicity Mitigation at Inference Time for Multimodal and Massively Multilingual Translation** \[[Paper](https://arxiv.org/abs/2311.06532)\] <br />
Marta R. Costa-jussà,  David Dale,  Maha Elbayad,  Bokai Yu (2023)<br />
- **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** \[[Paper](https://arxiv.org/abs/2401.02906)\] <br />
Renjie Pi,  Tianyang Han,  Jianshu Zhang,  Yueqi Xie,  Rui Pan,  Qing Lian,  Hanze Dong,  Jipeng Zhang,  Tong Zhang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou,  Kai Chen,  Zhili Liu,  Lanqing Hong,  Hang Xu,  Zhenguo Li,  Dit-Yan Yeung,  James T. Kwok,  Yu Zhang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou,  Kai Chen,  Zhili Liu,  Lanqing Hong,  Hang Xu,  Zhenguo Li,  Dit-Yan Yeung,  James T. Kwok,  Yu Zhang (2024)<br />
- **A Mutation-Based Method for Multi-Modal Jailbreaking Attack Detection** \[[Paper](https://arxiv.org/abs/2312.10766)\] <br />
Xiaoyu Zhang,  Cen Zhang,  Tianlin Li,  Yihao Huang,  Xiaojun Jia,  Ming Hu,  Jie Zhang,  Yang Liu,  Shiqing Ma,  Chao Shen (2023)<br />
- **SLM as Guardian: Pioneering AI Safety with Small Language Models** \[[Paper](https://arxiv.org/abs/2405.19795
   )\] <br />
Ohjoon Kwon,  Donghyeon Jeon,  Nayoung Choi,  Gyu-Hwung Cho,  Changbong Kim,  Hyunwoo Lee,  Inho Kang,  Sun Kim,  Taiwoo Park (2024)<br />
- **MoGU: A Framework for Enhancing Safety of Open-Sourced LLMs While Preserving Their Usability** \[[Paper](https://arxiv.org/abs/2405.14488
   )\] <br />
Yanrui Du,  Sendong Zhao,  Danyang Zhao,  Ming Ma,  Yuhan Chen,  Liangyu Huo,  Qing Yang,  Dongliang Xu,  Bing Qin (2024)<br />
- **SelfDefend: LLMs Can Defend Themselves against Jailbreaking in a Practical Manner** \[[Paper](https://arxiv.org/abs/2406.05498
   )\] <br />
Xunguang Wang,  Daoyuan Wu,  Zhenlan Ji,  Zongjie Li,  Pingchuan Ma,  Shuai Wang,  Yingjiu Li,  Yang Liu,  Ning Liu,  Juergen Rahmel (2024)<br />
- **Latent Guard: a Safety Framework for Text-to-image Generation** \[[Paper](https://arxiv.org/abs/2404.08031
   )\] <br />
Runtao Liu,  Ashkan Khakzar,  Jindong Gu,  Qifeng Chen,  Philip Torr,  Fabio Pizzati (2024)<br />
- **Tiny Refinements Elicit Resilience: Toward Efficient Prefix-Model Against LLM Red-Teaming** \[[Paper](https://arxiv.org/abs/2405.12604
   )\] <br />
Jiaxu Liu,  Xiangyu Yin,  Sihao Wu,  Jianhong Wang,  Meng Fang,  Xinping Yi,  Xiaowei Huang (2024)<br />
- **SLM as Guardian: Pioneering AI Safety with Small Language Models** \[[Paper](https://arxiv.org/abs/2405.19795
   )\] <br />
Ohjoon Kwon,  Donghyeon Jeon,  Nayoung Choi,  Gyu-Hwung Cho,  Changbong Kim,  Hyunwoo Lee,  Inho Kang,  Sun Kim,  Taiwoo Park (2024)<br />
- **Gradient Cuff: Detecting Jailbreak Attacks on Large Language Models by Exploring Refusal Loss Landscapes** \[[Paper](https://arxiv.org/abs/2403.00867)\] <br />
Xiaomeng Hu,  Pin-Yu Chen,  Tsung-Yi Ho (2024)<br />
- **Defending Jailbreak Prompts via In-Context Adversarial Game** \[[Paper](https://arxiv.org/abs/2402.13148)\] <br />
Yujun Zhou,  Yufei Han,  Haomin Zhuang,  Kehan Guo,  Zhenwen Liang,  Hongyan Bao,  Xiangliang Zhang (2024)<br />
- **Round Trip Translation Defence against Large Language Model Jailbreaking Attacks** \[[Paper](https://arxiv.org/abs/2402.13517)\] <br />
Canaan Yung,  Hadi Mohaghegh Dolatabadi,  Sarah Erfani,  Christopher Leckie (2024)<br />
- **ShieldLM: Empowering LLMs as Aligned,Customizable and Explainable Safety Detectors** \[[Paper](https://arxiv.org/abs/2402.16444)\] <br />
Zhexin Zhang,  Yida Lu,  Jingyuan Ma,  Di Zhang,  Rui Li,  Pei Ke,  Hao Sun,  Lei Sha,  Zhifang Sui,  Hongning Wang,  Minlie Huang (2024)<br />
- **Detection and Defense Against Prominent Attacks on Preconditioned LLM-Integrated Virtual Assistants** \[[Paper](https://arxiv.org/abs/2401.00994)\] <br />
Chun Fai Chan,  Daniel Wankit Yip,  Aysan Esmradi (2024)<br />
- **AI Control: Improving Safety Despite Intentional Subversion** \[[Paper](https://arxiv.org/abs/2312.06942)\] <br />
Ryan Greenblatt,  Buck Shlegeris,  Kshitij Sachan,  Fabien Roger (2023)<br />
- **Maatphor: Automated Variant Analysis for Prompt Injection Attacks** \[[Paper](https://arxiv.org/abs/2312.11513)\] <br />
Ahmed Salem,  Andrew Paverd,  Boris Köpf (2023)<br />
- **Robust Safety Classifier for Large Language Models: Adversarial Prompt Shield** \[[Paper](https://arxiv.org/abs/2311.00172)\] <br />
Jinhwa Kim,  Ali Derakhshan,  Ian G. Harris (2023)<br />
- **SPML: A DSL for Defending Language Models Against Prompt Attacks** \[[Paper](https://arxiv.org/abs/2402.11755)\] <br />
Reshabh K Sharma,  Vinayak Gupta,  Dan Grossman (2024)<br />
#### Output Guardrails
- **MirrorCheck: Efficient Adversarial Defense for Vision-Language Models** \[[Paper](https://arxiv.org/abs/2406.09250
   )\] <br />
Samar Fares,  Klea Ziu,  Toluwani Aremu,  Nikita Durasov,  Martin Takáč,  Pascal Fua,  Karthik Nandakumar,  Ivan Laptev (2024)<br />
- **Jailbreaking is Best Solved by Definition** \[[Paper](https://arxiv.org/abs/2403.14725)\] <br />
Taeyoun Kim,  Suhas Kotha,  Aditi Raghunathan (2024)<br />
- **Defending LLMs against Jailbreaking Attacks via Backtranslation** \[[Paper](https://arxiv.org/abs/2402.16459)\] <br />
Yihan Wang,  Zhouxing Shi,  Andrew Bai,  Cho-Jui Hsieh (2024)<br />
- **Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks** \[[Paper](https://arxiv.org/abs/2401.17263)\] <br />
Andy Zhou,  Bo Li,  Haohan Wang (2024)<br />
- **LLM Self Defense: By Self Examination,LLMs Know They Are Being Tricked** \[[Paper](https://arxiv.org/abs/2308.07308)\] <br />
Mansi Phute,  Alec Helbling,  Matthew Hull,  ShengYun Peng,  Sebastian Szyller,  Cory Cornelius,  Duen Horng Chau (2023)<br />
#### Input & Output Guardrails
- **TorchOpera: A Compound AI System for LLM Safety** \[[Paper](https://arxiv.org/abs/2406.10847
   )\] <br />
Shanshan Han,  Yuhang Yao,  Zijian Hu,  Dimitris Stripelis,  Zhaozhuo Xu,  Chaoyang He (2024)<br />
- **RigorLLM: Resilient Guardrails for Large Language Models against Undesired Content** \[[Paper](https://arxiv.org/abs/2403.13031)\] <br />
Zhuowen Yuan,  Zidi Xiong,  Yi Zeng,  Ning Yu,  Ruoxi Jia,  Dawn Song,  Bo Li (2024)<br />
- **Llama Guard: LLM-based Input-Output Safeguard for Human-AI Conversations** \[[Paper](https://arxiv.org/abs/2312.06674)\] <br />
Hakan Inan,  Kartikeya Upasani,  Jianfeng Chi,  Rashi Rungta,  Krithika Iyer,  Yuning Mao,  Michael Tontchev,  Qing Hu,  Brian Fuller,  Davide Testuggine,  Madian Khabsa (2023)<br />
- **NeMo Guardrails: A Toolkit for Controllable and Safe LLM Applications with Programmable Rails** \[[Paper](https://arxiv.org/abs/2310.10501)\] <br />
Traian Rebedea,  Razvan Dinu,  Makesh Sreedhar,  Christopher Parisien,  Jonathan Cohen (2023)<br />
### Defenses against Adversarial Suffix
- **Defending Large Language Models against Jailbreak Attacks via Semantic Smoothing** \[[Paper](https://arxiv.org/abs/2402.16192)\] <br />
Jiabao Ji,  Bairu Hou,  Alexander Robey,  George J. Pappas,  Hamed Hassani,  Yang Zhang,  Eric Wong,  Shiyu Chang (2024)<br />
- **Token-Level Adversarial Prompt Detection Based on Perplexity Measures and Contextual Information** \[[Paper](https://arxiv.org/abs/2311.11509)\] <br />
Zhengmian Hu,  Gang Wu,  Saayan Mitra,  Ruiyi Zhang,  Tong Sun,  Heng Huang,  Viswanathan Swaminathan (2023)<br />
- **SmoothLLM: Defending Large Language Models Against Jailbreaking Attacks** \[[Paper](https://arxiv.org/abs/2310.03684)\] <br />
Alexander Robey,  Eric Wong,  Hamed Hassani,  George J. Pappas (2023)<br />
- **Certifying LLM Safety against Adversarial Prompting** \[[Paper](https://arxiv.org/abs/2309.02705)\] <br />
Aounon Kumar,  Chirag Agarwal,  Suraj Srinivas,  Aaron Jiaxun Li,  Soheil Feizi,  Himabindu Lakkaraju (2023)<br />
- **Detecting Language Model Attacks with Perplexity** \[[Paper](https://arxiv.org/abs/2308.14132)\] <br />
Gabriel Alon,  Michael Kamfonas (2023)<br />
- **Baseline Defenses for Adversarial Attacks Against Aligned Language Models** \[[Paper](https://arxiv.org/abs/2309.00614)\] <br />
Neel Jain,  Avi Schwarzschild,  Yuxin Wen,  Gowthami Somepalli,  John Kirchenbauer,  Ping-yeh Chiang,  Micah Goldblum,  Aniruddha Saha,  Jonas Geiping,  Tom Goldstein (2023)<br />
### Decoding Defenses
- **A Framework for Real-time Safeguarding the Text Generation of Large Language Model** \[[Paper](https://arxiv.org/abs/2404.19048
   )\] <br />
Ximing Dong,  Dayi Lin,  Shaowei Wang,  Ahmed E. Hassan (2024)<br />
- **Constrained Decoding for Secure Code Generation** \[[Paper](https://arxiv.org/abs/2405.00218
   )\] <br />
Yanjun Fu,  Ethan Baker,  Yu Ding,  Yizheng Chen (2024)<br />
- **Defending Large Language Models Against Attacks With Residual Stream Activation Analysis** \[[Paper](https://arxiv.org/abs/2406.03230
   )\] <br />
Amelia Kawasaki,  Andrew Davis,  Houssam Abbas (2024)<br />
- **Adversarial Contrastive Decoding: Boosting Safety Alignment of Large Language Models via Opposite Prompt Optimization** \[[Paper](https://arxiv.org/abs/2406.16743
   )\] <br />
Zhengyue Zhao,  Xiaoyun Zhang,  Kaidi Xu,  Xing Hu,  Rui Zhang,  Zidong Du,  Qi Guo,  Yunji Chen (2024)<br />
- **SafeInfer: Context Adaptive Decoding Time Safety Alignment for Large Language Models** \[[Paper](https://arxiv.org/abs/2406.12274
   )\] <br />
Somnath Banerjee,  Soham Tripathy,  Sayan Layek,  Shanu Kumar,  Animesh Mukherjee,  Rima Hazra (2024)<br />
- **SafeAligner: Safety Alignment against Jailbreak Attacks via Response Disparity Guidance** \[[Paper](https://arxiv.org/abs/2406.18118
   )\] <br />
Caishuang Huang,  Wanxu Zhao,  Rui Zheng,  Huijie Lv,  Shihan Dou,  Sixian Li,  Xiao Wang,  Enyu Zhou,  Junjie Ye,  Yuming Yang,  Tao Gui,  Qi Zhang,  Xuanjing Huang (2024)<br />
- **Towards Safety and Helpfulness Balanced Responses via Controllable Large Language Models** \[[Paper](https://arxiv.org/abs/2404.01295)\] <br />
Yi-Lin Tuan,  Xilun Chen,  Eric Michael Smith,  Louis Martin,  Soumya Batra,  Asli Celikyilmaz,  William Yang Wang,  Daniel M. Bikel (2024)<br />
- **SafeDecoding: Defending against Jailbreak Attacks via Safety-Aware Decoding** \[[Paper](https://arxiv.org/abs/2402.08983)\] <br />
Zhangchen Xu,  Fengqing Jiang,  Luyao Niu,  Jinyuan Jia,  Bill Yuchen Lin,  Radha Poovendran (2024)<br />