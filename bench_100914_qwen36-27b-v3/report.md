# Holo3 Benchmark Report — 20260423_100914_qwen36-27b-v3_replay

- Patient: 00000001
- Screens: 6
- Time: 2026-04-23T10:09:14.714731 → 2026-04-23T10:12:15.463939

## Summary

| Metric | Value |
|---|---|
| Grounding hit rate | **0.625** (20/32) |
| Mean pixel distance | **111.1 px** |
| OCR mean recall | **1.000** |

## Per-screen

### login

- Grounding: 2/2

![login](annotated/login.png)

### patient_list

- Grounding: 6/6

![patient_list](annotated/patient_list.png)

### karte

- Grounding: 4/6

![karte](annotated/karte.png)

### labs

- Grounding: 5/6
- OCR[lab_results]: 6/6 (recall 1.00)

![labs](annotated/labs.png)

### meds

- Grounding: 1/6
- OCR[medications]: 1/1 (recall 1.00)

![meds](annotated/meds.png)

### diagnoses

- Grounding: 2/6
- OCR[diagnoses]: 2/2 (recall 1.00)

![diagnoses](annotated/diagnoses.png)
