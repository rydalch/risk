# AI Security & Governance

Comprehensive resources for understanding and managing security risks in artificial intelligence systems, including Large Language Models (LLMs), machine learning systems, and AI governance frameworks.

## AI Security Frameworks

### OWASP Top 10 for Large Language Models

[OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/): Identifies the most critical security risks specific to LLM implementations

  - LLM01: Prompt Injection
  - LLM02: Insecure Output Handling
  - LLM03: Training Data Poisoning
  - LLM04: Model Denial of Service
  - LLM05: Supply Chain Vulnerabilities
  - LLM06: Sensitive Information Disclosure
  - LLM07: Insecure Plugin Design
  - LLM08: Model Theft
  - LLM09: Unauthorized Code Execution
  - LLM10: Model Poisoning

### MITRE ATLAS (Adversarial Tactics, Techniques and Common Knowledge)

[MITRE ATLAS Framework](https://atlas.mitre.org/): Knowledge base of adversary tactics and techniques against AI systems

  - Focuses on real-world attacks and security testing methodologies
  - Provides guidance for red teaming AI systems
  - Maps attack chains and defensive strategies

### Cloud Security Alliance AI Security Framework

[CSA AI Security Guidance](https://cloudsecurityalliance.org/): Comprehensive AI security controls and best practices

  - Data protection and privacy considerations
  - Model governance and lifecycle management
  - Continuous monitoring and incident response
  - Supply chain security for AI/ML systems

### CSA MAESTRO AI Threat Modeling

[CSA MAESTRO Framework](https://cloudsecurityalliance.org/blog/2025/02/06/agentic-ai-threat-modeling-framework-maestro): Specialized threat modeling methodology for agentic AI systems ([GitHub Repository](https://github.com/CloudSecurityAlliance/MAESTRO))

  - **MAESTRO** = Multi-Agent Environment, Security, Threat, Risk, and Outcome
  - Seven-layer approach for agentic AI security:
    1. Foundation Models
    2. Data Operations
    3. Agent Frameworks
    4. Deployment Infrastructure
    5. Evaluation and Observability
    6. Security and Compliance
    7. Agent Ecosystem
  - Addresses AI autonomy, emergent behaviors, and multi-agent interactions
  - Complements traditional frameworks (STRIDE, PASTA, LINDDUN, OCTAVE)
  - Cross-layer threat analysis for complex AI systems

### CoSAI (Coalition for Secure AI)

[CoSAI Official Website](https://www.coalitionforsecureai.org/): An industry-led initiative to provide a collaborative ecosystem for secure AI development.
- Focuses on developing open standards and best practices for AI security.
- Provides tools like [CoSAI Wizards](https://billbrietstout.github.io/cosai-wizards/) to help navigate AI security requirements.

### Open Security Architecture (OSA)

[OSA SP-027: Generative AI Application Security Pattern](https://www.opensecurityarchitecture.org/patterns/sp-027/): Architectural pattern for securing generative AI applications.
- Provides a vendor-neutral framework for AI security controls.
- Covers data protection, model security, and application integration.

## Model Risk Management

### Federal Reserve SR 11-7 Guidance

[SR 11-7: Guidance on Model Risk Management](https://www.federalreserve.gov/supervisionreg/srletters/sr1107.htm): Foundational guidance for managing risks in model-based decision systems

  - Applicable to AI/ML models in financial institutions
  - Covers model validation, governance, and documentation
  - Emphasizes third-party risk management

### IIA AI Auditing Framework

[The Institute of Internal Auditors - AI Auditing Framework](https://www.theiia.org/): Framework for auditing AI systems and governance

  - Risk assessment methodologies for AI systems
  - Control evaluation frameworks
  - Audit procedures for algorithm transparency and bias

## Agentic AI Security

### OWASP Top 10 for Agentic AI (2026)

[OWASP Top 10 for Agentic Applications](https://owasp.org/): Critical security risks for autonomous AI systems

  - **ASI01: Agent Goal Hijack**: Manipulation of AI agent objectives through prompt injection, poisoned data, or other methods, causing unintended actions
  - **ASI02: Tool Misuse and Exploitation**: Agents exploited to misuse legitimate tools for data exfiltration, destructive actions, or other malicious purposes
  - **ASI03: Identity and Privilege Abuse**: Vulnerabilities in agent identity, delegation, or privilege inheritance leading to unauthorized access escalation
  - **ASI04: Agentic Supply Chain Vulnerabilities**: Compromised third-party components (agents, tools, models) introducing hidden instructions or unsafe behaviors
  - **ASI05: Unexpected Code Execution**: Agent-generated or agent-invoked code executing in unforeseen ways, compromising the host environment
  - **ASI06: Memory and Context Poisoning**: Corruption of persistent agent memory, RAG stores, embeddings, or shared context to influence future actions
  - **ASI07: Insecure Inter-Agent Communication**: Weaknesses in authentication, integrity, or validation enabling message spoofing and manipulation
  - **ASI08: Cascading Failures**: Single faults (hallucinations, poisoned memory, compromised tools) propagating across autonomous agents
  - **ASI09: Human-Agent Trust Exploitation**: Agents exploiting human trust, authority bias, or automation bias to influence decisions or extract information
  - **ASI10: Rogue Agents**: Agents acting harmfully and deceptively, even when individual actions appear legitimate

### AARM (Agentic AI Risk Management)

[AARM Framework](https://aarm.dev/): A comprehensive framework specifically designed for managing risks associated with autonomous and agentic AI systems.
- Focuses on the unique lifecycle and operational risks of AI agents.
- Provides practical guidance for risk identification, assessment, and mitigation in agentic workflows.

### Agentic Trust Framework

[Agentic Trust Framework](https://github.com/massivescale-ai/agentic-trust-framework): A framework for establishing trust and security in multi-agent systems.
- Addresses the complexities of autonomous agent interactions and delegation.
- Provides a structured approach to agent identity, authorization, and auditability.
- Also see: https://cloudsecurityalliance.org/blog/2026/02/02/the-agentic-trust-framework-zero-trust-governance-for-ai-agents/

### Agentic AI Security Considerations

- Implement robust goal validation and alignment mechanisms
- Establish strict tool usage policies and permission boundaries
- Use principle of least privilege for agent identity and access
- Regularly audit third-party agent components and dependencies
- Sandbox agent code execution environments
- Implement integrity checks for agent memory and context stores
- Secure inter-agent communication with strong authentication
- Monitor for cascading failures with circuit breakers
- Design human-in-the-loop controls for sensitive operations
- Establish detection mechanisms for rogue agent behavior

## Threats & Vulnerabilities

### Common AI Security Threats

- **Prompt Injection**: Crafted inputs designed to manipulate model behavior
- **Data Poisoning**: Malicious training data affecting model behavior
- **Model Extraction**: Attacks to steal or replicate proprietary models
- **Adversarial Examples**: Inputs crafted to cause model misclassification
- **Supply Chain Attacks**: Compromised dependencies or training datasets
- **Privacy Leakage**: Models memorizing and reproducing sensitive training data

### Vulnerability Assessment

- [AI Security Scanning Tools](https://github.com/topics/ai-security): Open-source tools for testing AI system security
- Red team exercises specifically designed for AI systems
- Prompt injection and jailbreak testing
- Data exfiltration attempts
- Model poisoning scenarios
- Adversarial input generation
- Bias and fairness testing
- Regulatory compliance audits
- Continuous monitoring for model drift and performance degradation

## AI Security Resources & Research

### Academic & Research Resources

- [AI and Security Research](https://arxiv.org/list/cs.CR/recent): Latest research on AI security threats and defenses
- [Center for AI Safety](https://www.safe.ai/): Research on AI safety and security challenges
- [MIT AI Risk Initiative](https://airisk.mit.edu/): A comprehensive living database of over 1700 AI risks categorized by their cause and risk domain (broader than just cybersecurity)
- [CSA AI Research Publications](https://cloudsecurityalliance.org/research/publications?term=artificial-intelligence): Whitepapers, reports, and other resources focused on AI security
- [ZeroLeaks: OpenClaw Security Assessment](https://zeroleaks.ai/reports/openclaw-analysis.pdf): Detailed red team analysis of security vulnerabilities in an open-source AI project
- [Open Source Security at Astral](https://astral.sh/blog/open-source-security-at-astral): Insights into security practices for modern open-source toolchains.
- [Cisco Foundation Sec-8B](https://blogs.cisco.com/security/foundation-sec-8b-reasoning-first-open-weight-security-reasoning-model): A reasoning-first open-weight security reasoning model for AI.

## Governance & Risk Management

### AI Risk Management

- Establish clear ownership and accountability for AI systems
- Document all assumptions and limitations in model development
- Implement continuous monitoring for model performance drift
- Establish incident response procedures for AI failures
- Regular third-party audits of critical AI systems

- [NIST AI Risk Management Framework](https://www.nist.gov/): Framework for managing risks in AI systems

### Compliance Considerations

- **GDPR**: Right to explanation for automated decisions
- **CCPA**: Consumer rights regarding data used in AI models
- **Fair Lending Laws**: Bias detection in credit/lending AI systems
- **EU AI Act**: Various requirements based on risk level of AI system

## Related Documentation

- [Risk Assessment Methods](./risk-methods.md) - General risk assessment frameworks
- [Security Testing & Tools](./security.md) - Security testing methodologies
- [Threat Modeling](./threat-modeling.md) - Threat identification and analysis
- [Cloud Security](./cloud-security.md) - Cloud-specific AI deployment considerations
