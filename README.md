# Reasoning with (Large) Language Models

<div align="center">
    <img src="res/tutorial_dalle3.png" width="400">
</div>




- [BHI 2023 Tutorial (Oct 2023)](https://docs.google.com/presentation/d/1AVaEFgnW5X_PKt4VALecafz-9Ygr2b62jEBfhMN2rTU/edit?usp=sharing)


- [ACL 2023 Tutorial (July 2023)](https://docs.google.com/presentation/d/1oa8ZyMh327OM44AAHI_-tAyAnKuT2jBSDDRHi6QlOtQ/edit?resourcekey=0-rlTwNGBzaNQNRd0aRHrDpA#slide=id.g195972482bd_1_854)


### Notebooks


- [Language Models](https://github.com/madaan/llm-reasoning-tutorial/blob/main/Part_1_Language_Models.ipynb): An overview of language models, focusing on GPT-2's architecture and operation. Contains interactive demonstrations of how these models estimate word sequence probabilities, predict the next tokens, and generate coherent text.

- [Prompting Basics](https://github.com/madaan/llm-reasoning-tutorial/blob/main/Part_2_Prompting_Basics.ipynb): Demonstrates few-shot and zero-shot prompting. Utilizing the OpenAI API, allows playing with parameters like temperature, stop tokens, and maximum tokens, observing their impact on language model outputs.

- [Prompting Key Techniques](https://github.com/madaan/llm-reasoning-tutorial/blob/main/Part_3_Prompting_Key_Techniques.ipynb): Shows a typical workflow for prompting language models, including choosing between prompts (direct and chain-of-thought prompts) and parsing outputs for evaluation. It also includes a demonstration of the `memory` assisted prompting, where the prompt is updated with the generated text at each step.


### Other resources

- [My blog](https://madaan.github.io/prompting) on prompting large language models, used for a tutorial at the CMU LTI Seminar on Large Language Models (April 2023). In the blog, I draw an analogy between LLMs as stochastic compilers and prompting as a high-level language for specifying tasks.
