# OpenRedTeaming

## Our Survey: Against The Achilles’ Heel: A Survey on Red Teaming for Generative Models [[Paper](https://arxiv.org/abs/2404.00629)]
To gain a comprehensive understanding of potential attacks on GenAI and develop robust safeguards. We:
* Survey over 120 papers, cover the pipeline from risk taxonomy, attack strategies, evaluation metrics, and benchmarks to defensive approaches.
* propose a comprehensive taxonomy of LLM attack strategies grounded in the inherent capabilities of models developed during pretraining and fine-tuning.
* Implemented more than 30+ auto red teaming methods.

To stay updated or try our RedTeaming tool, please subscribe to our newsletter at [our website](https://www.librai.tech/) or join us on [Discord](https://discord.com/invite/ssxtFVbDdT)!



# Latest Papers about Red Teaming 
<details>
<summary><h2>Surveys, Taxonomies and more</h2></summary>

<details>
<summary><h3>__Surveys</summary>

<!-- Markdown content -->
## Surveys
- **Personal LLM Agents: Insights and Survey about the Capability,Efficiency and Security** \[[Paper](https://arxiv.org/abs/2401.05459)\] <br />
Yuanchun Li, Hao Wen, Weijun Wang, Xiangyu Li, Yizhen Yuan, Guohong Liu, Jiacheng Liu, Wenxing Xu, Xiang Wang, Yi Sun, Rui Kong, Yile Wang, Hanfei Geng, Jian Luan, Xuefeng Jin, Zilong Ye, Guanjing Xiong, Fan Zhang, Xiang Li, Mengwei Xu, Zhijun Li, Peng Li, Yang Liu, Ya-Qin Zhang, Yunxin Liu (2024)<br />
- **TrustLLM: Trustworthiness in Large Language Models** \[[Paper](https://arxiv.org/abs/2401.05561)\] <br />
Lichao Sun, Yue Huang, Haoran Wang, Siyuan Wu, Qihui Zhang, Yuan Li, Chujie Gao, Yixin Huang, Wenhan Lyu, Yixuan Zhang, Xiner Li, Zhengliang Liu, Yixin Liu, Yijue Wang, Zhikun Zhang, Bertie Vidgen, Bhavya Kailkhura, Caiming Xiong, Chaowei Xiao, Chunyuan Li, Eric Xing, Furong Huang, Hao Liu, Heng Ji, Hongyi Wang, Huan Zhang, Huaxiu Yao, Manolis Kellis, Marinka Zitnik, Meng Jiang, Mohit Bansal, James Zou, Jian Pei, Jian Liu, Jianfeng Gao, Jiawei Han, Jieyu Zhao, Jiliang Tang, Jindong Wang, Joaquin Vanschoren, John Mitchell, Kai Shu, Kaidi Xu, Kai-Wei Chang, Lifang He, Lifu Huang, Michael Backes, Neil Zhenqiang Gong, Philip S. Yu, Pin-Yu Chen, Quanquan Gu, Ran Xu, Rex Ying, Shuiwang Ji, Suman Jana, Tianlong Chen, Tianming Liu, Tianyi Zhou, William Wang, Xiang Li, Xiangliang Zhang, Xiao Wang, Xing Xie, Xun Chen, Xuyu Wang, Yan Liu, Yanfang Ye, Yinzhi Cao, Yong Chen, Yue Zhao (2024)<br />
- **Risk Taxonomy,Mitigation,and Assessment Benchmarks of Large Language Model Systems** \[[Paper](https://arxiv.org/abs/2401.05778)\] <br />
Tianyu Cui, Yanling Wang, Chuanpu Fu, Yong Xiao, Sijia Li, Xinhao Deng, Yunpeng Liu, Qinglin Zhang, Ziyi Qiu, Peiyang Li, Zhixing Tan, Junwu Xiong, Xinyu Kong, Zujie Wen, Ke Xu, Qi Li (2024)<br />
- **Security and Privacy Challenges of Large Language Models: A Survey** \[[Paper](https://arxiv.org/abs/2402.00888)\] <br />
Badhan Chandra Das, M. Hadi Amini, Yanzhao Wu (2024)<br />
### Surveys on Attacks
- **Robust Testing of AI Language Model Resiliency with Novel Adversarial Prompts** \[[Paper](https://www.mdpi.com/2079-9292/13/5/842)\] <br />
Brendan Hannon,  Yulia Kumar,  Dejaun Gayle,  J. Jenny Li,  Patricia Morreale (2024)<br />
- **Don't Listen To Me: Understanding and Exploring Jailbreak Prompts of Large Language Models** \[[Paper](https://arxiv.org/abs/2403.16432)\] <br />
Yue Xu, Wenjie Wang (2024)<br />
- **Breaking Down the Defenses: A Comparative Survey of Attacks on Large Language Models** \[[Paper](https://arxiv.org/abs/2403.04786)\] <br />
Arijit Ghosh Chowdhury, Md Mofijul Islam, Vaibhav Kumar, Faysal Hossain Shezan, Vaibhav Kumar, Vinija Jain, Aman Chadha (2024)<br />
- **LLM Jailbreak Attack versus Defense Techniques -- A Comprehensive Study** \[[Paper](https://arxiv.org/abs/2402.13457)\] <br />
Zihao Xu, Yi Liu, Gelei Deng, Yuekang Li, Stjepan Picek (2024)<br />
- **An Early Categorization of Prompt Injection Attacks on Large Language Models** \[[Paper](https://arxiv.org/abs/2402.00898)\] <br />
Sippo Rossi, Alisia Marianne Michel, Raghava Rao Mukkamala, Jason Bennett Thatcher (2024)<br />
- **Comprehensive Assessment of Jailbreak Attacks Against LLMs** \[[Paper](https://arxiv.org/abs/2402.05668)\] <br />
Junjie Chu, Yugeng Liu, Ziqing Yang, Xinyue Shen, Michael Backes, Yang Zhang (2024)<br />
- **"Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models** \[[Paper](https://arxiv.org/abs/2308.03825)\] <br />
Xinyue Shen, Zeyuan Chen, Michael Backes, Yun Shen, Yang Zhang (2023)<br />
- **Survey of Vulnerabilities in Large Language Models Revealed by Adversarial Attacks** \[[Paper](https://arxiv.org/abs/2310.10844)\] <br />
Erfan Shayegani, Md Abdullah Al Mamun, Yu Fu, Pedram Zaree, Yue Dong, Nael Abu-Ghazaleh (2023)<br />
- **Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition** \[[Paper](https://arxiv.org/abs/2311.16119)\] <br />
Sander Schulhoff, Jeremy Pinto, Anaum Khan, Louis-François Bouchard, Chenglei Si, Svetlina Anati, Valen Tagliabue, Anson Liu Kost, Christopher Carnahan, Jordan Boyd-Graber (2023)<br />
- **Adversarial Attacks and Defenses in Large Language Models: Old and New Threats** \[[Paper](https://arxiv.org/abs/2310.19737)\] <br />
Leo Schwinn, David Dobre, Stephan Günnemann, Gauthier Gidel (2023)<br />
- **Tricking LLMs into Disobedience: Formalizing,Analyzing,and Detecting Jailbreaks** \[[Paper](https://arxiv.org/abs/2305.14965)\] <br />
Abhinav Rao, Sachin Vashistha, Atharva Naik, Somak Aditya, Monojit Choudhury (2023)<br />
- **Summon a Demon and Bind it: A Grounded Theory of LLM Red Teaming in the Wild** \[[Paper](https://arxiv.org/abs/2311.06237)\] <br />
Nanna Inie, Jonathan Stray, Leon Derczynski (2023)<br />
- **A Comprehensive Survey of Attack Techniques,Implementation,and Mitigation Strategies in Large Language Models** \[[Paper](https://arxiv.org/abs/2312.10982)\] <br />
Aysan Esmradi, Daniel Wankit Yip, Chun Fai Chan (2023)<br />
- **Beyond Boundaries: A Comprehensive Survey of Transferable Attacks on AI Systems** \[[Paper](https://arxiv.org/abs/2311.11796)\] <br />
Guangjing Wang, Ce Zhou, Yuanda Wang, Bocheng Chen, Hanqing Guo, Qiben Yan (2023)<br />
- **Beyond Boundaries: A Comprehensive Survey of Transferable Attacks on AI Systems** \[[Paper](https://arxiv.org/abs/2311.11796)\] <br />
Guangjing Wang, Ce Zhou, Yuanda Wang, Bocheng Chen, Hanqing Guo, Qiben Yan (2023)<br />
### Surveys on Risks
- **Mapping LLM Security Landscapes: A Comprehensive Stakeholder Risk Assessment Proposal** \[[Paper](https://arxiv.org/abs/2403.13309)\] <br />
Rahul Pankajakshan, Sumitra Biswal, Yuvaraj Govindarajulu, Gilad Gressel (2024)<br />
- **Securing Large Language Models: Threats,Vulnerabilities and Responsible Practices** \[[Paper](https://arxiv.org/abs/2403.12503)\] <br />
Sara Abdali, Richard Anarfi, CJ Barberan, Jia He (2024)<br />
- **Privacy in Large Language Models: Attacks,Defenses and Future Directions** \[[Paper](https://arxiv.org/abs/2310.10383)\] <br />
Haoran Li, Yulin Chen, Jinglong Luo, Yan Kang, Xiaojin Zhang, Qi Hu, Chunkit Chan, Yangqiu Song (2023)<br />
- **Beyond the Safeguards: Exploring the Security Risks of ChatGPT** \[[Paper](https://arxiv.org/abs/2305.08005)\] <br />
Erik Derner, Kristina Batistič (2023)<br />
- **Towards Safer Generative Language Models: A Survey on Safety Risks,Evaluations,and Improvements** \[[Paper](https://arxiv.org/abs/2302.0927)\] <br />
Jiawen Deng, Jiale Cheng, Hao Sun, Zhexin Zhang, Minlie Huang (2023)<br />
- **Use of LLMs for Illicit Purposes: Threats,Prevention Measures,and Vulnerabilities** \[[Paper](https://arxiv.org/abs/2308.12833)\] <br />
Maximilian Mozes, Xuanli He, Bennett Kleinberg, Lewis D. Griffin (2023)<br />
- **From ChatGPT to ThreatGPT: Impact of Generative AI in Cybersecurity and Privacy** \[[Paper](https://arxiv.org/abs/2307.00691)\] <br />
Maanak Gupta, CharanKumar Akiri, Kshitiz Aryal, Eli Parker, Lopamudra Praharaj (2023)<br />
- **Identifying and Mitigating Vulnerabilities in LLM-Integrated Applications** \[[Paper](https://arxiv.org/abs/2311.16153)\] <br />
Fengqing Jiang, Zhangchen Xu, Luyao Niu, Boxin Wang, Jinyuan Jia, Bo Li, Radha Poovendran (2023)<br />
- **The power of generative AI in cybersecurity: Opportunities and challenges** \[[Paper](https://ace.ewapublishing.org/media/50a3b1ae25cc43f4b2a62ca50409a1e2.marked.pdf)\] <br />
Shibo Wen (2024)<br />
</details>

<details>
<summary><h3>__Taxonomies</summary>

<!-- Markdown content -->
## Taxonomies
- **Coercing LLMs to do and reveal (almost) anything** \[[Paper](https://arxiv.org/abs/2402.1402)\] <br />
Jonas Geiping, Alex Stein, Manli Shu, Khalid Saifullah, Yuxin Wen, Tom Goldstein (2024)<br />
- **The History and Risks of Reinforcement Learning and Human Feedback** \[[Paper](https://arxiv.org/abs/2310.13595)\] <br />
Nathan Lambert, Thomas Krendl Gilbert, Tom Zick (2023)<br />
- **From Chatbots to PhishBots? -- Preventing Phishing scams created using ChatGPT,Google Bard and Claude** \[[Paper](https://arxiv.org/abs/2310.19181)\] <br />
Sayak Saha Roy, Poojitha Thota, Krishna Vamsi Naragam, Shirin Nilizadeh (2023)<br />
- **Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study** \[[Paper](https://arxiv.org/abs/2305.1386)\] <br />
Yi Liu, Gelei Deng, Zhengzi Xu, Yuekang Li, Yaowen Zheng, Ying Zhang, Lida Zhao, Tianwei Zhang, Kailong Wang, Yang Liu (2023)<br />
- **Generating Phishing Attacks using ChatGPT** \[[Paper](https://arxiv.org/abs/2305.05133)\] <br />
Sayak Saha Roy, Krishna Vamsi Naragam, Shirin Nilizadeh (2023)<br />
- **Personalisation within bounds: A risk taxonomy and policy framework for the alignment of large language models with personalised feedback** \[[Paper](https://arxiv.org/abs/2303.05453)\] <br />
Hannah Rose Kirk, Bertie Vidgen, Paul Röttger, Scott A. Hale (2023)<br />
- **AI Deception: A Survey of Examples,Risks,and Potential Solutions** \[[Paper](https://arxiv.org/abs/2308.14752)\] <br />
Peter S. Park, Simon Goldstein, Aidan O'Gara, Michael Chen, Dan Hendrycks (2023)<br />
- **A Security Risk Taxonomy for Large Language Models** \[[Paper](https://arxiv.org/abs/2311.11415)\] <br />
Erik Derner, Kristina Batistič, Jan Zahálka, Robert Babuška (2023)<br />

</details>

<details>
<summary><h3>__Positions</summary>

<!-- Markdown content -->

## Positions
- **Red-Teaming for Generative AI: Silver Bullet or Security Theater?** \[[Paper](https://arxiv.org/abs/2401.15897)\] <br />
Michael Feffer, Anusha Sinha, Zachary C. Lipton, Hoda Heidari (2024)<br />
- **The Ethics of Interaction: Mitigating Security Threats in LLMs** \[[Paper](https://arxiv.org/abs/2401.12273)\] <br />
Ashutosh Kumar, Sagarika Singh, Shiv Vignesh Murty, Swathy Ragupathy (2024)<br />
- **A Safe Harbor for AI Evaluation and Red Teaming** \[[Paper](https://arxiv.org/abs/2403.04893)\] <br />
Shayne Longpre, Sayash Kapoor, Kevin Klyman, Ashwin Ramaswami, Rishi Bommasani, Borhane Blili-Hamelin, Yangsibo Huang, Aviya Skowron, Zheng-Xin Yong, Suhas Kotha, Yi Zeng, Weiyan Shi, Xianjun Yang, Reid Southen, Alexander Robey, Patrick Chao, Diyi Yang, Ruoxi Jia, Daniel Kang, Sandy Pentland, Arvind Narayanan, Percy Liang, Peter Henderson (2024)<br />
- **Red teaming ChatGPT via Jailbreaking: Bias,Robustness,Reliability and Toxicity** \[[Paper](https://arxiv.org/abs/2301.12867)\] <br />
Terry Yue Zhuo, Yujin Huang, Chunyang Chen, Zhenchang Xing (2023)<br />
- **The Promise and Peril of Artificial Intelligence -- Violet Teaming Offers a Balanced Path Forward** \[[Paper](https://arxiv.org/abs/2308.14253)\] <br />
Alexander J. Titus, Adam H. Russell (2023)<br />
</details>

<details>
<summary><h3>__Phenomenons</summary>

<!-- Markdown content -->
## Phenomenons
- **Red-Teaming Segment Anything Model** \[[Paper](https://arxiv.org/abs/2404.02067)\] <br />
Krzysztof Jankowski, Bartlomiej Sobieski, Mateusz Kwiatkowski, Jakub Szulc, Michal Janik, Hubert Baniecki, Przemyslaw Biecek (2024)<br />
- **A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity** \[[Paper](https://arxiv.org/abs/2401.01967)\] <br />
Andrew Lee, Xiaoyan Bai, Itamar Pres, Martin Wattenberg, Jonathan K. Kummerfeld, Rada Mihalcea (2024)<br />
- **Speak Out of Turn: Safety Vulnerability of Large Language Models in Multi-turn Dialogue** \[[Paper](https://arxiv.org/abs/2402.17262)\] <br />
Zhenhong Zhou, Jiuyang Xiang, Haopeng Chen, Quan Liu, Zherui Li, Sen Su (2024)<br />
- **Tradeoffs Between Alignment and Helpfulness in Language Models** \[[Paper](https://arxiv.org/abs/2401.16332)\] <br />
Yotam Wolf, Noam Wies, Dorin Shteyman, Binyamin Rothberg, Yoav Levine, Amnon Shashua (2024)<br />
- **Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications** \[[Paper](https://arxiv.org/abs/2402.05162)\] <br />
Boyi Wei, Kaixuan Huang, Yangsibo Huang, Tinghao Xie, Xiangyu Qi, Mengzhou Xia, Prateek Mittal, Mengdi Wang, Peter Henderson (2024)<br />
- **"It's a Fair Game'',or Is It? Examining How Users Navigate Disclosure Risks and Benefits When Using LLM-Based Conversational Agents** \[[Paper](https://arxiv.org/abs/2309.11653)\] <br />
Zhiping Zhang, Michelle Jia, Hao-Ping Lee, Bingsheng Yao, Sauvik Das, Ada Lerner, Dakuo Wang, Tianshi Li (2023)<br />
- **Exploiting Programmatic Behavior of LLMs: Dual-Use Through Standard Security Attacks** \[[Paper](https://arxiv.org/abs/2302.05733)\] <br />
aniel Kang, Xuechen Li, Ion Stoica, Carlos Guestrin, Matei Zaharia, Tatsunori Hashimoto (2023)<br />
- **Can Large Language Models Change User Preference Adversarially?** \[[Paper](https://arxiv.org/abs/2302.10291)\] <br />
Varshini Subhash (2023)<br />
- **Are aligned neural networks adversarially aligned?** \[[Paper](https://arxiv.org/abs/2306.15447)\] <br />
Nicholas Carlini, Milad Nasr, Christopher A. Choquette-Choo, Matthew Jagielski, Irena Gao, Anas Awadalla, Pang Wei Koh, Daphne Ippolito, Katherine Lee, Florian Tramer, Ludwig Schmidt (2023)<br />
- **Fake Alignment: Are LLMs Really Aligned Well?** \[[Paper](https://arxiv.org/abs/2311.05915)\] <br />
Yixu Wang, Yan Teng, Kexin Huang, Chengqi Lyu, Songyang Zhang, Wenwei Zhang, Xingjun Ma, Yu-Gang Jiang, Yu Qiao, Yingchun Wang (2023)<br />
- **Causality Analysis for Evaluating the Security of Large Language Models** \[[Paper](https://arxiv.org/abs/2312.07876)\] <br />
Wei Zhao, Zhe Li, Jun Sun (2023)<br />
- **Transfer Attacks and Defenses for Large Language Models on Coding Tasks** \[[Paper](https://arxiv.org/abs/2311.13445)\] <br />
Chi Zhang, Zifan Wang, Ravi Mangal, Matt Fredrikson, Limin Jia, Corina Pasareanu (2023)<br />
</details>
</details>


<details>
<summary><h2>Attack Strategies</h2></summary>

<details>
<summary><h3>__Completion Compliance</summary>

<!-- Markdown content -->
## Completion Compliance
- **Few-Shot Adversarial Prompt Learning on Vision-Language Models** \[[Paper](https://arxiv.org/abs/2403.14774)\] <br />
Yiwei Zhou, Xiaobo Xia, Zhiwei Lin, Bo Han, Tongliang Liu (2024)<br />
- **Hijacking Context in Large Multi-modal Models** \[[Paper](https://arxiv.org/abs/2312.07553)\] <br />
Joonhyun Jeong (2023)<br />
- **Great,Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack** \[[Paper](https://arxiv.org/abs/2404.01833)\] <br />
Mark Russinovich, Ahmed Salem, Ronen Eldan (2024)<br />
- **BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models** \[[Paper](https://arxiv.org/abs/2401.12242)\] <br />
Zhen Xiang, Fengqing Jiang, Zidi Xiong, Bhaskar Ramasubramanian, Radha Poovendran, Bo Li (2024)<br />
- **Universal Vulnerabilities in Large Language Models: Backdoor Attacks for In-context Learning** \[[Paper](https://arxiv.org/abs/2401.05949)\] <br />
Shuai Zhao, Meihuizi Jia, Luu Anh Tuan, Fengjun Pan, Jinming Wen (2024)<br />
- **Nevermind: Instruction Override and Moderation in Large Language Models** \[[Paper](https://arxiv.org/abs/2402.03303)\] <br />
Edward Kim (2024)<br />
- **Red-Teaming Large Language Models using Chain of Utterances for Safety-Alignment** \[[Paper](https://arxiv.org/abs/2308.09662)\] <br />
Rishabh Bhardwaj, Soujanya Poria (2023)<br />
- **Backdoor Attacks for In-Context Learning with Language Models** \[[Paper](https://arxiv.org/abs/2307.14692)\] <br />
Nikhil Kandpal, Matthew Jagielski, Florian Tramèr, Nicholas Carlini (2023)<br />
- **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations** \[[Paper](https://arxiv.org/abs/2310.06387)\] <br />
Zeming Wei, Yifei Wang, Yisen Wang (2023)<br />
- **Analyzing the Inherent Response Tendency of LLMs: Real-World Instructions-Driven Jailbreak** \[[Paper](https://arxiv.org/abs/2312.04127)\] <br />
Yanrui Du, Sendong Zhao, Ming Ma, Yuhan Chen, Bing Qin (2023)<br />
- **Bypassing the Safety Training of Open-Source LLMs with Priming Attacks** \[[Paper](https://arxiv.org/abs/2312.12321)\] <br />
Jason Vega, Isha Chaudhary, Changming Xu, Gagandeep Singh (2023)<br />
- **Hijacking Large Language Models via Adversarial In-Context Learning** \[[Paper](https://arxiv.org/abs/2311.09948)\] <br />
Yao Qiang, Xiangyu Zhou, Dongxiao Zhu (2023)<br />
</details>
<details>
<summary><h3>__Inference Indirection</summary>

<!-- Markdown content -->
## Instruction Indirection
- **On the Robustness of Large Multimodal Models Against Image Adversarial Attacks** \[[Paper](https://arxiv.org/abs/2312.03777)\] <br />
Xuanming Cui, Alejandro Aparcedo, Young Kyun Jang, Ser-Nam Lim (2023)<br />
- **Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks** \[[Paper](https://arxiv.org/abs/2402.00626)\] <br />
Maan Qraitem, Nazia Tasnim, Piotr Teterwak, Kate Saenko, Bryan A. Plummer (2024)<br />
- **Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2403.09792)\] <br />
Yifan Li, Hangyu Guo, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen (2024)<br />
- **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** \[[Paper](https://arxiv.org/abs/2311.05608)\] <br />
Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang (2023)<br />
- **InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models** \[[Paper](https://arxiv.org/abs/2312.01886)\] <br />
Xunguang Wang, Zhenlan Ji, Pingchuan Ma, Zongjie Li, Shuai Wang (2023)<br />
- **Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs** \[[Paper](https://arxiv.org/abs/2307.1049)\] <br />
Eugene Bagdasaryan, Tsung-Yin Hsieh, Ben Nassi, Vitaly Shmatikov (2023)<br />
- **Visual Adversarial Examples Jailbreak Aligned Large Language Models** \[[Paper](https://arxiv.org/abs/2306.13213)\] <br />
Xiangyu Qi, Kaixuan Huang, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal (2023)<br />
- **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** \[[Paper](https://arxiv.org/abs/2307.14539)\] <br />
Erfan Shayegani, Yue Dong, Nael Abu-Ghazaleh (2023)<br />
- **Play Guessing Game with LLM: Indirect Jailbreak Attack with Implicit Clues** \[[Paper](https://arxiv.org/abs/2402.09091)\] <br />
Zhiyuan Chang, Mingyang Li, Yi Liu, Junjie Wang, Qing Wang, Yang Liu (2024)<br />
- **FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models** \[[Paper](https://arxiv.org/abs/2309.05274)\] <br />
Dongyu Yao, Jianshu Zhang, Ian G. Harris, Marcel Carlsson (2023)<br />
- **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts** \[[Paper](https://arxiv.org/abs/2309.10253)\] <br />
Jiahao Yu, Xingwei Lin, Zheng Yu, Xinyu Xing (2023)<br />
- **Prompt Packer: Deceiving LLMs through Compositional Instruction with Hidden Attacks** \[[Paper](https://arxiv.org/abs/2310.10077)\] <br />
Shuyu Jiang, Xingshu Chen, Rui Tang (2023)<br />
- **DeepInception: Hypnotize Large Language Model to Be Jailbreaker** \[[Paper](https://arxiv.org/abs/2311.03191)\] <br />
Xuan Li, Zhanke Zhou, Jianing Zhu, Jiangchao Yao, Tongliang Liu, Bo Han (2023)<br />
- **A Wolf in Sheep's Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily** \[[Paper](https://arxiv.org/abs/2311.08268)\] <br />
Peng Ding, Jun Kuang, Dan Ma, Xuezhi Cao, Yunsen Xian, Jiajun Chen, Shujian Huang (2023)<br />
- **Safety Alignment in NLP Tasks: Weakly Aligned Summarization as an In-Context Attack** \[[Paper](https://arxiv.org/abs/2312.06924)\] <br />
Yu Fu, Yufei Li, Wen Xiao, Cong Liu, Yue Dong (2023)<br />
- **Cognitive Overload: Jailbreaking Large Language Models with Overloaded Logical Thinking** \[[Paper](https://arxiv.org/abs/2311.09827)\] <br />
Nan Xu, Fei Wang, Ben Zhou, Bang Zheng Li, Chaowei Xiao, Muhao Chen (2023)<br />
</details>

<details>
<summary><h3>__Generalization Glide</summary>

<!-- Markdown content -->
## Generalization Glide
### Languages
- **A Cross-Language Investigation into Jailbreak Attacks in Large Language Models** \[[Paper](https://arxiv.org/abs/2401.16765)\] <br />
Jie Li, Yi Liu, Chongyang Liu, Ling Shi, Xiaoning Ren, Yaowen Zheng, Yang Liu, Yinxing Xue (2024)<br />
- **The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts** \[[Paper](https://arxiv.org/abs/2401.13136)\] <br />
Lingfeng Shen, Weiting Tan, Sihao Chen, Yunmo Chen, Jingyu Zhang, Haoran Xu, Boyuan Zheng, Philipp Koehn, Daniel Khashabi (2024)<br />
- **Sandwich attack: Multi-language Mixture Adaptive Attack on LLMs** \[[Paper](https://arxiv.org/abs/2404.07242)\] <br />
Bibek Upadhayay, Vahid Behzadan (2024)<br />
- **Backdoor Attack on Multilingual Machine Translation** \[[Paper](https://arxiv.org/abs/2404.02393)\] <br />
Jun Wang, Qiongkai Xu, Xuanli He, Benjamin I. P. Rubinstein, Trevor Cohn (2024)<br />
- **Multilingual Jailbreak Challenges in Large Language Models** \[[Paper](https://arxiv.org/abs/2310.06474)\] <br />
Yue Deng, Wenxuan Zhang, Sinno Jialin Pan, Lidong Bing (2023)<br />
- **Low-Resource Languages Jailbreak GPT-4** \[[Paper](https://arxiv.org/abs/2310.02446)\] <br />
Zheng-Xin Yong, Cristina Menghini, Stephen H. Bach (2023)<br />
### Cipher
- **Using Hallucinations to Bypass GPT4's Filter** \[[Paper](https://arxiv.org/abs/2403.04769)\] <br />
Benjamin Lemkin (2024)<br />
- **The Butterfly Effect of Altering Prompts: How Small Changes and Jailbreaks Affect Large Language Model Performance** \[[Paper](https://arxiv.org/abs/2401.03729)\] <br />
Abel Salinas, Fred Morstatter (2024)<br />
- **Making Them Ask and Answer: Jailbreaking Large Language Models in Few Queries via Disguise and Reconstruction** \[[Paper](https://arxiv.org/abs/2402.18104)\] <br />
Tong Liu, Yingjie Zhang, Zhe Zhao, Yinpeng Dong, Guozhu Meng, Kai Chen (2024)<br />
- **PRP: Propagating Universal Perturbations to Attack Large Language Model Guard-Rails** \[[Paper](https://arxiv.org/abs/2402.15911)\] <br />
Neal Mangaokar, Ashish Hooda, Jihye Choi, Shreyas Chandrashekaran, Kassem Fawaz, Somesh Jha, Atul Prakash (2024)<br />
- **GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher** \[[Paper](https://arxiv.org/abs/2308.06463)\] <br />
Youliang Yuan, Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Pinjia He, Shuming Shi, Zhaopeng Tu (2023)<br />
- **Punctuation Matters! Stealthy Backdoor Attack for Language Models** \[[Paper](https://arxiv.org/abs/2312.15867)\] <br />
Xuan Sheng, Zhicheng Li, Zhaoyang Han, Xiangmao Chang, Piji Li (2023)<br />
### Personification
- **Foot In The Door: Understanding Large Language Model Jailbreaking via Cognitive Psychology** \[[Paper](https://arxiv.org/abs/2402.1569)\] <br />
Zhenhua Wang, Wei Xie, Baosheng Wang, Enze Wang, Zhiwen Gui, Shuoyoucheng Ma, Kai Chen (2024)<br />
- **PsySafe: A Comprehensive Framework for Psychological-based Attack,Defense,and Evaluation of Multi-agent System Safety** \[[Paper](https://arxiv.org/abs/2401.1188)\] <br />
Zaibin Zhang, Yongting Zhang, Lijun Li, Hongzhi Gao, Lijun Wang, Huchuan Lu, Feng Zhao, Yu Qiao, Jing Shao (2024)<br />
- **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs** \[[Paper](https://arxiv.org/abs/2401.06373)\] <br />
Yi Zeng, Hongpeng Lin, Jingwen Zhang, Diyi Yang, Ruoxi Jia, Weiyan Shi (2024)<br />
- **Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation** \[[Paper](https://arxiv.org/abs/2311.03348)\] <br />
Rusheb Shah, Quentin Feuillade--Montixi, Soroush Pour, Arush Tagade, Stephen Casper, Javier Rando (2023)<br />
- **Who is ChatGPT? Benchmarking LLMs' Psychological Portrayal Using PsychoBench** \[[Paper](https://arxiv.org/abs/2310.01386)\] <br />
Jen-tse Huang, Wenxuan Wang, Eric John Li, Man Ho Lam, Shujie Ren, Youliang Yuan, Wenxiang Jiao, Zhaopeng Tu, Michael R. Lyu (2023)<br />
- **Exploiting Large Language Models (LLMs) through Deception Techniques and Persuasion Principles** \[[Paper](https://arxiv.org/abs/2311.14876)\] <br />
Sonali Singh, Faranak Abri, Akbar Siami Namin (2023)<br />
</details>

<details>
<summary><h3>__Model Manipulation</h3></summary>

<!-- Markdown content -->
## Model Manipulation
### Backdoor Attacks
- **Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models** \[[Paper](https://arxiv.org/abs/2402.06659)\] <br />
Yuancheng Xu, Jiarui Yao, Manli Shu, Yanchao Sun, Zichu Wu, Ning Yu, Tom Goldstein, Furong Huang (2024)<br />
- **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training** \[[Paper](https://arxiv.org/abs/2401.05566)\] <br />
Evan Hubinger, Carson Denison, Jesse Mu, Mike Lambert, Meg Tong, Monte MacDiarmid, Tamera Lanham, Daniel M. Ziegler, Tim Maxwell, Newton Cheng, Adam Jermyn, Amanda Askell, Ansh Radhakrishnan, Cem Anil, David Duvenaud, Deep Ganguli, Fazl Barez, Jack Clark, Kamal Ndousse, Kshitij Sachan, Michael Sellitto, Mrinank Sharma, Nova DasSarma, Roger Grosse, Shauna Kravec, Yuntao Bai, Zachary Witten, Marina Favaro, Jan Brauner, Holden Karnofsky, Paul Christiano, Samuel R. Bowman, Logan Graham, Jared Kaplan, Sören Mindermann, Ryan Greenblatt, Buck Shlegeris, Nicholas Schiefer, Ethan Perez (2024)<br />
- **What's in Your "Safe" Data?: Identifying Benign Data that Breaks Safety** \[[Paper](https://arxiv.org/abs/2404.01099)\] <br />
Luxi He, Mengzhou Xia, Peter Henderson (2024)<br />
- **Data Poisoning Attacks on Off-Policy Policy Evaluation Methods** \[[Paper](https://arxiv.org/abs/2404.04714)\] <br />
Elita Lobo, Harvineet Singh, Marek Petrik, Cynthia Rudin, Himabindu Lakkaraju (2024)<br />
- **BadEdit: Backdooring large language models by model editing** \[[Paper](https://arxiv.org/abs/2403.13355)\] <br />
Yanzhou Li, Tianlin Li, Kangjie Chen, Jian Zhang, Shangqing Liu, Wenhan Wang, Tianwei Zhang, Yang Liu (2024)<br />
- **Best-of-Venom: Attacking RLHF by Injecting Poisoned Preference Data** \[[Paper](https://arxiv.org/abs/2404.0553)\] <br />
Tim Baumgärtner, Yang Gao, Dana Alon, Donald Metzler (2024)<br />
- **Learning to Poison Large Language Models During Instruction Tuning** \[[Paper](https://arxiv.org/abs/2402.13459)\] <br />
Yao Qiang, Xiangyu Zhou, Saleh Zare Zade, Mohammad Amin Roshani, Douglas Zytko, Dongxiao Zhu (2024)<br />
- **Exploring Backdoor Vulnerabilities of Chat Models** \[[Paper](https://arxiv.org/abs/2404.02406)\] <br />
Yunzhuo Hao, Wenkai Yang, Yankai Lin (2024)<br />
- **Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models** \[[Paper](https://arxiv.org/abs/2305.1471)\] <br />
Jiashu Xu, Mingyu Derek Ma, Fei Wang, Chaowei Xiao, Muhao Chen (2023)<br />
- **Forcing Generative Models to Degenerate Ones: The Power of Data Poisoning Attacks** \[[Paper](https://arxiv.org/abs/2312.04748)\] <br />
Shuli Jiang, Swanand Ravindra Kadhe, Yi Zhou, Ling Cai, Nathalie Baracaldo (2023)<br />
- **Stealthy and Persistent Unalignment on Large Language Models via Backdoor Injections** \[[Paper](https://arxiv.org/abs/2312.00027)\] <br />
Yuanpu Cao, Bochuan Cao, Jinghui Chen (2023)<br />
- **Backdoor Activation Attack: Attack Large Language Models using Activation Steering for Safety-Alignment** \[[Paper](https://arxiv.org/abs/2311.09433)\] <br />
Haoran Wang, Kai Shu (2023)<br />
- **On the Exploitability of Reinforcement Learning with Human Feedback for Large Language Models** \[[Paper](https://arxiv.org/abs/2311.09641)\] <br />
Jiongxiao Wang, Junlin Wu, Muhao Chen, Yevgeniy Vorobeychik, Chaowei Xiao (2023)<br />
- **Test-time Backdoor Mitigation for Black-Box Large Language Models with Defensive Demonstrations** \[[Paper](https://arxiv.org/abs/2311.09763)\] <br />
Wenjie Mo, Jiashu Xu, Qin Liu, Jiongxiao Wang, Jun Yan, Chaowei Xiao, Muhao Chen (2023)<br />
- **Universal Jailbreak Backdoors from Poisoned Human Feedback** \[[Paper](https://arxiv.org/abs/2311.14455)\] <br />
Javier Rando, Florian Tramèr (2023)<br />
### Fine-tuning Risks
- **LoRA-as-an-Attack! Piercing LLM Safety Under The Share-and-Play Scenario** \[[Paper](https://arxiv.org/abs/2403.00108)\] <br />
Hongyi Liu, Zirui Liu, Ruixiang Tang, Jiayi Yuan, Shaochen Zhong, Yu-Neng Chuang, Li Li, Rui Chen, Xia Hu (2024)<br />
- **Emulated Disalignment: Safety Alignment for Large Language Models May Backfire!** \[[Paper](https://arxiv.org/abs/2402.12343)\] <br />
Zhanhui Zhou, Jie Liu, Zhichen Dong, Jiaheng Liu, Chao Yang, Wanli Ouyang, Yu Qiao (2024)<br />
- **LoRA Fine-tuning Efficiently Undoes Safety Training in Llama 2-Chat 70B** \[[Paper](https://arxiv.org/abs/2310.20624)\] <br />
Simon Lermen, Charlie Rogers-Smith, Jeffrey Ladish (2023)<br />
- **BadLlama: cheaply removing safety fine-tuning from Llama 2-Chat 13B** \[[Paper](https://arxiv.org/abs/2311.00117)\] <br />
Pranav Gade, Simon Lermen, Charlie Rogers-Smith, Jeffrey Ladish (2023)<br />
- **Language Model Unalignment: Parametric Red-Teaming to Expose Hidden Harms and Biases** \[[Paper](https://arxiv.org/abs/2310.14303)\] <br />
Rishabh Bhardwaj, Soujanya Poria (2023)<br />
- **Removing RLHF Protections in GPT-4 via Fine-Tuning** \[[Paper](https://arxiv.org/abs/2311.05553)\] <br />
Qiusi Zhan, Richard Fang, Rohan Bindu, Akul Gupta, Tatsunori Hashimoto, Daniel Kang (2023)<br />
- **On the Safety of Open-Sourced Large Language Models: Does Alignment Really Prevent Them From Being Misused?** \[[Paper](https://arxiv.org/abs/2310.01581)\] <br />
Hangfan Zhang, Zhimeng Guo, Huaisheng Zhu, Bochuan Cao, Lu Lin, Jinyuan Jia, Jinghui Chen, Dinghao Wu (2023)<br />
- **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models** \[[Paper](https://arxiv.org/abs/2310.02949)\] <br />
Xianjun Yang, Xiao Wang, Qi Zhang, Linda Petzold, William Yang Wang, Xun Zhao, Dahua Lin (2023)<br />
- **Fine-tuning Aligned Language Models Compromises Safety,Even When Users Do Not Intend To!** \[[Paper](https://arxiv.org/abs/2310.03693)\] <br />
Xiangyu Qi, Yi Zeng, Tinghao Xie, Pin-Yu Chen, Ruoxi Jia, Prateek Mittal, Peter Henderson (2023)<br />
</details>
</details>

<details>
<summary><h2>Attack Searcher</h2></summary>
<details>
<summary><h3>__Suffix Searchers</h3></summary>

<!-- Markdown content -->
## Suffix Searchers
- **Prompting4Debugging: Red-Teaming Text-to-Image Diffusion Models by Finding Problematic Prompts** \[[Paper](https://arxiv.org/abs/2309.06135)\] <br />
Zhi-Yi Chin, Chieh-Ming Jiang, Ching-Chun Huang, Pin-Yu Chen, Wei-Chen Chiu (2023)<br />
- **From Noise to Clarity: Unraveling the Adversarial Suffix of Large Language Model Attacks via Translation of Text Embeddings** \[[Paper](https://arxiv.org/abs/2402.16006)\] <br />
Hao Wang, Hao Li, Minlie Huang, Lei Sha (2024)<br />
- **Fast Adversarial Attacks on Language Models In One GPU Minute** \[[Paper](https://arxiv.org/abs/2402.1557)\] <br />
Vinu Sankar Sadasivan, Shoumik Saha, Gaurang Sriramanan, Priyatham Kattakinda, Atoosa Chegini, Soheil Feizi (2024)<br />
- **Gradient-Based Language Model Red Teaming** \[[Paper](https://arxiv.org/abs/2401.16656)\] <br />
Nevan Wichers, Carson Denison, Ahmad Beirami (2024)<br />
- **Automatic and Universal Prompt Injection Attacks against Large Language Models** \[[Paper](https://arxiv.org/abs/2403.04957)\] <br />
Xiaogeng Liu, Zhiyuan Yu, Yizhe Zhang, Ning Zhang, Chaowei Xiao (2024)<br />
- **$\textit{LinkPrompt}$: Natural and Universal Adversarial Attacks on Prompt-based Language Models** \[[Paper](https://arxiv.org/abs/2403.16432)\] <br />
Yue Xu, Wenjie Wang (2024)<br />
- **Neural Exec: Learning (and Learning from) Execution Triggers for Prompt Injection Attacks** \[[Paper](https://arxiv.org/abs/2403.03792)\] <br />
Dario Pasquini, Martin Strohmeier, Carmela Troncoso (2024)<br />
- **Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks** \[[Paper](https://arxiv.org/abs/2404.02151)\] <br />
Maksym Andriushchenko, Francesco Croce, Nicolas Flammarion (2024)<br />
- **Rapid Optimization for Jailbreaking LLMs via Subconscious Exploitation and Echopraxia** \[[Paper](https://arxiv.org/abs/2402.05467)\] <br />
Guangyu Shen, Siyuan Cheng, Kaiyuan Zhang, Guanhong Tao, Shengwei An, Lu Yan, Zhuo Zhang, Shiqing Ma, Xiangyu Zhang (2024)<br />
- **AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models** \[[Paper](https://arxiv.org/abs/2310.1514)\] <br />
Sicheng Zhu, Ruiyi Zhang, Bang An, Gang Wu, Joe Barrow, Zichao Wang, Furong Huang, Ani Nenkova, Tong Sun (2023)<br />
- **Universal and Transferable Adversarial Attacks on Aligned Language Models** \[[Paper](https://arxiv.org/abs/2307.15043)\] <br />
Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr, J. Zico Kolter, Matt Fredrikson (2023)<br />
- **Soft-prompt Tuning for Large Language Models to Evaluate Bias** \[[Paper](https://arxiv.org/abs/2306.04735)\] <br />
Jacob-Junqi Tian, David Emerson, Sevil Zanjani Miyandoab, Deval Pandya, Laleh Seyyed-Kalantari, Faiza Khan Khattak (2023)<br />
- **TrojLLM: A Black-box Trojan Prompt Attack on Large Language Models** \[[Paper](https://arxiv.org/abs/2306.06815)\] <br />
Jiaqi Xue, Mengxin Zheng, Ting Hua, Yilin Shen, Yepeng Liu, Ladislau Boloni, Qian Lou (2023)<br />
- **AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models** \[[Paper](https://arxiv.org/abs/2310.04451)\] <br />
Xiaogeng Liu, Nan Xu, Muhao Chen, Chaowei Xiao (2023)<br />
</details>
<details>
<summary><h3>__Suffix Searchers</h3></summary>

<!-- Markdown content -->
## Prompt Searchers
### Language Model
- **Eliciting Language Model Behaviors using Reverse Language Models** \[[Paper](https://openreview.net/pdf?id=m6xyTie61H)\] <br />
Jacob Pfau,  Alex Infanger,  Abhay Sheshadri,  Ayush Panda,  Julian Michael,  Curtis Huebner

 (2023)<br />
- **All in How You Ask for It: Simple Black-Box Method for Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2401.09798)\] <br />
Kazuhiro Takemoto (2024)<br />
- **Adversarial Attacks on GPT-4 via Simple Random Search** \[[Paper](https://arxiv.org/abs/2404.0553)\] <br />
Tim Baumgärtner, Yang Gao, Dana Alon, Donald Metzler (2024)<br />
- **Tastle: Distract Large Language Models for Automatic Jailbreak Attack** \[[Paper](https://arxiv.org/abs/2403.08424)\] <br />
Zeguan Xiao, Yan Yang, Guanhua Chen, Yun Chen (2024)<br />
- **Red Teaming Language Models with Language Models** \[[Paper](https://arxiv.org/abs/2202.03286)\] <br />
Ethan Perez, Saffron Huang, Francis Song, Trevor Cai, Roman Ring, John Aslanides, Amelia Glaese, Nat McAleese, Geoffrey Irving (2022)<br />
- **An LLM can Fool Itself: A Prompt-Based Adversarial Attack** \[[Paper](https://arxiv.org/abs/2310.13345)\] <br />
Xilie Xu, Keyi Kong, Ning Liu, Lizhen Cui, Di Wang, Jingfeng Zhang, Mohan Kankanhalli (2023)<br />
- **Jailbreaking Black Box Large Language Models in Twenty Queries** \[[Paper](https://arxiv.org/abs/2310.08419)\] <br />
Patrick Chao, Alexander Robey, Edgar Dobriban, Hamed Hassani, George J. Pappas, Eric Wong (2023)<br />
- **Tree of Attacks: Jailbreaking Black-Box LLMs Automatically** \[[Paper](https://arxiv.org/abs/2312.02119)\] <br />
Anay Mehrotra, Manolis Zampetakis, Paul Kassianik, Blaine Nelson, Hyrum Anderson, Yaron Singer, Amin Karbasi (2023)<br />
- **AART: AI-Assisted Red-Teaming with Diverse Data Generation for New LLM-powered Applications** \[[Paper](https://arxiv.org/abs/2311.08592)\] <br />
Bhaktipriya Radharapu, Kevin Robinson, Lora Aroyo, Preethi Lahoti (2023)<br />
- **DALA: A Distribution-Aware LoRA-Based Adversarial Attack against Language Models** \[[Paper](https://arxiv.org/abs/2311.08598)\] <br />
Yibo Wang, Xiangjue Dong, James Caverlee, Philip S. Yu (2023)<br />
- **JAB: Joint Adversarial Prompting and Belief Augmentation** \[[Paper](https://arxiv.org/abs/2311.09473)\] <br />
Ninareh Mehrabi, Palash Goyal, Anil Ramakrishna, Jwala Dhamala, Shalini Ghosh, Richard Zemel, Kai-Wei Chang, Aram Galstyan, Rahul Gupta (2023)<br />
- **No Offense Taken: Eliciting Offensiveness from Language Models** \[[Paper](https://arxiv.org/abs/2310.00892)\] <br />
Anugya Srivastava, Rahul Ahuja, Rohith Mukku (2023)<br />
- **LoFT: Local Proxy Fine-tuning For Improving Transferability Of Adversarial Attacks Against Large Language Model** \[[Paper](https://arxiv.org/abs/2310.04445)\] <br />
Muhammad Ahmed Shah, Roshan Sharma, Hira Dhamyal, Raphael Olivier, Ankit Shah, Joseph Konan, Dareen Alharthi, Hazim T Bukhari, Massa Baali, Soham Deshmukh, Michael Kuhlmann, Bhiksha Raj, Rita Singh (2023)<br />
### Decoding
- **Weak-to-Strong Jailbreaking on Large Language Models** \[[Paper](https://arxiv.org/abs/2401.17256)\] <br />
Xuandong Zhao, Xianjun Yang, Tianyu Pang, Chao Du, Lei Li, Yu-Xiang Wang, William Yang Wang (2024)<br />
- **COLD-Attack: Jailbreaking LLMs with Stealthiness and Controllability** \[[Paper](https://arxiv.org/abs/2402.08679)\] <br />
Xingang Guo, Fangxu Yu, Huan Zhang, Lianhui Qin, Bin Hu (2024)<br />
### Genetic Algorithm
- **Semantic Mirror Jailbreak: Genetic Algorithm Based Jailbreak Prompts Against Open-source LLMs** \[[Paper](https://arxiv.org/abs/2402.14872)\] <br />
Xiaoxia Li, Siyuan Liang, Jiyi Zhang, Han Fang, Aishan Liu, Ee-Chien Chang (2024)<br />
- **Open Sesame! Universal Black Box Jailbreaking of Large Language Models** \[[Paper](https://arxiv.org/abs/2309.01446)\] <br />
Raz Lapid, Ron Langberg, Moshe Sipper (2023)<br />
### Reinforcement Learning
- **SneakyPrompt: Jailbreaking Text-to-image Generative Models** \[[Paper](https://arxiv.org/abs/2305.12082)\] <br />
Yuchen Yang, Bo Hui, Haolin Yuan, Neil Gong, Yinzhi Cao (2023)<br />
- **Red Teaming Game: A Game-Theoretic Framework for Red Teaming Language Models** \[[Paper](https://arxiv.org/abs/2310.00322)\] <br />
Chengdong Ma, Ziran Yang, Minquan Gao, Hai Ci, Jun Gao, Xuehai Pan, Yaodong Yang (2023)<br />
- **Explore,Establish,Exploit: Red Teaming Language Models from Scratch** \[[Paper](https://arxiv.org/abs/2306.09442)\] <br />
Stephen Casper, Jason Lin, Joe Kwon, Gatlen Culp, Dylan Hadfield-Menell (2023)<br />
- **Unveiling the Implicit Toxicity in Large Language Models** \[[Paper](https://arxiv.org/abs/2311.17391)\] <br />
Jiaxin Wen, Pei Ke, Hao Sun, Zhexin Zhang, Chengfei Li, Jinfeng Bai, Minlie Huang (2023)<br />
</details>
</details>

<details>
<summary><h2>Defenses</h2></summary>
<details>
<summary><h3>__Training Time Defenses</h3></summary>

<!-- Markdown content -->
## Training Time Defenses
### RLHF
- **Configurable Safety Tuning of Language Models with Synthetic Preference Data** \[[Paper](https://arxiv.org/abs/2404.00495)\] <br />
Victor Gallego (2024)<br />
- **Enhancing LLM Safety via Constrained Direct Preference Optimization** \[[Paper](https://arxiv.org/abs/2403.02475)\] <br />
Zixuan Liu, Xiaolin Sun, Zizhan Zheng (2024)<br />
- **Safe RLHF: Safe Reinforcement Learning from Human Feedback** \[[Paper](https://arxiv.org/abs/2310.12773)\] <br />
Josef Dai, Xuehai Pan, Ruiyang Sun, Jiaming Ji, Xinbo Xu, Mickel Liu, Yizhou Wang, Yaodong Yang (2023)<br />
- **BeaverTails: Towards Improved Safety Alignment of LLM via a Human-Preference Dataset** \[[Paper](https://arxiv.org/abs/2307.04657)\] <br />
Jiaming Ji, Mickel Liu, Juntao Dai, Xuehai Pan, Chi Zhang, Ce Bian, Chi Zhang, Ruiyang Sun, Yizhou Wang, Yaodong Yang (2023)<br />
- **Safer-Instruct: Aligning Language Models with Automated Preference Data** \[[Paper](https://arxiv.org/abs/2311.08685)\] <br />
Taiwei Shi, Kai Chen, Jieyu Zhao (2023)<br />
### Fine-tuning
- **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models** \[[Paper](https://arxiv.org/abs/2404.06666)\] <br />
Xinfeng Li, Yuchen Yang, Jiangyi Deng, Chen Yan, Yanjiao Chen, Xiaoyu Ji, Wenyuan Xu (2024)<br />
- **Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models** \[[Paper](https://arxiv.org/abs/2402.02207)\] <br />
Yongshuo Zong, Ondrej Bohdal, Tingyang Yu, Yongxin Yang, Timothy Hospedales (2024)<br />
- **Developing Safe and Responsible Large Language Models -- A Comprehensive Framework** \[[Paper](https://arxiv.org/abs/2404.01399)\] <br />
Shaina Raza, Oluwanifemi Bamgbose, Shardul Ghuge, Fatemeh Tavakoli, Deepak John Reji (2024)<br />
- **Immunization against harmful fine-tuning attacks** \[[Paper](https://arxiv.org/abs/2402.16382)\] <br />
Domenic Rosati, Jan Wehner, Kai Williams, Łukasz Bartoszcze, Jan Batzner, Hassan Sajjad, Frank Rudzicz (2024)<br />
- **Mitigating Fine-tuning Jailbreak Attack with Backdoor Enhanced Alignment** \[[Paper](https://arxiv.org/abs/2402.14968)\] <br />
Jiongxiao Wang, Jiazhao Li, Yiquan Li, Xiangyu Qi, Junjie Hu, Yixuan Li, Patrick McDaniel, Muhao Chen, Bo Li, Chaowei Xiao (2024)<br />
- **Dialectical Alignment: Resolving the Tension of 3H and Security Threats of LLMs** \[[Paper](https://arxiv.org/abs/2404.00486)\] <br />
Shu Yang, Jiayuan Su, Han Jiang, Mengdi Li, Keyuan Cheng, Muhammad Asif Ali, Lijie Hu, Di Wang (2024)<br />
- **Pruning for Protection: Increasing Jailbreak Resistance in Aligned LLMs Without Fine-Tuning** \[[Paper](https://arxiv.org/abs/2401.10862)\] <br />
Adib Hasan, Ileana Rugina, Alex Wang (2024)<br />
- **Eraser: Jailbreaking Defense in Large Language Models via Unlearning Harmful Knowledge** \[[Paper](https://arxiv.org/abs/2404.0588)\] <br />
Weikai Lu, Ziqian Zeng, Jianwei Wang, Zhengdong Lu, Zelin Chen, Huiping Zhuang, Cen Chen (2024)<br />
- **Two Heads are Better than One: Nested PoE for Robust Defense Against Multi-Backdoors** \[[Paper](https://arxiv.org/abs/2404.02356)\] <br />
Victoria Graf, Qin Liu, Muhao Chen (2024)<br />
- **Defending Against Weight-Poisoning Backdoor Attacks for Parameter-Efficient Fine-Tuning** \[[Paper](https://arxiv.org/abs/2402.12168)\] <br />
Shuai Zhao, Leilei Gan, Luu Anh Tuan, Jie Fu, Lingjuan Lyu, Meihuizi Jia, Jinming Wen (2024)<br />
- **Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions** \[[Paper](https://arxiv.org/abs/2309.07875)\] <br />
Federico Bianchi, Mirac Suzgun, Giuseppe Attanasio, Paul Röttger, Dan Jurafsky, Tatsunori Hashimoto, James Zou (2023)<br />
- **Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM** \[[Paper](https://arxiv.org/abs/2309.14348)\] <br />
Bochuan Cao, Yuanpu Cao, Lu Lin, Jinghui Chen (2023)<br />
- **Learn What NOT to Learn: Towards Generative Safety in Chatbots** \[[Paper](https://arxiv.org/abs/2304.1122)\] <br />
Leila Khalatbari, Yejin Bang, Dan Su, Willy Chung, Saeed Ghadimi, Hossein Sameti, Pascale Fung (2023)<br />
- **Jatmo: Prompt Injection Defense by Task-Specific Finetuning** \[[Paper](https://arxiv.org/abs/2312.17673)\] <br />
Julien Piet, Maha Alrashed, Chawin Sitawarin, Sizhe Chen, Zeming Wei, Elizabeth Sun, Basel Alomair, David Wagner (2023)<br />
</details>

<details>
<summary><h3>__Training Time Defenses</h3></summary>

<!-- Markdown content -->
## Inference Time Defenses
### Prompting
- **AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting** \[[Paper](https://arxiv.org/abs/2403.09513)\] <br />
Yu Wang, Xiaogeng Liu, Yu Li, Muhao Chen, Chaowei Xiao (2024)<br />
- **Break the Breakout: Reinventing LM Defense Against Jailbreak Attacks with Self-Refinement** \[[Paper](https://arxiv.org/abs/2402.1518)\] <br />
Heegyu Kim, Sehyun Yuk, Hyunsouk Cho (2024)<br />
- **On Prompt-Driven Safeguarding for Large Language Models** \[[Paper](https://arxiv.org/abs/2401.18018)\] <br />
Chujie Zheng, Fan Yin, Hao Zhou, Fandong Meng, Jie Zhou, Kai-Wei Chang, Minlie Huang, Nanyun Peng (2024)<br />
- **Signed-Prompt: A New Approach to Prevent Prompt Injection Attacks Against LLM-Integrated Applications** \[[Paper](https://arxiv.org/abs/2401.07612)\] <br />
Xuchen Suo (2024)<br />
- **Intention Analysis Makes LLMs A Good Jailbreak Defender** \[[Paper](https://arxiv.org/abs/2401.06561)\] <br />
Yuqi Zhang, Liang Ding, Lefei Zhang, Dacheng Tao (2024)<br />
- **Defending Against Indirect Prompt Injection Attacks With Spotlighting** \[[Paper](https://arxiv.org/abs/2403.1472)\] <br />
Keegan Hines, Gary Lopez, Matthew Hall, Federico Zarfati, Yonatan Zunger, Emre Kiciman (2024)<br />
- **Ensuring Safe and High-Quality Outputs: A Guideline Library Approach for Language Models** \[[Paper](https://arxiv.org/abs/2403.11838)\] <br />
Yi Luo, Zhenghao Lin, Yuhao Zhang, Jiashuo Sun, Chen Lin, Chengjin Xu, Xiangdong Su, Yelong Shen, Jian Guo, Yeyun Gong (2024)<br />
- **Goal-guided Generative Prompt Injection Attack on Large Language Models** \[[Paper](https://arxiv.org/abs/2404.07234)\] <br />
Chong Zhang, Mingyu Jin, Qinkai Yu, Chengzhi Liu, Haochen Xue, Xiaobo Jin (2024)<br />
- **StruQ: Defending Against Prompt Injection with Structured Queries** \[[Paper](https://arxiv.org/abs/2402.06363)\] <br />
Sizhe Chen, Julien Piet, Chawin Sitawarin, David Wagner (2024)<br />
- **Studious Bob Fight Back Against Jailbreaking via Prompt Adversarial Tuning** \[[Paper](https://arxiv.org/abs/2402.06255)\] <br />
Yichuan Mo, Yuji Wang, Zeming Wei, Yisen Wang (2024)<br />
- **Self-Guard: Empower the LLM to Safeguard Itself** \[[Paper](https://arxiv.org/abs/2310.15851)\] <br />
Zezhong Wang, Fangkai Yang, Lu Wang, Pu Zhao, Hongru Wang, Liang Chen, Qingwei Lin, Kam-Fai Wong (2023)<br />
- **Using In-Context Learning to Improve Dialogue Safety** \[[Paper](https://arxiv.org/abs/2302.00871)\] <br />
Nicholas Meade, Spandana Gella, Devamanyu Hazarika, Prakhar Gupta, Di Jin, Siva Reddy, Yang Liu, Dilek Hakkani-Tür (2023)<br />
- **Defending Large Language Models Against Jailbreaking Attacks Through Goal Prioritization** \[[Paper](https://arxiv.org/abs/2311.09096)\] <br />
Zhexin Zhang, Junxiao Yang, Pei Ke, Minlie Huang (2023)<br />
- **Bergeron: Combating Adversarial Attacks through a Conscience-Based Alignment Framework** \[[Paper](https://arxiv.org/abs/2312.00029)\] <br />
Matthew Pisano, Peter Ly, Abraham Sanders, Bingsheng Yao, Dakuo Wang, Tomek Strzalkowski, Mei Si (2023)<br />
### Ensemble
- **Combating Adversarial Attacks with Multi-Agent Debate** \[[Paper](https://arxiv.org/abs/2401.05998)\] <br />
Steffi Chern, Zhen Fan, Andy Liu (2024)<br />
- **TrustAgent: Towards Safe and Trustworthy LLM-based Agents through Agent Constitution** \[[Paper](https://arxiv.org/abs/2402.01586)\] <br />
Wenyue Hua, Xianjun Yang, Zelong Li, Wei Cheng, Yongfeng Zhang (2024)<br />
- **AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2403.04783)\] <br />
Yifan Zeng, Yiran Wu, Xiao Zhang, Huazheng Wang, Qingyun Wu (2024)<br />
- **Learn to Disguise: Avoid Refusal Responses in LLM's Defense via a Multi-agent Attacker-Disguiser Game** \[[Paper](https://arxiv.org/abs/2404.02532)\] <br />
Qianqiao Xu, Zhiliang Tian, Hongyan Wu, Zhen Huang, Yiping Song, Feng Liu, Dongsheng Li (2024)<br />
- **Jailbreaker in Jail: Moving Target Defense for Large Language Models** \[[Paper](https://arxiv.org/abs/2310.02417)\] <br />
Bocheng Chen, Advait Paliwal, Qiben Yan (2023)<br />
### Guardrails
#### Input Guardrails
- **UFID: A Unified Framework for Input-level Backdoor Detection on Diffusion Models** \[[Paper](https://arxiv.org/abs/2404.01101)\] <br />
Zihan Guan, Mengxuan Hu, Sheng Li, Anil Vullikanti (2024)<br />
- **Universal Prompt Optimizer for Safe Text-to-Image Generation** \[[Paper](https://arxiv.org/abs/2402.10882)\] <br />
Zongyu Wu, Hongcheng Gao, Yueze Wang, Xiang Zhang, Suhang Wang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang (2024)<br />
- **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** \[[Paper](https://arxiv.org/abs/2401.02906)\] <br />
Renjie Pi, Tianyang Han, Yueqi Xie, Rui Pan, Qing Lian, Hanze Dong, Jipeng Zhang, Tong Zhang (2024)<br />
- **Added Toxicity Mitigation at Inference Time for Multimodal and Massively Multilingual Translation** \[[Paper](https://arxiv.org/abs/2311.06532)\] <br />
Marta R. Costa-jussà, David Dale, Maha Elbayad, Bokai Yu (2023)<br />
- **A Mutation-Based Method for Multi-Modal Jailbreaking Attack Detection** \[[Paper](https://arxiv.org/abs/2312.10766)\] <br />
Xiaoyu Zhang, Cen Zhang, Tianlin Li, Yihao Huang, Xiaojun Jia, Xiaofei Xie, Yang Liu, Chao Shen (2023)<br />
- **Detection and Defense Against Prominent Attacks on Preconditioned LLM-Integrated Virtual Assistants** \[[Paper](https://arxiv.org/abs/2401.00994)\] <br />
Chun Fai Chan, Daniel Wankit Yip, Aysan Esmradi (2024)<br />
- **ShieldLM: Empowering LLMs as Aligned,Customizable and Explainable Safety Detectors** \[[Paper](https://arxiv.org/abs/2402.16444)\] <br />
Zhexin Zhang, Yida Lu, Jingyuan Ma, Di Zhang, Rui Li, Pei Ke, Hao Sun, Lei Sha, Zhifang Sui, Hongning Wang, Minlie Huang (2024)<br />
- **Round Trip Translation Defence against Large Language Model Jailbreaking Attacks** \[[Paper](https://arxiv.org/abs/2402.13517)\] <br />
Canaan Yung, Hadi Mohaghegh Dolatabadi, Sarah Erfani, Christopher Leckie (2024)<br />
- **Gradient Cuff: Detecting Jailbreak Attacks on Large Language Models by Exploring Refusal Loss Landscapes** \[[Paper](https://arxiv.org/abs/2403.00867)\] <br />
Xiaomeng Hu, Pin-Yu Chen, Tsung-Yi Ho (2024)<br />
- **Defending Jailbreak Prompts via In-Context Adversarial Game** \[[Paper](https://arxiv.org/abs/2402.13148)\] <br />
Yujun Zhou, Yufei Han, Haomin Zhuang, Taicheng Guo, Kehan Guo, Zhenwen Liang, Hongyan Bao, Xiangliang Zhang (2024)<br />
- **SPML: A DSL for Defending Language Models Against Prompt Attacks** \[[Paper](https://arxiv.org/abs/2402.11755)\] <br />
Reshabh K Sharma, Vinayak Gupta, Dan Grossman (2024)<br />
- **Robust Safety Classifier for Large Language Models: Adversarial Prompt Shield** \[[Paper](https://arxiv.org/abs/2311.00172)\] <br />
Jinhwa Kim, Ali Derakhshan, Ian G. Harris (2023)<br />
- **AI Control: Improving Safety Despite Intentional Subversion** \[[Paper](https://arxiv.org/abs/2312.06942)\] <br />
Ryan Greenblatt, Buck Shlegeris, Kshitij Sachan, Fabien Roger (2023)<br />
- **Maatphor: Automated Variant Analysis for Prompt Injection Attacks** \[[Paper](https://arxiv.org/abs/2312.11513)\] <br />
Ahmed Salem, Andrew Paverd, Boris Köpf (2023)<br />
#### Output Guardrails
- **Defending LLMs against Jailbreaking Attacks via Backtranslation** \[[Paper](https://arxiv.org/abs/2402.16459)\] <br />
Yihan Wang, Zhouxing Shi, Andrew Bai, Cho-Jui Hsieh (2024)<br />
- **Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks** \[[Paper](https://arxiv.org/abs/2401.17263)\] <br />
Andy Zhou, Bo Li, Haohan Wang (2024)<br />
- **Jailbreaking is Best Solved by Definition** \[[Paper](https://arxiv.org/abs/2403.14725)\] <br />
Taeyoun Kim, Suhas Kotha, Aditi Raghunathan (2024)<br />
- **LLM Self Defense: By Self Examination,LLMs Know They Are Being Tricked** \[[Paper](https://arxiv.org/abs/2308.07308)\] <br />
Mansi Phute, Alec Helbling, Matthew Hull, ShengYun Peng, Sebastian Szyller, Cory Cornelius, Duen Horng Chau (2023)<br />
#### Input & Output Guardrails
- **RigorLLM: Resilient Guardrails for Large Language Models against Undesired Content** \[[Paper](https://arxiv.org/abs/2403.13031)\] <br />
Zhuowen Yuan, Zidi Xiong, Yi Zeng, Ning Yu, Ruoxi Jia, Dawn Song, Bo Li (2024)<br />
- **NeMo Guardrails: A Toolkit for Controllable and Safe LLM Applications with Programmable Rails** \[[Paper](https://arxiv.org/abs/2310.10501)\] <br />
Traian Rebedea, Razvan Dinu, Makesh Sreedhar, Christopher Parisien, Jonathan Cohen (2023)<br />
- **Llama Guard: LLM-based Input-Output Safeguard for Human-AI Conversations** \[[Paper](https://arxiv.org/abs/2312.06674)\] <br />
Hakan Inan, Kartikeya Upasani, Jianfeng Chi, Rashi Rungta, Krithika Iyer, Yuning Mao, Michael Tontchev, Qing Hu, Brian Fuller, Davide Testuggine, Madian Khabsa (2023)<br />
### Adversarial Suffix Defenses
- **Defending Large Language Models against Jailbreak Attacks via Semantic Smoothing** \[[Paper](https://arxiv.org/abs/2402.16192)\] <br />
Jiabao Ji, Bairu Hou, Alexander Robey, George J. Pappas, Hamed Hassani, Yang Zhang, Eric Wong, Shiyu Chang (2024)<br />
- **Certifying LLM Safety against Adversarial Prompting** \[[Paper](https://arxiv.org/abs/2309.02705)\] <br />
Aounon Kumar, Chirag Agarwal, Suraj Srinivas, Aaron Jiaxun Li, Soheil Feizi, Himabindu Lakkaraju (2023)<br />
- **Baseline Defenses for Adversarial Attacks Against Aligned Language Models** \[[Paper](https://arxiv.org/abs/2309.00614)\] <br />
Neel Jain, Avi Schwarzschild, Yuxin Wen, Gowthami Somepalli, John Kirchenbauer, Ping-yeh Chiang, Micah Goldblum, Aniruddha Saha, Jonas Geiping, Tom Goldstein (2023)<br />
- **Detecting Language Model Attacks with Perplexity** \[[Paper](https://arxiv.org/abs/2308.14132)\] <br />
Gabriel Alon, Michael Kamfonas (2023)<br />
- **SmoothLLM: Defending Large Language Models Against Jailbreaking Attacks** \[[Paper](https://arxiv.org/abs/2310.03684)\] <br />
Alexander Robey, Eric Wong, Hamed Hassani, George J. Pappas (2023)<br />
- **Token-Level Adversarial Prompt Detection Based on Perplexity Measures and Contextual Information** \[[Paper](https://arxiv.org/abs/2311.11509)\] <br />
Zhengmian Hu, Gang Wu, Saayan Mitra, Ruiyi Zhang, Tong Sun, Heng Huang, Viswanathan Swaminathan (2023)<br />
### Decoding Defenses
- **Towards Safety and Helpfulness Balanced Responses via Controllable Large Language Models** \[[Paper](https://arxiv.org/abs/2404.01295)\] <br />
Yi-Lin Tuan, Xilun Chen, Eric Michael Smith, Louis Martin, Soumya Batra, Asli Celikyilmaz, William Yang Wang, Daniel M. Bikel (2024)<br />
- **SafeDecoding: Defending against Jailbreak Attacks via Safety-Aware Decoding** \[[Paper](https://arxiv.org/abs/2402.08983)\] <br />
Zhangchen Xu, Fengqing Jiang, Luyao Niu, Jinyuan Jia, Bill Yuchen Lin, Radha Poovendran (2024)<br />
</details>
</details>

<details>
<summary><h2>Evaluations</h2></summary>
<details>
<summary><h3>__Evaluation Metrics</h3></summary>

<!-- Markdown content -->
## Evaluation Metrics
### Attack Metrics
- **A Novel Evaluation Framework for Assessing Resilience Against Prompt Injection Attacks in Large Language Models** \[[Paper](https://arxiv.org/abs/2401.00991)\] <br />
Daniel Wankit Yip, Aysan Esmradi, Chun Fai Chan (2024)<br />
- **AttackEval: How to Evaluate the Effectiveness of Jailbreak Attacking on Large Language Models** \[[Paper](https://arxiv.org/abs/2401.09002)\] <br />
Dong shu, Mingyu Jin, Suiyuan Zhu, Beichen Wang, Zihao Zhou, Chong Zhang, Yongfeng Zhang (2024)<br />
- **Take a Look at it! Rethinking How to Evaluate Language Model Jailbreak** \[[Paper](https://arxiv.org/abs/2404.06407)\] <br />
Hongyu Cai, Arjun Arunasalam, Leo Y. Lin, Antonio Bianchi, Z. Berkay Celik (2024)<br />
### Defense Metrics
- **How (un)ethical are instruction-centric responses of LLMs? Unveiling the vulnerabilities of safety guardrails to harmful queries** \[[Paper](https://arxiv.org/abs/2402.15302)\] <br />
Somnath Banerjee, Sayan Layek, Rima Hazra, Animesh Mukherjee (2024)<br />
- **The Art of Defending: A Systematic Evaluation and Analysis of LLM Defense Strategies on Safety and Over-Defensiveness** \[[Paper](https://arxiv.org/abs/2401.00287)\] <br />
Neeraj Varshney, Pavel Dolin, Agastya Seth, Chitta Baral (2023)<br />
</details>

<details>
<summary><h3>__Evaluation Benchmarks</h3></summary>

<!-- Markdown content -->
## Evaluation Benchmarks
- **JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models** \[[Paper](https://arxiv.org/abs/2404.01318)\] <br />
Patrick Chao, Edoardo Debenedetti, Alexander Robey, Maksym Andriushchenko, Francesco Croce, Vikash Sehwag, Edgar Dobriban, Nicolas Flammarion, George J. Pappas, Florian Tramer, Hamed Hassani, Eric Wong (2024)<br />
- **SafetyPrompts: a Systematic Review of Open Datasets for Evaluating and Improving Large Language Model Safety** \[[Paper](https://arxiv.org/abs/2404.05399)\] <br />
Paul Röttger, Fabio Pernisi, Bertie Vidgen, Dirk Hovy (2024)<br />
- **From Representational Harms to Quality-of-Service Harms: A Case Study on Llama 2 Safety Safeguards** \[[Paper](https://arxiv.org/abs/2403.13213)\] <br />
Khaoula Chehbouni, Megha Roshan, Emmanuel Ma, Futian Andrew Wei, Afaf Taik, Jackie CK Cheung, Golnoosh Farnadi (2024)<br />
- **SALAD-Bench: A Hierarchical and Comprehensive Safety Benchmark for Large Language Models** \[[Paper](https://arxiv.org/abs/2402.05044)\] <br />
Lijun Li, Bowen Dong, Ruohui Wang, Xuhao Hu, Wangmeng Zuo, Dahua Lin, Yu Qiao, Jing Shao (2024)<br />
- **A StrongREJECT for Empty Jailbreaks** \[[Paper](https://arxiv.org/abs/2402.1026)\] <br />
Alexandra Souly, Qingyuan Lu, Dillon Bowen, Tu Trinh, Elvis Hsieh, Sana Pandey, Pieter Abbeel, Justin Svegliato, Scott Emmons, Olivia Watkins, Sam Toyer (2024)<br />
- **HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal** \[[Paper](https://arxiv.org/abs/2402.04249)\] <br />
Mantas Mazeika, Long Phan, Xuwang Yin, Andy Zou, Zifan Wang, Norman Mu, Elham Sakhaee, Nathaniel Li, Steven Basart, Bo Li, David Forsyth, Dan Hendrycks (2024)<br />
- **SafetyBench: Evaluating the Safety of Large Language Models with Multiple Choice Questions** \[[Paper](https://arxiv.org/abs/2309.07045)\] <br />
Zhexin Zhang, Leqi Lei, Lindong Wu, Rui Sun, Yongkang Huang, Chong Long, Xiao Liu, Xuanyu Lei, Jie Tang, Minlie Huang (2023)<br />
- **XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models** \[[Paper](https://arxiv.org/abs/2308.01263)\] <br />
Paul Röttger, Hannah Rose Kirk, Bertie Vidgen, Giuseppe Attanasio, Federico Bianchi, Dirk Hovy (2023)<br />
- **Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs** \[[Paper](https://arxiv.org/abs/2308.13387)\] <br />
Yuxia Wang, Haonan Li, Xudong Han, Preslav Nakov, Timothy Baldwin (2023)<br />
- **Safety Assessment of Chinese Large Language Models** \[[Paper](https://arxiv.org/abs/2304.10436)\] <br />
Hao Sun, Zhexin Zhang, Jiawen Deng, Jiale Cheng, Minlie Huang (2023)<br />
- **Red Teaming Language Models to Reduce Harms: Methods,Scaling Behaviors,and Lessons Learned** \[[Paper](https://arxiv.org/abs/2209.07858)\] <br />
Deep Ganguli, Liane Lovitt, Jackson Kernion, Amanda Askell, Yuntao Bai, Saurav Kadavath, Ben Mann, Ethan Perez, Nicholas Schiefer, Kamal Ndousse, Andy Jones, Sam Bowman, Anna Chen, Tom Conerly, Nova DasSarma, Dawn Drain, Nelson Elhage, Sheer El-Showk, Stanislav Fort, Zac Hatfield-Dodds, Tom Henighan, Danny Hernandez, Tristan Hume, Josh Jacobson, Scott Johnston, Shauna Kravec, Catherine Olsson, Sam Ringer, Eli Tran-Johnson, Dario Amodei, Tom Brown, Nicholas Joseph, Sam McCandlish, Chris Olah, Jared Kaplan, Jack Clark (2022)<br />
- **DICES Dataset: Diversity in Conversational AI Evaluation for Safety** \[[Paper](https://arxiv.org/abs/2306.11247)\] <br />
Lora Aroyo, Alex S. Taylor, Mark Diaz, Christopher M. Homan, Alicia Parrish, Greg Serapio-Garcia, Vinodkumar Prabhakaran, Ding Wang (2023)<br />
- **Latent Jailbreak: A Benchmark for Evaluating Text Safety and Output Robustness of Large Language Models** \[[Paper](https://arxiv.org/abs/2307.08487)\] <br />
Huachuan Qiu, Shuai Zhang, Anqi Li, Hongliang He, Zhenzhong Lan (2023)<br />
- **Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game** \[[Paper](https://arxiv.org/abs/2311.01011)\] <br />
Sam Toyer, Olivia Watkins, Ethan Adrian Mendes, Justin Svegliato, Luke Bailey, Tiffany Wang, Isaac Ong, Karim Elmaaroufi, Pieter Abbeel, Trevor Darrell, Alan Ritter, Stuart Russell (2023)<br />
- **Can LLMs Follow Simple Rules?** \[[Paper](https://arxiv.org/abs/2311.04235)\] <br />
Norman Mu, Sarah Chen, Zifan Wang, Sizhe Chen, David Karamardian, Lulwa Aljeraisy, Basel Alomair, Dan Hendrycks, David Wagner (2023)<br />
- **SimpleSafetyTests: a Test Suite for Identifying Critical Safety Risks in Large Language Models** \[[Paper](https://arxiv.org/abs/2311.0837)\] <br />
Bertie Vidgen, Nino Scherrer, Hannah Rose Kirk, Rebecca Qian, Anand Kannappan, Scott A. Hale, Paul Röttger (2023)<br />
- **Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models** \[[Paper](https://arxiv.org/abs/2312.14197)\] <br />
Jingwei Yi, Yueqi Xie, Bin Zhu, Emre Kiciman, Guangzhong Sun, Xing Xie, Fangzhao Wu (2023)<br />
- **SC-Safety: A Multi-round Open-ended Question Adversarial Safety Benchmark for Large Language Models in Chinese** \[[Paper](https://arxiv.org/abs/2310.05818)\] <br />
Liang Xu, Kangkang Zhao, Lei Zhu, Hang Xue (2023)<br />
- **Walking a Tightrope -- Evaluating Large Language Models in High-Risk Domains** \[[Paper](https://arxiv.org/abs/2311.14966)\] <br />
Chia-Chien Hung, Wiem Ben Rim, Lindsay Frost, Lars Bruckner, Carolin Lawrence (2023)<br />
</details>
</details>

<details>
<summary><h2>Applications</h2></summary>
<details>
<summary><h3>__Application Domains</h3></summary>

<!-- Markdown content -->
## Application Domains
### Agent
- **MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2311.176)\] <br />
Xin Liu, Yichen Zhu, Jindong Gu, Yunshi Lan, Chao Yang, Yu Qiao (2023)<br />
- **Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast** \[[Paper](https://arxiv.org/abs/2402.08567)\] <br />
Xiangming Gu, Xiaosen Zheng, Tianyu Pang, Chao Du, Qian Liu, Ye Wang, Jing Jiang, Min Lin (2024)<br />
- **How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs** \[[Paper](https://arxiv.org/abs/2311.16101)\] <br />
Haoqin Tu, Chenhang Cui, Zijun Wang, Yiyang Zhou, Bingchen Zhao, Junlin Han, Wangchunshu Zhou, Huaxiu Yao, Cihang Xie (2023)<br />
- **Towards Red Teaming in Multimodal and Multilingual Translation** \[[Paper](https://arxiv.org/abs/2401.16247)\] <br />
Christophe Ropers, David Dale, Prangthip Hansanti, Gabriel Mejia Gonzalez, Ivan Evtimov, Corinne Wong, Christophe Touret, Kristina Pereyra, Seohyun Sonia Kim, Cristian Canton Ferrer, Pierre Andrews, Marta R. Costa-jussà (2024)<br />
- **JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2404.03027)\] <br />
Weidi Luo, Siyuan Ma, Xiaogeng Liu, Xiaoyu Guo, Chaowei Xiao (2024)<br />
- **Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks?** \[[Paper](https://arxiv.org/abs/2404.03411)\] <br />
Shuo Chen, Zhen Han, Bailan He, Zifeng Ding, Wenqian Yu, Philip Torr, Volker Tresp, Jindong Gu (2024)<br />
- **R-Judge: Benchmarking Safety Risk Awareness for LLM Agents** \[[Paper](https://arxiv.org/abs/2401.10019)\] <br />
Tongxin Yuan, Zhiwei He, Lingzhong Dong, Yiming Wang, Ruijie Zhao, Tian Xia, Lizhen Xu, Binglin Zhou, Fangqi Li, Zhuosheng Zhang, Rui Wang, Gongshen Liu (2024)<br />
- **GPT in Sheep's Clothing: The Risk of Customized GPTs** \[[Paper](https://arxiv.org/abs/2401.09075)\] <br />
Sagiv Antebi, Noam Azulay, Edan Habler, Ben Ganon, Asaf Shabtai, Yuval Elovici (2024)<br />
- **ToolSword: Unveiling Safety Issues of Large Language Models in Tool Learning Across Three Stages** \[[Paper](https://arxiv.org/abs/2402.10753)\] <br />
Junjie Ye, Sixian Li, Guanyu Li, Caishuang Huang, Songyang Gao, Yilong Wu, Qi Zhang, Tao Gui, Xuanjing Huang (2024)<br />
- **A Trembling House of Cards? Mapping Adversarial Attacks against Language Agents** \[[Paper](https://arxiv.org/abs/2402.10196)\] <br />
Lingbo Mo, Zeyi Liao, Boyuan Zheng, Yu Su, Chaowei Xiao, Huan Sun (2024)<br />
- **Rapid Adoption,Hidden Risks: The Dual Impact of Large Language Model Customization** \[[Paper](https://arxiv.org/abs/2402.09179)\] <br />
Rui Zhang, Hongwei Li, Rui Wen, Wenbo Jiang, Yuan Zhang, Michael Backes, Yun Shen, Yang Zhang (2024)<br />
- **Goal-Oriented Prompt Attack and Safety Evaluation for LLMs** \[[Paper](https://arxiv.org/abs/2309.1183)\] <br />
Chengyuan Liu, Fubang Zhao, Lizhi Qing, Yangyang Kang, Changlong Sun, Kun Kuang, Fei Wu (2023)<br />
- **Identifying the Risks of LM Agents with an LM-Emulated Sandbox** \[[Paper](https://arxiv.org/abs/2309.15817)\] <br />
Yangjun Ruan, Honghua Dong, Andrew Wang, Silviu Pitis, Yongchao Zhou, Jimmy Ba, Yann Dubois, Chris J. Maddison, Tatsunori Hashimoto (2023)<br />
- **CValues: Measuring the Values of Chinese Large Language Models from Safety to Responsibility** \[[Paper](https://arxiv.org/abs/2307.09705)\] <br />
Guohai Xu, Jiayi Liu, Ming Yan, Haotian Xu, Jinghui Si, Zhuoran Zhou, Peng Yi, Xing Gao, Jitao Sang, Rong Zhang, Ji Zhang, Chao Peng, Fei Huang, Jingren Zhou (2023)<br />
- **Exploiting Novel GPT-4 APIs** \[[Paper](https://arxiv.org/abs/2312.14302)\] <br />
Kellin Pelrine, Mohammad Taufeeque, Michał Zając, Euan McLean, Adam Gleave (2023)<br />
- **Evil Geniuses: Delving into the Safety of LLM-based Agents** \[[Paper](https://arxiv.org/abs/2311.11855)\] <br />
Yu Tian, Xiao Yang, Jingyuan Zhang, Yinpeng Dong, Hang Su (2023)<br />
- **Assessing Prompt Injection Risks in 200+ Custom GPTs** \[[Paper](https://arxiv.org/abs/2311.11538)\] <br />
Jiahao Yu, Yuhang Wu, Dong Shu, Mingyu Jin, Xinyu Xing (2023)<br />
### Programming
- **DeceptPrompt: Exploiting LLM-driven Code Generation via Adversarial Natural Language Instructions** \[[Paper](https://arxiv.org/abs/2312.0473)\] <br />
Fangzhou Wu, Xiaogeng Liu, Chaowei Xiao (2023)<br />
- **Poisoned ChatGPT Finds Work for Idle Hands: Exploring Developers' Coding Practices with Insecure Suggestions from Poisoned AI Models** \[[Paper](https://arxiv.org/abs/2312.06227)\] <br />
Sanghak Oh, Kiho Lee, Seonhye Park, Doowon Kim, Hyoungshick Kim (2023)<br />
</details>

<details>
<summary><h3>__Application Risks</h3></summary>

<!-- Markdown content -->
## Application Risks
### Prompt Injection
- **Scaling Behavior of Machine Translation with Large Language Models under Prompt Injection Attacks** \[[Paper](https://arxiv.org/abs/2403.09832)\] <br />
Zhifan Sun, Antonio Valerio Miceli-Barone (2024)<br />
- **From Prompt Injections to SQL Injection Attacks: How Protected is Your LLM-Integrated Web Application?** \[[Paper](https://arxiv.org/abs/2308.0199)\] <br />
Rodrigo Pedro, Daniel Castro, Paulo Carreira, Nuno Santos (2023)<br />
- **Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection** \[[Paper](https://arxiv.org/abs/2302.12173)\] <br />
Kai Greshake, Sahar Abdelnabi, Shailesh Mishra, Christoph Endres, Thorsten Holz, Mario Fritz (2023)<br />
- **Prompt Injection attack against LLM-integrated Applications** \[[Paper](https://arxiv.org/abs/2306.05499)\] <br />
Yi Liu, Gelei Deng, Yuekang Li, Kailong Wang, Zihao Wang, Xiaofeng Wang, Tianwei Zhang, Yepang Liu, Haoyu Wang, Yan Zheng, Yang Liu (2023)<br />
### Prompt Extraction
- **Jailbreaking GPT-4V via Self-Adversarial Attacks with System Prompts** \[[Paper](https://arxiv.org/abs/2311.09127)\] <br />
Yuanwei Wu, Xiang Li, Yixin Liu, Pan Zhou, Lichao Sun (2023)<br />
- **Prompt Stealing Attacks Against Large Language Models** \[[Paper](https://arxiv.org/abs/2402.12959)\] <br />
Zeyang Sha, Yang Zhang (2024)<br />
- **Effective Prompt Extraction from Language Models** \[[Paper](https://arxiv.org/abs/2307.06865)\] <br />
Yiming Zhang, Nicholas Carlini, Daphne Ippolito (2023)<br />
</details>
</details>

<details>
<summary><h2>Multimodal Red Teaming</h2></summary>

<details>
<summary><h3>__Attack Strategies</h3></summary>

<!-- Markdown content -->
## Attack Strategies
### Completion Compliance
- **Few-Shot Adversarial Prompt Learning on Vision-Language Models** \[[Paper](https://arxiv.org/abs/2403.14774)\] <br />
Yiwei Zhou, Xiaobo Xia, Zhiwei Lin, Bo Han, Tongliang Liu (2024)<br />
- **Hijacking Context in Large Multi-modal Models** \[[Paper](https://arxiv.org/abs/2312.07553)\] <br />
Joonhyun Jeong (2023)<br />
### Instruction Indirection
- **On the Robustness of Large Multimodal Models Against Image Adversarial Attacks** \[[Paper](https://arxiv.org/abs/2312.03777)\] <br />
Xuanming Cui, Alejandro Aparcedo, Young Kyun Jang, Ser-Nam Lim (2023)<br />
- **Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2403.09792)\] <br />
Yifan Li, Hangyu Guo, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen (2024)<br />
- **Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks** \[[Paper](https://arxiv.org/abs/2402.00626)\] <br />
Maan Qraitem, Nazia Tasnim, Piotr Teterwak, Kate Saenko, Bryan A. Plummer (2024)<br />
- **Visual Adversarial Examples Jailbreak Aligned Large Language Models** \[[Paper](https://arxiv.org/abs/2306.13213)\] <br />
Xiangyu Qi, Kaixuan Huang, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal (2023)<br />
- **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** \[[Paper](https://arxiv.org/abs/2307.14539)\] <br />
Erfan Shayegani, Yue Dong, Nael Abu-Ghazaleh (2023)<br />
- **Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs** \[[Paper](https://arxiv.org/abs/2307.1049)\] <br />
Eugene Bagdasaryan, Tsung-Yin Hsieh, Ben Nassi, Vitaly Shmatikov (2023)<br />
- **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** \[[Paper](https://arxiv.org/abs/2311.05608)\] <br />
Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang (2023)<br />
- **InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models** \[[Paper](https://arxiv.org/abs/2312.01886)\] <br />
Xunguang Wang, Zhenlan Ji, Pingchuan Ma, Zongjie Li, Shuai Wang (2023)<br />
</details>
<details>
<summary><h3>__Attack Searchers</h3></summary>

<!-- Markdown content -->
## Attack Searchers
### Image Searchers
- **Diffusion Attack: Leveraging Stable Diffusion for Naturalistic Image Attacking** \[[Paper](https://arxiv.org/abs/2403.14778)\] <br />
Qianyu Guo, Jiaming Fu, Yawen Lu, Dongming Gan (2024)<br />
- **On the Adversarial Robustness of Multi-Modal Foundation Models** \[[Paper](https://arxiv.org/abs/2308.10741)\] <br />
Christian Schlarmann, Matthias Hein (2023)<br />
- **How Robust is Google's Bard to Adversarial Image Attacks?** \[[Paper](https://arxiv.org/abs/2309.11751)\] <br />
Yinpeng Dong, Huanran Chen, Jiawei Chen, Zhengwei Fang, Xiao Yang, Yichi Zhang, Yu Tian, Hang Su, Jun Zhu (2023)<br />
- **Test-Time Backdoor Attacks on Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2402.08577)\] <br />
Dong Lu, Tianyu Pang, Chao Du, Qian Liu, Xianjun Yang, Min Lin (2024)<br />
### Cross Modality Searchers
- **SA-Attack: Improving Adversarial Transferability of Vision-Language Pre-training Models via Self-Augmentation** \[[Paper](https://arxiv.org/abs/2312.04913)\] <br />
Bangyan He, Xiaojun Jia, Siyuan Liang, Tianrui Lou, Yang Liu, Xiaochun Cao (2023)<br />
- **MMA-Diffusion: MultiModal Attack on Diffusion Models** \[[Paper](https://arxiv.org/abs/2311.17516)\] <br />
Yijun Yang, Ruiyuan Gao, Xiaosen Wang, Tsung-Yi Ho, Nan Xu, Qiang Xu (2023)<br />
- **Improving Adversarial Transferability of Visual-Language Pre-training Models through Collaborative Multimodal Interaction** \[[Paper](https://arxiv.org/abs/2403.10883)\] <br />
Jiyuan Fu, Zhaoyu Chen, Kaixun Jiang, Haijing Guo, Jiafeng Wang, Shuyong Gao, Wenqiang Zhang (2024)<br />
- **An Image Is Worth 1000 Lies: Transferability of Adversarial Images across Prompts on Vision-Language Models** \[[Paper](https://openreview.net/forum?id=nc5GgFAvtk)\] <br />
Haochen Luo,  Jindong Gu,  Fengyuan Liu,  Philip Torr (2024)<br />
### Others
- **SneakyPrompt: Jailbreaking Text-to-image Generative Models** \[[Paper](https://arxiv.org/abs/2305.12082)\] <br />
Yuchen Yang, Bo Hui, Haolin Yuan, Neil Gong, Yinzhi Cao (2023)<br />
- **Prompting4Debugging: Red-Teaming Text-to-Image Diffusion Models by Finding Problematic Prompts** \[[Paper](https://arxiv.org/abs/2309.06135)\] <br />
Zhi-Yi Chin, Chieh-Ming Jiang, Ching-Chun Huang, Pin-Yu Chen, Wei-Chen Chiu (2023)<br />
</details>
<details>
<summary><h3>__Defense</h3></summary>

<!-- Markdown content -->
## Defense
### Guardrail Defenses
- **UFID: A Unified Framework for Input-level Backdoor Detection on Diffusion Models** \[[Paper](https://arxiv.org/abs/2404.01101)\] <br />
Zihan Guan, Mengxuan Hu, Sheng Li, Anil Vullikanti (2024)<br />
- **Universal Prompt Optimizer for Safe Text-to-Image Generation** \[[Paper](https://arxiv.org/abs/2402.10882)\] <br />
Zongyu Wu, Hongcheng Gao, Yueze Wang, Xiang Zhang, Suhang Wang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang (2024)<br />
- **Eyes Closed,Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation** \[[Paper](https://arxiv.org/abs/2403.09572)\] <br />
Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang (2024)<br />
- **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** \[[Paper](https://arxiv.org/abs/2401.02906)\] <br />
Renjie Pi, Tianyang Han, Yueqi Xie, Rui Pan, Qing Lian, Hanze Dong, Jipeng Zhang, Tong Zhang (2024)<br />
- **Added Toxicity Mitigation at Inference Time for Multimodal and Massively Multilingual Translation** \[[Paper](https://arxiv.org/abs/2311.06532)\] <br />
Marta R. Costa-jussà, David Dale, Maha Elbayad, Bokai Yu (2023)<br />
- **A Mutation-Based Method for Multi-Modal Jailbreaking Attack Detection** \[[Paper](https://arxiv.org/abs/2312.10766)\] <br />
Xiaoyu Zhang, Cen Zhang, Tianlin Li, Yihao Huang, Xiaojun Jia, Xiaofei Xie, Yang Liu, Chao Shen (2023)<br />
### Other Defenses
- **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models** \[[Paper](https://arxiv.org/abs/2404.06666)\] <br />
Xinfeng Li, Yuchen Yang, Jiangyi Deng, Chen Yan, Yanjiao Chen, Xiaoyu Ji, Wenyuan Xu (2024)<br />
- **AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting** \[[Paper](https://arxiv.org/abs/2403.09513)\] <br />
Yu Wang, Xiaogeng Liu, Yu Li, Muhao Chen, Chaowei Xiao (2024)<br />
- **Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models** \[[Paper](https://arxiv.org/abs/2402.02207)\] <br />
Yongshuo Zong, Ondrej Bohdal, Tingyang Yu, Yongxin Yang, Timothy Hospedales (2024)<br />
</details>
<details>
<summary><h3>__Application</h3></summary>

<!-- Markdown content -->
## Application
### Agents
- **Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks?** \[[Paper](https://arxiv.org/abs/2404.03411)\] <br />
Shuo Chen, Zhen Han, Bailan He, Zifeng Ding, Wenqian Yu, Philip Torr, Volker Tresp, Jindong Gu (2024)<br />
- **JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks** \[[Paper](https://arxiv.org/abs/2404.03027)\] <br />
Weidi Luo, Siyuan Ma, Xiaogeng Liu, Xiaoyu Guo, Chaowei Xiao (2024)<br />
- **Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast** \[[Paper](https://arxiv.org/abs/2402.08567)\] <br />
Xiangming Gu, Xiaosen Zheng, Tianyu Pang, Chao Du, Qian Liu, Ye Wang, Jing Jiang, Min Lin (2024)<br />
- **MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models** \[[Paper](https://arxiv.org/abs/2311.176)\] <br />
Xin Liu, Yichen Zhu, Jindong Gu, Yunshi Lan, Chao Yang, Yu Qiao (2023)<br />
- **How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs** \[[Paper](https://arxiv.org/abs/2311.16101)\] <br />
Haoqin Tu, Chenhang Cui, Zijun Wang, Yiyang Zhou, Bingchen Zhao, Junlin Han, Wangchunshu Zhou, Huaxiu Yao, Cihang Xie (2023)<br />
- **Towards Red Teaming in Multimodal and Multilingual Translation** \[[Paper](https://arxiv.org/abs/2401.16247)\] <br />
Christophe Ropers, David Dale, Prangthip Hansanti, Gabriel Mejia Gonzalez, Ivan Evtimov, Corinne Wong, Christophe Touret, Kristina Pereyra, Seohyun Sonia Kim, Cristian Canton Ferrer, Pierre Andrews, Marta R. Costa-jussà (2024)<br />
</details>
<details>
<summary><h3>__Benchmarks</h3></summary>

<!-- Markdown content -->
## Benchmarks
- **Adversarial Nibbler: An Open Red-Teaming Method for Identifying Diverse Harms in Text-to-Image Generation** \[[Paper](https://arxiv.org/abs/2403.12075)\] <br />
Jessica Quaye, Alicia Parrish, Oana Inel, Charvi Rastogi, Hannah Rose Kirk, Minsuk Kahng, Erin van Liemt, Max Bartolo, Jess Tsang, Justin White, Nathan Clement, Rafael Mosquera, Juan Ciro, Vijay Janapa Reddi, Lora Aroyo (2024)<br />
- **Red Teaming Visual Language Models** \[[Paper](https://arxiv.org/abs/2401.12915)\] <br />
Mukai Li, Lei Li, Yuwei Yin, Masood Ahmed, Zhenguang Liu, Qi Liu (2024)<br />

</details>
</details>


### Citation
```
@article{lin2024achilles,
      title={Against The Achilles' Heel: A Survey on Red Teaming for Generative Models}, 
      author={Lizhi Lin and Honglin Mu and Zenan Zhai and Minghan Wang and Yuxia Wang and Renxi Wang and Junjie Gao and Yixuan Zhang and Wanxiang Che and Timothy Baldwin and Xudong Han and Haonan Li},
      year={2024},
      journal={arXiv preprint, arXiv:2404.00629},
      primaryClass={cs.CL}
}
```
