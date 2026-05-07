AI Risk Assessment Template

Status: In Progress — Target completion Q3 2026

A practitioner-built framework for assessing AI risk in regulated environments. Maps NIST AI RMF 1.0 + ISO/IEC 42001 controls to GRC language enterprises already use — so compliance teams, auditors, and risk managers can evaluate AI systems without first becoming AI engineers.

The Problem This Solves
Most AI risk assessment frameworks are written for one of two audiences: AI engineers who understand the technology but not the regulatory exposure, or compliance theorists who understand the frameworks but not how to operationalize them.
Neither works in a regulated environment with real audit timelines, real vendor contracts, and real boards asking real questions.
This template is built for the people in the middle — GRC practitioners, security managers, and risk officers who need to assess AI systems using the frameworks they already know and the audit language they already speak.

What It Will Include
Model Risk Translation Table
Maps NIST AI RMF GOVERN, MAP, MEASURE, and MANAGE functions to ISO/IEC 42001 controls and to the GRC control language enterprises already use (NIST CSF, ISO 27001, SOX-adjacent frameworks). Eliminates the translation step that slows down every regulated-environment AI assessment.
AI Risk Assessment Template (filled example)
A completed sample assessment for a hypothetical enterprise AI deployment — showing how to document training data provenance, drift monitoring, edge case scope, and accountability ownership in audit-ready language.
AI Vendor Risk Questionnaire Module
25-question due diligence framework for evaluating third-party AI vendors. Addresses the gap left by pre-2023 vendor contracts that predate AI capability: training data disclosure, model update notification, contractual audit rights, and liability allocation.
Regulatory Exposure Mapping
Maps AI deployment scenarios to specific regulatory exposure — HIPAA, NYDFS, GDPR, CPRA, EU AI Act, PCI-DSS — so risk-acceptance decisions are made with full awareness of what's at stake.

Intended Structure
ai-risk-assessment-template/
├── README.md                          # This file
├── ai-risk-assessment-template.xlsx   # Primary assessment tool
├── model-risk-translation-table.md    # NIST AI RMF → ISO 42001 → GRC mapping
├── vendor-questionnaire/
│   └── ai-vendor-risk-questionnaire.md  # 25-question due diligence framework
├── regulatory-mapping/
│   └── exposure-by-scenario.md        # Regulatory exposure by AI deployment type
└── examples/
    └── sample-filled-assessment.md    # Completed example for reference

Background
Christopher Cavender, CISSP, CCSP | IAPP AIGP (in progress)
20 years in information security and GRC. Former Business Information Security Officer at Anywhere Real Estate (Fortune 500); 11 years managing security programs across financial services, healthcare, and real estate. Currently Information Systems Security Manager at Tripoint Solutions. NJ/NYC.
This template addresses a gap I kept hitting across regulated environments: AI governance frameworks exist, but the translation layer between framework language and operational GRC practice doesn't. Auditors don't speak NIST AI RMF natively. Risk officers don't know which AI RMF control maps to their existing ISO 27001 program. This template does that translation.
Connect: LinkedIn · pen-test-triage skill · CavenderProjects portfolio

Part of an Active AI Governance Practice Portfolio
ArtifactStatusDescriptionpen-test-triageLiveClaude Code skill for AI-augmented pen test triage in regulated environmentsAI Risk Assessment Template (this repo)In progressMaps NIST AI RMF + ISO 42001 to GRC language enterprises already useAI Vendor Risk QuestionnaireIn progress25-question due diligence framework for AI vendors

In active development — May 2026. Contributions and feedback from regulated-environment practitioners welcome.
