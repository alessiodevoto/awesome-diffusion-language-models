# Awesome Large Language Diffusion Models 🚀🧠✨

A curated list of recent and important papers, tools, and resources on **Diffusion Large Language Models (DLMs)**.

> Contributions are welcome! Please submit a PR or open an issue. Your help makes this list even more awesome! 💖

---

## 💻 Open-Weight Models

- **[Llada](https://huggingface.co/GSAI-ML/LLaDA-8B-Instruct)** [![Hugging Face Model](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-blue)](https://huggingface.co/GSAI-ML/LLaDA-8B-Instruct)
- **[Dream](https://huggingface.co/Dream-org)** [![Hugging Face Model](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-blue)](https://huggingface.co/Dream-org)
- **[MMaDA](https://huggingface.co/Gen-Verse/MMaDA-8B-Base)** [![Hugging Face Model](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-blue)](https://huggingface.co/Gen-Verse/MMaDA-8B-Base)

---

## Closed-Weight Models
- [Google Gemini diffusion](https://deepmind.google/models/gemini-diffusion/)
- [Inception Mercury](https://chat.inceptionlabs.ai/)

---

## 🔥 Papers 

- **[LongLLaDA: Unlocking Long Context Capabilities in Diffusion LLMs](https://arxiv.org/abs/2506.14429)**
  *TLDR:* First systematic study of long-context capabilities in diffusion LLMs. Proposes LongLLaDA, a training-free extrapolation method, and finds they outperform AR models on some long-context tasks. 

- **[MMaDA: Multimodal Large Diffusion Language Models](https://arxiv.org/abs/2505.15809)**
  *TLDR:* Introduces MMaDA, a unified multimodal diffusion model excelling in textual reasoning, visual understanding, and text-to-image generation. Outperforms several SOTA models across domains. 

- **[Large Language Diffusion Models](https://arxiv.org/abs/2502.09992)**
  *TLDR:* LLaDA is a Transformer-based diffusion LLM trained from scratch. Matches or beats strong AR baselines like LLaMA3 8B, especially in instruction following and reversal tasks. 


- **[Simple and Effective Masked Diffusion Language Models](https://arxiv.org/abs/2406.07524)**
  *TLDR:* Shows masked diffusion models can nearly match AR performance with simple training tricks and a Rao-Blackwellized objective. Supports semi-autoregressive generation. 

- **[Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models](https://arxiv.org/abs/2503.09573)**
  *TLDR:* Proposes block diffusion models that combine the strengths of AR and diffusion methods. Enables flexible-length generation and improved efficiency using KV caching. 

- **[Scaling Diffusion Language Models via Adaptation from Autoregressive Models](https://arxiv.org/abs/2410.17891)**
  *TLDR:* Converts AR models like GPT-2 and LLaMA into diffusion models (DiffuGPT, DiffuLLaMA) using continual pretraining. Matches AR models on several benchmarks with less data. 

- **[Unifying Autoregressive and Diffusion-Based Sequence Generation](https://arxiv.org/abs/2504.06416)**
  *TLDR:* Proposes hyperschedules and hybrid noise processes to blend AR and diffusion models. Achieves strong perplexity and diverse generation while enabling error correction during decoding. 

- **[Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502)**
  *TLDR:* Introduces DDIMs, which speed up diffusion sampling by 10–50× using non-Markovian processes while maintaining high sample quality. 

---

## 📚 Blogs 

- **[Dream](https://github.com/HKUNLP/Dream)** [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HKUNLP/Dream) 
*TLDR:* A 7B diffusion LLM that rivals leading AR models in performance, demonstrating the feasibility of scalable diffusion-based LLMs. 

---

## 🤝 Contributing to this Awesome List

We wholeheartedly welcome contributions from the community! ✨

- 📄 **Add new papers:** Discovered a groundbreaking paper? Share it with us!
- 🧪 **Share codebases or demos:** Have a cool implementation or demo? Let's showcase it!
- 🛠 **Submit tutorials, blog posts, or benchmarks:** Help others learn and evaluate DLMs.

Feel free to open a pull request or issue! 🙏

---

Maintained by [Alessio Devoto](https://alessiodevoto.github.io/)