# Responsible AI Leaderboard：Balancing Capability and Safety

<p align="center" style="display: flex; flex-direction: row; justify-content: center; align-items: center">
🔱 <a href="https://test.leaderboard.librai.tech/LeaderBoard" target="_blank" style="margin-left: 10px">Leaderboard</a>
</p>

This leaderboard focuses on the balance between the safety and capability of AI models. 
- **Capability**: The capability of AI models. Currently, we consider the models as chatbots only.
- **Safety**: The safety of AI models, evaluated using several safety datasets from five aspects (see [Safety](#Safety)).
- **Utopia Score**: We introduce the Utopia Score (ranging between 0-1, larger is better) to measure the balance and trade-off between capability and safety of each model using the method introduced [here](#Balance-between-safety-and-capability). 
  
  In short, a models' Utopia Score is negatively correlated with its distance to the Utopia Point, where the utopia point is a hypothetical point in the objective space where each objective (capability and safety for now) attains its optimal value simultaneously. 

## Safety

We consider 5 types of safety datasets to evaluate the safety of each model, for each type of dataset, we calculate the safety score of the model. 

1. **Direct Risky Prompt**
    - **Data**: 5 datasets including: 
    [Do-Not-Answer](https://github.com/Libr-AI/do-not-answer), 
    [AdvBench](https://github.com/llm-attacks/llm-attacks/tree/main/data/advbench), etc.
2. **Adversarial Attack**
    - **Data**: 9 self-implemented adversarial attack covers: DoAnythingNow, Refusal Suppression, Persona Modulation, Multilingual Overload, Wrapped in Shell, Deep Inception, Ciphering, etc. (see details in this [paper](https://arxiv.org/pdf/2404.00629))
3. **Cybersecirity**
    - **Data**: [MITRE](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks/datasets/mitre)
4. **Instruction Hierarchy**
    - **Data**: [Tensor Trust](https://github.com/HumanCompatibleAI/tensor-trust-data),
5. **Over Refusal**
    - **Data**: 2 datasets including: 
    [I-PhysicalSafetySafe](https://github.com/vinid/safety-tuned-llamas/tree/main/data/evaluation), and one self-conducted dataset.

The overall safety score is the average of the safety scores of the five types of datasets, ranged from 0 to 100.

## Balance between safety and capability

Suppose we normalize the capability score and safety score to the range [0, 1], denoted as $x$ and $y$, respectively. There are many ways to calculate the combined score. Here are three common methods:

> Note that the figure below shows lines where all points on a line represent the same combined score for each method.
> - $x + y$: This method does not consider the balance between safety and performance, simply summing the two scores.
> - $\sqrt{(x^2 + y^2)}$: This method does not encourage a balance between safety and performance.
> - $\sqrt{(1 - x)^2 + (1 - y)^2}$: This method encourages a balance between the two metrics. We use this approach.
> <p align="center"> <img src="../assets/balance_score.png" style="width: 85%;" id="title-icon"></p>


## Score Calculation

- Capability score: The capability score is copied from the [Chatbot Arena leaderboard](https://chat.lmsys.org/). Range roughly in [800, 1500] (not fixed). The capability score is normalized to [0, 1] using the following formula: $\frac{\text{Elo} - \texttt{min}(\text{Elo})}{\texttt{max}(\text{Elo}) - \texttt{min}(\text{Elo})}$
- Safety score: Each safety aspect is normalized to [0,1]. The overall safety score is the marco-average of the five safety aspects. Range in [0,1]. 
- Utopia Score: The Utopia score is calculated according to the normalized Euclidean distance to the Utopia Point (a hypothetical model which achieves both optimal capability and safety simultaneously):

    $\text{Utopia Score} = 1 - \sqrt{\frac{(1-\text{Capability})^2 + (1-\text{Safety})^2}{2}}$


For more details about score aggregation and calculation, please read our [paper](https://aclanthology.org/2023.eacl-main.23.pdf) published at EACL-23.

## How to submit

Please contact us by email haonan.li@librai.tech.
