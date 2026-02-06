# F5 Labs CASI and ARS AI Leaerboards


## About the Data

This repository contains the underlying data used to produce the **CASI Leaderboards**, a set of metrics designed to help researchers, practitioners, and decision-makers better understand and compare the security posture of modern AI models.

The CASI Leaderboards were created to address a growing gap in AI evaluation. While many existing benchmarks focus heavily on capability and performance, far fewer provide meaningful insight into model security, resilience to abuse, and the real-world risks associated with deployment. CASI aims to provide a clearer, more balanced view by combining security, performance, and cost considerations into a single comparative framework.

The data is made publicly available to support transparency, independent analysis, and further research into AI security and risk.

---

## What the Metrics Represent

The dataset includes the following key metrics:

- **CASI Score**  
  A composite score intended to represent the overall security posture of an AI model. Rather than treating all failures equally, the CASI score accounts for the severity, complexity, and impact of different classes of attacks.

- **Agentic Resistance Score (ARS)**  
  Measures how well a model resists coordinated, multi-step attacks carried out by autonomous agentic systems. These attacks more closely resemble how real adversaries probe and exploit AI systems in practice.

- **Performance**  
  Aggregated results from widely used AI benchmarks, including measures of reasoning, problem solving, and code generation. These scores provide context for understanding security trade-offs relative to model capability.

- **Risk-to-Performance Ratio (RTP)**  
  A ratio that highlights the balance between a model’s security (CASI score) and its benchmark performance, helping to illustrate whether increased capability comes with disproportionate risk.

- **Cost of Security (CoS)**  
  An estimate of the relative inference cost required to achieve a given level of security, providing insight into the operational and financial implications of deploying more secure models.

---

## Methodology Overview

The data was generated using a combination of benchmark evaluation and adversarial testing:

- Standardised benchmark tests were used to establish baseline performance scores across a range of tasks.
- Automated and agent-based adversarial testing frameworks were employed to simulate real-world abuse scenarios, including prompt-based attacks and multi-step agentic strategies.
- Security outcomes were weighted and aggregated into composite metrics that reflect not just whether an attack succeeded, but how severe, repeatable, and impactful that failure was.

This methodology is intended to move beyond simplistic pass/fail measurements and provide a more realistic assessment of how AI systems behave under adversarial pressure.

---

## Source and Attribution

The structure, rationale, and high-level methodology for this dataset are based on the explainer article:

*Introducing the CASI Leaderboards*  
https://www.f5.com/labs/articles/introducing-the-casi-leaderboards
