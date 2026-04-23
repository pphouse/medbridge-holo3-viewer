# Holo3 Benchmark Report — 20260423_081325_qwen36-v2_replay

- Patient: 00000001
- Screens: 6
- Time: 2026-04-23T08:13:25.314389 → 2026-04-23T08:14:32.234504

## Summary

| Metric | Value |
|---|---|
| Grounding hit rate | **0.094** (3/32) |
| Mean pixel distance | **388.5 px** |
| OCR mean recall | **1.000** |

## Per-screen

### login

- Grounding: 2/2

![login](annotated/login.png)

### patient_list

- Grounding: 1/6

![patient_list](annotated/patient_list.png)

### karte

- Grounding: 0/6

![karte](annotated/karte.png)

### labs

- Grounding: 0/6
- OCR[lab_results]: 6/6 (recall 1.00)

![labs](annotated/labs.png)

### meds

- Grounding: 0/6
- OCR[medications]: 1/1 (recall 1.00)

![meds](annotated/meds.png)

### diagnoses

- Grounding: 0/6
- OCR[diagnoses]: 2/2 (recall 1.00)

![diagnoses](annotated/diagnoses.png)
