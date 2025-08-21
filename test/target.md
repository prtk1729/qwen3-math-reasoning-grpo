### Chunk 1: Introduction & Open Source Ecosystem
- [ ] 0:00 – 6:27

- [ ] 0:00–0:38: Speaker intro, session overview
- [ ] 0:38–1:48: Open source contributions, bug fixes, model releases
- [ ] 1:48–2:27: Free resources (Colab, Kaggle), importance of latest models
- [ ] 2:27–3:21: Model releases, quantization, bug fixes
- [ ] 3:21–4:41: History of Llama and open source movement
- [ ] 4:41–5:19: Slides access, Q&A format
- [ ] 5:19–6:27: Benchmarks: open vs closed source models

### Chunk 2: Model Training Phases & Terminology
- [ ] 6:27 – 16:50

- [ ] 6:27–7:40: Open source droughts, breakthroughs
- [ ] 7:40–8:29: Instruction fine-tuning & RL jumps
- [ ] 8:29–9:14: Reasoning capabilities & future steps
- [ ] 9:14–10:07: Training stages: cake analogy
- [ ] 10:07–11:17: Model training phases
- [ ] 11:17–12:49: Model naming conventions & terminology
- [ ] 12:49–13:59: Pre-training, mid-training, SFT, post-training, RLVR
- [ ] 13:59–15:42: Optimization pathways & training efficiency
- [ ] 15:42–16:50: Agents & RL loop


### Chunk 3: RL Fundamentals & Agents
- [ ] 16:50 – 24:18

- [ ] 16:50–17:48: RL loop in games vs LLMs
- [ ] 17:48–19:03: Reward functions: design, binary vs distance-based
- [ ] 19:03–21:04: RL in LLMs: maximizing good actions, OpenAI’s RHF
- [ ] 21:04–22:43: PPO, GPO, and model efficiency
- [ ] 22:43–24:18: Rewards, negative rewards, reference/generating policies
  
### Chunk 4: RL Algorithms & Reward Engineering
- [ ] 24:18 – 36:28

- [ ] 24:18–26:52: Single-turn vs multi-turn RL
- [ ] 26:52–28:53: Reward functions for math/code
- [ ] 28:53–30:39: Tool use, RL’s impact on model capabilities
- [ ] 30:39–33:55: RLVR stage, instruction following
- [ ] 33:55–35:59: Reward models & multi-turn RL
- [ ] 35:59–36:28: RLVR stage & instruction following
  
### Chunk 5: Model Updates, KL Divergence, and Capabilities
- [ ] 36:28 – 47:09

- [ ] 36:28–39:58: Reference models, sample efficiency, data generation
- [ ] 39:58–41:08: Protecting SFT, reward clipping, circuit learning
- [ ] 41:08–43:19: Parameter updates, efficient fine-tuning
- [ ] 43:19–45:02: KL divergence, capability elicitation strategies
- [ ] 45:02–47:09: Strategies for RL & capability elicitation
  
### Chunk 6: RL Math & PPO/GPO Details
- [ ] 47:09 – 1:09:03

- [ ] 47:09–49:19: Reward model simplification, random rewards
- [ ] 49:19–51:19: RL vs pre-training: maximizing actions
- [ ] 51:19–54:55: RL math: probability, rewards, maximization
- [ ] 54:55–58:00: Advantage functions, value models
- [ ] 58:00–1:09:03: PPO formula, overfitting prevention, GPO, rollouts, and training demonstration
  
### Chunk 7: Practical Notebook Walkthrough
- [ ] 1:09:03 – 2:06:02

- [ ] 1:09:03–1:32:06: Collab notebook walkthrough
- [ ] 1:32:06–1:46:03: System prompts, templates, training settings
- [ ] 1:46:03–2:06:02: Reward function engineering, data preparation, supervised fine-tuning, training process, evaluation, and metrics
  
### Chunk 8: RL Training Results & Analysis
- [ ] 2:06:02 – 2:23:44

- [ ] 2:06:02–2:14:02: Training output: reward columns, completion length, KR divergence
- [ ] 2:14:02–2:18:15: Rolling averages, model improvement over time
- [ ] 2:18:15–2:22:31: Output examples, reasoning traces
- [ ] 2:22:31–2:23:44: Base vs instruct models, efficiency considerations, fine-tuning, loss curves, priming stage
  
### Chunk 9: Scaling, Model Size, and Infrastructure
- [ ] 2:23:44 – 2:32:31

- [ ] 2:23:44–2:27:32: Model size: small vs big, tricks for scaling
- [ ] 2:27:32–2:29:33: Free collab/Kaggle for large models
- [ ] 2:29:33–2:32:31: VLM rollouts, memory sharing, infrastructure, asynchronous training, future support
  
### Chunk 10: Quantization, Kernels, torch.compile, and Closing
- [ ] 2:32:31 – 2:42:16

- [ ] 2:32:31–2:36:46: Quantization strategies, dynamic quantization
- [ ] 2:36:46–2:39:56: Layer selection, activation/weight quantization error, super weights paper
- [ ] 2:39:56–2:41:56: Blackwell chips, FP4, numerical precision
- [ ] 2:41:56–2:42:16: torch.compile for training efficiency, session wrap-up, community links, Q&A