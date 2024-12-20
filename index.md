# The Steganographic Potentials of Language Models

This is a research project in the AI safety field. The goal is to prevent LLMs deception via hidden reasoning in text, we evaluate and induce steganography.

Our contribution and impact:

- Evidence in favor or against LLMs steganography capabilities.
- Evaluation tool(s) to detect steganography.
- If we have a trained model on stego, this can be used to do research on steganography in LLMs (interpretability).
- Code base to conduct experiments with RL on current or future LLMs.
- Preventing models from hiding their reasoning in the plain text.
- Increasing trust in models text output (mech interpretability, AI control).
- Answering the question if models can hide their reasoning.
- Potential for other research directions (LLMs watermarking, stego tool, unknown steganography methods).


Why: to prevent LLMs deception

- AGI deception is a high risk factor and it is a likely outcome of capabilities increase. The rogue AI scenario.
- LLMs are likely to be the core of AGI.  Possibility of LLMs deception (collusion) through text.
- So we want to increase trust in the text (interpretability, control, fine tuning etc.) 

What: Deception via hidden reasoning in text

- If LLMs are able to hide their reasoning in plain text, then it is more difficult to prevent  their deception. Steganography enables hiding reasoning in the plain text.
- Steganography (stego) is hiding a message in such a way that its presence is undetected. Difference from cryptography is the hidden transmission. For text, images, audio, etc.
- Perfectly secure* (undetectable) steganography is possible.

How: evaluation and inducing steganography

- Rationale: It is neglected. There is one base steganography evaluation tool and only few publications addressing safety of stego by LLMs.
- Our solution: 
  - Prompting to eval stego, to have a good tool at hand for big labs and for research.
  - Inducing stego via SFT or RL, to understand current LLMs potential and find dangerous training conditions that might lead to it. Proof-of-concept.
- Why Reinforcement Learning (RL)? Unclear where LLMs might converge to when under optimization pressure. Interest in the indirect emergence of stego.

![image](https://github.com/user-attachments/assets/82013860-11df-4ee5-a8a5-c09e39973ca6)

Sources / references:

- Panickssery et al. LLM Evaluators Recognize and Favor Their Own Generations. 2024.
- Pfau et al. Let’s Think Dot by Dot: Hidden Computation in Transformer Language Models. 2024.
- Roger and Greenblatt, ‘Preventing Language Models From Hiding Their Reasoning’. 2023
- Motwani et al., ‘Secret Collusion Among Generative AI Agents’. 2024. Larger models are more capable.

