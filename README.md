<h1 align="center">🤗 Awesome-Backdoor-in-Agent 🤗</h1>

<p align="center"><em>A curated collection of backdoor attacks, related poisoning attacks, and defenses for LLM- and VLM-based agents.</em></p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="https://github.com/Robin-WZQ/Awesome-Backdoor-in-Agent"><img src="https://img.shields.io/github/stars/Robin-WZQ/Awesome-Backdoor-in-Agent?style=social" alt="GitHub stars"></a>
</p>

**115 unique papers** · Metadata checked: **2026-10-08**

Papers are organized by agent type, with attacks and defenses listed separately. Benchmarks, evaluation frameworks, surveys, and threat-modeling studies have dedicated sections. Component tags such as Memory, Tool, Skill, and Model describe the attack surface within each agent setting.

This collection covers conditional backdoors and related poisoning threats to agents. Poisoning, prompt injection, and hijacking do not necessarily constitute a backdoor; inclusion does not imply that every paper studies a trigger-based attack. The scope focuses on LLM/VLM agents as the affected system.

## 📜 Table of Contents

- [General-Purpose LLM Agents](#general-purpose-llm-agents)
- [GUI and Computer-Use Agents](#gui-and-computer-use-agents)
- [Web and Research Agents](#web-and-research-agents)
- [Embodied Agents](#embodied-agents)
- [Multi-Agent Systems](#multi-agent-systems)
- [Coding Agents](#coding-agents)
- [Self-Evolving Agents](#self-evolving-agents)
- [Benchmarks and Evaluation](#benchmarks-and-evaluation)
- [Surveys](#surveys)
- [Curation Notes](#curation-notes)
- [Related Collections](#related-collections)

## 👑 Awesome Papers

### General-Purpose LLM Agents

General-purpose assistants and reusable agent frameworks, including memory, tool, MCP, skill, and harness security across application settings.

#### Backdoor and Poisoning Attacks

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2023.12 | <a id="paper-2312-00374"></a>The Philosopher's Stone: Trojaning Plugins of Large Language Models<br><sub>Model · Also: Embodied</sub> | NDSS'25 | [link](https://arxiv.org/abs/2312.00374) | - |
| 2024.02 | <a id="paper-2402-11208"></a>Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents<br><sub>Model · Also: Web / Research</sub> | NeurIPS'24 | [link](https://arxiv.org/abs/2402.11208) | [code](https://github.com/lancopku/agent-backdoor-attacks) |
| 2024.06 | <a id="paper-2406-03007"></a>BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents<br><sub>Model</sub> | ACL'24 | [link](https://arxiv.org/abs/2406.03007) | [code](https://github.com/DPamK/BadAgent) |
| 2024.07 | <a id="paper-2407-12784"></a>AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases<br><sub>Memory · Knowledge · Also: Embodied</sub> | NeurIPS'24 | [link](https://arxiv.org/abs/2407.12784) | [code](https://github.com/AI-secure/AgentPoison) |
| 2024.10 | <a id="paper-2410-10760"></a>Denial-of-Service Poisoning Attacks against Large Language Models<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2410.10760) | [code](https://github.com/sail-sg/P-DoS) |
| 2025.02 | <a id="paper-2502-12575"></a>DemonAgent: Dynamically Encrypted Multi-Backdoor Implantation Attack on LLM-based Agent<br><sub>Observation</sub> | arXiv | [link](https://arxiv.org/abs/2502.12575) | [code](https://github.com/whfeLingYu/DemonAgent) |
| 2025.03 | <a id="paper-2503-03704"></a>Memory Injection Attacks on LLM Agents via Query-Only Interaction<br><sub>Memory</sub> | NeurIPS'25 | [link](https://arxiv.org/abs/2503.03704) | - |
| 2025.10 | <a id="paper-2510-05159"></a>Malice in Agentland: Down the Rabbit Hole of Backdoors in the AI Supply Chain<br><sub>Model · Observation · Also: Web / Research</sub> | arXiv | [link](https://arxiv.org/abs/2510.05159) | - |
| 2025.10 | <a id="paper-2510-08238"></a>Chain-of-Trigger: An Agentic Backdoor that Paradoxically Enhances Agentic Robustness<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2510.08238) | - |
| 2025.12 | <a id="paper-2512-02321"></a>LeechHijack: Covert Computational Resource Exploitation in Intelligent Agent Systems<br><sub>Tool</sub> | arXiv | [link](https://arxiv.org/abs/2512.02321) | - |
| 2025.12 | <a id="paper-2512-16962"></a>MemoryGraft: Persistent Compromise of LLM Agents via Poisoned Experience Retrieval<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2512.16962) | [code](https://github.com/Jacobhhy/Agent-Memory-Poisoning) |
| 2026.01 | <a id="paper-2601-05504"></a>Memory Poisoning Attack and Defense on Memory Based LLM-Agents<br><sub>Memory · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2601.05504) | - |
| 2026.01 | <a id="paper-2601-07395"></a>MCP-ITP: An Automated Framework for Implicit Tool Poisoning in MCP<br><sub>Tool</sub> | arXiv | [link](https://arxiv.org/abs/2601.07395) | - |
| 2026.02 | <a id="paper-2602-04653"></a>Inference-Time Backdoors via Chat Templates: From LLM Supply Chains to Agentic System Compromise<br><sub>Harness · Also: Multi-Agent</sub> | ICLRW'26 (Trustworthy AI) | [link](https://arxiv.org/abs/2602.04653) | - |
| 2026.03 | <a id="paper-2603-03371"></a>Sleeper Cell: Injecting Latent Malice Temporal Backdoors into Tool-Using LLMs<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2603.03371) | - |
| 2026.04 | <a id="paper-2604-05432"></a>Your LLM Agent Can Leak Your Data: Data Exfiltration via Backdoored Tool Use<br><sub>Model · Tool</sub> | ACL'26 | [link](https://arxiv.org/abs/2604.05432) | - |
| 2026.04 | <a id="paper-2604-06811"></a>SkillTrojan: Backdoor Attacks on Skill-Based Agent Systems<br><sub>Skill</sub> | arXiv | [link](https://arxiv.org/abs/2604.06811) | - |
| 2026.04 | <a id="paper-2604-09378"></a>BadSkill: Backdoor Attacks on Agent Skills via Model-in-Skill Poisoning<br><sub>Skill · Model</sub> | arXiv | [link](https://arxiv.org/abs/2604.09378) | - |
| 2026.05 | <a id="paper-2605-05846"></a>LoopTrap: Termination Poisoning Attacks on LLM Agents<br><sub>Observation</sub> | arXiv | [link](https://arxiv.org/abs/2605.05846) | - |
| 2026.05 | <a id="paper-2605-06158"></a>Stateful Agent Backdoors: Constructing Cross-Session Attack Programs<br><sub>Model · Memory</sub> | arXiv | [link](https://arxiv.org/abs/2605.06158) | - |
| 2026.05 | <a id="paper-2605-09033"></a>ShadowMerge: A Novel Poisoning Attack on Graph-Based Agent Memory via Relation-Channel Conflicts<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2605.09033) | - |
| 2026.05 | <a id="paper-2605-15338"></a>Hidden in Memory: Sleeper Memory Poisoning in LLM Agents<br><sub>Memory · Observation</sub> | arXiv | [link](https://arxiv.org/abs/2605.15338) | - |
| 2026.05 | <a id="paper-2605-26154"></a>MemMorph: Tool Hijacking in LLM Agents via Memory Poisoning<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2605.26154) | - |
| 2026.05 | <a id="paper-2605-29960"></a>MemPoison: Bypassing Selective Memory Mechanisms to Plant Backdoors in LLM Agents<br><sub>Memory</sub> | CCS'26 | [link](https://arxiv.org/abs/2605.29960) | - |
| 2026.06 | <a id="paper-2606-24402"></a>Poisoned Playbooks: Demystifying Knowledge Poisoning Effects on AI Security Agents<br><sub>Knowledge</sub> | arXiv | [link](https://arxiv.org/abs/2606.24402) | - |
| 2026.06 | <a id="paper-2606-27027"></a>ShareLock: A Stealthy Multi-Tool Threshold Poisoning Attack Against MCP<br><sub>Tool</sub> | arXiv | [link](https://arxiv.org/abs/2606.27027) | - |
| 2026.07 | <a id="paper-2607-05029"></a>Your Agent's Memories Are Not Its Own: Forged Reasoning Attacks on LLM Agent Memory and Defenses<br><sub>Memory · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2607.05029) | - |
| 2026.07 | <a id="paper-2607-06595"></a>When Agents Remember Too Much: Memory Poisoning Attacks on Large Language Model Agents<br><sub>Memory · Tool</sub> | arXiv | [link](https://arxiv.org/abs/2607.06595) | - |
| 2026.08 | <a id="paper-2608-01637"></a>Salami Attack: Stealthy Collusive Memory Poisoning against OpenClaw<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2608.01637) | - |
| 2026.08 | <a id="paper-2608-09577"></a>ElasticBack: Stealthy Conditional Backdoor in LLM-Agent Skills via Coupled Trigger-Rule Optimization<br><sub>Skill</sub> | arXiv | [link](https://arxiv.org/abs/2608.09577) | - |
| 2026.08 | <a id="paper-2608-23471"></a>InjecMEM: Memory Injection Attack on LLM Agent Memory Systems<br><sub>Memory</sub> | COLM'26 | [link](https://arxiv.org/abs/2608.23471) | - |
| 2026.09 | <a id="paper-2609-00523"></a>Transferable End-to-End Optimization for Indirect Long-Term Memory Poisoning in LLM Agents<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2609.00523) | - |
| 2026.09 | <a id="paper-2609-13889"></a>When Malicious Instructions Persist: Persistent Memory Poisoning Attack on Harness-Based Agents<br><sub>Memory · Observation · Also: Coding</sub> | arXiv | [link](https://arxiv.org/abs/2609.13889) | [code](https://github.com/hsh754/PMPA) |
| 2026.09 | <a id="paper-2609-14060"></a>AGENTQ: Quantization-Conditioned Backdoor Attacks on LLM Agents<br><sub>Model</sub> | EMNLP'26 | [link](https://arxiv.org/abs/2609.14060) | - |
| 2026.09 | <a id="paper-2609-15029"></a>Pick Your Poison: Learning to Select Poison Sets for Stronger LLM Backdoor Attacks<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2609.15029) | - |
| 2026.09 | <a id="paper-2609-27155"></a>The Like Trap: Multi-Stage Poisoning against Agents in Similarity-based Recommendation Systems<br><sub>Observation</sub> | arXiv | [link](https://arxiv.org/abs/2609.27155) | - |

Also see [Trust No Tool: Evaluating and Defending LLM Agents under Untrusted Tool Feedback](#paper-2605-17453); [From Prompt Injection to Persistent Control: Defending Agentic Harness Against Trojan Backdoors](#paper-2605-31042) (papers with both attack and defense contributions).

#### Detection and Defenses

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2025.06 | <a id="paper-2506-08336"></a>Your Agent Can Defend Itself against Backdoor Attacks<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2506.08336) | - |
| 2025.08 | <a id="paper-2508-06153"></a>SLIP: Soft Label Mechanism and Key-Extraction-Guided CoT-based Defense Against Instruction Backdoor in APIs<br><sub>Harness</sub> | Findings of ACL'26 | [link](https://arxiv.org/abs/2508.06153) | - |
| 2025.08 | <a id="paper-2508-20412"></a>MindGuard: Intrinsic Decision Inspection for Securing LLM Agents Against Metadata Poisoning<br><sub>Tool</sub> | arXiv | [link](https://arxiv.org/abs/2508.20412) | - |
| 2025.09 | <a id="paper-2510-02373"></a>A-MemGuard: A Proactive Defense Framework for LLM-Based Agent Memory<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2510.02373) | [code](https://github.com/TangciuYueng/AMemGuard) |
| 2025.11 | <a id="paper-2511-19874"></a>Cross-LLM Generalization of Behavioral Backdoor Detection in AI Agent Supply Chains | arXiv | [link](https://arxiv.org/abs/2511.19874) | - |
| 2026.04 | <a id="paper-2604-22888"></a>RouteGuard: Internal-Signal Detection of Skill Poisoning in LLM Agents<br><sub>Skill</sub> | arXiv | [link](https://arxiv.org/abs/2604.22888) | - |
| 2026.05 | <a id="paper-2605-03482"></a>MEMSAD: Gradient-Coupled Anomaly Detection for Memory Poisoning in Retrieval-Augmented Agents<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2605.03482) | - |
| 2026.05 | <a id="paper-2605-14421"></a>MemLineage: Lineage-Guided Enforcement for LLM Agent Memory<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2605.14421) | - |
| 2026.05 | <a id="paper-2605-17453"></a>Trust No Tool: Evaluating and Defending LLM Agents under Untrusted Tool Feedback<br><sub>Tool · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2605.17453) | - |
| 2026.05 | <a id="paper-2605-23723"></a>MemAudit: Post-hoc Auditing of Poisoned Agent Memory via Causal Attribution and Structural Anomaly Detection<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2605.23723) | - |
| 2026.05 | <a id="paper-2605-31042"></a>From Prompt Injection to Persistent Control: Defending Agentic Harness Against Trojan Backdoors<br><sub>Harness · Observation · Also: Coding · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2605.31042) | [code](https://github.com/RUC-NLPIR/ClawTrojan) |
| 2026.06 | <a id="paper-2606-12703"></a>SMSR: Certified Defence Against Runtime Memory Poisoning in Persistent LLM Agent Systems<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2606.12703) | - |
| 2026.06 | <a id="paper-2606-20922"></a>Think Twice Before You Act: Protecting LLM Agents Against Tool Description Poisoning via Isolated Planning<br><sub>Tool</sub> | ICML'26 | [link](https://arxiv.org/abs/2606.20922) | [code](https://github.com/shishishi123/Tool-Guard) |
| 2026.06 | <a id="paper-2606-22030"></a>When Does Belief-Based Agent Memory Help? Reliability-Conditional Updating and Provenance-Capped Poisoning Defense<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2606.22030) | - |
| 2026.06 | <a id="paper-2606-23416"></a>Detecting Malicious Agent Skills in the Wild using Attention<br><sub>Skill</sub> | arXiv | [link](https://arxiv.org/abs/2606.23416) | - |
| 2026.06 | <a id="paper-2606-24322"></a>Securing LLM-Agent Long-Term Memory Against Poisoning: Non-Malleable, Origin-Bound Authority with Machine-Checked Guarantees<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2606.24322) | - |
| 2026.06 | <a id="paper-2606-30566"></a>Retrieval Observability Bounds on Provenance Detection for Agent Memory Poisoning: Measured Coverage and a Falsified Standalone Detector<br><sub>Memory · Defense Evaluation</sub> | arXiv | [link](https://arxiv.org/abs/2606.30566) | - |
| 2026.07 | <a id="paper-2607-28103"></a>MIND: Lightweight and Effective Memory Injection Defense for LLM Agents via Intent-Aware Information Bottleneck<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2607.28103) | - |
| 2026.08 | <a id="paper-2608-10502"></a>From Faulty Memories to Corrected Actions: Dependency-Guided Rollback Repair for Memory-Augmented Agents<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2608.10502) | - |
| 2026.08 | <a id="paper-2608-11295"></a>Backdoor Decontamination Dynamics in LLM Agents<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2608.11295) | - |
| 2026.08 | <a id="paper-2608-21230"></a>Utility Under Attack: Agent Memory Poisoning and the Limits of Content Screening and Provenance Ranking<br><sub>Memory · Defense Evaluation</sub> | arXiv | [link](https://arxiv.org/abs/2608.21230) | - |
| 2026.09 | <a id="paper-2609-08747"></a>MemSentry: A Framework for Detecting Persistent Memory Poisoning in Agentic AI<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2609.08747) | - |
| 2026.09 | <a id="paper-2609-14723"></a>Detecting and Localizing Segment-Level Poisoning in Multi-Source LLM-Agent Inputs<br><sub>Knowledge</sub> | arXiv | [link](https://arxiv.org/abs/2609.14723) | - |
| 2026.09 | <a id="paper-2609-22818"></a>The Price of Safety: Benign-Case Utility and Token Overhead of Memory-Poisoning Defenses in LLM Agents<br><sub>Memory · Defense Evaluation</sub> | arXiv | [link](https://arxiv.org/abs/2609.22818) | - |

Also see [Memory Poisoning Attack and Defense on Memory Based LLM-Agents](#paper-2601-05504); [Your Agent's Memories Are Not Its Own: Forged Reasoning Attacks on LLM Agent Memory and Defenses](#paper-2607-05029) (papers with both attack and defense contributions).


### GUI and Computer-Use Agents

Mobile, desktop, screenshot-based, and other graphical user interface agents.

#### Backdoor and Poisoning Attacks

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2025.05 | <a id="paper-2505-14418"></a>Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents<br><sub>Model · Attack + Defense</sub> | Findings of EMNLP'25 | [link](https://arxiv.org/abs/2505.14418) | [code](https://github.com/CTZhou-byte/AgentGhost) |
| 2025.06 | <a id="paper-2506-13205"></a>Poison Once, Control Anywhere: Clean-Text Visual Backdoors in VLM-based Mobile Agents<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2506.13205) | - |
| 2025.07 | <a id="paper-2507-06899"></a>VisualTrap: A Stealthy Backdoor Attack on GUI Agents via Visual Grounding Manipulation<br><sub>Model</sub> | COLM'25 | [link](https://arxiv.org/abs/2507.06899) | [code](https://github.com/whi497/VisualTrap) |
| 2026.03 | <a id="paper-2603-08316"></a>SlowBA: An efficiency backdoor attack towards VLM-based GUI agents<br><sub>Model</sub> | ECCV'26 | [link](https://arxiv.org/abs/2603.08316) | [code](https://github.com/tu-tuing/SlowBA) |
| 2026.03 | <a id="paper-2603-23007"></a>AgentRAE: Remote Action Execution through Notification-based Visual Backdoors against Screenshots-based Mobile GUI Agents<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2603.23007) | - |

#### Detection and Defenses

Also see [Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents](#paper-2505-14418) (papers with both attack and defense contributions).


### Web and Research Agents

Browsing, search, deep research, and agentic retrieval-augmented generation systems.

#### Backdoor and Poisoning Attacks

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2025.08 | <a id="paper-2509-00124"></a>A Whole New World: Creating a Parallel-Poisoned Web Only AI-Agents Can See<br><sub>Observation</sub> | arXiv | [link](https://arxiv.org/abs/2509.00124) | - |
| 2025.12 | <a id="paper-2512-14448"></a>Reasoning-Style Poisoning of LLM Agents via Stealthy Style Transfer: Process-Level Attacks and Runtime Monitoring in RSV Space<br><sub>Knowledge · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2512.14448) | - |
| 2026.04 | <a id="paper-2604-02623"></a>Poison Once, Exploit Forever: Environment-Injected Memory Poisoning Attacks on Web Agents<br><sub>Memory · Observation</sub> | arXiv | [link](https://arxiv.org/abs/2604.02623) | - |
| 2026.06 | <a id="paper-2606-06387"></a>WebMCP Tool Surface Poisoning: Runtime Manipulation Attacks on LLM Agents<br><sub>Tool</sub> | arXiv | [link](https://arxiv.org/abs/2606.06387) | - |
| 2026.06 | <a id="paper-2606-10742"></a>MemVenom: Triggered Poisoning of Multimodal Memories in Web Agents<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2606.10742) | - |
| 2026.07 | <a id="paper-2607-00422"></a>KidnapRAG: A Black-Box Attack for Hijacking Reasoning in Agentic Retrieval-Augmented Generation Systems<br><sub>Knowledge</sub> | EMNLP'26 | [link](https://arxiv.org/abs/2607.00422) | [code](https://github.com/chanwoochoi316/KidnapRAG) |
| 2026.07 | <a id="paper-2607-04718"></a>FORGE: Research-Trajectory Hijacking Attacks on Deep Research Agents<br><sub>Knowledge · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2607.04718) | [code](https://github.com/yvepan/FORGE) |
| 2026.07 | <a id="paper-2607-10712"></a>Distributed Denial of Science: How Indirect Data Poisoning of AI Systems Can Industrialize Scientific Fraud<br><sub>Knowledge</sub> | arXiv | [link](https://arxiv.org/abs/2607.10712) | - |

#### Detection and Defenses

Also see [Reasoning-Style Poisoning of LLM Agents via Stealthy Style Transfer: Process-Level Attacks and Runtime Monitoring in RSV Space](#paper-2512-14448); [FORGE: Research-Trajectory Hijacking Attacks on Deep Research Agents](#paper-2607-04718) (papers with both attack and defense contributions).


### Embodied Agents

LLM- or VLM-based robots, autonomous driving, and decision-making systems that interact with physical environments.

#### Backdoor and Poisoning Attacks

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2024.05 | <a id="paper-2405-20774"></a>Can We Trust Embodied Agents? Exploring Backdoor Attacks against Embodied LLM-based Decision-Making Systems<br><sub>Model · Knowledge · Observation</sub> | ICLR'25 | [link](https://arxiv.org/abs/2405.20774) | - |
| 2024.08 | <a id="paper-2408-02882"></a>Compromising Embodied Agents with Contextual Backdoor Attacks<br><sub>Harness</sub> | arXiv | [link](https://arxiv.org/abs/2408.02882) | - |
| 2025.10 | <a id="paper-2510-27623"></a>BEAT: Visual Backdoor Attacks on VLM-based Embodied Agents via Contrastive Trigger Learning<br><sub>Model</sub> | ICLR'26 | [link](https://arxiv.org/abs/2510.27623) | - |
| 2026.04 | <a id="paper-2604-03890"></a>From Prompt to Physical Action: Structured Backdoor Attacks on LLM-Mediated Robotic Control Systems<br><sub>Model</sub> | arXiv | [link](https://arxiv.org/abs/2604.03890) | - |
| 2026.09 | <a id="paper-2609-26184"></a>Silent Sabotage: Internal State Triggered Backdoor Attacks on LLM-Powered Robotic Systems<br><sub>Harness</sub> | arXiv | [link](https://arxiv.org/abs/2609.26184) | - |

#### Detection and Defenses

No standalone papers are listed in this subsection yet.


### Multi-Agent Systems

Collaborating agents, inter-agent communication, shared memory, and distributed attacks across agent roles.

#### Backdoor and Poisoning Attacks

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2025.10 | <a id="paper-2510-11246"></a>Collaborative Shadows: Distributed Backdoor Attacks in LLM-Based Multi-Agent Systems<br><sub>Tool</sub> | arXiv | [link](https://arxiv.org/abs/2510.11246) | [code](https://github.com/whfeLingYu/Distributed-Backdoor-Attacks-in-MAS) |
| 2025.11 | <a id="paper-2511-07176"></a>Graph Representation-based Model Poisoning on the Heterogeneous Internet of Agents<br><sub>Model</sub> | IWCMC'26 | [link](https://arxiv.org/abs/2511.07176) | - |
| 2026.08 | <a id="paper-2608-01085"></a>When Collaboration Becomes a Trigger: Collective Evidence-Threshold Backdoors in Multi-Agent Systems<br><sub>Model · Communication · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2608.01085) | - |
| 2026.08 | <a id="paper-2608-24069"></a>Poisoning Agentic Alpha: Adversarial Vulnerabilities Across Roles and Architectures in Multi-Agent Trading Systems<br><sub>Communication · Knowledge</sub> | arXiv | [link](https://arxiv.org/abs/2608.24069) | - |

#### Detection and Defenses

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2025.05 | <a id="paper-2505-11642"></a>PeerGuard: Defending Multi-Agent Systems Against Backdoor Attacks Through Mutual Reasoning | IEEE IRI'25 | [link](https://arxiv.org/abs/2505.11642) | - |
| 2026.02 | <a id="paper-2603-02240"></a>SuperLocalMemory: Privacy-Preserving Multi-Agent Memory with Bayesian Trust Defense Against Memory Poisoning<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2603.02240) | [code](https://github.com/varun369/SuperLocalMemoryV2) |
| 2026.05 | <a id="paper-2605-22842"></a>The Misattribution Gap: When Memory Poisoning Looks Like Model Failure in Agentic AI Systems<br><sub>Memory · Knowledge · Defense Evaluation</sub> | arXiv | [link](https://arxiv.org/abs/2605.22842) | - |
| 2026.07 | <a id="paper-2607-11751"></a>When Local Monitors Miss Compositional Harm: Diagnosing Distributed Backdoors in Multi-Agent Systems<br><sub>Tool · Defense Evaluation</sub> | arXiv | [link](https://arxiv.org/abs/2607.11751) | - |
| 2026.07 | <a id="paper-2607-19430"></a>ChannelGuard: Safe Models Do Not Compose into Safe Multi-Agent Systems<br><sub>Communication · Tool · Memory</sub> | arXiv | [link](https://arxiv.org/abs/2607.19430) | - |
| 2026.07 | <a id="paper-2607-24893"></a>Early Detection of Distributed Backdoors in Multi-Agent LLM Systems: A Characterization Study<br><sub>Tool · Defense Evaluation</sub> | arXiv | [link](https://arxiv.org/abs/2607.24893) | - |
| 2026.08 | <a id="paper-2608-00426"></a>MAPLE-Guard: Memory-Aware Link Enforcement Against Memory-Link Poisoning in Multi-Agent Systems<br><sub>Memory</sub> | arXiv | [link](https://arxiv.org/abs/2608.00426) | [code](https://github.com/xiong-wenjun/MAPLE-Guard) |
| 2026.08 | <a id="paper-2608-08100"></a>Defending Retrieval-Augmented Intrusion Detection Against Knowledge Poisoning and Prompt Injection<br><sub>Knowledge</sub> | arXiv | [link](https://arxiv.org/abs/2608.08100) | - |

Also see [When Collaboration Becomes a Trigger: Collective Evidence-Threshold Backdoors in Multi-Agent Systems](#paper-2608-01085) (papers with both attack and defense contributions).


### Coding Agents

Software engineering agents, coding workflows, repositories, and coding skill ecosystems.

#### Backdoor and Poisoning Attacks

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2026.03 | <a id="paper-2603-19974"></a>Trojan's Whisper: Stealthy Manipulation of OpenClaw through Injected Bootstrapped Guidance<br><sub>Harness · Skill</sub> | arXiv | [link](https://arxiv.org/abs/2603.19974) | - |
| 2026.04 | <a id="paper-2604-03081"></a>Supply-Chain Poisoning Attacks Against LLM Coding Agent Skill Ecosystems<br><sub>Skill</sub> | arXiv | [link](https://arxiv.org/abs/2604.03081) | - |

#### Detection and Defenses

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2026.07 | <a id="paper-2607-25619"></a>SkillGate: Cost Efficient Runtime Malicious Skill File Detection in Coding Agents<br><sub>Skill</sub> | arXiv | [link](https://arxiv.org/abs/2607.25619) | - |


### Self-Evolving Agents

Agents that learn or modify memories, skills, code, or policies through experience, feedback, or self-modification.

#### Backdoor and Poisoning Attacks

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2026.05 | <a id="paper-2605-18930"></a>OEP: Poisoning Self-Evolving LLM Agents via Locally Correct but Non-Transferable Experiences<br><sub>Feedback · Memory · Also: General</sub> | arXiv | [link](https://arxiv.org/abs/2605.18930) | - |
| 2026.08 | <a id="paper-2608-03509"></a>SkillJack: Persistent Skill Backdoors in Self-Evolving Agents<br><sub>Feedback · Skill</sub> | arXiv | [link](https://arxiv.org/abs/2608.03509) | - |
| 2026.08 | <a id="paper-2608-05563"></a>When Experience Becomes Instruction: Trajectory Poisoning in Self-Evolving Agent Skill Systems<br><sub>Feedback · Skill</sub> | arXiv | [link](https://arxiv.org/abs/2608.05563) | - |
| 2026.08 | <a id="paper-2608-08303"></a>Query-Only Backdoor Attacks on Self-Evolving Skills via Trajectory Poisoning<br><sub>Feedback · Skill</sub> | arXiv | [link](https://arxiv.org/abs/2608.08303) | - |
| 2026.08 | <a id="paper-2608-25776"></a>EVOMAL: Self-Poisoning in Self-Evolving Coding Agents<br><sub>Skill · Feedback · Also: Coding · Attack + Defense</sub> | arXiv | [link](https://arxiv.org/abs/2608.25776) | - |
| 2026.09 | <a id="paper-2609-17817"></a>Reflections on Trusting Trust, Revisited: Contaminating Self-Modifying AI Coding Agents with Poisoned Benchmarks<br><sub>Feedback · Also: Coding</sub> | arXiv | [link](https://arxiv.org/abs/2609.17817) | - |

#### Detection and Defenses

Also see [EVOMAL: Self-Poisoning in Self-Evolving Coding Agents](#paper-2608-25776) (papers with both attack and defense contributions).

### Benchmarks and Evaluation

Agent type and component tags are shown beneath each title.

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2024.10 | <a id="paper-2410-02644"></a>Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents<br><sub>General-Purpose LLM Agents · Model · Memory · Tool · Harness · Also: Web / Research · Also: Embodied</sub> | ICLR'25 | [link](https://arxiv.org/abs/2410.02644) | [code](https://github.com/agiresearch/ASB) |
| 2025.08 | <a id="paper-2508-14925"></a>MCPTox: A Benchmark for Tool Poisoning Attack on Real-World MCP Servers<br><sub>General-Purpose LLM Agents · Tool</sub> | arXiv | [link](https://arxiv.org/abs/2508.14925) | - |
| 2026.01 | <a id="paper-2601-04566"></a>BackdoorAgent: A Unified Framework for Backdoor Attacks on LLM-based Agents<br><sub>General-Purpose LLM Agents · Memory · Tool · Harness · Also: Web / Research · Also: Coding · Also: Embodied</sub> | arXiv | [link](https://arxiv.org/abs/2601.04566) | - |
| 2026.05 | <a id="paper-2605-01970"></a>Trojan Hippo Bench: A Dynamic Benchmark for Persistent Memory Attacks and Defenses in LLM Agents<br><sub>General-Purpose LLM Agents · Memory · Tool</sub> | arXiv | [link](https://arxiv.org/abs/2605.01970) | - |
| 2026.05 | <a id="paper-2605-24069"></a>When the Manual Lies: A Realistic Benchmark to Evaluate MCP Poisoning Attacks for LLM Agents<br><sub>General-Purpose LLM Agents · Tool</sub> | arXiv | [link](https://arxiv.org/abs/2605.24069) | - |
| 2026.06 | <a id="paper-2606-04329"></a>From Untrusted Input to Trusted Memory: A Systematic Study of Memory Poisoning Attacks in LLM Agents<br><sub>General-Purpose LLM Agents · Memory</sub> | arXiv | [link](https://arxiv.org/abs/2606.04329) | - |
| 2026.07 | <a id="paper-2607-05189"></a>When Claws Remember but Do Not Tell: Stealthy Memory Injection in Persistent Personal Agents<br><sub>General-Purpose LLM Agents · Memory · Tool</sub> | arXiv | [link](https://arxiv.org/abs/2607.05189) | - |
| 2026.07 | <a id="paper-2607-14651"></a>MemPoison: Uncovering Persistent Memory Threats and Structural Blind Spots in LLM Agents<br><sub>General-Purpose LLM Agents · Memory</sub> | arXiv | [link](https://arxiv.org/abs/2607.14651) | - |
| 2026.07 | <a id="paper-2607-20759"></a>IssueTrojanBench: Benchmarking AI Coding Agents Against Malicious Issue Requests<br><sub>Coding Agents · Repository</sub> | arXiv | [link](https://arxiv.org/abs/2607.20759) | - |
| 2026.07 | <a id="paper-2607-27080"></a>MemSecBench: Tracking Agent Memory Poisoning from Persistence to Consequence and Repair<br><sub>General-Purpose LLM Agents · Memory</sub> | arXiv | [link](https://arxiv.org/abs/2607.27080) | - |
| 2026.08 | <a id="paper-2608-30686"></a>Beyond the Payload: How User Invocation Shapes Coding Agent Vulnerability to Repository Poisoning<br><sub>Coding Agents · Repository</sub> | EMNLP'26 | [link](https://arxiv.org/abs/2608.30686) | - |
| 2026.09 | <a id="paper-2609-02265"></a>CAPTURE: Disentangling Preference Drift from Memory Poisoning in Personalized LLM Agents<br><sub>General-Purpose LLM Agents · Memory</sub> | arXiv | [link](https://arxiv.org/abs/2609.02265) | - |
| 2026.09 | <a id="paper-2609-06027"></a>Evaluating Deep-Search Agents under Hierarchical Web Evidence Poisoning<br><sub>Web and Research Agents · Knowledge</sub> | arXiv | [link](https://arxiv.org/abs/2609.06027) | [code](https://github.com/ant-research/HAE-GEO/tree/main) |
| 2026.09 | <a id="paper-2609-06972"></a>AgentDrift: A Step-Labeled Benchmark of Injection-Hijacked LLM Agent Trajectories<br><sub>General-Purpose LLM Agents · Tool</sub> | arXiv | [link](https://arxiv.org/abs/2609.06972) | [code](https://github.com/Asif-0209/AgentDrift) |

### Surveys

This section also includes threat-modeling and perspective papers.

| Time | Title | Venue | Paper | Code |
| --- | --- | :---: | :---: | :---: |
| 2026.03 | <a id="paper-2603-20357"></a>Memory poisoning and secure multi-agent systems<br><sub>Multi-Agent Systems · Memory</sub> | arXiv | [link](https://arxiv.org/abs/2603.20357) | - |
| 2026.03 | <a id="paper-2603-22489"></a>Model Context Protocol Threat Modeling and Analyzing Vulnerabilities to Prompt Injection with Tool Poisoning<br><sub>General-Purpose LLM Agents · Tool</sub> | arXiv | [link](https://arxiv.org/abs/2603.22489) | - |

## Curation Notes

- **One primary entry per paper.** The main setting determines the agent category. General frameworks and studies spanning multiple application settings are placed under General-Purpose LLM Agents; additional contexts appear as tags. Papers centered on self-evolution are placed under Self-Evolving Agents even when the implementation uses a coding agent.
- **Contribution roles.** Papers with attack and defense methods are tagged Attack + Defense and cross-referenced between the two subsections. Defense Evaluation identifies studies of detection limits or defense behavior, which should not be read as deployment-ready defenses.
- **Time.** Dates use the month of the first arXiv submission, rather than the conference date or the arXiv identifier prefix. Entries are ordered chronologically within each subsection.
- **Venue.** Conference and workshop labels are recorded only when supported by official proceedings or an explicit acceptance statement on the paper's arXiv record. Findings and workshops are identified separately. arXiv is used where a venue has not been verified; submission or review status is not treated as acceptance.
- **Code.** Links point to author-provided code or artifact repositories. A dash means that a usable author-linked code repository was not confirmed during this pass; it does not establish that no code exists.
- **Coverage.** This release organizes an existing 115-paper literature collection reviewed on 2026-09-28, with titles and arXiv records checked on 2026-10-08. It is not a claim of exhaustive coverage through that date. The structured index is available in [data/papers.csv](data/papers.csv).
- **Version updates.** The latest title of [Trojan Hippo Bench](https://arxiv.org/abs/2605.01970) is used and the paper is listed as a benchmark. The latest revision of [Retrieval Observability Bounds on Provenance Detection for Agent Memory Poisoning](https://arxiv.org/abs/2606.30566) reverses its earlier practical detector recommendation; it is tagged Defense Evaluation.

Corrections and additions are welcome through pull requests or issues. Please provide the paper title, first public date, agent setting, contribution type, paper URL, and author-provided code URL when available.

## Related Collections

- [Awesome-Backdoor-on-LMMs](https://github.com/Robin-WZQ/Awesome-Backdoor-on-LMMs)
