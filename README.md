# LLMLingua

### Unlocking the Power of Prompt Compression with LLMLingua. Here are some key highlights about it:

Innovative Technique: LLMLingua is an innovative technique designed to compress prompts from coarse-grained to fine-grained levels, enhancing the efficiency of large language models (LLMs) like GPT-3.5 Turbo and Claude 1.3.

Budget Controller: The method incorporates a "budget controller" component, which dynamically distributes different compression ratios to elements of original prompts based on their significance. Instructions and questions, crucial for generating outcomes, receive higher budgets compared to repetitive demonstrations.

Use of Smaller Language Model: LLMLingua utilizes a smaller language model such as GPT-2 or LLaMA to manage budget allocation, considering the perplexity of each demonstration to gauge its relevance to the model's response.

Iterative Token-Level Prompt Compression (ITPC) Algorithm: LLMLingua employs the ITPC algorithm for fine-grained compression, segmenting prompts and retaining tokens with high perplexity to preserve key information and conditional dependencies.

Instruction Tuning-based Method: LLMLingua employs an instruction tuning-based method to synchronize distribution patterns between large and small language models, enhancing compression effectiveness.

Testing and Performance: LLMLingua outperforms prior methods across various benchmarks, achieving higher accuracy and remarkable compression ratios, such as 5x and 3x in reasoning and in-context learning benchmarks, and 9x and 3.3x in contextual understanding benchmarks.

Speed and Efficiency: Despite its complexity, LLMLingua offers significant speedup ranging from 1.7x to 5.7x with minimal computational overhead, making it practical for wider adoption.

Practical Implications: LLMLingua reduces computational costs and accommodates longer contexts in LLMs, offering practical solutions for various applications.

Open-Source Availability: Microsoft has made LLMLingua accessible through an open-source library, enabling developers to integrate it into their applications easily.

Potential for Adoption: LLMLingua's ease of use and effectiveness make it a promising solution for improving the efficiency and performance of large language models in diverse applications.


### Here are some resources that you can explore to get more information of it.
![TechTalks article on "Reduce the cost of GPT-4 with Prompt Compression"](https://bdtechtalks.com/2023/12/20/llmlingua-prompt-compression/)
![LLMLingua Microsoft's offcial GitHub Repo](https://github.com/microsoft/LLMLingua/tree/main)

