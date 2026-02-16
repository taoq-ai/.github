<div align="center">

# TaoQ AI Labs 🧘

### Advanced AI Engineering | Applied Research | Machine Learning

[![Website](https://img.shields.io/badge/Website-taoq.ai-blue)](https://taoq.ai)
[![GitHub](https://img.shields.io/badge/GitHub-taoq--ai-181717?logo=github)](https://github.com/taoq-ai)

**Building secure, trustworthy AI systems with a focus on MLOps and production deployment**

</div>

---

## 🎯 Mission

TaoQ AI Labs is dedicated to advancing the state of AI engineering through rigorous research, open-source development, and a commitment to security-first principles. We focus on bridging the gap between cutting-edge AI research and production-ready systems that organizations can trust and deploy with confidence.

Our work emphasizes:

- **AI Agent Security** — Pioneering research and tooling for securing AI agents with tools, memory, and multi-step reasoning
- **MLOps Excellence** — Building robust frameworks for monitoring, deploying, and scaling machine learning systems
- **Production AI** — Developing practical solutions for real-world AI deployment challenges
- **Applied Research** — Translating academic advances into production-grade tools and methodologies

---

## 🚀 Projects

### [ZIRAN](https://github.com/taoq-ai/ziran) 🧘

**AI Agent Security Testing Framework**

[![PyPI](https://img.shields.io/pypi/v/ziran.svg)](https://pypi.org/project/ziran/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/taoq-ai/ziran/blob/main/LICENSE)
[![Python 3.11+](https://img.shields.io/badge/python-3.11%2B-blue.svg)](https://www.python.org/downloads/)

ZIRAN is the first comprehensive security testing framework specifically designed for AI agents — not just LLMs, but complete agentic systems with tools, memory, and complex reasoning chains.

**Key Features:**
- 🔍 **Tool Chain Analysis** — Detects dangerous tool combinations (e.g., `read_file` → `http_request` = data exfiltration)
- 🎯 **Multi-Phase Trust Exploitation** — Progressive attack campaigns that mimic real attacker behavior
- 🕸️ **Knowledge Graph Tracking** — Every capability, relationship, and attack path tracked in a live graph
- 🌐 **Remote Agent Scanning** — Test any published agent over HTTPS with support for REST, OpenAI, MCP, and A2A protocols
- 🔗 **Framework Agnostic** — Works with LangChain, CrewAI, MCP, or custom implementations
- 🛡️ **CI/CD Integration** — Use as a security quality gate in your deployment pipeline

```bash
pip install ziran
ziran scan --framework langchain --agent-path my_agent.py
```

[Documentation](https://taoq-ai.github.io/ziran/) | [Examples](https://github.com/taoq-ai/ziran/tree/main/examples)

---

## 🌟 Research Areas

Our research spans multiple domains at the intersection of AI safety, security, and operational excellence:

- **Agent Security** — Vulnerability detection in multi-agent systems and tool-using AI
- **Trust & Safety** — Building reliable evaluation frameworks for AI systems
- **MLOps** — Continuous deployment, monitoring, and improvement of ML models
- **AI Red Teaming** — Adversarial testing methodologies for production AI systems
- **OWASP AI Security** — Contributing to industry standards for AI application security

---

## 🤝 Community

We believe in open collaboration and knowledge sharing:

- **Open Source** — Our projects are released under permissive licenses (Apache 2.0)
- **Contributions Welcome** — We actively encourage community contributions
- **Security Research** — Submit Skill CVEs and attack vectors to improve AI safety
- **Knowledge Sharing** — Documentation, examples, and best practices freely available

---

## 📚 Learn More

- **Website:** [taoq.ai](https://taoq.ai)
- **GitHub:** [github.com/taoq-ai](https://github.com/taoq-ai)
- **ZIRAN Docs:** [taoq-ai.github.io/ziran](https://taoq-ai.github.io/ziran/)

---

## 📬 Contact

Interested in collaborating, contributing, or learning more about our work?

- Open an issue in one of our repositories
- Check out our [contribution guidelines](https://github.com/taoq-ai/ziran/blob/main/CONTRIBUTING.md)
- Visit [taoq.ai/about](https://taoq.ai/about) for more information

---

<p align="center">
  <strong>Building the future of secure, trustworthy AI</strong>
</p>