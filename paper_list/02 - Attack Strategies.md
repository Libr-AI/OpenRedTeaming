# Attack Strategies
## Table of Contents
- Attack Strategies
	 - [Completion Compliance](#completion-compliance)
		 - [In-Context Learning](#in-context-learning)
		 - [Multi turn Dialog](#multi-turn-dialog)
		 - [Special Tokens](#special-tokens)
	 - [Instruction Indirection](#instruction-indirection)
	 - [Generalization Glide](#generalization-glide)
		 - [Languages](#languages)
		 - [Cipher](#cipher)
		 - [Personification](#personification)
	 - [Model Manipulation](#model-manipulation)
		 - [Backdoor Attacks](#backdoor-attacks)
		 - [Model Fine-tuning](#model-fine-tuning)
		 - [Activations Manipulation](#activations-manipulation)
## Completion Compliance
### In-Context Learning
- **Few-Shot Adversarial Prompt Learning on Vision-Language Models** \[[Paper](https://arxiv.org/abs/2403.14774)\] <br />
Yiwei Zhou,  Xiaobo Xia,  Zhiwei Lin,  Bo Han,  Tongliang Liu (2024)<br />
- **Hijacking Context in Large Multi-modal Models** \[[Paper](https://arxiv.org/abs/2312.07553)\] <br />
Joonhyun Jeong (2023)<br />
- **Backdoor Attacks for In-Context Learning with Language Models** \[[Paper](https://arxiv.org/abs/2307.14692)\] <br />
Nikhil Kandpal,  Matthew Jagielski,  Florian Tramèr,  Nicholas Carlini (2023)<br />
- **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations** \[[Paper](https://arxiv.org/abs/2310.06387)\] <br />
Zeming Wei,  Yifei Wang,  Ang Li,  Yichuan Mo,  Yisen Wang (2023)<br />
- **Hijacking Large Language Models via Adversarial In-Context Learning** \[[Paper](https://arxiv.org/abs/2311.09948)\] <br />
Yao Qiang,  Xiangyu Zhou,  Dongxiao Zhu (2023)<br />
- **Analyzing the Inherent Response Tendency of LLMs: Real-World Instructions-Driven Jailbreak** \[[Paper](https://arxiv.org/abs/2312.04127)\] <br />
Yanrui Du,  Sendong Zhao,  Ming Ma,  Yuhan Chen,  Bing Qin (2023)<br />
- **Bypassing the Safety Training of Open-Source LLMs with Priming Attacks** \[[Paper](https://arxiv.org/abs/2312.12321)\] <br />
Jason Vega,  Isha Chaudhary,  Changming Xu,  Gagandeep Singh (2023)<br />
- **Improved Few-Shot Jailbreaking Can Circumvent Aligned Language Models and Their Defenses** \[[Paper](https://arxiv.org/abs/2406.01288
   )\] <br />
Xiaosen Zheng,  Tianyu Pang,  Chao Du,  Qian Liu,  Jing Jiang,  Min Lin (2024)<br />
- **Don't Say No: Jailbreaking LLM by Suppressing Refusal** \[[Paper](https://arxiv.org/abs/2404.16369
   )\] <br />
Yukai Zhou,  Wenjie Wang (2024)<br />
- **Improved Generation of Adversarial Examples Against Safety-aligned LLMs** \[[Paper](https://arxiv.org/abs/2405.20778
   )\] <br />
Qizhang Li,  Yiwen Guo,  Wangmeng Zuo,  Hao Chen (2024)<br />
- **Large Language Models Are Involuntary Truth-Tellers: Exploiting Fallacy Failure for Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2407.00869
   )\] <br />
Yue Zhou,  Henry Peng Zou,  Barbara Di Eugenio,  Yang Zhang (2024)<br />
- **Universal Vulnerabilities in Large Language Models: Backdoor Attacks for In-context Learning** \[[Paper](https://arxiv.org/abs/2401.05949)\] <br />
Shuai Zhao,  Meihuizi Jia,  Luu Anh Tuan,  Fengjun Pan,  Jinming Wen (2024)<br />
### Multi turn Dialog
- **Investigating the prompt leakage effect and black-box defenses for multi-turn LLM interactions** \[[Paper](https://arxiv.org/abs/2404.16251
   )\] <br />
Divyansh Agarwal,  Alexander R. Fabbri,  Philippe Laban,  Ben Risher,  Shafiq Joty,  Caiming Xiong,  Chien-Sheng Wu (2024)<br />
- **CoSafe: Evaluating Large Language Model Safety in Multi-Turn Dialogue Coreference** \[[Paper](https://arxiv.org/abs/2406.17626
   )\] <br />
Erxin Yu,  Jing Li,  Ming Liao,  Siqi Wang,  Zuchen Gao,  Fei Mi,  Lanqing Hong (2024)<br />
- **Chain of Attack: a Semantic-Driven Contextual Multi-Turn attacker for LLM** \[[Paper](https://arxiv.org/abs/2405.05610
   )\] <br />
Xikang Yang,  Xuehai Tang,  Songlin Hu,  Jizhong Han (2024)<br />
- **Great,Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack** \[[Paper](https://arxiv.org/abs/2404.01833)\] <br />
Mark Russinovich,  Ahmed Salem,  Ronen Eldan (2024)<br />
- **BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models** \[[Paper](https://arxiv.org/abs/2401.12242)\] <br />
Zhen Xiang,  Fengqing Jiang,  Zidi Xiong,  Bhaskar Ramasubramanian,  Radha Poovendran,  Bo Li (2024)<br />
- **Red-Teaming Large Language Models using Chain of Utterances for Safety-Alignment** \[[Paper](https://arxiv.org/abs/2308.09662)\] <br />
Rishabh Bhardwaj,  Soujanya Poria (2023)<br />
### Special Tokens
- **Enhancing Jailbreak Attack Against Large Language Models through Silent Tokens** \[[Paper](https://arxiv.org/abs/2405.20653
   )\] <br />
Jiahao Yu,  Haozheng Luo,  Jerry Yao-Chieh Hu,  Wenbo Guo,  Han Liu,  Xinyu Xing (2024)<br />
- **Talk Too Much: Poisoning Large Language Models under Token Limit** \[[Paper](https://arxiv.org/abs/2404.14795
   )\] <br />
Jiaming He,  Wenbo Jiang,  Guanyu Hou,  Wenshu Fan,  Rui Zhang,  Hongwei Li (2024)<br />
- **ChatBug: A Common Vulnerability of Aligned LLMs Induced by Chat Templates** \[[Paper](https://arxiv.org/abs/2406.12935
   )\] <br />
Fengqing Jiang,  Zhangchen Xu,  Luyao Niu,  Bill Yuchen Lin,  Radha Poovendran (2024)<br />
- **Not All Prompts Are Secure: A Switchable Backdoor Attack Against Pre-trained Vision Transformers** \[[Paper](https://arxiv.org/abs/2405.10612
   )\] <br />
Sheng Yang,  Jiawang Bai,  Kuofeng Gao,  Yong Yang,  Yiming Li,  Shu-tao Xia (2024)<br />
## Instruction Indirection
- **On the Robustness of Large Multimodal Models Against Image Adversarial Attacks** \[[Paper](https://arxiv.org/abs/2312.03777)\] <br />
Xuanming Cui,  Alejandro Aparcedo,  Young Kyun Jang,  Ser-Nam Lim (2023)<br />
- **Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2403.09792)\] <br />
Yifan Li,  Hangyu Guo,  Kun Zhou,  Wayne Xin Zhao,  Ji-Rong Wen (2024)<br />
- **Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks** \[[Paper](https://arxiv.org/abs/2402.00626)\] <br />
Maan Qraitem,  Nazia Tasnim,  Piotr Teterwak,  Kate Saenko,  Bryan A. Plummer (2024)<br />
- **Visual Adversarial Examples Jailbreak Aligned Large Language Models** \[[Paper](https://arxiv.org/abs/2306.13213)\] <br />
Xiangyu Qi,  Kaixuan Huang,  Ashwinee Panda,  Peter Henderson,  Mengdi Wang,  Prateek Mittal (2023)<br />
- **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** \[[Paper](https://arxiv.org/abs/2307.14539)\] <br />
Erfan Shayegani,  Yue Dong,  Nael Abu-Ghazaleh (2023)<br />
- **InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models** \[[Paper](https://arxiv.org/abs/2312.01886)\] <br />
Xunguang Wang,  Zhenlan Ji,  Pingchuan Ma,  Zongjie Li,  Shuai Wang (2023)<br />
- **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** \[[Paper](https://arxiv.org/abs/2311.05608)\] <br />
Yichen Gong,  Delong Ran,  Jinyuan Liu,  Conglei Wang,  Tianshuo Cong,  Anyu Wang,  Sisi Duan,  Xiaoyun Wang (2023)<br />
- **Cross-Modality Jailbreak and Mismatched Attacks on Medical Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2405.20775
   )\] <br />
Xijie Huang,  Xinyuan Wang,  Hantao Zhang,  Jiawen Xi,  Jingkun An,  Hao Wang,  Chengwei Pan (2024)<br />
- **Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs** \[[Paper](https://arxiv.org/abs/2307.1049)\] <br />
Eugene Bagdasaryan,  Tsung-Yin Hsieh,  Ben Nassi,  Vitaly Shmatikov (2023)<br />
- **Image-to-Text Logic Jailbreak: Your Imagination can Help You Do Anything** \[[Paper](https://arxiv.org/abs/2407.02534
   )\] <br />
Xiaotian Zou,  Yongkang Chen (2024)<br />
- **From LLMs to MLLMs: Exploring the Landscape of Multimodal Jailbreaking** \[[Paper](https://arxiv.org/abs/2406.14859
   )\] <br />
Siyuan Wang,  Zhuohan Long,  Zhihao Fan,  Zhongyu Wei (2024)<br />
- **Unveiling the Safety of GPT-4o: An Empirical Study using Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2406.06302
   )\] <br />
Zonghao Ying,  Aishan Liu,  Xianglong Liu,  Dacheng Tao (2024)<br />
- **Voice Jailbreak Attacks Against GPT-4o** \[[Paper](https://arxiv.org/abs/2405.19103
   )\] <br />
Xinyue Shen,  Yixin Wu,  Michael Backes,  Yang Zhang (2024)<br />
- **Nevermind: Instruction Override and Moderation in Large Language Models** \[[Paper](https://arxiv.org/abs/2402.03303)\] <br />
Edward Kim (2024)<br />
- **Can LLMs Deeply Detect Complex Malicious Queries? A Framework for Jailbreaking via Obfuscating Intent** \[[Paper](https://arxiv.org/abs/2405.03654
   )\] <br />
Shang Shang,  Xinqiang Zhao,  Zhongjiang Yao,  Yepeng Yao,  Liya Su,  Zijing Fan,  Xiaodan Zhang,  Zhengwei Jiang (2024)<br />
- **Hidden You Malicious Goal Into Benign Narratives: Jailbreak Large Language Models through Logic Chain Injection** \[[Paper](https://arxiv.org/abs/2404.04849
   )\] <br />
Zhilong Wang,  Yebo Cao,  Peng Liu (2024)<br />
- **ObscurePrompt: Jailbreaking Large Language Models via Obscure Input** \[[Paper](https://arxiv.org/abs/2406.13662
   )\] <br />
Yue Huang,  Jingyu Tang,  Dongping Chen,  Bingda Tang,  Yao Wan,  Lichao Sun,  Xiangliang Zhang (2024)<br />
- **Preemptive Answer "Attacks" on Chain-of-Thought Reasoning** \[[Paper](https://arxiv.org/abs/2405.20902
   )\] <br />
Rongwu Xu,  Zehan Qi,  Wei Xu (2024)<br />
- **Play Guessing Game with LLM: Indirect Jailbreak Attack with Implicit Clues** \[[Paper](https://arxiv.org/abs/2402.09091)\] <br />
Zhiyuan Chang,  Mingyang Li,  Yi Liu,  Junjie Wang,  Qing Wang,  Yang Liu (2024)<br />
- **Safety Alignment in NLP Tasks: Weakly Aligned Summarization as an In-Context Attack** \[[Paper](https://arxiv.org/abs/2312.06924)\] <br />
Yu Fu,  Yufei Li,  Wen Xiao,  Cong Liu,  Yue Dong (2023)<br />
- **DeepInception: Hypnotize Large Language Model to Be Jailbreaker** \[[Paper](https://arxiv.org/abs/2311.03191)\] <br />
Xuan Li,  Zhanke Zhou,  Jianing Zhu,  Jiangchao Yao,  Tongliang Liu,  Bo Han (2023)<br />
- **A Wolf in Sheep's Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily** \[[Paper](https://arxiv.org/abs/2311.08268)\] <br />
Peng Ding,  Jun Kuang,  Dan Ma,  Xuezhi Cao,  Yunsen Xian,  Jiajun Chen,  Shujian Huang (2023)<br />
- **Prompt Packer: Deceiving LLMs through Compositional Instruction with Hidden Attacks** \[[Paper](https://arxiv.org/abs/2310.10077)\] <br />
Shuyu Jiang,  Xingshu Chen,  Rui Tang (2023)<br />
- **FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models** \[[Paper](https://arxiv.org/abs/2309.05274)\] <br />
Dongyu Yao,  Jianshu Zhang,  Ian G. Harris,  Marcel Carlsson (2023)<br />
- **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts** \[[Paper](https://arxiv.org/abs/2309.10253)\] <br />
Jiahao Yu,  Xingwei Lin,  Zheng Yu,  Xinyu Xing (2023)<br />
- **Cognitive Overload: Jailbreaking Large Language Models with Overloaded Logical Thinking** \[[Paper](https://arxiv.org/abs/2311.09827)\] <br />
Nan Xu,  Fei Wang,  Ben Zhou,  Bang Zheng Li,  Chaowei Xiao,  Muhao Chen (2023)<br />
## Generalization Glide
### Languages
- **Jailbreaking LLMs with Arabic Transliteration and Arabizi** \[[Paper](https://arxiv.org/abs/2406.18725
   )\] <br />
Mansour Al Ghanim,  Saleh Almohaimeed,  Mengxin Zheng,  Yan Solihin,  Qian Lou (2024)<br />
- **Backdoor Attack on Multilingual Machine Translation** \[[Paper](https://arxiv.org/abs/2404.02393)\] <br />
Jun Wang,  Qiongkai Xu,  Xuanli He,  Benjamin I. P. Rubinstein,  Trevor Cohn (2024)<br />
- **Sandwich attack: Multi-language Mixture Adaptive Attack on LLMs** \[[Paper](https://arxiv.org/abs/2404.07242)\] <br />
Bibek Upadhayay,  Vahid Behzadan (2024)<br />
- **The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts** \[[Paper](https://arxiv.org/abs/2401.13136)\] <br />
Lingfeng Shen,  Weiting Tan,  Sihao Chen,  Yunmo Chen,  Jingyu Zhang,  Haoran Xu,  Boyuan Zheng,  Philipp Koehn,  Daniel Khashabi (2024)<br />
- **A Cross-Language Investigation into Jailbreak Attacks in Large Language Models** \[[Paper](https://arxiv.org/abs/2401.16765)\] <br />
Jie Li,  Yi Liu,  Chongyang Liu,  Ling Shi,  Xiaoning Ren,  Yaowen Zheng,  Yang Liu,  Yinxing Xue (2024)<br />
- **Low-Resource Languages Jailbreak GPT-4** \[[Paper](https://arxiv.org/abs/2310.02446)\] <br />
Zheng-Xin Yong,  Cristina Menghini,  Stephen H. Bach (2023)<br />
- **Multilingual Jailbreak Challenges in Large Language Models** \[[Paper](https://arxiv.org/abs/2310.06474)\] <br />
Yue Deng,  Wenxuan Zhang,  Sinno Jialin Pan,  Lidong Bing (2023)<br />
### Cipher
- **Using Hallucinations to Bypass GPT4's Filter** \[[Paper](https://arxiv.org/abs/2403.04769)\] <br />
Benjamin Lemkin (2024)<br />
- **The Butterfly Effect of Altering Prompts: How Small Changes and Jailbreaks Affect Large Language Model Performance** \[[Paper](https://arxiv.org/abs/2401.03729)\] <br />
Abel Salinas,  Fred Morstatter (2024)<br />
- **Punctuation Matters! Stealthy Backdoor Attack for Language Models** \[[Paper](https://arxiv.org/abs/2312.15867)\] <br />
Xuan Sheng,  Zhicheng Li,  Zhaoyang Han,  Xiangmao Chang,  Piji Li (2023)<br />
- **GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher** \[[Paper](https://arxiv.org/abs/2308.06463)\] <br />
Youliang Yuan,  Wenxiang Jiao,  Wenxuan Wang,  Jen-tse Huang,  Pinjia He,  Shuming Shi,  Zhaopeng Tu (2023)<br />
- **Making Them Ask and Answer: Jailbreaking Large Language Models in Few Queries via Disguise and Reconstruction** \[[Paper](https://arxiv.org/abs/2402.18104)\] <br />
Tong Liu,  Yingjie Zhang,  Zhe Zhao,  Yinpeng Dong,  Guozhu Meng,  Kai Chen (2024)<br />
- **PRP: Propagating Universal Perturbations to Attack Large Language Model Guard-Rails** \[[Paper](https://arxiv.org/abs/2402.15911)\] <br />
Neal Mangaokar,  Ashish Hooda,  Jihye Choi,  Shreyas Chandrashekaran,  Kassem Fawaz,  Somesh Jha,  Atul Prakash (2024)<br />
- **Jailbreaking Large Language Models Against Moderation Guardrails via Cipher Characters** \[[Paper](https://arxiv.org/abs/2405.20413
   )\] <br />
Haibo Jin,  Andy Zhou,  Joe D. Menke,  Haohan Wang (2024)<br />
- **Revisiting character-level adversarial attacks** \[[Paper](https://arxiv.org/abs/2405.04346
   )\] <br />
Elias Abad Rocamora,  Yongtao Wu,  Fanghui Liu,  Grigorios G. Chrysos,  Volkan Cevher (2024)<br />
- **Single Character Perturbations Break LLM Alignment** \[[Paper](https://arxiv.org/abs/2407.03232
   )\] <br />
Leon Lin,  Hannah Brown,  Kenji Kawaguchi,  Michael Shieh (2024)<br />
- **Enhance Robustness of Language Models Against Variation Attack through Graph Integration** \[[Paper](https://arxiv.org/abs/2404.12014
   )\] <br />
Zi Xiong,  Lizhi Qing,  Yangyang Kang,  Jiawei Liu,  Hongsong Li,  Changlong Sun,  Xiaozhong Liu,  Wei Lu (2024)<br />
### Personification
- **Exploiting Large Language Models (LLMs) through Deception Techniques and Persuasion Principles** \[[Paper](https://arxiv.org/abs/2311.14876)\] <br />
Sonali Singh,  Faranak Abri,  Akbar Siami Namin (2023)<br />
- **Who is ChatGPT? Benchmarking LLMs' Psychological Portrayal Using PsychoBench** \[[Paper](https://arxiv.org/abs/2310.01386)\] <br />
Jen-tse Huang,  Wenxuan Wang,  Eric John Li,  Man Ho Lam,  Shujie Ren,  Youliang Yuan,  Wenxiang Jiao,  Zhaopeng Tu,  Michael R. Lyu (2023)<br />
- **Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation** \[[Paper](https://arxiv.org/abs/2311.03348)\] <br />
Rusheb Shah,  Quentin Feuillade--Montixi,  Soroush Pour,  Arush Tagade,  Stephen Casper,  Javier Rando (2023)<br />
- **PsySafe: A Comprehensive Framework for Psychological-based Attack,Defense,and Evaluation of Multi-agent System Safety** \[[Paper](https://arxiv.org/abs/2401.1188)\] <br />
Zaibin Zhang,  Yongting Zhang,  Lijun Li,  Hongzhi Gao,  Lijun Wang,  Huchuan Lu,  Feng Zhao,  Yu Qiao,  Jing Shao (2024)<br />
- **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs** \[[Paper](https://arxiv.org/abs/2401.06373)\] <br />
Yi Zeng,  Hongpeng Lin,  Jingwen Zhang,  Diyi Yang,  Ruoxi Jia,  Weiyan Shi (2024)<br />
- **Foot In The Door: Understanding Large Language Model Jailbreaking via Cognitive Psychology** \[[Paper](https://arxiv.org/abs/2402.1569)\] <br />
Zhenhua Wang,  Wei Xie,  Baosheng Wang,  Enze Wang,  Zhiwen Gui,  Shuoyoucheng Ma,  Kai Chen (2024)<br />
- **Evaluating Implicit Bias in Large Language Models by Attacking From a Psychometric Perspective** \[[Paper](https://arxiv.org/abs/2406.14023
   )\] <br />
Yuchen Wen,  Keping Bi,  Wei Chen,  Jiafeng Guo,  Xueqi Cheng (2024)<br />
- **SoP: Unlock the Power of Social Facilitation for Automatic Jailbreak Attack** \[[Paper](https://arxiv.org/abs/2407.01902
   )\] <br />
Yan Yang,  Zeguan Xiao,  Xin Lu,  Hongru Wang,  Hailiang Huang,  Guanhua Chen,  Yun Chen (2024)<br />
- **Defending Against Social Engineering Attacks in the Age of LLMs** \[[Paper](https://arxiv.org/abs/2406.12263
   )\] <br />
Lin Ai,  Tharindu Kumarage,  Amrita Bhattacharjee,  Zizhou Liu,  Zheng Hui,  Michael Davinroy,  James Cook,  Laura Cassani,  Kirill Trapeznikov,  Matthias Kirchner,  Arslan Basharat,  Anthony Hoogs,  Joshua Garland,  Huan Liu,  Julia Hirschberg (2024)<br />
## Model Manipulation
### Backdoor Attacks
- **Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models** \[[Paper](https://arxiv.org/abs/2402.06659)\] <br />
Yuancheng Xu,  Jiarui Yao,  Manli Shu,  Yanchao Sun,  Zichu Wu,  Ning Yu,  Tom Goldstein,  Furong Huang (2024)<br />
- **Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models** \[[Paper](https://arxiv.org/abs/2404.12916
   )\] <br />
Zhenyang Ni,  Rui Ye,  Yuxi Wei,  Zhen Xiang,  Yanfeng Wang,  Siheng Chen (2024)<br />
- **What's in Your "Safe" Data?: Identifying Benign Data that Breaks Safety** \[[Paper](https://arxiv.org/abs/2404.01099)\] <br />
Luxi He,  Mengzhou Xia,  Peter Henderson (2024)<br />
- **Exploring Backdoor Vulnerabilities of Chat Models** \[[Paper](https://arxiv.org/abs/2404.02406)\] <br />
Yunzhuo Hao,  Wenkai Yang,  Yankai Lin (2024)<br />
- **Data Poisoning Attacks on Off-Policy Policy Evaluation Methods** \[[Paper](https://arxiv.org/abs/2404.04714)\] <br />
Elita Lobo,  Harvineet Singh,  Marek Petrik,  Cynthia Rudin,  Himabindu Lakkaraju (2024)<br />
- **Best-of-Venom: Attacking RLHF by Injecting Poisoned Preference Data** \[[Paper](https://arxiv.org/abs/2404.0553)\] <br />
Tim Baumgärtner,  Yang Gao,  Dana Alon,  Donald Metzler (2024)<br />
- **BadEdit: Backdooring large language models by model editing** \[[Paper](https://arxiv.org/abs/2403.13355)\] <br />
Yanzhou Li,  Tianlin Li,  Kangjie Chen,  Jian Zhang,  Shangqing Liu,  Wenhan Wang,  Tianwei Zhang,  Yang Liu (2024)<br />
- **Learning to Poison Large Language Models During Instruction Tuning** \[[Paper](https://arxiv.org/abs/2402.13459)\] <br />
Yao Qiang,  Xiangyu Zhou,  Saleh Zare Zade,  Mohammad Amin Roshani,  Douglas Zytko,  Dongxiao Zhu (2024)<br />
- **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training** \[[Paper](https://arxiv.org/abs/2401.05566)\] <br />
Evan Hubinger,  Carson Denison,  Jesse Mu,  Mike Lambert,  Meg Tong,  Monte MacDiarmid,  Tamera Lanham,  Daniel M. Ziegler,  Tim Maxwell,  Newton Cheng,  Adam Jermyn,  Amanda Askell,  Ansh Radhakrishnan,  Cem Anil,  David Duvenaud,  Deep Ganguli,  Fazl Barez,  Jack Clark,  Kamal Ndousse,  Kshitij Sachan,  Michael Sellitto,  Mrinank Sharma,  Nova DasSarma,  Roger Grosse,  Shauna Kravec,  Yuntao Bai,  Zachary Witten,  Marina Favaro,  Jan Brauner,  Holden Karnofsky,  Paul Christiano,  Samuel R. Bowman,  Logan Graham,  Jared Kaplan,  Sören Mindermann,  Ryan Greenblatt,  Buck Shlegeris,  Nicholas Schiefer,  Ethan Perez (2024)<br />
- **Forcing Generative Models to Degenerate Ones: The Power of Data Poisoning Attacks** \[[Paper](https://arxiv.org/abs/2312.04748)\] <br />
Shuli Jiang,  Swanand Ravindra Kadhe,  Yi Zhou,  Ling Cai,  Nathalie Baracaldo (2023)<br />
- **Backdoor Activation Attack: Attack Large Language Models using Activation Steering for Safety-Alignment** \[[Paper](https://arxiv.org/abs/2311.09433)\] <br />
Haoran Wang,  Kai Shu (2023)<br />
- **On the Exploitability of Reinforcement Learning with Human Feedback for Large Language Models** \[[Paper](https://arxiv.org/abs/2311.09641)\] <br />
Jiongxiao Wang,  Junlin Wu,  Muhao Chen,  Yevgeniy Vorobeychik,  Chaowei Xiao (2023)<br />
- **Test-time Backdoor Mitigation for Black-Box Large Language Models with Defensive Demonstrations** \[[Paper](https://arxiv.org/abs/2311.09763)\] <br />
Wenjie Mo,  Jiashu Xu,  Qin Liu,  Jiongxiao Wang,  Jun Yan,  Chaowei Xiao,  Muhao Chen (2023)<br />
- **Universal Jailbreak Backdoors from Poisoned Human Feedback** \[[Paper](https://arxiv.org/abs/2311.14455)\] <br />
Javier Rando,  Florian Tramèr (2023)<br />
- **Stealthy and Persistent Unalignment on Large Language Models via Backdoor Injections** \[[Paper](https://arxiv.org/abs/2312.00027)\] <br />
Yuanpu Cao,  Bochuan Cao,  Jinghui Chen (2023)<br />
- **Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models** \[[Paper](https://arxiv.org/abs/2305.1471)\] <br />
Jiashu Xu,  Mingyu Derek Ma,  Fei Wang,  Chaowei Xiao,  Muhao Chen (2023)<br />
### Model Fine-tuning
- **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models** \[[Paper](https://arxiv.org/abs/2310.02949)\] <br />
Xianjun Yang,  Xiao Wang,  Qi Zhang,  Linda Petzold,  William Yang Wang,  Xun Zhao,  Dahua Lin (2023)<br />
- **Fine-tuning Aligned Language Models Compromises Safety,Even When Users Do Not Intend To!** \[[Paper](https://arxiv.org/abs/2310.03693)\] <br />
Xiangyu Qi,  Yi Zeng,  Tinghao Xie,  Pin-Yu Chen,  Ruoxi Jia,  Prateek Mittal,  Peter Henderson (2023)<br />
- **Language Model Unalignment: Parametric Red-Teaming to Expose Hidden Harms and Biases** \[[Paper](https://arxiv.org/abs/2310.14303)\] <br />
Rishabh Bhardwaj,  Soujanya Poria (2023)<br />
- **LoRA Fine-tuning Efficiently Undoes Safety Training in Llama 2-Chat 70B** \[[Paper](https://arxiv.org/abs/2310.20624)\] <br />
Simon Lermen,  Charlie Rogers-Smith,  Jeffrey Ladish (2023)<br />
- **BadLlama: cheaply removing safety fine-tuning from Llama 2-Chat 13B** \[[Paper](https://arxiv.org/abs/2311.00117)\] <br />
Pranav Gade,  Simon Lermen,  Charlie Rogers-Smith,  Jeffrey Ladish (2023)<br />
- **On the Safety of Open-Sourced Large Language Models: Does Alignment Really Prevent Them From Being Misused?** \[[Paper](https://arxiv.org/abs/2310.01581)\] <br />
Hangfan Zhang,  Zhimeng Guo,  Huaisheng Zhu,  Bochuan Cao,  Lu Lin,  Jinyuan Jia,  Jinghui Chen,  Dinghao Wu (2023)<br />
- **Removing RLHF Protections in GPT-4 via Fine-Tuning** \[[Paper](https://arxiv.org/abs/2311.05553)\] <br />
Qiusi Zhan,  Richard Fang,  Rohan Bindu,  Akul Gupta,  Tatsunori Hashimoto,  Daniel Kang (2023)<br />
- **LoRA-as-an-Attack! Piercing LLM Safety Under The Share-and-Play Scenario** \[[Paper](https://arxiv.org/abs/2403.00108)\] <br />
Hongyi Liu,  Zirui Liu,  Ruixiang Tang,  Jiayi Yuan,  Shaochen Zhong,  Yu-Neng Chuang,  Li Li,  Rui Chen,  Xia Hu (2024)<br />
- **Emulated Disalignment: Safety Alignment for Large Language Models May Backfire!** \[[Paper](https://arxiv.org/abs/2402.12343)\] <br />
Zhanhui Zhou,  Jie Liu,  Zhichen Dong,  Jiaheng Liu,  Chao Yang,  Wanli Ouyang,  Yu Qiao (2024)<br />
- **Covert Malicious Finetuning: Challenges in Safeguarding LLM Adaptation** \[[Paper](https://arxiv.org/abs/2406.20053
   )\] <br />
Danny Halawi,  Alexander Wei,  Eric Wallace,  Tony T. Wang,  Nika Haghtalab,  Jacob Steinhardt (2024)<br />
- **Transforming Computer Security and Public Trust Through the Exploration of Fine-Tuning Large Language Models** \[[Paper](https://arxiv.org/abs/2406.00628
   )\] <br />
Garrett Crumrine,  Izzat Alsmadi,  Jesus Guerrero,  Yuvaraj Munian (2024)<br />
- **Increased LLM Vulnerabilities from Fine-tuning and Quantization** \[[Paper](https://arxiv.org/abs/2404.04392)\] <br />
Divyanshu Kumar,  Anurakt Kumar,  Sahil Agarwal,  Prashanth Harshangi (2024)<br />
- **Best-of-Venom: Attacking RLHF by Injecting Poisoned Preference Data** \[[Paper](https://arxiv.org/abs/2404.05530
   )\] <br />
Tim Baumgärtner,  Yang Gao,  Dana Alon,  Donald Metzler (2024)<br />
- **No Two Devils Alike: Unveiling Distinct Mechanisms of Fine-tuning Attacks** \[[Paper](https://arxiv.org/abs/2405.16229
   )\] <br />
Chak Tou Leong,  Yi Cheng,  Kaishuai Xu,  Jian Wang,  Hanlin Wang,  Wenjie Li (2024)<br />
- **Badllama 3: removing safety finetuning from Llama 3 in minutes** \[[Paper](https://arxiv.org/abs/2407.01376
   )\] <br />
Dmitrii Volkov (2024)<br />
- **No Two Devils Alike: Unveiling Distinct Mechanisms of Fine-tuning Attacks** \[[Paper](https://arxiv.org/abs/2405.16229
   )\] <br />
Chak Tou Leong,  Yi Cheng,  Kaishuai Xu,  Jian Wang,  Hanlin Wang,  Wenjie Li (2024)<br />
### Activations Manipulation
- **Open the Pandora's Box of LLMs: Jailbreaking LLMs through Representation Engineering** \[[Paper](https://arxiv.org/abs/2401.06824)\] <br />
Tianlong Li,  Shihan Dou,  Wenhao Liu,  Muling Wu,  Changze Lv,  Xiaoqing Zheng,  Xuanjing Huang (2024)<br />
- **Scaling Laws for Adversarial Attacks on Language Model Activations** \[[Paper](https://arxiv.org/abs/2312.0278)\] <br />
Stanislav Fort (2023)<br />