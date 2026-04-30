# ISMS Scope

**CloudVault Federal Health Exchange (FHX)**
**ISO 27001:2022, Clause 4.3**
**Prepared By:** Enechi P.C. Njeze, ISSO/ISSM

---

## Purpose

This folder contains the ISMS scope statement and context documents for CloudVault FHX. ISO 27001 Clause 4.3 requires the organization to determine the boundaries and applicability of the ISMS. The scope statement is one of the first documents a certification auditor reviews because it defines what the ISMS covers and what it explicitly excludes.

## Documents in This Folder

| Document | Description | Clause | Status |
|---|---|---|---|
| isms-scope-statement.md | Formal scope statement defining ISMS boundaries | 4.3 | In Progress |
| context-of-organization.md | Internal and external issues affecting the ISMS | 4.1 | Planned |
| interested-parties.md | Stakeholders with requirements relevant to the ISMS | 4.2 | Planned |

## ISMS Scope Statement for CloudVault FHX

The ISMS for CloudVault Federal Health Exchange (FHX) covers the information security management of the FHX application platform, its supporting AWS GovCloud infrastructure, the data processed and stored within the authorization boundary, and all personnel with access to FHX systems or data.

**In scope:** FHX application services, AWS GovCloud us-gov-east-1 and us-gov-west-1 environments, all PHI/PII/FTI/CUI data processing, FHX operations team, and contracted support staff with system access.

**Explicitly out of scope:** End-user workstations at the 47 connected federal agencies, external agency network infrastructure, and AWS GovCloud physical data center infrastructure (covered by AWS's own ISO 27001 certification).

## Key Context Factors

**Internal factors:** CloudVault FHX is a HIGH-impact federal system. The ISMS must align with FISMA, HIPAA, and FedRAMP authorization requirements. Senior leadership commitment is demonstrated through AO engagement and documented management review records.

**External factors:** 47 federal agencies depend on FHX availability. Regulatory requirements from HHS, IRS, OMB, and NIST impose specific controls. The threat environment for federal health data platforms is rated HIGH by CISA.

## Related Documents

- [README (Repository Index)](../README.md)
- [Risk Assessment](../risk-assessment/README.md)
- [Statement of Applicability](../soa/README.md)
- [FedRAMP SSP Authorization Boundary](https://github.com/enechi-njeze/cloudvault-fedramp-ato/blob/main/docs/system-security-plan.md)

---

*Enechi P.C. Njeze, CGRC, CISA, CISM, PMP, PMI-RMP, Security+, CHP, CSCS*
*ISSO and ISSM, CloudVault Federal Health Exchange (FHX)*
