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

- [NIST AI Risk Management Framework](https://www.nist.gov/): Framework for managing risks in AI systems
- [AI and Security Research](https://arxiv.org/list/cs.CR/recent): Latest research on AI security threats and defenses
- [Center for AI Safety](https://www.safe.ai/): Research on AI safety and security challenges
- [MIT AI Risk Initiative](https://airisk.mit.edu/): A comprehensive living database of over 1700 AI risks categorized by their cause and risk domain (broader than just cybersecurity)
- [CSA AI Research Publications](https://cloudsecurityalliance.org/research/publications?term=artificial-intelligence): Whitepapers, reports, and other resources focused on AI security

## Governance & Risk Management

### AI Risk Management Fundamentals

- Establish clear ownership and accountability for AI systems
- Document all assumptions and limitations in model development
- Implement continuous monitoring for model performance drift
- Establish incident response procedures for AI failures
- Regular third-party audits of critical AI systems

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
