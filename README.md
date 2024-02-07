# Papers about red-teaming

[Lizhi Lin](https://github.com/Shomvel),
[Yuxia Wang](https://github.com/yuxiaw),
[Haonan Li](https://haonan-li.github.io/),
[Zenan Zhai](https://github.com/zenanz),
[Xudong Han](https://github.com/HanXudong),
[Renxi Wang](https://renxiwang.site/),
[Honglin Mu](https://github.com/hlmu),
[Junjie Gao](https://github.com/Junjie-Gao19)

## Introduction
We review recent papers about red-teaming foundation models, collecting 150+ papers covering risk taxonomy, attack methods of language models and multimodal models, defenses and evaluations. We highlight the conflicting optimization objective of helpfulness and harmlessness and the way in which core capabilities of foundation models are involved, and build attack taxonomies accordingly. Survey paper coming soon. 

**Disclaimer: We may miss some relevant papers in the list. If you have any suggestions or would like to add some papers, please submit a pull request or email us. Your contribution is much appreciated!**


## Papers
- [Papers about red-teaming](#papers-about-red-teaming)
  - [Introduction](#introduction)
  - [Papers](#papers)
    - [Surveys and Collections](#surveys-and-collections)
    - [Application Risks](#application-risks)
      - [Agents and GPTs](#agents-and-gpts)
      - [Fine-tuning](#fine-tuning)
      - [Others](#others)
    - [Multilingual](#multilingual)
    - [Risk Taxonomy](#risk-taxonomy)
      - [Analysis](#analysis)
    - [Attacking Language Models](#attacking-language-models)
      - [LLM Synthesis](#llm-synthesis)
      - [Template Based](#template-based)
        - [Composition](#composition)
        - [Psychology and Persona](#psychology-and-persona)
      - [Search Based](#search-based)
      - [Activation Based](#activation-based)
      - [Decoding Strategy](#decoding-strategy)
      - [Transfer Attack](#transfer-attack)
      - [Other](#other)
    - [Attacking Multimodal Models](#attacking-multimodal-models)
      - [Language Attack](#language-attack)
      - [Vision Attack](#vision-attack)
      - [Intermodal Attack](#intermodal-attack)
    - [Defense](#defense)
      - [Prompting](#prompting)
      - [RLHF](#rlhf)
      - [Multi-Stage](#multi-stage)
      - [Language Models Ensemble](#language-models-ensemble)
      - [Fine-tuning](#fine-tuning-1)
      - [Targets](#targets)
        - [Against Adversarial Suffixes](#against-adversarial-suffixes)
        - [Multimodal Defense](#multimodal-defense)
    - [Evaluation](#evaluation)
      - [Metrics](#metrics)
      - [Benchmarks](#benchmarks)


### Surveys and Collections

- **LLM Security** \[Github\](https://llmsecurity.net/)

- **LLM Security & Privacy** \[Github\](https://github.com/chawins/llm-sp)

- **Awesome LLM-Safety** \[[GitHub](https://github.com/ydyjya/Awesome-LLM-Safety/tree/main)\] <br />

- **EasyJailbreak: A Unified Framework for Jailbreaking Large Language Models** \[[GitHub](https://github.com/EasyJailbreak/EasyJailbreak)\] <br />

- **Survey of Vulnerabilities in Large Language Models Revealed by Adversarial Attacks** \[[Paper](https://arxiv.org/pdf/2310.10844.pdf)\] <br />
Erfan Shayegani and Md Abdullah Al Mamun and Yu Fu and Pedram Zaree and Yue Dong and Nael Abu-Ghazaleh (2023)<br />

- **A Comprehensive Survey of Attack Techniques, Implementation, and Mitigation Strategies in Large Language Models** \[[Paper](https://arxiv.org/pdf/2312.10982.pdf)\] <br />
Aysan Esmradi and Daniel Wankit Yip and Chun Fai Chan (2023)<br />

- **Towards Safer Generative Language Models: A Survey on Safety Risks, Evaluations, and Improvements** \[[Paper](https://arxiv.org/pdf/2302.09270.pdf)\] <br />
Jiawen Deng and Jiale Cheng and Hao Sun and Zhexin Zhang and Minlie Huang (2023)<br />

- **Security and Privacy Challenges of Large Language Models: A Survey** \[[Paper](https://arxiv.org/pdf/2402.00888.pdf)\] <br />
Badhan Chandra Das and M. Hadi Amini and Yanzhao Wu (2024)<br />

### Application Risks

#### Agents and GPTs

- **Testing Language Model Agents Safely in the Wild** \[[Paper](https://arxiv.org/pdf/2311.10538.pdf)\] <br />
Silen Naihin and David Atkinson and Marc Green and Merwane Hamadi and Craig Swift and Douglas Schonholtz and Adam Tauman Kalai and David Bau (2023)<br />

- **R-Judge: Benchmarking Safety Risk Awareness for LLM Agents** \[[Paper](https://arxiv.org/pdf/2401.10019.pdf)\] <br />
Tongxin Yuan and Zhiwei He and Lingzhong Dong and Yiming Wang and Ruijie Zhao and Tian Xia and Lizhen Xu and Binglin Zhou and Fangqi Li and Zhuosheng Zhang and Rui Wang and Gongshen Liu (2024)<br />

- **Evil Geniuses: Delving into the Safety of LLM-based Agents** \[[Paper](https://arxiv.org/pdf/2311.11855.pdf)\] <br />
Yu Tian and Xiao Yang and Jingyuan Zhang and Yinpeng Dong and Hang Su (2023)<br />

- **Identifying the Risks of LM Agents with an LM-Emulated Sandbox** \[[Paper](https://arxiv.org/pdf/2309.15817.pdf)\] <br />
Yangjun Ruan and Honghua Dong and Andrew Wang and Silviu Pitis and Yongchao Zhou and Jimmy Ba and Yann Dubois and Chris J. Maddison and Tatsunori Hashimoto (2023)<br />

- **GPT in Sheep's Clothing: The Risk of Customized GPTs** \[[Paper](https://arxiv.org/pdf/2401.09075.pdf)\] <br />
Sagiv Antebi and Noam Azulay and Edan Habler and Ben Ganon and Asaf Shabtai and Yuval Elovici (2024)<br />

- **Assessing Prompt Injection Risks in 200+ Custom GPTs** \[[Paper](https://arxiv.org/pdf/2311.11538.pdf)\] <br />
Jiahao Yu and Yuhang Wu and Dong Shu and Mingyu Jin and Xinyu Xing (2023)<br />

- **PsySafe: A Comprehensive Framework for Psychological-based Attack, Defense, and Evaluation of Multi-agent System Safety** \[[Paper](https://arxiv.org/pdf/2401.11880.pdf)\] <br />
Zaibin Zhang and Yongting Zhang and Lijun Li and Hongzhi Gao and Lijun Wang and Huchuan Lu and Feng Zhao and Yu Qiao and Jing Shao (2024)<br />


#### Fine-tuning

- **LoRA Fine-tuning Efficiently Undoes Safety Training in Llama 2-Chat 70B** \[[Paper](https://arxiv.org/pdf/2310.20624.pdf)\] <br />
Simon Lermen and Charlie Rogers-Smith and Jeffrey Ladish (2023)<br />

- **Removing RLHF Protections in GPT-4 via Fine-Tuning** \[[Paper](https://arxiv.org/pdf/2311.05553.pdf)\] <br />
Qiusi Zhan and Richard Fang and Rohan Bindu and Akul Gupta and Tatsunori Hashimoto and Daniel Kang (2023)<br />

- **Forcing Generative Models to Degenerate Ones: The Power of Data Poisoning Attacks** \[[Paper](https://arxiv.org/pdf/2312.04748.pdf)\] <br />
Shuli Jiang and Swanand Ravindra Kadhe and Yi Zhou and Ling Cai and Nathalie Baracaldo (2023)<br />

- **BadLlama: cheaply removing safety fine-tuning from Llama 2-Chat 13B** \[[Paper](https://arxiv.org/pdf/2312.04127.pdf)\] <br />
Pranav Gade and Simon Lermen and Charlie Rogers-Smith and Jeffrey Ladish (2023)<br />

- **Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!** \[[Paper](https://arxiv.org/pdf/2310.03693)\] <br />
Xiangyu Qi and Yi Zeng and Tinghao Xie and Pin-Yu Chen and Ruoxi Jia and Prateek Mittal and Peter Henderson (2023)<br />

- **The Janus Interface: How Fine-Tuning in Large Language Models Amplifies the Privacy Risks** \[[Paper](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1002/anie.202218122)\] <br />
Xiaoyi Chen and Siyuan Tang and Rui Zhu and Shijun Yan and Lei Jin and Zihao Wang and Liya Su and XiaoFeng Wang and Haixu Tang (2023)<br />

- **Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions** \[[Paper](https://arxiv.org/pdf/2309.07875)\] <br />
Federico Bianchi and Mirac Suzgun and Giuseppe Attanasio and Paul Röttger and Dan Jurafsky and Tatsunori Hashimoto and James Zou (2023)<br />

- **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models** \[[Paper](https://arxiv.org/pdf/2310.02949)\] <br />
Xianjun Yang and Xiao Wang and Qi Zhang and Linda Petzold and William Yang Wang and Xun Zhao and Dahua Lin (2023)<br />

- **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety
Training** \[[Paper](https://arxiv.org/pdf/2401.05566.pdf)\] <br />
Evan Hubinger and Carson Denison and Jesse Mu and Mike Lambert and Meg Tong and Monte MacDiarmid and Tamera Lanham and Daniel M. Ziegler and Tim Maxwell and Newton Cheng and Adam Jermyn and Amanda Askell and Ansh Radhakrishnan and Cem Anil and David Duvenaud and Deep Ganguli and Fazl Barez and Jack Clark and Kamal Ndousse and Kshitij Sachan and Michael Sellitto and Mrinank Sharma and Nova DasSarma and Roger Grosse and Shauna Kravec and Yuntao Bai and Zachary Witten and Marina Favaro and Jan Brauner and Holden Karnofsky and Paul Christiano and Samuel R. Bowman and Logan Graham and Jared Kaplan and Sören Mindermann and Ryan Greenblatt and Buck Shlegeris and Nicholas Schiefer and Ethan Perez (2024)<br />

- **Can Sensitive Information Be Deleted From LLMs? Objectives for Defending Against Extraction Attacks** \[[Paper](https://arxiv.org/abs/2309.17410)\] <br />
Vaidehi Patil and Peter Hase and Mohit Bansal (2023)<br />

#### Others

- **From Prompt Injections to SQL Injection Attacks: How Protected is Your LLM-Integrated Web Application?** \[[Paper](https://arxiv.org/pdf/2308.01990)\] <br />
Rodrigo Pedro and Daniel Castro and Paulo Carreira and Nuno Santos (2023)<br />

- **Transfer Attacks and Defenses for Large Language Models on Coding Tasks** \[[Paper](https://arxiv.org/pdf/2311.13445.pdf)\] <br />
Chi Zhang and Zifan Wang and Ravi Mangal and Matt Fredrikson and Limin Jia and Corina Pasareanu (2023)<br />

- **Unveiling the dark side of chatgpt: Exploring cyberattacks and enhancing user awareness** \[[Paper](https://www.preprints.org/manuscript/202309.1768/v1/download)\] <br />
Alawida, Moatsum and Abu Shawar, Bayan and Abiodun, Oludare Isaac and Mehmood, Abid and Omolara, Abiodun Esther and Al Hwaitat, Ahmad K (2024)<br />

  

### Multilingual

- **Multilingual Jailbreak Challenges in Large Language Models** \[[Paper](https://arxiv.org/pdf/2310.06474.pdf)\] <br />
Yue Deng and Wenxuan Zhang and Sinno Jialin Pan and Lidong Bing (2023)<br />

- **All Languages Matter: On the Multilingual Safety of Large Language Models** \[[Paper](https://arxiv.org/pdf/2310.00905)\] <br />
Wenxuan Wang and Zhaopeng Tu and Chang Chen and Youliang Yuan and Jen-tse Huang and Wenxiang Jiao and Michael R. Lyu (2023)<br />

- **Low-Resource Languages Jailbreak GPT-4** \[[Paper](https://arxiv.org/pdf/2310.02446.pdf)\] <br />
Zheng-Xin Yong and Cristina Menghini and Stephen H. Bach (2023)<br />

- **The Language Barrier: Dissecting Safety Challenges of LLMs in Multilingual Contexts** \[[Paper](https://arxiv.org/pdf/2401.13136.pdf)\] <br />
Lingfeng Shen and Weiting Tan and Sihao Chen and Yunmo Chen and Jingyu Zhang and Haoran Xu and Boyuan Zheng and Philipp Koehn and Daniel Khashabi (2024)<br />

  

### Risk Taxonomy

- **Tricking LLMs into Disobedience: Understanding, Analyzing, and Preventing Jailbreaks** \[[Paper](http://arxiv.org/pdf/2305.14965)\] <br />
Abhinav Rao and Sachin Vashistha and Atharva Naik and Somak Aditya and Monojit Choudhury (2023)<br />

- **Can LLMs Follow Simple Rules?** \[[Paper](https://arxiv.org/pdf/2311.04235.pdf)\] <br />
Norman Mu and Sarah Chen and Zifan Wang and Sizhe Chen and David Karamardian and Lulwa Aljeraisy and Dan Hendrycks and David Wagner (2023)<br />

- **A Security Risk Taxonomy for Large Language Models** \[[Paper](https://arxiv.org/pdf/2311.11415.pdf)\] <br />
Erik Derner and Kristina Batistič and Jan Zahálka and Robert Babuška (2023)<br />

- **Summon a Demon and Bind it: A Grounded Theory of LLM Red Teaming in the Wild** \[[Paper](https://arxiv.org/abs/2311.06237)\] <br />
Nanna Inie and Jonathan Stray and Leon Derczynski (2023)<br />

- **On the Risk of Misinformation Pollution with Large Language Models** \[[Paper](https://arxiv.org/pdf/2312.10982.pdf)\] <br />
Yikang Pan and Liangming Pan and Wenhu Chen and Preslav Nakov and Min-Yen Kan and William Yang Wang (2023)<br />

- **Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection** \[[Paper](https://arxiv.org/pdf/2302.12173)\] <br />
Kai Greshake and Sahar Abdelnabi and Shailesh Mishra and Christoph Endres and Thorsten Holz and Mario Fritz (2023)<br />

- **Prompt Injection Attacks and Defenses in LLM-Integrated Applications** \[[Paper](http://arxiv.org/pdf/2306.04735)\] <br />
Yupei Liu and Yuqi Jia and Runpeng Geng and Jinyuan Jia and Neil Zhenqiang Gong (2023)<br />

- **Risk Taxonomy, Mitigation, and Assessment Benchmarks of Large Language Model Systems** \[[Paper](http://arxiv.org/pdf/2303.05453)\] <br />
Tianyu Cui and Yanling Wang and Chuanpu Fu and Yong Xiao and Sijia Li and Xinhao Deng and Yunpeng Liu and Qinglin Zhang and Ziyi Qiu and Peiyang Li and Zhixing Tan and Junwu Xiong and Xinyu Kong and Zujie Wen and Ke Xu and Qi Li (2024)<br />

- **Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study** \[[Paper](http://arxiv.org/pdf/2305.13860)\] <br />
Yi Liu and Gelei Deng and Zhengzi Xu and Yuekang Li and Yaowen Zheng and Ying Zhang and Lida Zhao and Tianwei Zhang and Yang Liu (2023)<br />

- **Privacy in Large Language Models: Attacks, Defenses and Future Directions** \[[Paper](https://arxiv.org/pdf/2310.10383.pdf)\] <br />
Haoran Li and Yulin Chen and Jinglong Luo and Yan Kang and Xiaojin Zhang and Qi Hu and Chunkit Chan and Yangqiu Song (2023)<br />

- **"Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models** \[[Paper](https://arxiv.org/pdf/2308.03825)\] <br />
Xinyue Shen and Zeyuan Chen and Michael Backes and Yun Shen and Yang Zhang (2023)<br />

- **AI Deception: A Survey of Examples, Risks, and Potential Solutions** \[[Paper](https://arxiv.org/pdf/2308.14752)\] <br />
Peter S. Park and Simon Goldstein and Aidan O'Gara and Michael Chen and Dan Hendrycks (2023)<br />

- **Safety Assessment of Chinese Large Language Models** \[[Paper](https://arxiv.org/pdf/2304.10436.pdf)\] <br />
Hao Sun and Zhexin Zhang and Jiawen Deng and Jiale Cheng and Minlie Huang (2023)<br />

- **Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs Through a Global Prompt Hacking Competition** \[[Paper](https://arxiv.org/pdf/2311.16119.pdf)\] <br />
Sander V Schulhoff and Jeremy Pinto and Anaum Khan and Louis-FranÃois Bouchard and Chenglei Si and Jordan Lee Boyd-Graber and Svetlina Anati and Valen Tagliabue and Anson Liu Kost and Christopher R Carnahan (2023)<br />

#### Analysis

- **Jailbroken: How Does LLM Safety Training Fail?** \[[Paper](https://arxiv.org/pdf/2307.02483)\] <br />
Alexander Wei and Nika Haghtalab and Jacob Steinhardt (2023)<br />

- **Safety Alignment in NLP Tasks: Weakly Aligned Summarization as an In-Context Attack** \[[Paper](https://arxiv.org/pdf/2312.06924.pdf)\] <br />
Yu Fu and Yufei Li and Wen Xiao and Cong Liu and Yue Dong (2023)<br />

- **Why do universal adversarial attacks work on large language models?: Geometry might be the answer** \[[Paper](https://arxiv.org/pdf/2309.00254)\] <br />
Subhash, Varshini and Bialas, Anna and Pan, Weiwei and Doshi-Velez, Finale (2023)<br />

- **Navigating the OverKill in Large Language Models** \[[Paper](https://arxiv.org/abs/2401.17633)\] <br />
Chenyu Shi and Xiao Wang and Qiming Ge and Songyang Gao and Xianjun Yang and Tao Gui and Qi Zhang and Xuanjing Huang and Xun Zhao and Dahua Lin (2024)<br />

- **Forbidden Facts: An Investigation of Competing Objectives in Llama-2** \[[Paper](https://arxiv.org/pdf/2312.08793.pdf)\] <br />
Tony T. Wang and Miles Wang and Kaivalya Hariharan and Nir Shavit (2023)<br />

  

### Attacking Language Models

#### LLM Synthesis

  

- **Automatic Hallucination Assessment for Aligned Large Language Models via
Transferable Adversarial Attacks** \[[Paper](https://arxiv.org/pdf/2310.12516.pdf)\] <br />
Xiaodong Yu and Hao Cheng and Xiaodong Liu and Dan Roth and Jianfeng Gao (2023)<br />

- **Attack Prompt Generation for Red Teaming and Defending Large Language
Models** \[[Paper](http://arxiv.org/pdf/2306.05499)\] <br />
Boyi Deng and Wenjie Wang and Fuli Feng and Yang Deng and Qifan Wang and Xiangnan He (2023)<br />

- **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts** \[[Paper](https://arxiv.org/pdf/2309.10253)\] <br />
Jiahao Yu and Xingwei Lin and Zheng Yu and Xinyu Xing (2023)<br />

- **All in How You Ask for It: Simple Black-Box Method for Jailbreak Attacks** \[[Paper](https://arxiv.org/pdf/2401.09798.pdf)\] <br />
Kazuhiro Takemoto (2024)<br />

- **An LLM can Fool Itself: A Prompt-Based Adversarial Attack** \[[Paper](https://arxiv.org/pdf/2310.13345.pdf)\] <br />
Xilie Xu and Keyi Kong and Ning Liu and Lizhen Cui and Di Wang and Jingfeng Zhang and Mohan Kankanhalli (2023)<br />

- **Jailbreaking black box large language models in twenty queries** \[[Paper](https://arxiv.org/pdf/2310.08419)\] <br />
Chao, Patrick and Robey, Alexander and Dobriban, Edgar and Hassani, Hamed and Pappas, George J and Wong, Eric (2023)<br />

- **Tree of attacks: Jailbreaking black-box llms automatically** \[[Paper](https://arxiv.org/pdf/2312.02119.pdf)\] <br />
Mehrotra, Anay and Zampetakis, Manolis and Kassianik, Paul and Nelson, Blaine and Anderson, Hyrum and Singer, Yaron and Karbasi, Amin (2023)<br />

- **Red-Teaming Large Language Models using Chain of Utterances for Safety-Alignment** \[[Paper](https://arxiv.org/pdf/2306.09442)\] <br />
Rishabh Bhardwaj and Soujanya Poria (2023)<br />

- **TrojLLM: A Black-box Trojan Prompt Attack on Large Language Models** \[[Paper](https://arxiv.org/pdf/2306.06815.pdf)\] <br />
Jiaqi Xue and Mengxin Zheng and Ting Hua and Yilin Shen and Yepeng Liu and Ladislau B{\"o}l{\"o}ni and Qian Lou (2023)<br />

#### Template Based

- **Goal-Oriented Prompt Attack and Safety Evaluation for LLMs** \[[Paper](https://arxiv.org/pdf/2309.11830.pdf)\] <br />
Chengyuan Liu and Fubang Zhao and Lizhi Qing and Yangyang Kang and Changlong Sun and Kun Kuang and Fei Wu (2023)<br />
- **Prompt Injection attack against LLM-integrated Applications** \[[Paper](https://arxiv.org/pdf/2306.05499.pdf)\] <br />
Yi Liu and Gelei Deng and Yuekang Li and Kailong Wang and Tianwei Zhang and Yepang Liu and Haoyu Wang and Yan Zheng and Yang Liu (2023)<br />

- **Cognitive Overload: Jailbreaking Large Language Models with Overloaded
Logical Thinking** \[[Paper](https://arxiv.org/pdf/2311.09827.pdf)\] <br />
Nan Xu and Fei Wang and Ben Zhou and Bang Zheng Li and Chaowei Xiao and Muhao Chen (2023)<br />

- **DeepInception: Hypnotize Large Language Model to Be Jailbreaker** \[[Paper](https://arxiv.org/pdf/2311.03191.pdf)\] <br />
Xuan Li and Zhanke Zhou and Jianing Zhu and Jiangchao Yao and Tongliang Liu and Bo Han (2023)<br />

  
##### Composition

- **A Wolf in Sheep's Clothing: Generalized Nested Jailbreak Prompts can
Fool Large Language Models Easily** \[[Paper](https://arxiv.org/pdf/2311.08268.pdf)\] <br />
Peng Ding and Jun Kuang and Dan Ma and Xuezhi Cao and Yunsen Xian and Jiajun Chen and Shujian Huang (2023)<br />

- **FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models** \[[Paper](https://arxiv.org/pdf/2309.05274)\] <br />
Dongyu Yao and Jianshu Zhang and Ian G. Harris and Marcel Carlsson (2023)<br />

- **Prompt Packer: Deceiving LLMs through Compositional Instruction with
Hidden Attacks** \[[Paper](https://arxiv.org/pdf/2310.10077.pdf)\] <br />
Shuyu Jiang and Xingshu Chen and Rui Tang (2023)<br />

##### Psychology and Persona

- **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to
Challenge AI Safety by Humanizing LLMs** \[[Paper](https://arxiv.org/pdf/2401.06373.pdf)\] <br />
Yi Zeng and Hongpeng Lin and Jingwen Zhang and Diyi Yang and Ruoxi Jia and Weiyan Shi (2024)<br />

- **PsySafe: A Comprehensive Framework for Psychological-based Attack, Defense, and Evaluation of Multi-agent System Safety** \[[Paper](https://arxiv.org/pdf/2401.11880.pdf)\] <br />
Zaibin Zhang and Yongting Zhang and Lijun Li and Hongzhi Gao and Lijun Wang and Huchuan Lu and Feng Zhao and Yu Qiao and Jing Shao (2024)<br />

- **Scalable and Transferable Black-Box Jailbreaks for Language Models via
Persona Modulation** \[[Paper](https://arxiv.org/pdf/2311.03348.pdf)\] <br />
Rusheb Shah and Quentin Feuillade--Montixi and Soroush Pour and Arush Tagade and Stephen Casper and Javier Rando (2023)<br />

#### Search Based

- **Universal and transferable adversarial attacks on aligned language models** \[[Paper](https://arxiv.org/pdf/2307.15043.pdf)\] <br />
Zou, Andy and Wang, Zifan and Kolter, J Zico and Fredrikson, Matt (2023)<br />

- **JADE: A Linguistics-based Safety Evaluation Platform for Large Language Models** \[[Paper](https://arxiv.org/pdf/2311.00286.pdf)\] <br />
Mi Zhang and Xudong Pan and Min Yang (2023)<br />

- **Open Sesame! Universal Black Box Jailbreaking of Large Language Models** \[[Paper](https://arxiv.org/pdf/2309.01446)\] <br />
Raz Lapid and Ron Langberg and Moshe Sipper (2023)<br />

- **AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models** \[[Paper](https://arxiv.org/pdf/2310.04451)\] <br />
Sicheng Zhu and Ruiyi Zhang and Bang An and Gang Wu and Joe Barrow and Zichao Wang and Furong Huang and Ani Nenkova and Tong Sun (2023)<br />

- **AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models** \[[Paper](https://arxiv.org/pdf/2310.04451.pdf)\] <br />
Xiaogeng Liu and Nan Xu and Muhao Chen and Chaowei Xiao (2023)<br />


#### Activation Based

- **Open the Pandora's Box of LLMs: Jailbreaking LLMs through Representation
Engineering** \[[Paper](https://arxiv.org/pdf/2401.06824.pdf)\] <br />
Tianlong Li and Xiaoqing Zheng and Xuanjing Huang (2024)<br />

- **Backdoor Activation Attack: Attack Large Language Models using
Activation Steering for Safety-Alignment** \[[Paper](https://arxiv.org/pdf/2311.09433.pdf)\] <br />
Haoran Wang and Kai Shu (2023)<br />

- **Scaling Laws for Adversarial Attacks on Language Model Activations** \[[Paper](https://arxiv.org/pdf/2312.02780.pdf)\] <br />
Stanislav Fort (2023)<br />

- **Universal and transferable adversarial attacks on aligned language models** \[[Paper](https://arxiv.org/abs/2307.15043)\] <br />
Zou, Andy and Wang, Zifan and Kolter, J Zico and Fredrikson, Matt (2023)<br />

#### Decoding Strategy

- **On the Safety of Open-Sourced Large Language Models: Does Alignment
Really Prevent Them From Being Misused?** \[[Paper](https://arxiv.org/pdf/2310.01581)\] <br />
Hangfan Zhang and Zhimeng Guo and Huaisheng Zhu and Bochuan Cao and Lu Lin and Jinyuan Jia and Jinghui Chen and Dinghao Wu (2023)<br />

- **Catastrophic Jailbreak of Open-source LLMs via Exploiting Generation** \[[Paper](https://arxiv.org/pdf/2310.06987.pdf)\] <br />
Yangsibo Huang and Samyak Gupta and Mengzhou Xia and Kai Li and Danqi Chen (2023)<br />

#### Transfer Attack

- **AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models** \[[Paper](https://arxiv.org/pdf/2310.04451)\] <br />
Sicheng Zhu and Ruiyi Zhang and Bang An and Gang Wu and Joe Barrow and Zichao Wang and Furong Huang and Ani Nenkova and Tong Sun (2023)<br />

- **Weak-to-Strong Jailbreaking on Large Language Models** \[[Paper](https://arxiv.org/pdf/2401.17256.pdf)\] <br />
Xuandong Zhao and Xianjun Yang and Tianyu Pang and Chao Du and Lei Li and Yu-Xiang Wang and William Yang Wang (2024)<br />

- **Universal and transferable adversarial attacks on aligned language models** \[[Paper](https://arxiv.org/abs/2307.15043)\] <br />
Zou, Andy and Wang, Zifan and Kolter, J Zico and Fredrikson, Matt (2023)<br />


#### Other

- **GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher** \[[Paper](https://arxiv.org/pdf/2308.06463)\] <br />
Youliang Yuan and Wenxiang Jiao and Wenxuan Wang and Jen-tse Huang and Pinjia He and Shuming Shi and Zhaopeng Tu (2023)<br />

- **Analyzing the Inherent Response Tendency of LLMs: Real-World
Instructions-Driven Jailbreak** \[[Paper](https://arxiv.org/pdf/2312.04127.pdf)\] <br />
Yanrui Du and Sendong Zhao and Ming Ma and Yuhan Chen and Bing Qin (2023)<br />

- **Bypassing the Safety Training of Open-Source LLMs with Priming Attacks** \[[Paper](https://arxiv.org/pdf/2312.12321.pdf)\] <br />
Jason Vega and Isha Chaudhary and Changming Xu and Gagandeep Singh (2023)<br />

- **MasterKey: Automated Jailbreak Across Multiple Large Language Model Chatbots** \[[Paper](https://arxiv.org/pdf/2307.08715.pdf)\] <br />
Gelei Deng and Yi Liu and Yuekang Li and Kailong Wang and Ying Zhang and Zefeng Li and Haoyu Wang and Tianwei Zhang and Yang Liu (2023)<br />

- **Multi-step Jailbreaking Privacy Attacks on ChatGPT** \[[Paper](https://arxiv.org/abs/2304.05197)\] <br />
Haoran Li and Dadi Guo and Wei Fan and Mingshi Xu and Jie Huang and Fanpu Meng and Yangqiu Song (2023)<br />

- **Adversarial Attacks and Defenses in Large Language Models: Old and New
Threats** \[[Paper](https://arxiv.org/pdf/2310.19737.pdf)\] <br />
Leo Schwinn and David Dobre and Stephan Günnemann and Gauthier Gidel (2023)<br />

### Attacking Multimodal Models 

- **Red Teaming Visual Language Models** \[[Paper](https://arxiv.org/pdf/2401.12915.pdf)\] <br />
Mukai Li and Lei Li and Yuwei Yin and Masood Ahmed and Zhenguang Liu and Qi Liu (2024)<br />

#### Language Attack

- **Jailbreaking GPT-4V via Self-Adversarial Attacks with System Prompts** \[[Paper](https://arxiv.org/pdf/2311.09127.pdf)\] <br />
Yuanwei Wu and Xiang Li and Yixin Liu and Pan Zhou and Lichao Sun (2023)<br />

- **Visual Adversarial Examples Jailbreak Aligned Large Language Models** \[[Paper](https://arxiv.org/pdf/2312.04127.pdf)\] <br />
Xiangyu Qi and Kaixuan Huang and Ashwinee Panda and Peter Henderson and Mengdi Wang and Prateek Mittal (2023)<br />

- **Asymmetric Bias in Text-to-Image Generation with Adversarial Attacks** \[[Paper](https://arxiv.org/pdf/2312.14440.pdf)\] <br />
Haz Sameen Shahgir and Xianghao Kong and Greg Ver Steeg and Yue Dong (2023)<br />

- **FLIRT: Feedback Loop In-context Red Teaming** \[[Paper](https://arxiv.org/pdf/2308.04265.pdf)\] <br />
Ninareh Mehrabi and Palash Goyal and Christophe Dupuy and Qian Hu and Shalini Ghosh and Richard Zemel and Kai-Wei Chang and Aram Galstyan and Rahul Gupta (2023)<br />

#### Vision Attack

- **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** \[[Paper](https://arxiv.org/pdf/2311.05608.pdf)\] <br />
Yichen Gong and Delong Ran and Jinyuan Liu and Conglei Wang and Tianshuo Cong and Anyu Wang and Sisi Duan and Xiaoyun Wang (2023)<br />

- **How Robust is Google's Bard to Adversarial Image Attacks?** \[[Paper](https://arxiv.org/pdf/2309.11751)\] <br />
Yinpeng Dong and Huanran Chen and Jiawei Chen and Zhengwei Fang and Xiao Yang and Yichi Zhang and Yu Tian and Hang Su and Jun Zhu (2023)<br />

- **How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for
Vision LLMs** \[[Paper](https://arxiv.org/pdf/2311.16101.pdf)\] <br />
Haoqin Tu and Chenhang Cui and Zijun Wang and Yiyang Zhou and Bingchen Zhao and Junlin Han and Wangchunshu Zhou and Huaxiu Yao and Cihang Xie (2023)<br />

- **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** \[[Paper](https://arxiv.org/pdf/2307.14539.pdf)\] <br />
Erfan Shayegani and Yue Dong and Nael Abu-Ghazaleh (2023)<br />

- **Query-Relevant Images Jailbreak Large Multi-Modal Models** \[[Paper](https://arxiv.org/pdf/2311.17600.pdf)\] <br />
Xin Liu and Yichen Zhu and Yunshi Lan and Chao Yang and Yu Qiao (2023)<br />

- **On the Robustness of Large Multimodal Models Against Image Adversarial
Attacks** \[[Paper](https://arxiv.org/pdf/2312.03777.pdf)\] <br />
Xuanming Cui and Alejandro Aparcedo and Young Kyun Jang and Ser-Nam Lim (2023)<br />

- **Black box adversarial prompting for foundation models** \[[Paper](https://arxiv.org/pdf/2302.04237.pdf)\] <br />
Maus, Natalie and Chao, Patrick and Wong, Eric and Gardner, Jacob R (2023)<br />

#### Intermodal Attack

- **SA-Attack: Improving Adversarial Transferability of Vision-Language Pre-training Models via Self-Augmentation** \[[Paper](https://arxiv.org/pdf/2312.04913.pdf)\] <br />
Bangyan He and Xiaojun Jia and Siyuan Liang and Tianrui Lou and Yang Liu and Xiaochun Cao (2023)<br />

- **MMA-Diffusion: MultiModal Attack on Diffusion Models** \[[Paper](https://arxiv.org/pdf/2311.17516.pdf)\] <br />
Yijun Yang and Ruiyuan Gao and Xiaosen Wang and Tsung-Yi Ho and Nan Xu and Qiang Xu (2023)<br />

- **InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models** \[[Paper](https://arxiv.org/pdf/2312.01886.pdf)\] <br />
Xunguang Wang and Zhenlan Ji and Pingchuan Ma and Zongjie Li and Shuai Wang (2024)<br />


### Defense

#### Prompting

- **Intention Analysis Prompting Makes Large Language Models A Good
Jailbreak Defender** \[[Paper](https://arxiv.org/pdf/2401.06561.pdf)\] <br />
Yuqi Zhang and Liang Ding and Lefei Zhang and Dacheng Tao (2024)<br />

- **Jailbreak and Guard Aligned Language Models with Only Few In-Context
Demonstrations** \[[Paper](https://arxiv.org/pdf/2310.06387)\] <br />
Zeming Wei and Yifei Wang and Yisen Wang (2023)<br />

- **Self-Guard: Empower the LLM to Safeguard Itself** \[[Paper](https://arxiv.org/pdf/2310.15851.pdf)\] <br />
Zezhong Wang and Fangkai Yang and Lu Wang and Pu Zhao and Hongru Wang and Liang Chen and Qingwei Lin and Kam-Fai Wong (2023)<br />

- **Using In-Context Learning to Improve Dialogue Safety** \[[Paper](https://arxiv.org/pdf/2302.00871.pdf)\] <br />
Nicholas Meade and Spandana Gella and Devamanyu Hazarika and Prakhar Gupta and Di Jin and Siva Reddy and Yang Liu and Dilek Hakkani-Tür (2023)<br />

- **Defending ChatGPT against jailbreak attack via self-reminders** \[[Paper](https://www.nature.com/articles/s42256-023-00765-8)\] <br />
Yueqi Xie and Jingwei Yi and Jiawei Shao and Justin Curl and Lingjuan Lyu and Qifeng Chen and Xing Xie and Fangzhao Wu (2023)<br />

#### RLHF

- **BeaverTails: Towards Improved Safety Alignment of LLM via a Human-Preference Dataset** \[[Paper](https://arxiv.org/pdf/2307.04657)\] <br />
Jiaming Ji and Mickel Liu and Juntao Dai and Xuehai Pan and Chi Zhang and Ce Bian and Chi Zhang and Ruiyang Sun and Yizhou Wang and Yaodong Yang (2023)<br />

- **The History and Risks of Reinforcement Learning and Human Feedback** \[[Paper](https://arxiv.org/pdf/2310.13595.pdf)\] <br />
Nathan Lambert and Thomas Krendl Gilbert and Tom Zick (2023)<br />

- **Safer-Instruct: Aligning Language Models with Automated Preference Data** \[[Paper](https://arxiv.org/pdf/2311.08685.pdf)\] <br />
Taiwei Shi and Kai Chen and Jieyu Zhao (2023)<br />

- **Safe RLHF: Safe Reinforcement Learning from Human Feedback** \[[Paper](https://arxiv.org/pdf/2310.12773.pdf)\] <br />
Josef Dai and Xuehai Pan and Ruiyang Sun and Jiaming Ji and Xinbo Xu and Mickel Liu and Yizhou Wang and Yaodong Yang (2023)<br />

- **MART: Improving LLM Safety with Multi-round Automatic Red-Teaming** \[[Paper](https://arxiv.org/pdf/2311.07689.pdf)\] <br />
Suyu Ge and Chunting Zhou and Rui Hou and Madian Khabsa and Yi-Chia Wang and Qifan Wang and Jiawei Han and Yuning Mao (2023)<br />

#### Multi-Stage

- **NeMo Guardrails: A Toolkit for Controllable and Safe LLM Applications
with Programmable Rails** \[[Paper](https://arxiv.org/pdf/2310.10501.pdf)\] <br />
Traian Rebedea and Razvan Dinu and Makesh Sreedhar and Christopher Parisien and Jonathan Cohen (2023)<br />

- **GUARDIAN: A Multi-Tiered Defense Architecture for Thwarting Prompt Injection Attacks on LLMs** \[[Paper](https://www.scirp.org/journal/paperinformation?paperid=130663)\] <br />
Rai, Parijat and Sood, Saumil and Madisetti, Vijay K and Bahga, Arshdeep (2024)<br />

- **Baseline defenses for adversarial attacks against aligned language models** \[[Paper](https://arxiv.org/pdf/2309.00614.pdf)\] <br />
Jain, Neel and Schwarzschild, Avi and Wen, Yuxin and Somepalli, Gowthami and Kirchenbauer, John and Chiang, Ping-yeh and Goldblum, Micah and Saha, Aniruddha and Geiping, Jonas and Goldstein, Tom (2023)<br />

- **Bergeron: Combating Adversarial Attacks through a Conscience-Based Alignment Framework** \[[Paper](https://arxiv.org/pdf/2312.00029.pdf)\] <br />
Matthew Pisano and Peter Ly and Abraham Sanders and Bingsheng Yao and Dakuo Wang and Tomek Strzalkowski and Mei Si (2023)<br />

#### Language Models Ensemble

- **Jailbreaker in Jail: Moving Target Defense for Large Language Models** \[[Paper](https://arxiv.org/pdf/2310.02417.pdf)\] <br />
Bocheng Chen and Advait Paliwal and Qiben Yan (2023)<br />

- **Combating Adversarial Attacks with Multi-Agent Debate** \[[Paper](https://arxiv.org/pdf/2401.05998.pdf)\] <br />
Steffi Chern and Zhen Fan and Andy Liu (2024)<br />

#### Fine-tuning

- **Self-Guard: Empower the LLM to Safeguard Itself** \[[Paper](https://arxiv.org/pdf/2310.15851.pdf)\] <br />
Zezhong Wang and Fangkai Yang and Lu Wang and Pu Zhao and Hongru Wang and Liang Chen and Qingwei Lin and Kam-Fai Wong (2023)<br />

- **Recipes for Safety in Open-domain Chatbots** \[[Paper](https://arxiv.org/pdf/2010.07079.pdf)\] <br />
Jing Xu and Da Ju and Margaret Li and Y-Lan Boureau and Jason Weston and Emily Dinan (2020)<br />

- **Learn What NOT to Learn: Towards Generative Safety in Chatbots** \[[Paper](https://arxiv.org/pdf/2304.11220.pdf)\] <br />
Leila Khalatbari and Yejin Bang and Dan Su and Willy Chung and Saeed Ghadimi and Hossein Sameti and Pascale Fung (2023)<br />

- **Pruning for Protection: Increasing Jailbreak Resistance in Aligned LLMs
Without Fine-Tuning** \[[Paper](https://arxiv.org/pdf/2401.10862.pdf)\] <br />
Adib Hasan and Ileana Rugina and Alex Wang (2024)<br />

#### Targets

##### Against Adversarial Suffixes

- **Detecting Language Model Attacks with Perplexity** \[[Paper](https://arxiv.org/pdf/2308.14132.pdf)\] <br />
Gabriel Alon and Michael Kamfonas (2023)<br />

- **Certifying LLM Safety against Adversarial Prompting** \[[Paper](https://arxiv.org/pdf/2309.02705.pdf)\] <br />
Aounon Kumar and Chirag Agarwal and Suraj Srinivas and Aaron Jiaxun Li and Soheil Feizi and Himabindu Lakkaraju (2023)<br />

- **SmoothLLM: Defending Large Language Models Against Jailbreaking Attacks** \[[Paper](https://arxiv.org/pdf/2310.03684)\] <br />
Alexander Robey and Eric Wong and Hamed Hassani and George J. Pappas (2023)<br />

##### Multimodal Defense

- **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** \[[Paper](https://arxiv.org/pdf/2401.02906.pdf)\] <br />
Renjie Pi and Tianyang Han and Yueqi Xie and Rui Pan and Qing Lian and Hanze Dong and Jipeng Zhang and Tong Zhang (2024)<br />

  

### Evaluation

#### Metrics

- **A Novel Evaluation Framework for Assessing Resilience Against Prompt
Injection Attacks in Large Language Models** \[[Paper](https://arxiv.org/pdf/2401.00991.pdf)\] <br />
Daniel Wankit Yip and Aysan Esmradi and Chun Fai Chan (2024)<br />

- **AttackEval: How to Evaluate the Effectiveness of Jailbreak Attacking on Large Language Models** \[[Paper](https://arxiv.org/pdf/2401.09002.pdf)\] <br />
Dong shu and Mingyu Jin and Suiyuan Zhu and Beichen Wang and Zihao Zhou and Chong Zhang and Yongfeng Zhang (2024)<br />

- **Prompts Should not be Seen as Secrets: Systematically Measuring Prompt
Extraction Attack Success** \[[Paper](https://arxiv.org/pdf/2307.06865)\] <br />
Yiming Zhang and Daphne Ippolito (2023)<br />

- **Beyond the Safeguards: Exploring the Security Risks of ChatGPT** \[[Paper](http://arxiv.org/pdf/2305.08005)\] <br />
Erik Derner and Kristina Batistič (2023)<br />

- **It's a Fair Game or Is It? Examining How Users Navigate Disclosure Risks and Benefits When Using LLM-Based Conversational Agents** \[[Paper](https://arxiv.org/pdf/2309.11653)\] <br />
Zhiping Zhang and Michelle Jia and Hao-Ping and Lee and Bingsheng Yao and Sauvik Das and Ada Lerner and Dakuo Wang and Tianshi Li. (2023)<br />



#### Benchmarks 

- **Walking a Tightrope -- Evaluating Large Language Models in High-Risk Domains** \[[Paper](https://arxiv.org/pdf/2311.14966.pdf)\] <br />
Chia-Chien Hung and Wiem Ben Rim and Lindsay Frost and Lars Bruckner and Carolin Lawrence. (2023)<br />

- **SC-Safety: A Multi-round Open-ended Question Adversarial Safety Benchmark for Large Language Models in Chinese** \[[Paper](https://arxiv.org/pdf/2310.05818)\] <br />
Liang Xu and Kangkang Zhao and Lei Zhu and Hang Xue (2023)<br />

- **DICES Dataset: Diversity in Conversational AI Evaluation for Safety** \[[Paper](http://arxiv.org/pdf/2306.11247)\] <br />
Lora Aroyo and Alex S. Taylor and Mark Diaz and Christopher M. Homan and Alicia Parrish and Greg Serapio-Garcia and Vinodkumar Prabhakaran and Ding Wang (2023)<br />

- **Benchmarking and Defending Against Indirect Prompt Injection Attacks on
Large Language Models** \[[Paper](https://arxiv.org/pdf/2312.14197.pdf)\] <br />
Jingwei Yi and Yueqi Xie and Bin Zhu and Keegan Hines and Emre Kiciman and Guangzhong Sun and Xing Xie and Fangzhao Wu (2023)<br />

- **Control Risk for Potential Misuse of Artificial Intelligence in Science** \[[Paper](https://arxiv.org/pdf/2312.06632.pdf)\] <br />
Jiyan He and Weitao Feng and Yaosen Min and Jingwei Yi and Kunsheng Tang and Shuai Li and Jie Zhang and Kejiang Chen and Wenbo Zhou and Xing Xie and Weiming Zhang and Nenghai Yu and Shuxin Zheng (2023)<br />

- **SimpleSafetyTests: a Test Suite for Identifying Critical Safety Risks in Large Language Models** \[[Paper](https://arxiv.org/pdf/2311.08370.pdf)\] <br />
Bertie Vidgen and Hannah Rose Kirk and Rebecca Qian and Nino Scherrer and Anand Kannappan and Scott A. Hale and Paul Röttger (2023)<br />

- **Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game** \[[Paper](https://arxiv.org/pdf/2311.01011.pdf)\] <br />
Sam Toyer and Olivia Watkins and Ethan Adrian Mendes and Justin Svegliato and Luke Bailey and Tiffany Wang and Isaac Ong and Karim Elmaaroufi and Pieter Abbeel and Trevor Darrell and Alan Ritter and Stuart Russell (2023)<br />

- **SafetyBench: Evaluating the Safety of Large Language Models with Multiple Choice Questions** \[[Paper](https://arxiv.org/pdf/2309.07045)\] <br />
Zhexin Zhang and Leqi Lei and Lindong Wu and Rui Sun and Yongkang Huang and Chong Long and Xiao Liu and Xuanyu Lei and Jie Tang and Minlie Huang (2023)<br />

- **Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs** \[[Paper](https://arxiv.org/pdf/2308.13387.pdf)\] <br />
Yuxia Wang and Haonan Li and Xudong Han and Preslav Nakov and Timothy Baldwin (2023)<br />

- **CValues: Measuring the Values of Chinese Large Language Models from Safety to Responsibility** \[[Paper](https://arxiv.org/pdf/2307.09705)\] <br />
Guohai Xu and Jiayi Liu and Ming Yan and Haotian Xu and Jinghui Si and Zhuoran Zhou and Peng Yi and Xing Gao and Jitao Sang and Rong Zhang and Ji Zhang and Chao Peng and Fei Huang and Jingren Zhou (2023)<br />

- **XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models** \[[Paper](https://arxiv.org/pdf/2308.01263)\] <br />
Paul Röttger and Hannah Rose Kirk and Bertie Vidgen and Giuseppe Attanasio and Federico Bianchi and Dirk Hovy (2023)<br />

- **Latent Jailbreak: A Benchmark for Evaluating Text Safety and Output
Robustness of Large Language Models** \[[Paper](https://arxiv.org/pdf/2307.08487)\] <br />
Huachuan Qiu and Shuai Zhang and Anqi Li and Hongliang He and Zhenzhong Lan (2023)<br />

- **Tall Tales at Different Scales: Evaluating Scaling Trends For Deception in Language Models** \[[Paper](https://openreview.net/forum?id=YRXDl6I3j5)\] <br />
Anonymous (2024)<br />

- **How Far Are We from Believable AI Agents? A Framework for Evaluating the
Believability of Human Behavior Simulation** \[[Paper](https://arxiv.org/pdf/2312.17115.pdf)\] <br />
Yang Xiao and Yi Cheng and Jinlan Fu and Jiashuo Wang and Wenjie Li and Pengfei Liu (2023)<br />
