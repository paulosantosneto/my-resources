# Reasoning

### 2022

- [ ] [Locating and Editing Factual Associations in GPT](https://arxiv.org/abs/2202.05262)

- [ ] [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903) (2022)

- [ ] [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171) (2022)

### 2023

- [ ] [Towards a Mechanistic Interpretation of Multi-Step Reasoning Capabilities of Language Models](https://arxiv.org/abs/2310.14491)

- [ ] [Contrastive Decoding Improves Reasoning in Large Language Models](https://arxiv.org/abs/2309.09117)

- [ ] Dissecting Chain-of-Thought: Compositionality through In-Context Filtering and Learning

- [ ] Accelerating Large Language Model Decoding with Speculative Sampling

- [ ] Towards Revealing the Mystery behind Chain of Thought: A Theoretical Perspective

- [ ] [Linearity of Relation Decoding in Transformer Language Models](https://arxiv.org/abs/2308.09124)

### 2024


- [ ] [Distributional reasoning in LLMs: Parallel reasoning process in multi-hop reasoning](https://arxiv.org/abs/2406.13858)

- [ ] [Understanding and Patching Compositional Reasoning in LLMs](https://arxiv.org/abs/2402.14328)

- [ ] [Do Large Language Models Latently Perform Multi-Hop Reasoning?]()

- [ ] []()
# Interpretability

- [ ] [LayerSkip: Enabling Early Exit Inference and Self-Speculative Decoding](https://arxiv.org/pdf/2404.16710)

# Decoding

### 2020

- [ ] [Mirostat: A Neural Text Decoding Algorithm that Directly Controls Perplexity](https://arxiv.org/abs/2007.14966)

### 2022

- [ ] [Constrative Search Is What You Need for Neural Text Generation](https://arxiv.org/abs/2210.14140)

- [ ] [A Thorough Examination of Decoding Methods in the Era of LLMs](https://arxiv.org/abs/2402.06925)

- [ ] [Beam Search Strategies for Neural Machine Translation](https://arxiv.org/abs/1702.01806)

- [ ] [Diverse Beam Search: Decoding Diverse Solutions from Neural Sequence Models](https://arxiv.org/abs/1610.02424)

- [ ] [A Call for Clarity in Beam Search: How It Works and When It Stops](https://arxiv.org/abs/2204.05424) (2022)

- [ ] [A Contrastive Framework for Neural Text Generation](https://arxiv.org/abs/2202.06417) (2022)

- [ ] [Locally Typical Sampling](https://arxiv.org/abs/2202.00666) (2022)
 
- [ ] [Truncation Sampling as Language Model Desmoothing](https://arxiv.org/abs/2210.15191) (2022)

- [ ] [Fast Inference from Transformers via Speculative Decoding](https://arxiv.org/abs/2211.17192) (2022)

### 2023

- [ ] [A Frustratingly Simple Decoding Method for Neural Text Generation](https://arxiv.org/abs/2305.12675) (2023)

- [ ] [Online Speculative Decoding](https://arxiv.org/abs/2310.07177) (2023)

### 2024

- [ ] [Exploring and Improving Drafts in Blockwise Parallel Decoding](https://arxiv.org/abs/2007.14966) (2024)

- [ ] [Decoding Speculative Decoding
](https://arxiv.org/abs/2402.01528) (2024)

- [ ] [Break the Sequential Dependency of LLM Inference Using Lookahead Decoding](https://arxiv.org/abs/2402.02057)

- [x] [Chain-of-Thought Reasoning Without Prompting](https://arxiv.org/abs/2402.10200)

    The authors show that the models present responses with CoT in the generation paths even when not prompt-induced (such as few-shot-CoT). In addition, they show that the models are more confident in the final response when there is CoT in the response. **Positive:** significant increase in accuracy (exact match), especially when used together with self consistency (aggregation). **Limitations:** need to explore K paths during generation; bottleneck for extracting the answer span. **Models:** PaLM-2 and Mistral. **Datasets:** Year parity, GSM8K and Coin Flip.

# Others

### 2020

- [ ] [Transformer Feed-Forward Layers Are Key-Value Memories](https://arxiv.org/abs/2012.14913)

- [ ] []()

### 2021

- [x] [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) 

### 2020

- [ ] [Transformer Feed-Forward Layers Build Predictions by Promoting Concepts in the Vocabulary Space](https://arxiv.org/abs/2203.14680)

### 2023

- [ ] [Dissecting Recall of Factual Associations in Auto-Regressive Language Models](https://arxiv.org/abs/2304.14767)

- [ ] [LM-Infinite: Zero-Shot Extreme Length Generalization
for Large Language Models](https://arxiv.org/abs/2308.16137)
    
    LM-Infinite applytwo techniques plug-in-play to solve three problems when thought about long input context. Authors show the viability that models pretrained on 4K tokens generalize to 200M tokens without decrease in performance. **Problems:** explosion of attention logits of sequences lengths that extrapolate pretrained bound limit, explosion of entropy for long sequences, and the intrinsic characteristic of isolation of starting new tokens.
### 2024

- [ ] [Why Warmup the Learning Rate?
Underlying Mechanisms and Improvements](https://arxiv.org/abs/2406.09405)

- [ ] [RHO-1: Not All Tokens Are What You Need](https://arxiv.org/abs/2404.07965) 
