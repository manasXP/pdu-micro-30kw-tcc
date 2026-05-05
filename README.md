# PDU-Micro-30KW — Testing, Certification & Commissioning

Execution procedures for the **30 kW PDU / 150 kW stack**: board-level and end-to-end test plans, certification dossiers, and field commissioning procedures. Engineering design lives in `../PDU-Micro-30KW-Spec/`; schedule / budget / risk live in `../PDU-Micro-30KW-PM/`.

See the programme [`../../VISION.md`](__Workspaces/Energy/PDU/VISION.md) (§2.1 for this variant) for objective and target specification, and [`../CLAUDE.md`](__Workspaces/Energy/PDU/PDU-Micro-30KW/CLAUDE.md) for shared Claude Code context.

## Scope

- Board-level bring-up and end-to-end test procedures
- HALT / burn-in specifications
- Production test specs
- Type-test dossiers (IEC 61851-23, UL 2202, CE/EMC, IEC 62368-1)
- OCPP 1.6 / ISO 15118 compliance evidence
- Field commissioning procedures

No engineering design content, no schedule / budget / risk artifacts.

## Layout

| Path | Purpose |
|---|---|
| `__init.md` | Obsidian index of test, cert, and commissioning content |
| `Testing/` | Board-level test procedure, end-to-end test plan, HALT / burn-in, production test spec |
| `Certification/` | Type-test dossiers, EMC test reports, compliance matrices, certificates |
| `Commissioning/` | Factory bring-up and field commissioning procedures, checklists |

> [!note] Rev 1.0 DAB Migration (2026-04-22)
> DC-DC stage migrated to 3-leg interleaved DAB (per Microchip DS70005603A × 3). Testing, commissioning, and certification targets updated: output ceiling **650 V → 900 V**, per-leg **4 kV reinforced isolation × 3 legs**, DC output→PE hipot **2750 → 3750 VAC**. Testing sub-plans and commissioning procedure carry Rev 1.0 banners; full test-script refresh is scheduled during EP-05 DCDC-02 PCB design kickoff.

## Compliance Targets

| Area | Standard |
|---|---|
| EV DC charging | IEC 61851-23 (Rev 1.0 — up to 900 V output) |
| Safety | IEC 62368-1 (4 kV reinforced per leg × 3), UL 2202 |
| EMC | EN 55032 Class B (conducted + radiated), incl. 900 V operating point |
| Regional marks | CE, UL |
| Protocols | CAN-FD; OCPP 1.6, ISO 15118 via external SECC |

## Siblings

| Workspace | Purpose |
|---|---|
| `../PDU-Micro-30KW-Spec/` | Engineering design (topology, firmware, PCB layout, BOM, thermal, EMI) |
| `../PDU-Micro-30KW-Design/` | Active CAD / PCB design artifacts |
| `../PDU-Micro-30KW-PM/` | Epics, sprints, budget, risk register |
