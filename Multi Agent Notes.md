# Effecient Agents Tutorial

[Tutorial link](https://xuanwang91.github.io/2026-07-02-acl26-tutorial)

## Efficiency: 
local deployment of small models for data privacy, low latency, nework stability and edge deployment (tobotics, IoT, wearables)

## Mutimodal:
Required input in every domain (healthcare, robotics, etc.)

## Multi-Agent:
coordingate between agents and human-agent collaborations

## Multi-agent Language Model Systems:

### Base Language Model Agent
- small vs large LM agent
- MM LM Agent 
- Tool Augmented Reasoning 

### Multi-agent Interactions
- Effective and Efficient Multi-agent interaction
- Scaling from task-level to systems lvl coordination

# Notes:
- The presenter draws attention to agents of smaller size being under performant to their large parameter counter part. However, they are still promising for many task and even greater with tool-calling.
- [Proposed Agentic Framework for small parameter models - Effgen](https://effgen.org)
- Presenter speculates that self-evolving models will continue to grow
- -  [DEBATE, TRAIN, EVOLVE: Self-Evolution of Language Model Reasoning](https://aclanthology.org/2025.emnlp-main.1666.pdf)

# Multimodal Agents (Vision Language Models)
- [Scaling Agentic Reinforcement Learning for Tool-Integrated Reasoning in VLMs](https://openaccess.thecvf.com/content/CVPR2026/papers/Lu_Scaling_Agentic_Reinforcement_Learning_for_Tool-Integrated_Reasoning_in_VLMs_CVPR_2026_paper.pdf)

# Future Directions
- Single-Agent LLM/VLM
- - Agentic Framework/Finetuning/Long-Context
- - Multimodal SLM Agents for Real-World Applications
- - Tool-Augmented Reasoning in LLM/VLM

# Collaborative INtelligence (Google Deep Mind Presenter)
- Safety steering: every hosted giant ships with a guard
  * user_input -> Input Guard (small classifier LM) -> Frozen Frontier Model -> Output Guard (screens response) -> Release

- Many models, never let prompts reach the model untouched and instead perform prompt enrichement.

- [AceSearcher: Bootstrapping Reasoning and Search for LLMs via Reinforced Self-Play](https://proceedings.neurips.cc/paper_files/paper/2025/file/30b00503cffe6acf25876fb1690a7357-Paper-Conference.pdf)
    * [code](https://github.com/ritaranx/AceSearcher/)

# LLM Agents
* [CAR-bench: Evaluating the Consistency and Limit-Awareness of LLM Agents under Real-World Uncertainty](https://arxiv.org/abs/2601.22027)
    * [Git- CAR-bench](https://github.com/CAR-bench/car-bench)


