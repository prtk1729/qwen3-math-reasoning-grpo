# qwen3-math-reasoning-grpo
Fine-tuned an open-source LLM using GRPO (a reinforcement learning algorithm) with reward models tailored for math reasoning and structured answer generation.

# Qwen3-4B GRPO Fine-Tuning for Math Reasoning

This project demonstrates **fine-tuning the Qwen3-4B-Base language model** to perform **structured mathematical reasoning** using **GRPO (Guided Reward Policy Optimization)**. We apply reinforcement learning on top of instruction tuning to reward correct and well-formatted reasoning chains.

---

## Goal

Convert `Qwen3-4B-Base` into a reasoning-augmented model via GRPO using the [OpenR1 DAPO-Math-17k dataset](https://huggingface.co/datasets/open-r1/DAPO-Math-17k-Processed).

---

## Why GRPO?

GRPO is a simplified RL framework:
- No value model required
- Uses only a reward model and a policy model
- Can handle multi-reward signal feedback like format, numerical closeness, and answer accuracy
- Much more memory-efficient than PPO or DPO

---

## Dataset

OpenR1’s `DAPO-Math-17k-Processed` contains:
- Reasoning-rich math prompts
- Ground-truth final answers
- Prompt format ideal for multi-step reward design

---

## Reward Functions

| Reward Name            | Description |
|------------------------|-------------|
| `match_format_exactly` | Reasoning and solution match expected format |
| `match_format_approx`  | Partial formatting, missing tags, etc.       |
| `check_answer`         | Final numerical answer correct               |
| `check_numbers`        | Output is numerically close to target        |

These rewards are combined with weighted scaling into a single scalar reward.

---

## Setup

Install requirements:
```bash
pip install -r requirements.txt
```