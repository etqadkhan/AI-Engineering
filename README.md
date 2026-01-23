# AI Engineering by Chip Huyen - Study Notes

Study materials summarizing key concepts from "AI Engineering" by Chip Huyen.

## Contents

### Chapter 1: Introduction to Building AI Applications with Foundation Models

**[Chapter 1 Part 1](./Chapter1Part1.pptx)**
- Language models and next-token prediction
- Foundation Models and transfer learning
- The self-supervised learning breakthrough
- Data labeling bottleneck and solutions

**[Chapter 1 Part 2](./Chapter1Part2.pptx)**
- AI's strengths and use cases
- Language model comparisons
- The AI Stack
- AI Engineering vs. ML Engineering

### Chapter 2: Understanding Foundation Models

**[Chapter 2 Part 1](./Chapter2Part1.pptx)**
- Attention Mechanism and math
- Transformer architecture
- Multilingual challenges
- Model efficiency and sparsity

**[Chapter 2 Part 2](./Chapter2Part2.pptx)**
- Scaling laws and Chinchilla Paper
- Supervised Fine-Tuning (SFT)
- Reward Models
- RLHF (Reinforcement Learning from Human Feedback)

**[Chapter 2 Part 3](./Chapter2Part3.pptx)**
- Sampling Parameters (Temperature, Top-K, Top-P)
- Test-Time Compute
- Hallucination and its mitigation
  
### Chapter 3: Evaluation Methodology
  
**[Chapter 3 Part 1](./Chapter3Part1.pptx)**
- Rise of Evaluation in AI
- Entropy
- Cross-Entropy
- KL Divergence
- Perplexity (PPL)
- Math example
  
**[Chapter 3 Part 2](./Chapter3Part2.pptx)**
- Exact Evaluation techniques
- Challenges of Reference Data
- An Intro to Embeddings
- Multimodal Embeddings
  
**[Chapter 3 Part 3](./Chapter3Part3.pptx)**
- Evaluation Toolkit
- AI as a Judge: Why and How
- Pointwise and Pairwise Evaluation
- Taxonomy and Limitations of AI Judges
- Comparative Evaluation and its Challenges
  
### Chapter 4: Evaluate AI Systems
  
**[Chapter 4 Part 1](./Chapter4Part1.pptx)**
- AI Evaluation 
- The Challenge of Factual Consistency 
- The SAFE Method 
- Benchmarking Truthfulness with TruthfuIQA 
- Evaluating Instruction-Following Capability 
- Verifiable Instructions (IFEval) 
- Optimising for Cost and Latency
   
**[Chapter 4 Part 2](./Chapter4Part2.pptx)**
- Systematic Workflow for Model Selection
- Nuances of 'Open Source' Models
- Public Benchmark to Production Monitoring
- Challenges of Navigating Public Benchmarks
   
**[Chapter 4 Part 3](./Chapter4Part3.pptx)**
- Data contamination with public benchmarks
- Custom, Weighted Leaderboards
- Designing Your Own Evaluation Pipeline 
- Principles for a World-Class Evaluation Pipeline
     
### Chapter 5: Prompt Engineering
  
**[Chapter 5 Part 1](./Chapter5Part1.pptx)**
- In-Context Learning (ICL)
- System vs. User Prompts
- Exponential Growth of the Context Window
- Needle in the Haystack (NIAH)
- Chain-of-Thought (CoT)
- Organizing and Versioning Prompts
- Prompt Engineering Best Practices

**[Chapter 5 Part 2](./Chapter5Part2.pptx)**
- Defensive Prompt Engineering
- Reverse Prompt Engineering
- Training Data Extraction
- Risk 3: Copyright Regurgitation
- Jailbreaking
- Prompt Injection
- Defence Strategies against Prompt Hacking
      
### Chapter 6: RAG and Agents
  
**[Chapter 6 Part 1](./Chapter6Part1.pptx)**
- Introduction to RAG
- RAG Architecture and Components
- Sparse Retrieval
- Dense Retrieval
- Retrieval Optimisation Techniques
- Evaluating a RAG system
- Multimodal RAG

**[Chapter 6 Part 2](./Chapter6Part2.pptx)**
- Intro to Agent
- Tools and its core Functions
- Agent Memory
- Memory Bottleneck

**[Chapter 6 Part 3](./Chapter6Part3.pptx)**
- Agent’s Reasoning Engine
- Using Foundation Models as Planners
- Example of an Agentic Flow
- Dynamic Function Calling
- Complex Control Flows
- Reflection in an Agent
- Tool Selection
- Evaluating an Agent
- Agent Failure Modes
      
### Chapter 7: Finetuning
  
**[Chapter 7 Part 1](./Chapter7Part1.pptx)**
- Finetuning vs Transfer Learning
- When to Finetune
- Finetune vs RAG
- Memory Bottleneck with Training
- Precision Formats and Trade-offs
- Memory Math for Finetuning

**[Chapter 7 Part 2](./Chapter7Part2.pptx)**
- The Problems of Full Finetuning
- Parameter-Efficient Finetuning (PEFT)
- Detailed Look at Low-order Rank Adaptation
- Introduction to Quantized LoRA

**[Chapter 7 Part 3](./Chapter7Part3.pptx)**
- Multi-Task Finetuning
- Discussion on Model Merging
- Model Merging Techniques
- Spherical Linear Interpolation (SLERP)
- Pruning Redundant Parameters
- Key Finetuning Hyperparameters
- A look into prompt_weight_loss
      
### Chapter 8: Dataset Engineering
  
**[Chapter 8 Part 1](./Chapter8Part1.pptx)**
- Pillars of Data Curation
- Data Quality Characteristics
- Data Coverage
- Data Quantity
- Data Synthesis

**[Chapter 8 Part 2](./Chapter8Part2.pptx)**
- Traditional Data Synthesis Techniques
- AI-Powered Synthesis
- Model Distillation
- Limitation of AI Generated Data
- Deduplication, Filter and Format
      
### Chapter 9: Inference Optimization
  
**[Chapter 9 Part 1](./Chapter9Part1.pptx)**
- Compute vs Bandwidth
- Capacity vs Bandwidth
- Prefill and Decode
- TTFT, TPOT
- Throughput vs Goodput
- Activity vs Efficiency
- MBU
- FLOPs vs FLOP/s
  
---

Based on "AI Engineering" by Chip Huyen. For detailed explanations, refer to the original book here: https://amzn.to/40orUvs
