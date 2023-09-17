# Security of AI

# Security Controls 
- OWASP AI Security and Privacy Guide 
- OWASP Top 10 for LLM: promopt injection, insecure output handling, training data poisioning, DOS, supply chain risk, access permissions, data leakage,  excessive agenctm overreliance, insecure plugins https://owasp.org/www-project-top-10-for-large-language-model-applications/assets/PDF/OWASP-Top-10-for-LLMs-2023-v05.pdf

# Risk Managment Framework
- Artificial Intelligence Risk Management Framework (AI RMF 1.0) https://nvlpubs.nist.gov/nistpubs/ai/nist.ai.100-1.pdf
- LLM OWASP Top 10: Very useful, but some of them are a stretch. Currently at v0.5  https://owasp.org/www-project-top-10-for-large-language-model-applications/assets/PDF/OWASP-Top-10-for-LLMs-2023-v05.pdf
- Prompt injection methods: GitHub - greshake/llm-security: New ways of breaking app-integrated LLMs 
- Skyflow data privacy for GPT: https://www.skyflow.com/post/generative-ai-data-privacy-skyflow-gpt-privacy-vault
- Daniel Miessler on AI Attack Surface Map: https://danielmiessler.com/blog/the-ai-attack-surface-map-v1-0/
- Generative AI: 5 Guidelines for Responsible Development - Salesforce
- Nvidia’s AI red team framework: :https://developer.nvidia.com/blog/nvidia-ai-red-team-an-introduction/
- IBM AI fairness 360 tools to detect bias: https://www.ibm.com/opensource/open/projects/ai-fairness-360/ -
- tldrsec on a similar topic: How to securely build product features using AI APIs (tldrsec.com)


# Risk areas & tools 
- Rebuff: A self-hardening prompt injection detector.
- LLMFuzzer: A fuzzing framework for LLMs.
- LLM Guard: A security toolkit for LLM interactions ,open source LLM Firewall
- LLM Gateway: Helps ensure that data being fed into and output from the LLM tool is free of proprietary company data.
- Data leakage, Inadequate sandboxing
- LLM vulnerability scanner - garak https://github.com/leondz/garak
- Arthur Shield: The First Firewall for LLMs
- Lakera is an AI security company. They have specific products to protect against Prompt injection: Lakera Guard | Unlock LLMs for Production | Lakera – Protecting AI teams that disrupt the world. 

# AI Security for Enterprise
- Enterprise architectures for LLMs (a16z)
- Corporate GenAI policies gartner
- Gandalf chatbot security game counters privacy fireballs
- Should you buy or build: When it comes to large language models, should you build or buy? | TechCrunch
- Companies blocking ChatGPT and other publicly trained chatbots: Employees are banned from using ChatGPT at these companies | Fortune
- Google thinks open source LLMs will be as good as OpenAI soon: Google’s Leaked Document Reveals Open Source Threat: A New Era in Language Models | BigTechWire
- Triveto language model whitepaper: https://www.truveta.com/wp-content/uploads/2023/04/Truveta-Language-Model.pdf
- 
# Playgrounds
- Aviary Explorer: A way to compare results from open source LLMs: Aviary Explorer (anyscale.com)
- A playground for prompt injection. Basically tricking LLMs in revealing secrets https://gandalf.lakera.ai/
- Holistic evaluation of LLMs (HELM) from Stanford: https://crfm.stanford.edu/helm/latest/ 
