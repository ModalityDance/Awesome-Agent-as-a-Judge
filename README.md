<a name="readme-top"></a>


<div align="center">
    <img src="https://readme-typing-svg.herokuapp.com?font=Lexend&weight=600&size=42&duration=1500&pause=1000&color=3271AE&center=true&vCenter=true&repeat=false&width=800&height=65&lines=%E2%9C%A8Awesome+Agent-as-a-Judge%E2%9C%A8" />

</div>



<div align="center">
<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
    <a href="https://arxiv.org/abs/2601.05111"><img src="https://img.shields.io/badge/arXiv-2601.05111-b31b1b.svg" alt="arXiv"></a>
    <a href="https://huggingface.co/papers/2601.05111"><img src="https://img.shields.io/badge/🤗%20HF%20Face-Paper-yellow" alt="Hugging Face"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
</p>
</div>


Welcome to **Awesome Agent-as-a-Judge**! 👋 This repository provides a collection of papers for [**A Survey on Agent-as-a-Judge**](https://arxiv.org/pdf/2601.05111), where LLM-based agents are used as judges to evaluate different types of outputs, including natural language generation, code generation, mathematical reasoning, and more.

<div align="center">
<img src="assets/agent.png" alt="Agent-as-a-Judge Illustration" width="500">

</div>






## 📑 Table of Contents <span id="table-of-contents">

* <a href='#taxonomy'>📊 Taxonomy</a>
* <a href='#papers'>📚 Papers</a>
* <a href='#community'>🪴 Acknowledge</a>
* <a href='#citation'> 📖 Citation </a>

## 📊 Taxonomy <span id="taxonomy">

<div align="center">
<img src="assets/taxonomy.png" alt="Agent-as-a-Judge Taxonomy" width="800"/>
</div>

## 📚 Papers <span id="papers">


### Methodologies


#### Multi-Agent Collaboration
- [2026/03] CollabEval: Enhancing LLM-as-a-Judge via Multi-Agent Collaboration | [paper](https://arxiv.org/abs/2603.00993) | Venue: AAAI 2025 Workshop
- [2025/11] HiMATE: A Hierarchical Multi-Agent Framework for Machine Translation Evaluation | [paper](https://arxiv.org/abs/2505.16281) | Venue: EMNLP 2025
- [2025/11] Efficient LLM Safety Evaluation through Multi-Agent Debate | [paper](https://arxiv.org/abs/2511.06396)
- [2025/11] No-Human in the Loop: Agentic Evaluation at Scale for Recommendation | [paper](https://arxiv.org/abs/2511.03051) | Venue: NeurIPS 2025 Workshop
- [2025/10] Multi-Agent Debate for LLM Judges with Adaptive Stability Detection | [paper](https://arxiv.org/abs/2510.12697) | Venue: NeurIPS 2025
- [2025/07] CourtEval: A courtroom-based multi-agent evaluation framework. | [paper](https://aclanthology.org/2025.findings-acl.1327) | Venue: ACL 2025
- [2025/05] CAFES: A Collaborative Multi-Agent Framework for Multi-Granular Multimodal Essay Scoring | [paper](https://arxiv.org/abs/2505.13965)
- [2025/05] Judging with Many Minds: Do More Perspectives Mean Less Prejudice? On Bias Amplification and Resistance in Multi-Agent Based LLM-as-Judge | [paper](https://arxiv.org/abs/2505.19477) | Venue: EMNLP Findings 2025
- [2025/04] Leveraging LLMs as Meta-Judges: A Multi-Agent Framework for Evaluating LLM Judgments | [paper](https://arxiv.org/abs/2504.17087)
- [2025/03] GEMA-Score: Granular Explainable Multi-Agent Score for Radiology Report Evaluation | [paper](https://arxiv.org/abs/2503.05347)
- [2025/02] Table-Critic: A Multi-Agent Framework for Collaborative Criticism and Refinement in Table Reasoning | [paper](https://arxiv.org/abs/2502.11799) | Venue: ACL 2025
- [2025/02] Faithful, Unfaithful or Ambiguous? Multi-Agent Debate with Initial Stance for Summary Evaluation | [paper](https://arxiv.org/abs/2502.08514) | Venue: NAACL 2025
- [2024/12] M-MAD: Multidimensional Multi-Agent Debate for Advanced Machine Translation Evaluation | [paper](https://arxiv.org/abs/2412.20127) | Venue: ACL 2025
- [2024/11] SAGEval: The frontiers of Satisfactory Agent based NLG Evaluation | [paper](https://arxiv.org/abs/2411.16077)
- [2024/01] ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate | [paper](https://arxiv.org/abs/2308.07201) | Venue: ICLR 2024
- [2023/03] Large language models are diverse role-players for summarization evaluation | [paper](https://arxiv.org/abs/2303.15078) | Venue: NLPCC 2023

#### Planning
- [2026/03] APRES: An Agentic Paper Revision and Evaluation System | [paper](https://arxiv.org/abs/2603.03142)
- [2026/01] Agentic Rubrics as Contextual Verifiers for SWE Agents | [paper](https://arxiv.org/abs/2601.04171)
- [2025/11] Large Language Models as User-Agents for Evaluating Task-Oriented-Dialogue Systems . | [paper](https://arxiv.org/abs/2411.09972)
- [2025/10] Online Rubrics Elicitation from Pairwise Comparisons | [paper](https://arxiv.org/abs/2510.07284)
- [2025/05] AGENT-X: Adaptive Guideline-based Expert Network for Threshold-free AI-generated teXt detection | [paper](https://arxiv.org/abs/2505.15261)
- [2025/04] EvalAgent: Discovering Implicit Evaluation Criteria from the Web | [paper](https://arxiv.org/abs/2504.15219) | Venue: COLM 2025
- [2025/01] Learning to Plan & Reason for Evaluation with Thinking-LLM-as-a-Judge | [paper](https://arxiv.org/abs/2501.18099) | Venue: ICML 2025
- [2024/12] Evaluation Agent: Efficient and Promptable Evaluation Framework for Visual Generative Models | [paper](https://arxiv.org/abs/2412.09645) | Venue: ACL 2025
- [2024/05] MATEval: A Multi-Agent Discussion Framework for Advancing Open-Ended Text Evaluation | [paper](https://arxiv.org/abs/2403.19305) | Venue: DASFAA 2024


#### Tool Integration
- [2026/04] AgentV-RL: Scaling Reward Modeling with Agentic Verifier | [paper](https://arxiv.org/abs/2604.16004)
- [2026/02] DREAM: Deep Research Evaluation with Agentic Metrics | [paper](https://arxiv.org/abs/2602.18940)
- [2026/02] Scaling Agentic Verifier for Competitive Coding | [paper](https://arxiv.org/abs/2602.04254)
- [2026/01] Agentic Reward Modeling: Verifying GUI Agent via Online Proactive Interaction | [paper](https://arxiv.org/abs/2602.00575)
- [2026/01] Scaling Medical Reasoning Verification via Tool-Integrated Reinforcement Learning | [paper](https://arxiv.org/abs/2601.20221)
- [2025/12] Multimodal Reinforcement Learning with Adaptive Verifier for AI Agents | [paper](https://arxiv.org/abs/2512.03438)
- [2025/12] ARM-Thinker: Reinforcing Multimodal Generative Reward Models with Agentic Tool Use and Visual Reasoning | [paper](https://arxiv.org/abs/2512.05111)
- [2025/12] CoSineVerifier: Tool-Augmented Answer Verification for Computation-Oriented Scientific Questions | [paper](https://arxiv.org/abs/2512.01224)
- [2025/11] HERMES: Towards Efficient and Verifiable Mathematical Reasoning in LLMs. | [paper](https://arxiv.org/abs/2511.1876)
- [2025/11] TIM-PRM: Verifying multimodal reasoning with Tool-Integrated PRM | [paper](https://arxiv.org/abs/2511.22998)
- [2025/11] Agent0-VL: Exploring Self-Evolving Agent for Tool-Integrated Vision-Language Reasoning | [paper](https://arxiv.org/abs/2511.19900) | Venue: ICLR 2026 Workshop
- [2025/10] OpenReward: Learning to Reward Long-form Agentic Tasks via Reinforcement Learning | [paper](https://arxiv.org/abs/2510.24636)
- [2025/10] TaTToo: Tool-Grounded Thinking PRM for Test-Time Scaling in Tabular Reasoning | [paper](https://arxiv.org/abs/2510.06217) | Venue: ICLR 2026
- [2025/08] Auto-Eval Judge: Towards a General Agentic Framework for Task Completion Evaluation | [paper](https://arxiv.org/abs/2508.05508)
- [2025/07] Can External Validation Tools Improve Annotation Quality for LLM-as-a-Judge? | [paper](https://arxiv.org/abs/2507.17015) | Venue: ACL 2025
- [2025/06] Mind2Web 2: Evaluating Agentic Search with Agent-as-a-Judge | [paper](https://arxiv.org/abs/2506.21506) | Venue: NeurIPS 2025
- [2025/04] CodeVisionary: An Agent-based Framework for Evaluating Large Language Models in Code Generation | [paper](https://arxiv.org/abs/2504.13472) | Venue: ASE 2025
- [2025/04] TALE: A Tool-Augmented Framework for Reference-Free Evaluation of Large Language Models | [paper](https://arxiv.org/abs/2504.07385)
- [2025/04] T1: Tool-integrated Self-verification for Test-time Compute Scaling in Small Language Models | [paper](https://arxiv.org/abs/2504.04718)
- [2025/04] VerifiAgent: a Unified Verification Agent in Language Model Reasoning | [paper](https://arxiv.org/abs/2504.00406) | Venue: EMNLP 2025
- [2025/02] Learning to Align Multi-Faceted Evaluation: A Unified and Robust Framework | [paper](https://arxiv.org/abs/2502.18874) | Venue: ACL Findings 2025
- [2025/02] Agentic Reward Modeling: Integrating Human Preferences with Verifiable Correctness Signals. | [paper](https://arxiv.org/abs/2502.19328) | Venue: ACL 2025
- [2024/12] Evaluation Agent: Efficient and Promptable Evaluation Framework for Visual Generative Models | [paper](https://arxiv.org/abs/2412.09645) | Venue: ACL 2025
- [2024/10] Agent-as-a-Judge: Evaluate Agents with Agent | [paper](https://arxiv.org/abs/2410.10934) | Venue: ICML 2025
- [2023/10] Tool-Augmented Reward Modeling | [paper](https://arxiv.org/abs/2310.01045) | Venue: ICLR 2024 Spotlight



#### Memory and Personalization
- [2025/12] ARM-Thinker: Reinforcing Multimodal Generative Reward Models with Agentic Tool Use and Visual Reasoning | [paper](https://arxiv.org/abs/2512.05111)
- [2025/11] HERMES: Towards Efficient and Verifiable Mathematical Reasoning in LLMs. | [paper](https://arxiv.org/abs/2511.1876)
- [2025/09] GUI-PRA: Process Reward Agent for GUI Tasks | [paper](https://arxiv.org/abs/2509.23263)
- [2025/08] PersRM-R1: Enhance Personalized Reward Modeling with Reinforcement Learning | [paper](https://arxiv.org/abs/2508.14076)
- [2025/06] SynthesizeMe! Inducing Persona-Guided Prompts for Personalized Reward Models in LLMs | [paper](https://arxiv.org/abs/2506.05598) | Venue: ACL 2025
- [2025/05] Teaching Language Models to Evolve with Users: Dynamic Profile Modeling for Personalized Alignment | [paper](https://arxiv.org/abs/2505.15456) | Venue: NeurIPS 2025
- [2025/02] FSPO: Few-Shot Preference Optimization of Synthetic Preference Data in LLMs Elicits Effective Personalization to Real Users | [paper](https://arxiv.org/abs/2502.19312)
- [2024/10] Agent-as-a-Judge: Evaluate Agents with Agent | [paper](https://arxiv.org/abs/2410.10934) | Venue: ICML 2025


#### Optimization Paradigms
- [2025/12] ARM-Thinker: Reinforcing Multimodal Generative Reward Models with Agentic Tool Use and Visual Reasoning | [paper](https://arxiv.org/abs/2512.05111)
- [2025/11] HERMES: Towards Efficient and Verifiable Mathematical Reasoning in LLMs. | [paper](https://arxiv.org/abs/2511.1876)
- [2025/10] Incentivizing Agentic Reasoning in LLM Judges via Tool-Integrated Reinforcement Learning | [paper](https://arxiv.org/abs/2510.23038)
- [2025/06] SynthesizeMe! Inducing Persona-Guided Prompts for Personalized Reward Models in LLMs | [paper](https://arxiv.org/abs/2506.05598) | Venue: ACL 2025
- [2025/05] AGENT-X: Adaptive Guideline-based Expert Network for Threshold-free AI-generated teXt detection | [paper](https://arxiv.org/abs/2505.15261)
- [2025/04] Multi-Agent LLM Judge: automatic personalized LLM judge design for evaluating natural language generation applications | [paper](https://arxiv.org/abs/2504.02867)
- [2024/12] Evaluation Agent: Efficient and Promptable Evaluation Framework for Visual Generative Models | [paper](https://arxiv.org/abs/2412.09645) | Venue: ACL 2025
- [2024/11] SAGEval: The frontiers of Satisfactory Agent based NLG Evaluation | [paper](https://arxiv.org/abs/2411.16077)


### Applications

#### Professional Domains

##### Education
- [2025/09] AutoSCORE: Enhancing Automated Scoring with Multi-Agent Large Language Models via Structured Component Recognition | [paper](https://arxiv.org/abs/2509.2191)
- [2025/07] Multi-agent-as-judge: Aligning llm-agent-based automated evaluation with multi-dimensional human evaluation. | [paper](https://arxiv.org/abs/2507.21028)
- [2025/03] Rubric Is All You Need: Enhancing LLM-based Code Evaluation With Question-Specific Rubrics | [paper](https://arxiv.org/abs/2503.23989) | Venue: ICER 2025
- [2024/10] A LLM-Powered Automatic Grading Framework with Human-Level Guidelines Optimization | [paper](https://arxiv.org/abs/2410.02165)
- [2024/05] Grade Like a Human: Rethinking Automated Assessment with Multi-Agent LLMs | [paper](https://arxiv.org/abs/2405.19694)

##### Finance
- [2025/07] FinResearchBench: A Logic Tree based Agent-as-a-Judge Evaluation Framework for Financial Research Agents | [paper](https://arxiv.org/abs/2507.16248) | Venue: ICAIF 2025
- [2025/07] From Tasks to Teams: A Risk-First Evaluation Framework for Multi-Agent LLM Systems in Finance | [paper](https://openreview.net/forum?id=frPFuji3Hz&noteId=w7sDUtTtQU) | Venue: ICML Workshop 2025
- [2025/02] FinDeepResearch: Evaluating Deep Research Agents in Rigorous Financial Analysis | [paper](https://arxiv.org/abs/2510.13936)
- [2025/02] Standard Benchmarks Fail -- Auditing LLM Agents in Finance Must Prioritize Risk | [paper](https://arxiv.org/abs/2502.15865)

##### Law
- [2025/09] SAMVAD: A Multi-Agent System for Simulating Judicial Deliberation Dynamics in India | [paper](https://arxiv.org/abs/2509.03793)
- [2024/12] AgentsBench: A Multi-Agent LLM Simulation Framework for Legal Judgment Prediction | [paper](https://arxiv.org/abs/2412.18697)
- [2024/03] AgentsCourt: Building judicial decision-making agents with court debate simulation and legal knowledge augmentation. | [paper](https://arxiv.org/abs/2403.02959) | Venue: EMNLP 2024

##### Medicine
- [2026/01] Scaling Medical Reasoning Verification via Tool-Integrated Reinforcement Learning | [paper](https://arxiv.org/abs/2601.20221)
- [2025/07] Multi-agent-as-judge: Aligning llm-agent-based automated evaluation with multi-dimensional human evaluation. | [paper](https://arxiv.org/abs/2507.21028)
- [2025/03] GEMA-Score: Granular Explainable Multi-Agent Score for Radiology Report Evaluation | [paper](https://arxiv.org/abs/2503.05347)
- [2024/02] Benchmarking Large Language Models on Communicative Medical Coaching: A Dataset and a Novel System | [paper](https://arxiv.org/abs/2402.05547) | Venue: ACL 2024
- [2024/02] Ai hospital: Benchmarking large language models in a multi-agent medical interaction simulator | [paper](https://arxiv.org/abs/2402.09742) | Venue: COLING 2025

#### General Domains

##### Multimodal and Vision
- [2025/12] ARM-Thinker: Reinforcing Multimodal Generative Reward Models with Agentic Tool Use and Visual Reasoning | [paper](https://arxiv.org/abs/2512.05111)
- [2025/04] CIGEval: A Unified Agentic Framework for Evaluating Conditional Image Generation | [paper](https://arxiv.org/abs/2504.07046) | Venue: ACL 2025
- [2024/12] Evaluation Agent: Efficient and Promptable Evaluation Framework for Visual Generative Models | [paper](https://arxiv.org/abs/2412.09645) | Venue: ACL 2025
- [2024/10] LRQ-Fact: LLM-Generated Relevant Questions for Multimodal Fact-Checking . | [paper](https://arxiv.org/abs/2410.04616)

##### Conversation and Interaction
- [2025/11] Large Language Models as User-Agents for Evaluating Task-Oriented-Dialogue Systems . | [paper](https://arxiv.org/abs/2411.09972)
- [2025/05] ESC-Judge: A Framework for Comparing Emotional Support Conversational Agents | [paper](https://arxiv.org/abs/2505.12531) | Venue: EMNLP 2025
- [2025/05] Sentient Agent as a Judge: Evaluating Higher-Order Social Cognition | [paper](https://arxiv.org/abs/2505.02847)
- [2025/01] IntellAgent: A Multi-Agent Framework for Evaluating Conversational AI Systems | [paper](https://arxiv.org/abs/2501.11067)
- [2025/01] PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agent | [paper](https://arxiv.org/abs/2501.01594)

##### Fact-Checking
- [2025/05] UrduFactCheck: An Agentic Fact-Checking Framework for Urdu | [paper](https://arxiv.org/abs/2505.15063) | Venue: EMNLP 2025
- [2025/02] FACT-AUDIT: An Adaptive Multi-Agent Framework for Dynamic Fact-Checking Evaluation | [paper](https://arxiv.org/abs/2502.17924) | Venue: ACL 2025
- [2025/01] NarrativeFactScore: Agent-as-Judge for Factual Summarization of Long Narratives | [paper](https://arxiv.org/abs/2501.09993) | Venue: EMNLP 2025

##### Math and Code
- [2026/02] Scaling Agentic Verifier for Competitive Coding | [paper](https://arxiv.org/abs/2602.04254)
- [2025/12] CoSineVerifier: Tool-Augmented Answer Verification for Computation-Oriented Scientific Questions | [paper](https://arxiv.org/abs/2512.01224)
- [2025/11] HERMES: Towards Efficient and Verifiable Mathematical Reasoning in LLMs. | [paper](https://arxiv.org/abs/2511.1876)
- [2025/08] CompassVerifier: A Unified and Robust Verifier for LLMs Evaluation and Outcome Reward | [paper](https://arxiv.org/abs/2508.03686) | Venue: EMNLP 2025
- [2025/05] Step-Wise Formal Verification for LLM-Based Mathematical Problem Solving | [paper](https://arxiv.org/abs/2505.20869)
- [2025/04] VerifiAgent: a Unified Verification Agent in Language Model Reasoning | [paper](https://arxiv.org/abs/2504.00406) | Venue: EMNLP 2025
- [2025/04] xVerify: Efficient Answer Verifier for Reasoning Model Evaluations | [paper](https://arxiv.org/abs/2504.10481)
- [2025/04] CodeVisionary: An Agent-based Framework for Evaluating Large Language Models in Code Generation | [paper](https://arxiv.org/abs/2504.13472) | Venue: ASE 2025
- [2025/02] Agentic Reward Modeling: Integrating Human Preferences with Verifiable Correctness Signals. | [paper](https://arxiv.org/abs/2502.19328) | Venue: ACL 2025
- [2025/02] Multi-Agent Verification: Scaling Test-Time Compute with Multiple Verifiers | [paper](https://arxiv.org/abs/2502.20379) | Venue: COLM 2025
- [2025/02] Popper: Automated Hypothesis Validation with Agentic Sequential Falsifications | [paper](https://arxiv.org/abs/2502.09858) | Venue: ICML 2025


## 🪴 Acknowledge <span id="community"></span>

We would like to thank the contributors, open-source projects, and research communities whose work made this collection possible. This repository builds upon the excellent research in agent-based evaluation methods.



<div align="center">


<a href="https://star-history.com/ModalityDance/Awesome-Agent-as-a-Judge&Date">
  <img src="https://api.star-history.com/svg?repos=ModalityDance/Awesome-Agent-as-a-Judge&type=Date" alt="Star History Chart" width="500"/>
</a>

</div>





## 📖 **Citation** <span id="citation"></span>


```bibtex
@misc{you2026agentasajudge,
      title={Agent-as-a-Judge}, 
      author={Runyang You and Hongru Cai and Caiqi Zhang and Qiancheng Xu and Meng Liu and Tiezheng Yu and Yongqi Li and Wenjie Li},
      year={2026},
      eprint={2601.05111},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2601.05111}, 
}
```


<div align="center">

<a href="https://github.com/ModalityDance/Awesome-Agent-as-a-Judge">
  <img src="https://img.shields.io/badge/⭐ Star%20us%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://github.com/ModalityDance/Awesome-Agent-as-a-Judge/issues">
  <img src="https://img.shields.io/badge/🐞 Report%20Issues-e74c3c?style=for-the-badge&logo=github" />
</a>


<br/>
⭐ <b>Thank you for visiting Awesome Agent-as-a-Judge!</b> ⭐

</div>
