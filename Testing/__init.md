---
tags: [PDU, testing, verification, validation, dsPIC33AK, dsPIC33CK, DC-DC, Microchip]
created: 2026-02-22
updated: 2026-04-22
---

# Testing

Complete test documentation for the 30 kW PDU. Split out from the engineering workspace on 2026-04-22.

## Documents

- [[__Workspaces/Energy/PDU/PDU-Micro-30KW/PDU-Micro-30KW-TCC/Testing/01-Board-Level Test Procedure]] — Lab-level prototype bring-up: equipment list, per-board test setups, step-by-step sequences with pass/fail criteria for all 4 PCBs, system integration tests, efficiency sweep, and test report templates
- [[__Workspaces/Energy/PDU/PDU-Micro-30KW/PDU-Micro-30KW-TCC/Testing/02-End-to-End Test Plan]] — Full V&V lifecycle: requirements traceability, type tests per standards (IEC 62368-1, IEC 61851-23, UL 2202, EMC), environmental qualification, HALT/burn-in, communication protocol validation, charging profile simulation, production test specification, and certification test matrix

## Related Documents

- `../Certification/` — Compliance evidence and test reports (sibling folder)
- `../Commissioning/01-Commissioning Procedure.md` — Field-level deployment and site acceptance testing
- `../../PDU-Micro-30KW/docs/Common/09-Protection and Safety.md` — Protection thresholds, hipot levels, safety compliance matrix
- `../../PDU-Micro-30KW-PM/Epics/EP-08 Pre-Production Validation.md` — Project stories for certification, HALT, and environmental testing

---

## Revision History

| Rev | Date | Author | Changes |
|-----|------|--------|---------|
| 0.1 | 2026-02-22 | Manas Pradhan | Initial creation — folder index |
| 0.2 | 2026-02-23 | Manas Pradhan | Updated tags for dsPIC33CH/DAB migration |
| 0.3 | 2026-03-12 | Manas Pradhan | Updated tags and references: DAB → DC-DC, dsPIC33CH → dsPIC33CK, output voltage 1000V → 650V |
| 0.4 | 2026-04-22 | Manas Pradhan | Extracted into sibling workspace `PDU-Micro-30KW-TCC/Testing/`. Cross-references updated to relative paths. |
