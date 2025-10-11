# Awesome Context Engineering Related Papers

## 📑 Research Paper
| Title | Venue | Link | Notes | 
|:---:|:---:|:---:|:---:|
|PENCIL: Long Thoughts with Short Memory|ICML 2025|[paper](https://openreview.net/forum?id=6wglsDXIei)|Addresses the excessive memory usage of CoT by incorporating a reduction mechanism to recursively erase unnecessary intermediate reasoning steps, thereby enabling deeper problem-solving within a limited context.|
|Scaling LLM Multi-turn RL with End-to-end Summarization-based Context Management|Arxiv 2510|[paper](https://arxiv.org/abs/2510.06727)|A reinforcement learning framework SUPO, which enables LLM agents to tackle long-horizon tasks by jointly learning a policy for both tool use and periodic context summarization, overcoming the limitations of a fixed context window.|
|ReSum: Unlocking Long-Horizon Search Intelligence via Context Summarization|Arxiv 2509|[paper](https://arxiv.org/abs/2509.13313)|ReSum, a paradigm that overcomes the context window limitations of LLM-based web agents by periodically summarizing the interaction history, enabling them to solve complex, long-horizon search tasks that would otherwise fail.|
|QwenLong-CPRS: Towards -LLMs with Dynamic Context Optimization|Arxiv 2505|[paper](https://arxiv.org/abs/2505.18092)|QWENLONG-CPRS, a dynamic context optimization framework that intelligently compresses long documents into concise, query-relevant segments to address the prohibitive computational cost and "lost-in-the-middle" performance degradation in large language models.|
|CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension|NeurIPS 2025|[paper](https://arxiv.org/abs/2510.05520)|CAM, a framework inspired by Piaget's theory to enhance large language model comprehension of long documents by organizing information into a memory structure that is hierarchical, flexible, and dynamically adaptive.|
|Learn to Memorize: Optimizing LLM-based Agents with Adaptive Memory Framework|Arxiv 2508|[paper](https://arxiv.org/abs/2508.16629)|earn to Memorize: Optimizing LLM-based Agents with Adaptive Memory Framework|
|MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent|Arxiv 2507|[paper](https://arxiv.org/abs/2507.02259)| MemAgent, a method that uses reinforcement learning to train a large language model to process infinitely long documents with linear time complexity by reading them in chunks and continuously updating a fixed-size memory with the most relevant information.|
|MEM1: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents|Arxiv 2506|[paper](https://www.arxiv.org/abs/2506.15841)|MEM1, a reinforcement learning framework that solves the problem of unbounded memory growth in long-horizon AI agents by training them to consolidate reasoning and memory into a compact, constant-size internal state at each step.|
|A-MEM: Agentic Memory for LLM Agents|Arxiv 2502|[paper](https://arxiv.org/abs/2502.12110)|A-MEM, an agentic memory system that solves the rigidity of predefined memory structures in LLM agents by enabling memories to be dynamically and autonomously organized, linked, and evolved into an interconnected knowledge network.|
|From Single to Multi-Granularity: Toward Long-Term Memory Association and Selection of Conversational Agents|Arxiv 2505|[paper](https://arxiv.org/abs/2505.19549)|This paper proposes MemGAS, a framework to improve long-term memory in conversational agents by creating and associating memories at multiple granularities (e.g., summaries, keywords, turns) and adaptively selecting the most relevant level of detail for retrieval based on the user's query.|

## 🧐 Survey Papers
|Title|Venue|Link|Repo|
|:---:|:---:|:---:|:---:|
|A Survey of Context Engineering for Large Language Models|Arxiv 2507|[paper](https://arxiv.org/abs/2507.13334)|[repo](https://github.com/Meirtz/Awesome-Context-Engineering)|

## 📊 Blogs
| Title | Date | Company | Homepage |
|:------:|:---:|:---:|:---:|
|Effective context engineering for AI agents|Sep 29, 2025|Anthropic|[blog](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)|
|Context Rot: How Increasing Input Tokens Impacts LLM Performance|July 14, 2025|Chroma|[blog](https://research.trychroma.com/context-rot)|
|Context Engineering for AI Agents: Lessons from Building Manus|July 18, 2025|Manus|[blog](https://manus.im/blog/Context-Engineering-for-AI-Agents-Lessons-from-Building-Manus)|
