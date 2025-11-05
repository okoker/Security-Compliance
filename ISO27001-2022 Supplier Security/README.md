# Supplier Cybersecurity Self-Assessment Tool

> A comprehensive ISO 27001:2022-based supply chain security assessment toolkit for evaluating vendor information security maturity

[![ISO 27001:2022](https://img.shields.io/badge/ISO-27001%3A2022-blue.svg)](https://www.iso.org/standard/27001)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Languages](https://img.shields.io/badge/languages-4-orange.svg)](README.md)

---

## Overview

This is a **turnkey supply chain security assessment tool** designed to help organizations evaluate the information security maturity of their suppliers and third-party vendors. Built on **ISO/IEC 27001:2022** standards, the tool provides a structured, consistent approach to vendor risk assessment without requiring complex infrastructure or backend systems.

---

## Use Cases

This tool is ideal for:

- **Supply chain risk management** - Evaluate vendor security posture
- **Due diligence** - Assess new supplier security capabilities
- **Compliance requirements** - Meet ISO 27001 supplier management controls
- **Audit preparation** - Document third-party security assessments
- **Security benchmarking** - Compare security maturity across vendors
- **Onboarding process** - Include in new supplier qualification
- **Periodic reviews** - Annual or quarterly security reassessment

---

### Key Features

- ✅ **Self-contained HTML form** - No server, database, or backend required
- ✅ **ISO 27001:2022 aligned** - Based on current international ISMS standards
- ✅ **39 comprehensive questions** across 10 security domains
- ✅ **Automatic maturity scoring** - 0-3 scale with instant calculation
- ✅ **Save & resume capability** - Suppliers can save progress and continue later
- ✅ **Multilingual support** - Instructions in English, Turkish, Spanish, and Italian
- ✅ **Data sovereignty** - All data stays on supplier's computer until they choose to share
- ✅ **Zero installation** - Works in any modern web browser

---

## Files

```
supplier-cybersecurity-assessment/
├── supplier-cybersecurity-assessment.html    # Main assessment form
├── instructions-english.md                   # English instructions
├── instructions-turkish.md                   # Turkish instructions (Türkçe)
├── instructions-spanish.md                   # Spanish instructions (Español)
├── instructions-italian.md                   # Italian instructions (Italiano)
└── README.md                                 # This file
```

---

## Assessment Domains

The assessment evaluates **10 critical security domains** with **39 questions** total:

| Domain | Questions | Focus Area |
|--------|-----------|------------|
| **1. Organizational Controls & Policies** | 4 | Security governance, policies, asset management |
| **2. Risk Management & Assessment** | 3 | Risk identification, treatment, threat monitoring |
| **3. People Controls & Awareness** | 4 | Background checks, training, NDAs, termination |
| **4. Access Control & Identity Management** | 4 | Access policies, authentication, privileged access |
| **5. Physical & Environmental Security** | 4 | Physical perimeters, entry controls, disposal |
| **6. Technical & Technological Controls** | 5 | Anti-malware, patching, encryption, network security |
| **7. Backup & Business Continuity** | 4 | Data backups, disaster recovery, testing |
| **8. Incident Management & Response** | 4 | Incident procedures, response plans, evidence collection |
| **9. Supplier & Third-Party Management** | 3 | Vendor risk assessment, contract requirements |
| **10. Compliance, Audit & Continuous Improvement** | 4 | Legal compliance, audits, management review |

---

## Maturity Levels

Each question is evaluated using a **5-point maturity scale**:

| Level | Score | Description |
|-------|-------|-------------|
| **Not Implemented** | 0 | No formal process or control exists |
| **Partially Implemented** | 1 | Process exists but is informal, inconsistent, or incomplete |
| **Implemented** | 2 | Process is documented and consistently followed |
| **Fully Mature** | 3 | Process is optimized, regularly reviewed, and continuously improved |
| **Not Applicable** | N/A | Control is not relevant to the organization |

### Maturity Classification

The tool automatically calculates an overall maturity score (0-3) and classifies it:

- **0.0 - 0.5** → **Initial** - Significant improvements needed
- **0.5 - 1.5** → **Developing** - Basic security practices in place
- **1.5 - 2.5** → **Defined** - Good security practices established
- **2.5 - 3.0** → **Optimized** - Mature security practices

---

## How to Use

### For Organizations (Assessment Requesters)

1. **Distribute the package** to your suppliers:
   - Send `supplier-cybersecurity-assessment.html`
   - Include the appropriate language instructions file
   
2. **Provide context** on:
   - Why you're requesting this assessment
   - Deadline for completion
   - Your contact person for questions

3. **Collect responses**:
   - Suppliers will email you the completed HTML files
   - Files include all answers and can be reopened in any browser

4. **Review results**:
   - Open the HTML files in a browser to review answers
   - Compare maturity scores across suppliers
   - Identify high-risk areas requiring follow-up

### For Suppliers (Assessment Completers)

1. **Open the HTML file** in any web browser (Chrome, Firefox, Edge, Safari)

2. **Complete the form**:
   - Fill in your company information
   - Answer all 39 questions honestly
   - Use the progress bar to track completion

3. **Save your work**:
   - Click "Save Assessment to Disk" when done (or to save progress)
   - File downloads with your answers preserved
   - You can reopen and modify anytime before submitting

4. **Submit**:
   - Email the saved HTML file to your designated contact
   - Keep a copy for your records

**Estimated time:** 15-25 minutes

---

## Multilingual Support

Complete instruction guides are provided in **4 languages**:

- 🇬🇧 **English** - `instructions-english.md`
- 🇹🇷 **Turkish (Türkçe)** - `instructions-turkish.md`
- 🇪🇸 **Spanish (Español)** - `instructions-spanish.md`
- 🇮🇹 **Italian (Italiano)** - `instructions-italian.md`

Each guide includes:
- Purpose and context
- Step-by-step completion instructions
- Maturity level definitions
- FAQ section
- Pre-submission checklist

---

## Privacy & Security

- **No data transmission** - All data stays on the supplier's computer until they choose to send it
- **No backend required** - No server, database, or API calls
- **No tracking** - No analytics, cookies, or external dependencies
- **Complete transparency** - Suppliers can inspect the HTML source code
- **Supplier control** - They decide when and how to share their assessment

---

## Benefits

### For Organizations
- Standardized vendor risk assessment process
- ISO 27001 compliance demonstration
- Quantifiable supplier security metrics
- Early identification of supply chain risks
- Foundation for security improvement plans

### For Suppliers
- Clear understanding of security expectations
- Self-assessment and improvement opportunity
- Competitive advantage through security maturity
- No complex software or training required
- Save and modify before submission

---

## Technical Details

- **Format:** Self-contained HTML5 + CSS3 + Vanilla JavaScript
- **Compatibility:** All modern browsers (Chrome, Firefox, Safari, Edge)
- **Dependencies:** None (fully standalone)
- **File size:** ~120KB (single HTML file)
- **Backend:** Not required
- **Installation:** None required

---

## 📖 ISO 27001:2022 Coverage

This assessment covers approximately **35-40%** of the 93 controls in ISO/IEC 27001:2022 Annex A, specifically focusing on:

- ✅ High-impact controls most relevant to supply chain risk
- ✅ Controls that suppliers can realistically implement
- ✅ Controls critical for third-party security evaluation

**Coverage by category:**
- Organizational Controls (37 total): ~12 covered
- People Controls (8 total): ~5 covered  
- Physical Controls (14 total): ~4 covered
- Technological Controls (34 total): ~15 covered

This assessment is designed for **supply chain evaluation**, not full ISO 27001 certification.

---

## 🔄 Workflow Example

```
┌─────────────────┐
│  Organization   │
│  Sends Package  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│    Supplier     │
│  Opens HTML     │
│  Form Browser   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│   Completes     │
│   39 Questions  │
│   (15-25 min)   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Clicks "Save"  │
│  Downloads File │
│  w/ Answers     │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Emails File    │
│  to Contact     │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Organization   │
│  Reviews in     │
│  Browser        │
└─────────────────┘
```

---

## Best Practices

### For Organizations
1. Provide context on why security matters in your relationship
2. Set realistic deadlines (allow 1-2 weeks)
3. Designate a point of contact for questions
4. Review results holistically, not just the score
5. Use low scores as opportunities for collaboration
6. Conduct follow-up discussions for high-risk areas
7. Store completed assessments securely
8. Request updates annually or when significant changes occur

### For Suppliers
1. Involve relevant teams (IT, security, compliance, operations)
2. Be honest - this helps both organizations
3. If unsure, choose the more conservative option
4. Document any "Not Applicable" selections
5. Provide context in the additional comments section
6. Review before submitting
7. Keep a copy for your records
8. Ask questions if anything is unclear

---

## Contributing

This is a standalone tool designed for direct use. If you have suggestions for improvements:

1. Test the form thoroughly in your environment
2. Document any issues or enhancement ideas
3. Share feedback with your organization's security team

---

## 📄 License

This tool is provided as-is for supply chain security assessment purposes. Organizations are free to customize and distribute to their suppliers as needed.

---

## Support

For questions or issues:

- **Suppliers:** Contact your designated point of contact at the requesting organization
- **Organizations:** Review the instruction guides or consult with your information security team

---

## Additional Resources

- [ISO/IEC 27001:2022 Standard](https://www.iso.org/standard/27001)
- [ISO/IEC 27002:2022 Controls](https://www.iso.org/standard/75652.html)
- [Supply Chain Risk Management Best Practices](https://www.nist.gov/itl/executive-order-improving-nations-cybersecurity/securing-software-supply-chain)

---

## Disclaimer

This assessment tool is based on ISO/IEC 27001:2022 requirements but does not constitute an official ISO certification or audit. Results should be used as part of a comprehensive supply chain risk management program, not as the sole basis for vendor decisions.

---

**Version:** 1.0  
**Last Updated:** November 2025  
**Based on:** ISO/IEC 27001:2022

---

*Built to strengthen security across the entire supply chain* 
