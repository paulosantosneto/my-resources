# Reasoning

- [x] [Chain-of-Thought Reasoning Without Prompting](https://arxiv.org/abs/2402.10200) (2024)

    The authors show that the models present responses with CoT in the generation paths even when not prompt-induced (such as few-shot-CoT). In addition, they show that the models are more confident in the final response when there is CoT in the response. **Positive:** significant increase in accuracy (exact match), especially when used together with self consistency (aggregation). **Weakness:** need to explore K paths during generation; bottleneck for extracting the answer span.
