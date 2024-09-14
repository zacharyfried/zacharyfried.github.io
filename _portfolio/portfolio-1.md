---
title: "Explicit and Implicit Large Language Model Personas Generate Opinions but Fail to Replicate Deeper Perceptions and Biases"
excerpt: "In this paper, we explore how large language models (LLMs) can be prompted with human-like personas to handle subjective tasks, like detecting bias or generating opinions. We find that while LLMs can mimic human responses to some extent, they often miss the deeper biases and lived experiences that shape real human behavior. This highlights some of the limitations of using LLMs in complex social science applications.<br/><img src='/images/persona.png'>"
collection: portfolio
---

### Links: 
- [Link to arxiv.org.](https://arxiv.org/abs/2406.14462)
- [Link to PDF.](https://arxiv.org/pdf/2406.14462)

### Abstract:
Large language models (LLMs) are increasingly being used in human-centered social scientific tasks, such as data annotation, synthetic data creation, and engaging in dialog. However, these tasks are highly subjective and dependent on human factors, such as one's environment, attitudes, beliefs, and lived experiences. Thus, employing LLMs (which do not have such human factors) in these tasks may result in a lack of variation in data, failing to reflect the diversity of human experiences. In this paper, we examine the role of prompting LLMs with human-like personas and asking the models to answer as if they were a specific human. This is done explicitly, with exact demographics, political beliefs, and lived experiences, or implicitly via names prevalent in specific populations. The LLM personas are then evaluated via (1) subjective annotation task (e.g., detecting toxicity) and (2) a belief generation task, where both tasks are known to vary across human factors. We examine the impact of explicit vs. implicit personas and investigate which human factors LLMs recognize and respond to. Results show that LLM personas show mixed results when reproducing known human biases, but generate generally fail to demonstrate implicit biases. We conclude that LLMs lack the intrinsic cognitive mechanisms of human thought, while capturing the statistical patterns of how people speak, which may restrict their effectiveness in complex social science applications.

### Code:

- [GitHub Repository](https://github.com/TTRUCurtis/rapids-helper-scripts)

### Publications:

**Citation**:  
S. Giorgi, T. Liu, A. Aich, K. Isman, G. Sherman, Z. Fried, J. Sedoc, L.H. Ungar, B. Curtis. (2024). *Explicit and Implicit Large Language Model Personas Generate Opinions but Fail to Replicate Deeper Perceptions and Biases*. arXiv preprint arXiv:2406.14462.
