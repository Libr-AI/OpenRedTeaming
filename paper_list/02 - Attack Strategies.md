# Attack Strategies
## Table of Contents
- Attack Strategies
	 - [Completion Compliance](#completion-compliance)
	 - [Instruction Indirection](#instruction-indirection)
	 - [Generalization Glide](#generalization-glide)
		 - [Languages](#languages)
		 - [Cipher](#cipher)
		 - [Personification](#personification)
	 - [Model Manipulation](#model-manipulation)
		 - [Backdoor Attacks](#backdoor-attacks)
		 - [Fine-tuning Risks](#fine-tuning-risks)
## Completion Compliance
- **Few-Shot Adversarial Prompt Learning on Vision-Language Models**\[[Paper](https://arxiv.org/abs/2403.14774)\] <br />
Yiwei Zhou, Xiaobo Xia, Zhiwei Lin, Bo Han, Tongliang Liu (2024)<br />
- **Hijacking Context in Large Multi-modal Models**\[[Paper](https://arxiv.org/abs/2312.07553)\] <br />
Joonhyun Jeong (2023)<br />
- **Great,Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack**\[[Paper](https://arxiv.org/abs/2404.01833)\] <br />
Mark Russinovich, Ahmed Salem, Ronen Eldan (2024)<br />
- **BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models**\[[Paper](https://arxiv.org/abs/2401.12242)\] <br />
Zhen Xiang, Fengqing Jiang, Zidi Xiong, Bhaskar Ramasubramanian, Radha Poovendran, Bo Li (2024)<br />
- **Universal Vulnerabilities in Large Language Models: Backdoor Attacks for In-context Learning**\[[Paper](https://arxiv.org/abs/2401.05949)\] <br />
Shuai Zhao, Meihuizi Jia, Luu Anh Tuan, Fengjun Pan, Jinming Wen (2024)<br />
- **Nevermind: Instruction Override and Moderation in Large Language Models**\[[Paper](https://arxiv.org/abs/2402.03303)\] <br />
Edward Kim (2024)<br />
- **Red-Teaming Large Language Models using Chain of Utterances for Safety-Alignment**\[[Paper](https://arxiv.org/abs/2308.09662)\] <br />
Rishabh Bhardwaj, Soujanya Poria (2023)<br />
- **Backdoor Attacks for In-Context Learning with Language Models**\[[Paper](https://arxiv.org/abs/2307.14692)\] <br />
Nikhil Kandpal, Matthew Jagielski, Florian Tramèr, Nicholas Carlini (2023)<br />
- **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations**\[[Paper](https://arxiv.org/abs/2310.06387)\] <br />
Zeming Wei, Yifei Wang, Yisen Wang (2023)<br />
- **Analyzing the Inherent Response Tendency of LLMs: Real-World Instructions-Driven Jailbreak**\[[Paper](https://arxiv.org/abs/2312.04127)\] <br />
Yanrui Du, Sendong Zhao, Ming Ma, Yuhan Chen, Bing Qin (2023)<br />
- **Bypassing the Safety Training of Open-Source LLMs with Priming Attacks**\[[Paper](https://arxiv.org/abs/2312.12321)\] <br />
Jason Vega, Isha Chaudhary, Changming Xu, Gagandeep Singh (2023)<br />
- **Hijacking Large Language Models via Adversarial In-Context Learning**\[[Paper](https://arxiv.org/abs/2311.09948)\] <br />
Yao Qiang, Xiangyu Zhou, Dongxiao Zhu (2023)<br />
## Instruction Indirection
- **On the Robustness of Large Multimodal Models Against Image Adversarial Attacks**\[[Paper](https://arxiv.org/abs/2312.03777)\] <br />
Xuanming Cui, Alejandro Aparcedo, Young Kyun Jang, Ser-Nam Lim (2023)<br />
- **Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks**\[[Paper](https://arxiv.org/abs/2402.00626)\] <br />
Maan Qraitem, Nazia Tasnim, Piotr Teterwak, Kate Saenko, Bryan A. Plummer (2024)<br />
- **Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models**\[[Paper](https://arxiv.org/abs/2403.09792)\] <br />
Yifan Li, Hangyu Guo, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen (2024)<br />
- **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts**\[[Paper](https://arxiv.org/abs/2311.05608)\] <br />
Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang (2023)<br />
- **InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models**\[[Paper](https://arxiv.org/abs/2312.01886)\] <br />
Xunguang Wang, Zhenlan Ji, Pingchuan Ma, Zongjie Li, Shuai Wang (2023)<br />
- **Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs**\[[Paper](https://arxiv.org/abs/2307.1049)\] <br />
Eugene Bagdasaryan, Tsung-Yin Hsieh, Ben Nassi, Vitaly Shmatikov (2023)<br />
- **Visual Adversarial Examples Jailbreak Aligned Large Language Models**\[[Paper](https://arxiv.org/abs/2306.13213)\] <br />
Xiangyu Qi, Kaixuan Huang, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal (2023)<br />
- **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models**\[[Paper](https://arxiv.org/abs/2307.14539)\] <br />
Erfan Shayegani, Yue Dong, Nael Abu-Ghazaleh (2023)<br />
- **Play Guessing Game with LLM: Indirect Jailbreak Attack with Implicit Clues**\[[Paper](https://arxiv.org/abs/2402.09091)\] <br />
Zhiyuan Chang, Mingyang Li, Yi Liu, Junjie Wang, Qing Wang, Yang Liu (2024)<br />
- **FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models**\[[Paper](https://arxiv.org/abs/2309.05274)\] <br />
Dongyu Yao, Jianshu Zhang, Ian G. Harris, Marcel Carlsson (2023)<br />
- **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts**\[[Paper](https://arxiv.org/abs/2309.10253)\] <br />
Jiahao Yu, Xingwei Lin, Zheng Yu, Xinyu Xing (2023)<br />
- **Prompt Packer: Deceiving LLMs through Compositional Instruction with Hidden Attacks**\[[Paper](https://arxiv.org/abs/2310.10077)\] <br />
Shuyu Jiang, Xingshu Chen, Rui Tang (2023)<br />
- **DeepInception: Hypnotize Large Language Model to Be Jailbreaker**\[[Paper](https://arxiv.org/abs/2311.03191)\] <br />
Xuan Li, Zhanke Zhou, Jianing Zhu, Jiangchao Yao, Tongliang Liu, Bo Han (2023)<br />
- **A Wolf in Sheep's Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily**\[[Paper](https://arxiv.org/abs/2311.08268)\] <br />
Peng Ding, Jun Kuang, Dan Ma, Xuezhi Cao, Yunsen Xian, Jiajun Chen, Shujian Huang (2023)<br />
- **Safety Alignment in NLP Tasks: Weakly Aligned Summarization as an In-Context Attack**\[[Paper](https://arxiv.org/abs/2312.06924)\] <br />
Yu Fu, Yufei Li, Wen Xiao, Cong Liu, Yue Dong (2023)<br />
- **Cognitive Overload: Jailbreaking Large Language Models with Overloaded Logical Thinking**\[[Paper](https://arxiv.org/abs/2311.09827)\] <br />
Nan Xu, Fei Wang, Ben Zhou, Bang Zheng Li, Chaowei Xiao, Muhao Chen (2023)<br />
## Generalization Glide
### Languages
- **A Cross-Language Investigation into Jailbreak Attacks in Large Language Models**\[[Paper](https://arxiv.org/abs/2401.16765)\] <br />
Jie Li, Yi Liu, Chongyang Liu, Ling Shi, Xiaoning Ren, Yaowen Zheng, Yang Liu, Yinxing Xue (2024)<br />
- **The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts**\[[Paper](https://arxiv.org/abs/2401.13136)\] <br />
Lingfeng Shen, Weiting Tan, Sihao Chen, Yunmo Chen, Jingyu Zhang, Haoran Xu, Boyuan Zheng, Philipp Koehn, Daniel Khashabi (2024)<br />
- **Sandwich attack: Multi-language Mixture Adaptive Attack on LLMs**\[[Paper](https://arxiv.org/abs/2404.07242)\] <br />
Bibek Upadhayay, Vahid Behzadan (2024)<br />
- **Backdoor Attack on Multilingual Machine Translation**\[[Paper](https://arxiv.org/abs/2404.02393)\] <br />
Jun Wang, Qiongkai Xu, Xuanli He, Benjamin I. P. Rubinstein, Trevor Cohn (2024)<br />
- **Multilingual Jailbreak Challenges in Large Language Models**\[[Paper](https://arxiv.org/abs/2310.06474)\] <br />
Yue Deng, Wenxuan Zhang, Sinno Jialin Pan, Lidong Bing (2023)<br />
- **Low-Resource Languages Jailbreak GPT-4**\[[Paper](https://arxiv.org/abs/2310.02446)\] <br />
Zheng-Xin Yong, Cristina Menghini, Stephen H. Bach (2023)<br />
### Cipher
- **Using Hallucinations to Bypass GPT4's Filter**\[[Paper](https://arxiv.org/abs/2403.04769)\] <br />
Benjamin Lemkin (2024)<br />
- **The Butterfly Effect of Altering Prompts: How Small Changes and Jailbreaks Affect Large Language Model Performance**\[[Paper](https://arxiv.org/abs/2401.03729)\] <br />
Abel Salinas, Fred Morstatter (2024)<br />
- **Making Them Ask and Answer: Jailbreaking Large Language Models in Few Queries via Disguise and Reconstruction**\[[Paper](https://arxiv.org/abs/2402.18104)\] <br />
Tong Liu, Yingjie Zhang, Zhe Zhao, Yinpeng Dong, Guozhu Meng, Kai Chen (2024)<br />
- **PRP: Propagating Universal Perturbations to Attack Large Language Model Guard-Rails**\[[Paper](https://arxiv.org/abs/2402.15911)\] <br />
Neal Mangaokar, Ashish Hooda, Jihye Choi, Shreyas Chandrashekaran, Kassem Fawaz, Somesh Jha, Atul Prakash (2024)<br />
- **GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher**\[[Paper](https://arxiv.org/abs/2308.06463)\] <br />
Youliang Yuan, Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Pinjia He, Shuming Shi, Zhaopeng Tu (2023)<br />
- **Punctuation Matters! Stealthy Backdoor Attack for Language Models**\[[Paper](https://arxiv.org/abs/2312.15867)\] <br />
Xuan Sheng, Zhicheng Li, Zhaoyang Han, Xiangmao Chang, Piji Li (2023)<br />
### Personification
- **Foot In The Door: Understanding Large Language Model Jailbreaking via Cognitive Psychology**\[[Paper](https://arxiv.org/abs/2402.1569)\] <br />
Zhenhua Wang, Wei Xie, Baosheng Wang, Enze Wang, Zhiwen Gui, Shuoyoucheng Ma, Kai Chen (2024)<br />
- **PsySafe: A Comprehensive Framework for Psychological-based Attack,Defense,and Evaluation of Multi-agent System Safety**\[[Paper](https://arxiv.org/abs/2401.1188)\] <br />
Zaibin Zhang, Yongting Zhang, Lijun Li, Hongzhi Gao, Lijun Wang, Huchuan Lu, Feng Zhao, Yu Qiao, Jing Shao (2024)<br />
- **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs**\[[Paper](https://arxiv.org/abs/2401.06373)\] <br />
Yi Zeng, Hongpeng Lin, Jingwen Zhang, Diyi Yang, Ruoxi Jia, Weiyan Shi (2024)<br />
- **Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation**\[[Paper](https://arxiv.org/abs/2311.03348)\] <br />
Rusheb Shah, Quentin Feuillade--Montixi, Soroush Pour, Arush Tagade, Stephen Casper, Javier Rando (2023)<br />
- **Who is ChatGPT? Benchmarking LLMs' Psychological Portrayal Using PsychoBench**\[[Paper](https://arxiv.org/abs/2310.01386)\] <br />
Jen-tse Huang, Wenxuan Wang, Eric John Li, Man Ho Lam, Shujie Ren, Youliang Yuan, Wenxiang Jiao, Zhaopeng Tu, Michael R. Lyu (2023)<br />
- **Exploiting Large Language Models (LLMs) through Deception Techniques and Persuasion Principles**\[[Paper](https://arxiv.org/abs/2311.14876)\] <br />
Sonali Singh, Faranak Abri, Akbar Siami Namin (2023)<br />
## Model Manipulation
### Backdoor Attacks
- **Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models**\[[Paper](https://arxiv.org/abs/2402.06659)\] <br />
Yuancheng Xu, Jiarui Yao, Manli Shu, Yanchao Sun, Zichu Wu, Ning Yu, Tom Goldstein, Furong Huang (2024)<br />
- **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training**\[[Paper](https://arxiv.org/abs/2401.05566)\] <br />
Evan Hubinger, Carson Denison, Jesse Mu, Mike Lambert, Meg Tong, Monte MacDiarmid, Tamera Lanham, Daniel M. Ziegler, Tim Maxwell, Newton Cheng, Adam Jermyn, Amanda Askell, Ansh Radhakrishnan, Cem Anil, David Duvenaud, Deep Ganguli, Fazl Barez, Jack Clark, Kamal Ndousse, Kshitij Sachan, Michael Sellitto, Mrinank Sharma, Nova DasSarma, Roger Grosse, Shauna Kravec, Yuntao Bai, Zachary Witten, Marina Favaro, Jan Brauner, Holden Karnofsky, Paul Christiano, Samuel R. Bowman, Logan Graham, Jared Kaplan, Sören Mindermann, Ryan Greenblatt, Buck Shlegeris, Nicholas Schiefer, Ethan Perez (2024)<br />
- **What's in Your "Safe" Data?: Identifying Benign Data that Breaks Safety**\[[Paper](https://arxiv.org/abs/2404.01099)\] <br />
Luxi He, Mengzhou Xia, Peter Henderson (2024)<br />
- **Data Poisoning Attacks on Off-Policy Policy Evaluation Methods**\[[Paper](https://arxiv.org/abs/2404.04714)\] <br />
Elita Lobo, Harvineet Singh, Marek Petrik, Cynthia Rudin, Himabindu Lakkaraju (2024)<br />
- **BadEdit: Backdooring large language models by model editing**\[[Paper](https://arxiv.org/abs/2403.13355)\] <br />
Yanzhou Li, Tianlin Li, Kangjie Chen, Jian Zhang, Shangqing Liu, Wenhan Wang, Tianwei Zhang, Yang Liu (2024)<br />
- **Best-of-Venom: Attacking RLHF by Injecting Poisoned Preference Data**\[[Paper](https://arxiv.org/abs/2404.0553)\] <br />
Tim Baumgärtner, Yang Gao, Dana Alon, Donald Metzler (2024)<br />
- **Learning to Poison Large Language Models During Instruction Tuning**\[[Paper](https://arxiv.org/abs/2402.13459)\] <br />
Yao Qiang, Xiangyu Zhou, Saleh Zare Zade, Mohammad Amin Roshani, Douglas Zytko, Dongxiao Zhu (2024)<br />
- **Exploring Backdoor Vulnerabilities of Chat Models**\[[Paper](https://arxiv.org/abs/2404.02406)\] <br />
Yunzhuo Hao, Wenkai Yang, Yankai Lin (2024)<br />
- **Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models**\[[Paper](https://arxiv.org/abs/2305.1471)\] <br />
Jiashu Xu, Mingyu Derek Ma, Fei Wang, Chaowei Xiao, Muhao Chen (2023)<br />
- **Forcing Generative Models to Degenerate Ones: The Power of Data Poisoning Attacks**\[[Paper](https://arxiv.org/abs/2312.04748)\] <br />
Shuli Jiang, Swanand Ravindra Kadhe, Yi Zhou, Ling Cai, Nathalie Baracaldo (2023)<br />
- **Stealthy and Persistent Unalignment on Large Language Models via Backdoor Injections**\[[Paper](https://arxiv.org/abs/2312.00027)\] <br />
Yuanpu Cao, Bochuan Cao, Jinghui Chen (2023)<br />
- **Backdoor Activation Attack: Attack Large Language Models using Activation Steering for Safety-Alignment**\[[Paper](https://arxiv.org/abs/2311.09433)\] <br />
Haoran Wang, Kai Shu (2023)<br />
- **On the Exploitability of Reinforcement Learning with Human Feedback for Large Language Models**\[[Paper](https://arxiv.org/abs/2311.09641)\] <br />
Jiongxiao Wang, Junlin Wu, Muhao Chen, Yevgeniy Vorobeychik, Chaowei Xiao (2023)<br />
- **Test-time Backdoor Mitigation for Black-Box Large Language Models with Defensive Demonstrations**\[[Paper](https://arxiv.org/abs/2311.09763)\] <br />
Wenjie Mo, Jiashu Xu, Qin Liu, Jiongxiao Wang, Jun Yan, Chaowei Xiao, Muhao Chen (2023)<br />
- **Universal Jailbreak Backdoors from Poisoned Human Feedback**\[[Paper](https://arxiv.org/abs/2311.14455)\] <br />
Javier Rando, Florian Tramèr (2023)<br />
### Fine-tuning Risks
- **LoRA-as-an-Attack! Piercing LLM Safety Under The Share-and-Play Scenario**\[[Paper](https://arxiv.org/abs/2403.00108)\] <br />
Hongyi Liu, Zirui Liu, Ruixiang Tang, Jiayi Yuan, Shaochen Zhong, Yu-Neng Chuang, Li Li, Rui Chen, Xia Hu (2024)<br />
- **Emulated Disalignment: Safety Alignment for Large Language Models May Backfire!**\[[Paper](https://arxiv.org/abs/2402.12343)\] <br />
Zhanhui Zhou, Jie Liu, Zhichen Dong, Jiaheng Liu, Chao Yang, Wanli Ouyang, Yu Qiao (2024)<br />
- **LoRA Fine-tuning Efficiently Undoes Safety Training in Llama 2-Chat 70B**\[[Paper](https://arxiv.org/abs/2310.20624)\] <br />
Simon Lermen, Charlie Rogers-Smith, Jeffrey Ladish (2023)<br />
- **BadLlama: cheaply removing safety fine-tuning from Llama 2-Chat 13B**\[[Paper](https://arxiv.org/abs/2311.00117)\] <br />
Pranav Gade, Simon Lermen, Charlie Rogers-Smith, Jeffrey Ladish (2023)<br />
- **Language Model Unalignment: Parametric Red-Teaming to Expose Hidden Harms and Biases**\[[Paper](https://arxiv.org/abs/2310.14303)\] <br />
Rishabh Bhardwaj, Soujanya Poria (2023)<br />
- **Removing RLHF Protections in GPT-4 via Fine-Tuning**\[[Paper](https://arxiv.org/abs/2311.05553)\] <br />
Qiusi Zhan, Richard Fang, Rohan Bindu, Akul Gupta, Tatsunori Hashimoto, Daniel Kang (2023)<br />
- **On the Safety of Open-Sourced Large Language Models: Does Alignment Really Prevent Them From Being Misused?**\[[Paper](https://arxiv.org/abs/2310.01581)\] <br />
Hangfan Zhang, Zhimeng Guo, Huaisheng Zhu, Bochuan Cao, Lu Lin, Jinyuan Jia, Jinghui Chen, Dinghao Wu (2023)<br />
- **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models**\[[Paper](https://arxiv.org/abs/2310.02949)\] <br />
Xianjun Yang, Xiao Wang, Qi Zhang, Linda Petzold, William Yang Wang, Xun Zhao, Dahua Lin (2023)<br />
- **Fine-tuning Aligned Language Models Compromises Safety,Even When Users Do Not Intend To!**\[[Paper](https://arxiv.org/abs/2310.03693)\] <br />
Xiangyu Qi, Yi Zeng, Tinghao Xie, Pin-Yu Chen, Ruoxi Jia, Prateek Mittal, Peter Henderson (2023)<br />