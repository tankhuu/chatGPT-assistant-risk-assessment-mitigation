- https://arxiv.org/html/2401.11641v1
  - [Design and Implementation of an LLM system to Improve Response Time for SMEs Technology Credit Evaluation](https://koreascience.kr/article/JAKO202329158308485.page)
    - credit assessment: Credit Scoring for SMEs (Small and/or Medium Enterprise)
  - [GPT Classifications, with Application to Credit Lending](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4649285)
    - Credit Scoring
    - Compare to Logistic Regression
  - [The Effects of Class Imbalance and Training Data Size on Classifier Learning: An Empirical Study](https://link.springer.com/article/10.1007/s42979-020-0074-0)
  - [Empowering Many, Biasing a Few: Generalist Credit Scoring through Large Language Models](https://arxiv.org/abs/2310.00566)
  - [AI-powered Fraud Detection in Decentralized Finance: A Project Life Cycle Perspective](https://arxiv.org/abs/2308.15992)
  - [Deep learning detecting fraud in credit card transactions](https://ieeexplore.ieee.org/document/8374722)
  - [PAYSIM: A FINANCIAL MOBILE MONEY SIMULATOR FOR FRAUD DETECTION](https://www.msc-les.org/proceedings/emss/2016/EMSS2016_249.pdf)
- https://www.mdpi.com/2071-1050/15/22/16071
- https://www.mdpi.com/2227-9091/11/9/166
- https://www.signitysolutions.com/blog/llms-in-finance-and-banking
  - good explaination about the purpose & benefits of using llm in risk assessment & management
- https://www.acorn.io/resources/learning-center/llm-security
  - the risk of LLM itself, not talking about the usage of LLM in banking or risk assessment, ...
- https://arxiv.org/html/2404.07452v1
- [Enhancing Credit Risk Reports Generation using LLMs: An Integration of Bayesian Networks and Labeled Guide Prompting](https://dl.acm.org/doi/fullHtml/10.1145/3604237.3626902)
- https://www.pacificdataintegrators.com/blogs/risk-assessment-and-investment-research-with-llms-in-finance
- https://www.shaip.com/blog/llm-in-banking-and-finance/
- [HOw to Seamlessly Integrate LLMs In Your Digital Banking Operations](https://www.venturedive.com/blog/large-language-models-banking-fis/)
- [Managing the risk of Large Language Models (LLMs) in Financial Services](https://truera.com/managing-the-risk-of-large-language-models-llms-in-financial-services/)
- https://www.getdynamiq.ai/post/generative-ai-and-llms-in-banking-examples-use-cases-limitations-and-solutions
- https://www.cfo.com/news/do-you-spend-enough-time-assessing-strategic-risks/655164/
- https://www.ncontracts.com/nsight-blog/creating-reliable-risk-assessments
- https://resources.probe42.in/learn-with-probe/risk-assessment-tools-in-banking-and-finance/
- https://www.savecg.com/en/risk-assessment-what-it-is-and-why-it-is-important-for-banks/
- https://www.hyperstack.cloud/blog/case-study/exploring-risk-assessment-with-machine-learning-in-finance
- https://www.unit21.ai/blog/risk-management-in-banking
- 


# Book

- [Risk Management in Banking](https://books.google.com.vn/books?hl=en&lr=&id=oq-MAjw2ezQC&oi=fnd&pg=PT19&dq=banking+risk+assessment+and+mitigation&ots=Creztyu0t7&sig=R7xzJoMDr_z6mU-9uf4Xj3sttzg&redir_esc=y#v=onepage&q=banking%20risk%20assessment%20and%20mitigation&f=falses)
- [Mitigation Banking: Theory And Practice](https://books.google.com.vn/books?hl=en&lr=&id=hMl5LPZNyKEC&oi=fnd&pg=PR2&dq=banking+risk+assessment+and+mitigation&ots=VofZmz4roj&sig=Kdwk4pLIT9cN7fgz3kCxr6C4mIc&redir_esc=y#v=onepage&q=banking%20risk%20assessment%20and%20mitigation&f=false)
- [Assessment and mitigation of credit risks in project financing](https://www.businessperspectives.org/images/pdf/applications/publishing/templates/article/assets/13205/BBS_2020_01_Naumenkova.pdf)
- https://www.pacificdataintegrators.com/hubfs/Website-Whitepapers/The%20PDI%20Guide%20to%20Gen%20AI%20in%20Finance.pdf
  - [Real-time Monitoring: The Future of Fraud Prevention](https://www.datavisor.com/wiki/real-time-monitoring/)
  - [Fraud & Risk Platform](https://www.datavisor.com/products/fraud-platform/)
- [OPERATIONAL RISKS: ASSESSMENT AND WAYS OF MITIGATION](http://pte.diit.edu.ua/index.php/2310-2438/article/view/151919)
- [Bank Agents: Risk Management,
Mitigation, and Supervision](https://www.mfw4a.org/sites/default/files/resources/Bank%20Agents%20-%20Risk%20Management,%20Mitigation,%20and%20Supervision.pdf)
- [Application of Artificial Intelligence in Risk Assessment and Mitigation in Banks - Not Free](https://onlinelibrary.wiley.com/doi/epdf/10.1002/9781394175574.ch2)

# Project

- https://github.com/The-FinAI/CALM: CALM is a project aimed at utilizing LLMs for credit and risk assessment in the financial industry. It offers a comprehensive benchmark and instruction datasets, fine-tuning methods, and bias analysis tools tailored for credit scoring, fraud detection, financial distress identification, and claim analysis.
- [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness): This project provides a unified framework to test generative language models on a large number of different evaluation tasks.
  - Features:
    - Over 60 standard academic benchmarks for LLMs, with hundreds of subtasks and variants implemented.
    - Support for models loaded via transformers (including quantization via GPTQModel and AutoGPTQ), GPT-NeoX, and Megatron-DeepSpeed, with a flexible tokenization-agnostic interface.
    - Support for fast and memory-efficient inference with vLLM.
    - Support for commercial APIs including OpenAI, and TextSynth.
    - Support for evaluation on adapters (e.g. LoRA) supported in HuggingFace's PEFT library.
    - Support for local models and benchmarks.
    - Evaluation with publicly available prompts ensures reproducibility and comparability between papers.
    - Easy support for custom prompts and evaluation metrics.
    - The Language Model Evaluation Harness is the backend for 🤗 Hugging Face's popular Open LLM Leaderboard, has been used in hundreds of papers, and is used internally by dozens of organizations including NVIDIA, Cohere, BigScience, BigCode, Nous Research, and Mosaic ML.

# Summary for Research Proposal

**Developing an AI ChatBot with LLM is likely we're training an asisstant which won't failed in human mistakes, super high memory, learn from the best knowledge and can be trained (fine-tuned) with a specific domain knowledge using smaller effort and data set, and provide the quality of suggestion with equal and higher quality day by day.**
The suggestion don't have to wait for expert data scientists to analyse company data, waiting for many triage, experimenting, which is the most time consuming cost for company util we can get the Risk Assessment result from there, LLM can inherit all of the benefits of the super pre-trained models, combine with the significant valuable info of company and provide the good answer for risk assessment, also saving many time and cost on expert data science team.

Use traditional ML models as baselines.
Compare with LLM.


Use Tools for more good functions of this AI: (Tools & Agents)
- fetch data/ add more knowledge / context (RAG)
- Take action: booking meeting, set calendar, alarms, notification, ...
- Perform calculation
- Modify UI


# Current solutions

- https://www.linkedin.com/pulse/risk-mitigation-banking-tools-techniques-best-cristina-firica-mba-zniif/
  - Types of Risks in Banking
    - Credit Risk
    - Market Risk
    - Operational Risk
    - Liquidity Risk
    - Compliance Risk
  - Tools for Risk Mitigation
    - Credit Scoring Models
    - Value-at-Risk (VaR) Models
    - Stress Testing and Scenario Analysis
    - Operational Risk Management (ORM) Tools
- https://www.intuition.com/operational-risk-management-for-the-banking-industry/
  - https://www.intuition.com/what-is-a-risk-management-framework/
  - Operational risk categories
    - Internal fraud
    - External fraud
    - Employment practices & workplace safety
    - Clients, products, & business practices
- https://www.fatf-gafi.org/en/publications/Fatfrecommendations/Risk-based-approach-banking-sector.html
- https://www.metricstream.com/risk-management-in-banking.html