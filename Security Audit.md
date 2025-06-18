# Botium Toys – Internal Security Audit

## Activity Overview

This internal audit was conducted as part of the Google Cybersecurity Certificate Program. The activity focused on evaluating the current security posture of Botium Toys and identifying missing controls or compliance gaps that could pose risks to operations, data, or customer privacy.

Audits are essential for proactively detecting vulnerabilities, monitoring for risk, and ensuring that security protocols are properly implemented. This report includes the scope and goals of the audit, the current state of controls and compliance, and recommended improvements.

## Scenario

Botium Toys is a fictional U.S.-based toy company with one physical location that serves as a main office, storefront, and product warehouse. The business has recently expanded its online presence and now serves customers in the U.S. and Europe.

The IT manager has initiated an internal audit to identify gaps in their security controls and ensure compliance with industry standards such as PCI DSS, GDPR, and SOC 1/SOC 2.

## Scope and Goals

**Scope**  
The audit covers all aspects of the security program, including:
- Employee and on-premises equipment
- Internal systems and infrastructure
- Data handling processes
- Network and legacy systems
- Compliance with relevant regulations

**Goals**  
- Assess the presence and effectiveness of cybersecurity controls  
- Evaluate compliance with U.S. and international standards  
- Identify risks or gaps that may impact business continuity  
- Provide actionable recommendations for improvement

## Current Asset Overview

Assets managed by Botium Toys' IT department include:
- On-site equipment and end-user devices (e.g., desktops, laptops, smartphones)
- Internal network infrastructure and internet access
- Business-critical systems (ecommerce, accounting, inventory, telecommunication)
- Legacy systems requiring manual monitoring
- Physical security: locks, CCTV surveillance, and fire prevention systems
- Customer data retention and storage

## Risk Assessment Summary

The company received a **risk score of 8 out of 10**, indicating a high level of vulnerability due to several missing or incomplete controls. The following key risks were identified:

- Lack of least privilege and separation of duties
- No encryption of stored or transmitted credit card data
- No intrusion detection system (IDS)
- No backups or disaster recovery plan
- Password policy is weak and not centrally enforced
- No asset classification for data management
- Manual legacy system oversight without formal scheduling

While some protective measures exist—such as a firewall, antivirus software, physical locks, and CCTV—the lack of core security practices exposes the company to potential data breaches, non-compliance penalties, and business disruptions.

## Recommendations Summary

To reduce risk and improve Botium Toys' security posture, the following actions are recommended:

1. **Implement least privilege access controls** and formal separation of duties.
2. **Deploy a centralized password management system** with strong enforcement policies.
3. **Encrypt all sensitive customer and payment data**, both at rest and in transit.
4. **Establish regular backups** and a formal disaster recovery plan.
5. **Deploy an intrusion detection system (IDS)** for real-time network monitoring.
6. **Classify and inventory all data assets**, aligning with GDPR and SOC standards.
7. **Formalize legacy system monitoring**, with defined schedules and documentation.

## Controls and Compliance Checklist


### Summary of Key Responses

**Controls**  
- Least Privilege: No  
- Disaster Recovery Plan: No  
- Password Policy: Yes (nominal)  
- IDS: No  
- Encryption: No  
- Antivirus: Yes  
- Firewall: Yes  
- Backups: No  

**Compliance (PCI DSS & GDPR)**  
- Authorized access to card data: No  
- Credit card processing in secure environment: No  
- Data encryption: No  
- EU data breach notification plan: Yes  
- Data classification and privacy enforcement: Partial

**Recomentation to Stake Holders:**

To reduce risks to critical assets and enhance Botium Toys’ overall security posture, it is recommended that the IT manager prioritize implementing least privilege access controls and a separation of duties to limit unnecessary data exposure. Immediate steps should include establishing a formal disaster recovery plan, deploying an intrusion detection system (IDS), and introducing encryption for all stored and transmitted customer data. Strengthening the current password policy and adopting a centralized password management system will further reduce vulnerabilities and improve user authentication. These improvements will not only align the company with industry standards such as PCI DSS, GDPR, and SOC 2 but also demonstrate a proactive commitment to protecting customer information and supporting business continuity.

## Files Included
 
- [`audit-recommendations.md` ](https://docs.google.com/document/d/1s2u_RuhRAI40JSh-eZHvaFsV1ZMxcNSWXifHDTOsgFc/template/preview#heading=h.evidx83t54sc)– Provided Security Audit 
- [`controls-compliance-checklist.docx](https://docs.google.com/document/d/1LURHx3pt6gAjdxldJ9itrZ2QjygNABcTzmmSlbXgNNk/edit?usp=sharing)` – Full checklist with responses  

---

This report demonstrates practical skills in auditing, identifying risks, and aligning organizational controls with frameworks like NIST CSF, PCI DSS, and GDPR.
