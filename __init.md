---
tags: [pdu-micro, testing, certification, commissioning, index]
created: 2026-04-22
---

# PDU-Micro-30KW — Testing, Certification & Commissioning

Execution procedures for the 30 kW PDU. Split out from the engineering workspace (`../PDU-Micro-30KW/`) on 2026-04-22.

## Structure

- [[__Workspaces/Energy/PDU/PDU-Micro-30KW/PDU-Micro-30KW-TCC/Testing/__init|Testing]] — board-level bring-up, end-to-end test plan, HALT/burn-in, production test spec
- [[__Workspaces/Energy/PDU/PDU-Micro-30KW/PDU-Micro-30KW-TCC/Certification/__init|Certification]] — IEC 61851-23, UL 2202, CE/EMC, OCPP 1.6, ISO 15118 compliance evidence
- [[__Workspaces/Energy/PDU/PDU-Micro-30KW/PDU-Micro-30KW-TCC/Commissioning/__init|Commissioning]] — factory bring-up and field commissioning procedures

## Cross-Workspace References

- Engineering design: `../PDU-Micro-30KW/` (topology, firmware, PCB layout, BOM, thermal, EMI)
- Project management: `../PDU-Micro-30KW-PM/` (epics, sprints, budget, risk register)

## Revision History

| Rev | Date | Author | Changes |
|---|---|---|---|
| 0.1 | 2026-04-22 | Manas Pradhan | Workspace split from PDU-Micro-30KW — test plans and commissioning procedure extracted into this sibling workspace; Certification/ created for forthcoming compliance dossiers |
