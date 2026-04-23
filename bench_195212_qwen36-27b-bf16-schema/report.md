# Holo3 Benchmark Report — 20260423_195212_qwen36-27b-bf16-schema_replay

- Patient: 00000001
- Screens: 6
- Time: 2026-04-23T19:52:12.889013 → 2026-04-23T19:54:30.673264

## Summary

| Metric | Value |
|---|---|
| Grounding hit rate | **0.844** (27/32) |
| Mean pixel distance | **126.5 px** |
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

- Grounding: 6/6
- OCR[lab_results]: 6/6 (recall 1.00)

![labs](annotated/labs.png)

### meds

- Grounding: 4/6
- OCR[medications]: 1/1 (recall 1.00)

![meds](annotated/meds.png)

### diagnoses

- Grounding: 5/6
- OCR[diagnoses]: 2/2 (recall 1.00)

![diagnoses](annotated/diagnoses.png)
