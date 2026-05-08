## WizardLM: Empowering Large Pre-Trained Language Models to Follow Complex Instructions

<p style="font-size:50px;" align="center">
🏠 <a href="https://wizardlm.github.io/" target="_blank">Home Page</a> </p>
<p align="center">
    
<p align="center">
🤗 <a href="https://huggingface.co/WizardLMTeam" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/WizardLM_AI" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.12244" target="_blank">[WizardLM] @ICLR2024</a>  • 📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>    • 📃 <a href="https://arxiv.org/abs/2308.09583" target="_blank">[WizardMath]</a> <br>
</p>
<p align="center">
    👋 Join our <a href="https://discord.gg/VZjjHtWrKs" target="_blank">Discord</a>
</p>

<p align="center" width="100%">
<a ><img src="imgs/WizardLM.png" alt="WizardLM" style="width: 20%; min-width: 300px; display: block; margin: auto;"></a>
</p>

[![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/LICENSE)
[![Data License](https://img.shields.io/badge/Data%20License-CC%20By%20NC%204.0-red.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/DATA_LICENSE)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/release/python-390/)

**Unofficial Video Introductions**

Thanks to the enthusiastic friends, their video introductions are more lively and interesting.
1. [NEW WizardLM 70b 🔥 Giant Model...Insane Performance](https://www.youtube.com/watch?v=WdpiIXrO4_o)
2. [GET WizardLM NOW! 7B LLM KING That Can Beat ChatGPT! I'm IMPRESSED!](https://www.youtube.com/watch?v=SaJ8wyKMBds)
3. [WizardLM: Enhancing Large Language Models to Follow Complex Instructions](https://www.youtube.com/watch?v=I6sER-qivYk)
4. [WizardCoder AI Is The NEW ChatGPT's Coding TWIN!](https://www.youtube.com/watch?v=XjsyHrmd3Xo)

## News

- 🔥🔥🔥[2024/01/04] We released **WizardCoder-33B-V1.1**  trained from deepseek-coder-33b-base, the **SOTA OSS Code LLM** on [EvalPlus Leaderboard](https://evalplus.github.io/leaderboard.html), achieves **79.9 pass@1** on HumanEval, **73.2 pass@1** on HumanEval-Plus, **78.9 pass@1** on MBPP, and **66.9 pass@1** on MBPP-Plus. **WizardCoder-33B-V1.1** outperforms **ChatGPT 3.5**, **Gemini Pro**, and **DeepSeek-Coder-33B-instruct** on HumanEval and HumanEval-Plus pass@1. **WizardCoder-33B-V1.1** is comparable with **ChatGPT 3.5**, and surpasses **Gemini Pro** on MBPP and MBPP-Plus pass@1.
- [2023/08/26] We released **WizardCoder-Python-34B-V1.0** , which achieves the **73.2 pass@1** and surpasses **GPT4 (2023/03/15)**, **ChatGPT-3.5**, and **Claude2** on the [HumanEval Benchmarks](https://github.com/openai/human-eval). For more details, please refer to [WizardCoder](https://github.com/nlpxucan/WizardLM/tree/main/WizardCoder).
- [2023/06/16] We released **WizardCoder-15B-V1.0** , which surpasses **Claude-Plus (+6.8)**, **Bard (+15.3)** and **InstructCodeT5+ (+22.3)** on the [HumanEval Benchmarks](https://github.com/openai/human-eval). For more details, please refer to [WizardCoder](https://github.com/nlpxucan/WizardLM/tree/main/WizardCoder).


|  Model  |  Checkpoint  | Paper    | HumanEval  |   HumanEval+ | MBPP | MBPP+ |
| ----- |------| ---- |------|-------| ----- |  ----- |
|  GPT-4-Turbo (Nov 2023)  | - | - | 85.4  | 81.7 | 83.0 | 70.7 |
|  GPT-4 (May 2023)  | - | - | 88.4  | 76.8 | - | - |
|  GPT-3.5-Turbo (Nov 2023)  | - | - | 72.6  | 65.9 | 81.7 | 69.4 |
|  Gemini Pro  | - | - | 63.4  | 55.5 | 72.9 | 57.9 |
|  DeepSeek-Coder-33B-instruct | - | - |  78.7 | 72.6 | 78.7 | 66.7 |
|  WizardCoder-33B-V1.1  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-33B-V1.1" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>  |  79.9  |  73.2  |  78.9  |  66.9  |
|  WizardCoder-Python-34B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-Python-34B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>  |  73.2  |  64.6  |  73.2  |  59.9  |
|  WizardCoder-15B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-15B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>  |  59.8  |  52.4  | --  | --  |
|  WizardCoder-Python-13B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-Python-13B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>  |  64.0  |  55.5  | --  | --  |
|  WizardCoder-Python-7B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-Python-7B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>  |  55.5  |  45.1  | --  | --  |
|  WizardCoder-3B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-3B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>  |  34.8  |  26.2  | --  | --  |
|  WizardCoder-1B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-1B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>  |  23.8  |  18.9  | --  | --  |

## Introduction

The WizardLM project aims to empower large pre-trained language models to follow complex instructions. Our key insight is that by using AI-evolved instructions (Evol-Instruct), we can generate more complex and diverse instruction data at scale, leading to better instruction-following LLMs.

## Overview

We introduce Evol-Instruct, a novel approach that evolves existing instruction data into more complex instructions. Starting from a seed set of instructions, we iteratively make them more complex via in-depth evolving (adding complexity/depth) or in-breadth evolving (adding diversity). The evolved instructions are then used to fine-tune large language models.

## Models

### WizardLM Series

- **WizardLM-13B-V1.2**: Achieves 89.17% on AlpacaEval, surpassing ChatGPT's 86.09%.
- **WizardLM-70B-V1.0**: The 70B version of our model.

### WizardCoder Series

Empowering Code LLMs with Evol-Instruct. See [WizardCoder](WizardCoder/) for details.

### WizardMath Series

Empowering Mathematical Reasoning for LLMs. See [WizardMath](WizardMath/) for details.

## How to Use

Please refer to the respective subdirectories for detailed instructions:
- [WizardLM](WizardLM/) - General instruction-following
- [WizardCoder](WizardCoder/) - Code generation
- [WizardMath](WizardMath/) - Mathematical reasoning

## Citation

```bibtex
@inproceedings{xu2024wizardlm,
  title={WizardLM: Empowering Large Language Models to Follow Complex Instructions},
  author={Xu, Can and Sun, Qingfeng and Zheng, Kai and Geng, Xiubo and Zhao, Pu and Feng, Jiazhan and Tao, Chongyang and Jiang, Daxin},
  booktitle={The Twelfth International Conference on Learning Representations},
  year={2024}
}

@inproceedings{luo2024wizardcoder,
  title={WizardCoder: Empowering Code Large Language Models with Evol-Instruct},
  author={Luo, Ziyang and Xu, Can and Zhao, Pu and Sun, Qingfeng and Geng, Xiubo and Hu, Wenxiang and Tao, Chongyang and Ma, Jing and Lin, Qingwei and Jiang, Daxin},
  booktitle={The Twelfth International Conference on Learning Representations},
  year={2024}
}

@article{luo2024wizardmath,
  title={WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct},
  author={Luo, Haipeng and Sun, Qingfeng and Xu, Can and Zhao, Pu and Lou, Jianguang and Tao, Chongyang and Geng, Xiubo and Lin, Qingwei and Chen, Shifeng and Zhang, Dongmei},
  journal={arXiv preprint arXiv:2308.09583},
  year={2023}
}
```

---

**Related project:** [stanford_alpaca](https://github.com/tatsu-lab/stanford_alpaca)
