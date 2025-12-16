# Cloud Security

Resources for securing cloud infrastructure and deployments across major cloud providers.

## Cloud Provider Security Resources

### Amazon Web Services (AWS)

- [AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/): Framework for secure AWS architecture
- [AWS Security Hub](https://aws.amazon.com/security-hub/): Centralized security findings and compliance monitoring
- [AWS Identity and Access Management](https://aws.amazon.com/iam/): IAM policies, roles, and permission management
- **Key Services**: VPC, Security Groups, IAM, KMS, Secrets Manager, GuardDuty, Config

### Google Cloud Platform (GCP)

- [GCP Security Best Practices](https://cloud.google.com/security/best-practices): Security guidance and recommendations
- [Google Cloud Trust & Security](https://cloud.google.com/security): Comprehensive security documentation
- [Cloud IAM Documentation](https://cloud.google.com/iam/docs): Identity and access management
- **Key Services**: VPC, Firewall Rules, Cloud IAM, Secret Manager, Security Command Center

### Microsoft Azure

- [Azure Security Best Practices](https://docs.microsoft.com/en-us/azure/security/): Azure security guidance
- [Azure Trust Center](https://www.microsoft.com/en-us/trustcenter): Compliance and security information
- [Azure RBAC Documentation](https://docs.microsoft.com/en-us/azure/role-based-access-control/): Role-based access control
- **Key Services**: Virtual Networks, Network Security Groups, Azure AD, Key Vault, Security Center

## Cloud Security Frameworks & Standards

### Cloud Security Alliance (CSA)

- [CSA Cloud Controls Matrix](https://cloudsecurityalliance.org/research/cloud-controls-matrix/): Comprehensive security control framework for cloud
- [CSA Cloud Security Guidance](https://cloudsecurityalliance.org/research/guidance): Security best practices and recommendations and mapping to ISO 27001, NIST, and other standards


## Cloud Security Tools & Services

### Configuration & Compliance Scanning

- [CloudMapper](https://github.com/duo-labs/cloudmapper): Helps identify insecure configurations in AWS
- [Prowler](https://github.com/prowler-cloud/prowler): Security assessment tool for AWS and GCP
- [Trivy](https://github.com/aquasecurity/trivy): Vulnerability scanner for containers and IaC
- [Checkov](https://www.checkov.io/): Infrastructure as code security scanning

### Runtime Security & Threat Detection

- AWS GuardDuty: Intelligent threat detection for AWS accounts
- Google Cloud Security Command Center: Security threat detection and response
- Azure Advanced Threat Protection: Behavioral analytics and threat detection
- [Falco](https://falco.org/): Container runtime security tool


## Basic Cloud Security Practices

### Access Control

- Use service accounts and roles instead of long-term credentials
- Implement MFA for all cloud accounts and administrative access
- Regularly audit and revoke unnecessary permissions
- Use temporary credentials with automatic expiration
- Implement cross-account access controls for multi-account architectures

### Data Protection

- Enable encryption for all data at rest using managed key services
- Use TLS 1.2+ for all data in transit
- Implement key rotation policies
- Use client-side encryption for highly sensitive data
- Enable versioning and implement backup/disaster recovery

### Monitoring & Logging

- Enable comprehensive logging for all cloud resources (CloudTrail, Stackdriver, etc.)
- Aggregate logs to centralized SIEM or logging service
- Implement real-time alerting for security events
- Maintain audit logs for compliance requirements
- Regularly review and analyze logs for anomalies

### Infrastructure Security

- Use Infrastructure as Code (IaC) with security validation
- Implement network segmentation and micro-segmentation
- Use Web Application Firewalls (WAF) for public-facing applications
- Enable DDoS protection for critical resources
- Regular security assessments and penetration testing

### Application Security

- Scan container images for vulnerabilities
- Implement secrets management for API keys and credentials
- Use service meshes for traffic encryption and authorization
- Implement runtime security policies
- Regular application dependency scanning

## Cloud Security Incident Response

- Establish cloud-specific incident response procedures
- Document and test playbooks for common cloud security incidents
- Ensure forensic capabilities and logging for investigation
- Plan for rapid resource isolation and remediation
- Coordinate with cloud provider support teams


## Related Documentation

- [Security Testing & Tools](./security.md) - General security testing methodologies
- [Risk Assessment Methods](./risk-methods.md) - Risk assessment frameworks
- [AI Security](./ai-security.md) - AI security in cloud environments
- [Frameworks & Standards](./frameworks.md) - Security frameworks and standards
