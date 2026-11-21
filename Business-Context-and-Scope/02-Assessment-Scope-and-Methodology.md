# NovaCart Retail Ltd.
# Cybersecurity Risk Assessment – Scope and Methodology

**DOCUMENT 02 · ASSESSMENT PLANNING**

| Document Information | Details |
|---|---|
| Document classification | Internal – Confidential |
| Document owner | Governance, Risk and Compliance (GRC) |
| Organisation | NovaCart Retail Ltd. |
| Version | 1.0 |
| Assessment period | November–December 2026 |
| Framework reference | NIST Cybersecurity Framework 2.0 |

## 1. Purpose of the Assessment

The purpose of this cybersecurity risk assessment is to identify, analyse, evaluate, and document information security risks that may affect NovaCart Retail Ltd.'s business operations, technology infrastructure, and information assets.

The assessment will provide management with an understanding of the organisation's cybersecurity risk exposure and the effectiveness of its existing security measures, based on the information and evidence made available during the assessment.

The results will support risk-based decision-making by identifying areas requiring additional security controls, improvements to existing processes, or other risk treatment actions. The assessment will also provide a structured foundation for ongoing cybersecurity risk monitoring and governance.

## 2. Assessment Objectives

The assessment will focus on identifying critical business and information assets, understanding their associated threats and vulnerabilities, and evaluating the potential consequences of security incidents.

It will also examine existing security controls to determine whether they are appropriately designed and supported by sufficient evidence of implementation and operation. Identified risks will be evaluated using defined likelihood and impact criteria, allowing them to be prioritised according to their potential effect on the organisation.

The assessment will ultimately produce a cybersecurity risk register and risk treatment plan that management can use to assign responsibilities, prioritise remediation activities, and monitor outstanding cybersecurity risks.

## 3. Assessment Scope and Boundaries

The assessment will cover the information systems, business processes, and technology dependencies that support NovaCart's e-commerce operations.

The in-scope environment includes the customer-facing website and mobile application, AWS-hosted infrastructure, customer information repositories, employee accounts and endpoints, CRM and ERP platforms, external payment integrations, third-party logistics and marketing services, and supporting backup and incident response processes.

The assessment will consider risks associated with the organisation's use of external service providers. However, it will not independently assess the internal security environments of those providers. Risks arising from third-party dependencies will be considered from NovaCart's perspective, including its contractual arrangements, supplier oversight, data-sharing practices, and reliance on external services.

Technical penetration testing, source-code reviews, physical security inspections, and formal regulatory certification activities are excluded from the assessment. Where these activities may be necessary to establish the organisation's risk exposure, the assessment will document them as recommended follow-up activities.

## 4. Assessment Approach

The assessment will follow a structured, evidence-based risk assessment approach. The GRC analyst will initially review the business information, system descriptions, existing security documentation, and historical incident information supplied for the assessment.

Following the initial review, the analyst will identify information gaps and request additional evidence from relevant business and technology stakeholders. This may include access control policies, asset inventories, vulnerability assessment reports, incident records, backup testing results, supplier security assessments, and security monitoring documentation.

Identified risks will first be evaluated using the information available at the beginning of the assessment. Following the review of additional evidence, the analyst will reassess relevant risks to determine whether the original risk ratings remain appropriate or require adjustment.

This approach will preserve the original assessment findings and provide traceability between evidence received, control observations, risk ratings, and treatment recommendations. Initial and updated risk assessments will be maintained separately, with changes recorded and supported by documented reasons.

## 5. Risk Identification Methodology

Risk identification will consider the relationship between business assets, potential threat events, vulnerabilities, existing security controls, and possible business consequences.

The analyst will identify assets that support important business activities and determine how their confidentiality, integrity, and availability could be affected by cybersecurity incidents.

Potential threats may include phishing, ransomware, unauthorised access, data exposure, malicious software, service disruption, and third-party security incidents. Vulnerabilities may include inadequate access restrictions, insufficient authentication controls, unpatched systems, weak monitoring, and ineffective supplier oversight.

Each identified risk will be documented as a business-relevant risk statement describing the potential event, its underlying cause, and its possible consequences. Risk statements will be linked to relevant assets, threats, vulnerabilities, control observations, and supporting evidence wherever available.

## 6. Risk Analysis Methodology

NovaCart will use a qualitative 5 × 5 risk assessment methodology for this portfolio case study. The methodology is designed to provide a consistent and repeatable approach to evaluating identified risks.

Risk likelihood will be assessed on a scale of 1 to 5, considering the probability of a threat event occurring within the organisation's operating environment. Risk impact will also be assessed on a scale of 1 to 5, considering the potential consequences for business operations, information confidentiality, data integrity, financial performance, customer trust, and applicable legal or regulatory obligations.

The overall risk score will be calculated by multiplying the likelihood score by the impact score.

**Risk Score = Likelihood × Impact**

The resulting score will be used to assign a risk classification according to the thresholds defined in this document. This scoring model is a project-defined qualitative assessment method and is not presented as a scoring model prescribed by NIST CSF 2.0.

### 6.1 Likelihood Rating Criteria

| Score | Rating | Description |
|---:|---|---|
| 1 | Rare | Very unlikely to occur under normal operating conditions. |
| 2 | Unlikely | Could occur, but is not expected in most circumstances. |
| 3 | Possible | May occur under certain circumstances. |
| 4 | Likely | Expected to occur in many circumstances. |
| 5 | Almost Certain | Expected to occur frequently or repeatedly. |

Likelihood ratings should consider relevant threat activity, known incidents, exposure of the affected asset, existing safeguards, and the available evidence. Where reliable information is unavailable, the rating and its supporting rationale must identify the uncertainty.

### 6.2 Impact Rating Criteria

| Score | Rating | Description |
|---:|---|---|
| 1 | Insignificant | Negligible business impact with minimal disruption. |
| 2 | Minor | Limited disruption or loss that can be recovered from easily. |
| 3 | Moderate | Noticeable operational or financial impact requiring management attention. |
| 4 | Major | Significant operational disruption, financial loss, or reputational damage. |
| 5 | Severe | Critical business disruption or substantial consequences affecting the organisation, customers, or important business obligations. |

Impact ratings should consider the potential consequences for confidentiality, integrity, availability, operational continuity, financial performance, customer trust, and applicable legal or contractual obligations.

### 6.3 Risk Rating Classification

The following risk classification will be applied consistently throughout the project.

| Risk Score | Risk Level | Interpretation |
|---:|---|---|
| 1–4 | Low | Risk is relatively limited and should be managed through routine security practices and monitoring. |
| 5–9 | Medium | Risk requires appropriate management attention and planned control improvements where necessary. |
| 10–16 | High | Risk requires prioritised treatment and regular management oversight. |
| 17–25 | Critical | Risk requires urgent management attention and prioritised action. |

### 6.4 Risk Likelihood and Impact Matrix

The following 5 × 5 matrix illustrates how likelihood and impact scores combine to determine the overall risk score and classification.

**Figure 1 – Cybersecurity Risk Assessment Matrix**

| Likelihood ↓ / Impact → | 1 – Insignificant | 2 – Minor | 3 – Moderate | 4 – Major | 5 – Severe |
|---|---:|---:|---:|---:|---:|
| **5 – Almost Certain** | 5 – Medium | 10 – High | 15 – High | 20 – Critical | 25 – Critical |
| **4 – Likely** | 4 – Low | 8 – Medium | 12 – High | 16 – High | 20 – Critical |
| **3 – Possible** | 3 – Low | 6 – Medium | 9 – Medium | 12 – High | 15 – High |
| **2 – Unlikely** | 2 – Low | 4 – Low | 6 – Medium | 8 – Medium | 10 – High |
| **1 – Rare** | 1 – Low | 2 – Low | 3 – Low | 4 – Low | 5 – Medium |

**How to interpret the matrix:** Select the likelihood rating from the left-hand column and the impact rating from the top row. Their intersection provides the overall risk score and classification. For example, a likelihood rating of 4 (Likely) and an impact rating of 5 (Severe) produces a score of 20, which is classified as Critical.

The matrix will be used to support consistent risk prioritisation. It does not replace professional judgement, documented risk rationale, or management review.

## 7. Inherent and Residual Risk Assessment

Inherent risk refers to the level of risk before considering the effect of existing security controls. It represents the organisation's exposure to a potential threat event based on the relevant assets, threats, vulnerabilities, and business consequences.

Residual risk refers to the risk remaining after existing controls and their demonstrated effectiveness have been considered. The analyst must evaluate available evidence before concluding that a control reduces the likelihood or impact of a risk.

Where sufficient evidence is unavailable, control effectiveness and residual risk will be recorded as unverified or pending assessment rather than assumed to be effective. Any residual risk rating must include a documented rationale explaining how the evaluated controls influence the likelihood or impact assessment.

## 8. Risk Treatment Methodology

Following risk evaluation, each identified risk will be assigned a proposed treatment approach based on its severity, business importance, and management considerations.

The assessment will consider four recognised risk treatment options:

**Risk Mitigation:** Implementing or improving security controls to reduce the likelihood or impact of a risk to an acceptable level.

**Risk Avoidance:** Discontinuing an activity or changing a business process to eliminate the associated risk.

**Risk Transfer:** Transferring certain financial or contractual consequences to another party, for example through insurance or contractual arrangements. The underlying cybersecurity risk may still remain with the organisation.

**Risk Acceptance:** Formally acknowledging and accepting a risk within the organisation's approved risk tolerance. Risk acceptance decisions will require approval from an authorised risk owner or management representative. The GRC analyst may recommend acceptance but must not represent an unapproved recommendation as a formal management decision.

Treatment actions will be documented with assigned owners, target completion dates, implementation priorities, and expected outcomes. Risks will be reassessed when treatment activities have been completed and sufficient evidence is available.

## 9. Roles and Responsibilities

The assessment will involve collaboration between the GRC function, IT department, information security personnel, business stakeholders, and relevant third-party relationship owners.

The GRC analyst will coordinate the assessment, review documentation, identify and analyse risks, maintain the risk register, and prepare treatment recommendations. The IT and security teams will provide relevant technical information and supporting evidence. Business stakeholders will explain operational dependencies and potential business impacts.

Risk owners will be responsible for reviewing assigned risks, agreeing on appropriate treatment actions, and monitoring remediation progress. Management will provide oversight and approve significant risk treatment and acceptance decisions according to the organisation's governance arrangements.

## 10. Assessment Limitations and Assumptions

This assessment is based on fictional organisational information created for educational and portfolio purposes. The completeness and accuracy of the assessment will depend on the information and supporting evidence made available during the exercise.

Where information is unavailable, the analyst will document assumptions, limitations, and outstanding evidence requirements. Risk ratings may change when additional evidence becomes available. Any simulated evidence created for this portfolio will be clearly identified as fictional and will not be represented as genuine organisational records.

The assessment does not constitute an independent audit, penetration test, legal opinion, or certification of compliance with any cybersecurity framework or regulatory requirement. Regulatory obligations will require further consideration of the countries in which NovaCart operates, the locations of its customers, and the relevant data-processing activities.

## 11. Framework Reference

The assessment will use the NIST Cybersecurity Framework 2.0 as a reference for organising cybersecurity risk management activities. Relevant CSF functions and outcomes will be mapped to identified risks, existing controls, identified gaps, and proposed treatment activities.

The framework reference will support structured analysis and communication of cybersecurity activities. It will not be used to claim that NovaCart is certified or fully compliant with NIST CSF 2.0.

## 12. Document Review and Maintenance

This document establishes the assessment boundaries, objectives, and methodology that will guide the development of the cybersecurity risk register. Any material changes to the assessment scope, risk scoring criteria, or methodology will be documented and reviewed to maintain consistency across the project.

The document will be reviewed when significant new information affects the assessment approach or when changes to the project assumptions require the methodology to be updated.
