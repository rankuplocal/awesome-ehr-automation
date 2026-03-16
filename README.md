# Awesome EHR Automation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, resources, and research for automating healthcare documentation and EHR workflows.

Maintained by the team at [Cheryl AI](https://cherylmd.com) — AI clinical documentation for small clinics.

## Contents

- [AI Documentation Tools](#ai-documentation-tools)
- [Billing & Coding Automation](#billing--coding-automation)
- [EHR Integration Methods](#ehr-integration-methods)
- [Clinical NLP & AI Research](#clinical-nlp--ai-research)
- [Datasets & Standards](#datasets--standards)
- [Regulatory & Compliance](#regulatory--compliance)
- [Communities & Forums](#communities--forums)
- [Contributing](#contributing)

## AI Documentation Tools

### Browser-Based / Extension

| Tool | Type | Specialty Support | EHR Compatibility | Pricing |
|------|------|-------------------|-------------------|---------|
| [Cheryl AI](https://cherylmd.com) | Chrome Extension | Chiro, Acupuncture, PT, TCM, 30+ specialties | Any web-based EHR (44+ verified) | $49/mo |
| [Heidi Health](https://www.heidihealth.com) | Browser App | General | Any (listens via browser) | Free/$30/mo |

### Ambient Listening / Voice

| Tool | Type | Specialty Support | EHR Compatibility | Pricing |
|------|------|-------------------|-------------------|---------|
| [Freed AI](https://www.getfreed.ai) | Ambient Listener | General | Limited direct | $99/mo |
| [Suki AI](https://www.suki.ai) | Voice Assistant | General | Epic, Cerner, athenahealth | Enterprise |
| [Nabla](https://www.nabla.com) | Ambient Scribe | General | Select EHRs | Enterprise |
| [DeepScribe](https://www.deepscribe.ai) | Ambient AI | General, some specialties | Select EHRs | $99+/mo |
| [Abridge](https://www.abridge.com) | Ambient AI | General | Epic, Oracle Health | Enterprise |
| [Nuance DAX](https://www.nuance.com/healthcare/dragon-ambient-experience.html) | Ambient AI | General | Epic, Cerner, MEDITECH | Enterprise |
| [Augmedix](https://www.augmedix.com) | Ambient + Human | General | Epic, Cerner | Enterprise |
| [ScribeAmerica AI](https://www.scribeamerica.com) | Hybrid AI+Human | General | Various | Enterprise |

### Specialty-Specific

| Tool | Specialty | Type | Pricing |
|------|-----------|------|---------|
| [Sprypt](https://www.sprypt.com) | PT, OT, SLP | AI Documentation | Contact |
| [IntakeQ](https://intakeq.com) | Multi-specialty | Smart Forms + Notes | $49+/mo |
| [ChiroTouch AI](https://chirotouch.com) | Chiropractic | Built-in AI features | $159+/mo |

## Billing & Coding Automation

### AI Coding Assistants

| Tool | Focus | Description |
|------|-------|-------------|
| [Cheryl AI Billing](https://cherylmd.com) | E/M, ICD-10, CPT, NCCI | Real-time billing optimization alongside chart generation |
| [Codapedia](https://www.codapedia.com) | Reference | Medical coding encyclopedia |
| [Find-A-Code](https://www.findacode.com) | ICD/CPT Lookup | Code search and crosswalk tools |

### Revenue Cycle Management (RCM)

| Tool | Focus | Pricing |
|------|-------|---------|
| [Waystar](https://www.waystar.com) | Full RCM Platform | Enterprise |
| [Availity](https://www.availity.com) | Eligibility, Claims | Free/Premium |
| [ClaimMD](https://www.claimmd.com) | Claims Clearinghouse | Per-claim |
| [Trizetto](https://www.trizetto.com) | RCM + Analytics | Enterprise |
| [Kareo Billing](https://www.tebra.com) | Small Practice RCM | $150+/mo |

### Coding References

- [CMS MPFS Lookup](https://www.cms.gov/medicare/payment/fee-schedules/physician) — Medicare Physician Fee Schedule
- [CMS NCCI Edits](https://www.cms.gov/medicare/coding-billing/national-correct-coding-initiative-edits) — National Correct Coding Initiative
- [AMA CPT Assistant](https://www.ama-assn.org/practice-management/cpt) — Official CPT guidance

## EHR Integration Methods

### Approaches Compared

| Method | Setup Time | IT Required | EHR Lock-in | Cost | Data Depth |
|--------|-----------|-------------|-------------|------|-----------|
| **FHIR/HL7 API** | Weeks-months | Yes | Per-EHR | High | Full |
| **Browser Extension** | Minutes | No | None (universal) | Low | Screen-level |
| **Ambient Listening** | Hours | Minimal | None | Medium | Audio only |
| **Direct Database** | Months | Yes | Per-EHR | Very High | Full |

### FHIR Resources

- [HL7 FHIR R4](https://hl7.org/fhir/) — Current standard for health data exchange
- [SMART on FHIR](https://smarthealthit.org/) — App launch framework for EHRs
- [Logica Health](https://www.logicahealth.org/) — Open-source FHIR sandbox
- [Firely Server](https://fire.ly/) — .NET FHIR server implementation

### EHR-Specific APIs

| EHR | API Type | Documentation |
|-----|----------|---------------|
| Epic | FHIR R4 + Proprietary | [open.epic.com](https://open.epic.com) |
| Oracle Health (Cerner) | FHIR R4 | [fhir.cerner.com](https://fhir.cerner.com) |
| athenahealth | REST + FHIR | [developer.athenahealth.com](https://developer.athenahealth.com) |
| DrChrono | REST | [developer.drchrono.com](https://developer.drchrono.com) |
| Cliniko | REST | [developer.cliniko.com](https://developer.cliniko.com) |
| SimplePractice | REST | [api.simplepractice.com](https://api.simplepractice.com) |
| Jane App | Limited REST | [jane.app/guide](https://jane.app/guide) |
| NextGen | FHIR R4 | [developer.nextgen.com](https://developer.nextgen.com) |

## Clinical NLP & AI Research

### Key Papers

- [The Documentation Burden in Healthcare](https://www.acpjournals.org/doi/10.7326/M18-3684) — Annals of Internal Medicine, 2019. Physicians spend 2+ hours daily on documentation.
- [Ambient AI Scribes: A Systematic Review](https://www.nature.com/articles/s41746-024-01234-5) — npj Digital Medicine, 2024. Comprehensive review of AI documentation tools.
- [GPT-4 Performance on Medical Documentation](https://arxiv.org/abs/2308.09873) — 2023. Evaluating LLM accuracy for clinical note generation.
- [Automated Medical Coding with NLP](https://academic.oup.com/jamia/article/29/5/867/6513617) — JAMIA, 2022. NLP approaches to ICD/CPT coding.
- [Burnout and Electronic Health Records](https://www.mayoclinicproceedings.org/article/S0025-6196(19)30836-5/fulltext) — Mayo Clinic Proceedings, 2020.

### Research Groups

- [Stanford AIMI](https://aimi.stanford.edu/) — Artificial Intelligence in Medicine & Imaging
- [MIT CSAIL Clinical ML](https://www.csail.mit.edu/) — Machine learning for healthcare
- [Google Health AI](https://health.google/) — Health AI research
- [Microsoft Health AI](https://www.microsoft.com/en-us/research/project/health-ai/) — Project Health AI

## Datasets & Standards

### Open Datasets

| Dataset | Description | Access |
|---------|-------------|--------|
| [MIMIC-IV](https://mimic.mit.edu/) | ICU clinical data (patients, labs, notes) | Free (credentialed) |
| [n2c2/i2b2 NLP](https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/) | Clinical NLP challenge datasets | Free (DUA) |
| [MTSamples](https://www.mtsamples.com/) | Medical transcription samples | Free |
| [PubMedQA](https://pubmedqa.github.io/) | Biomedical QA dataset | Free |

### Code Systems

- [ICD-10-CM](https://www.cms.gov/medicare/coding-billing/icd-10-codes) — Diagnosis codes (updated annually)
- [CPT Codes](https://www.ama-assn.org/practice-management/cpt) — Procedure codes (AMA)
- [SNOMED CT](https://www.snomed.org/) — Clinical terminology
- [LOINC](https://loinc.org/) — Lab observation codes
- [RxNorm](https://www.nlm.nih.gov/research/umls/rxnorm/) — Medication terminology

## Regulatory & Compliance

- [HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html) — Data protection requirements
- [ONC Health IT Certification](https://www.healthit.gov/topic/certification-ehrs) — EHR certification program
- [21st Century Cures Act](https://www.healthit.gov/curesrule/) — Information blocking rules
- [CMS Interoperability Rules](https://www.cms.gov/priorities/key-initiatives/burden-reduction/interoperability) — Patient access API requirements
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) — AI governance guidance

## Communities & Forums

- [r/healthIT](https://www.reddit.com/r/healthIT/) — Health IT discussions
- [r/medicine](https://www.reddit.com/r/medicine/) — Physician community
- [AMIA](https://amia.org/) — American Medical Informatics Association
- [HIMSS](https://www.himss.org/) — Healthcare Information and Management Systems Society
- [Health IT Buzz](https://www.healthit.gov/buzz-blog) — ONC official blog
- [CHIME](https://chimecentral.org/) — College of Healthcare Information Management Executives

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

- Add tools you've personally used or evaluated
- Include accurate pricing and compatibility info
- Keep descriptions objective and factual
- Link to official sources only

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0 — no rights reserved.

---

*Maintained by [Cheryl AI](https://cherylmd.com) — Stop losing $57K/year to undercoding.*
