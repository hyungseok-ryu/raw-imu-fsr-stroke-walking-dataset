# Raw IMU and FSR Walking Dataset

This repository provides raw thigh-mounted IMU and heel FSR data
collected during walking experiments.

Only the raw sensor signals corresponding to the temporal segments
actually used for data analysis are shared.
No filtering, windowing, event detection, or label generation is applied.

---

## Dataset Structure


---

## Subject Information

| Subject ID | Affected Side |
|------------|---------------|
| SUB1 | Left |
| SUB2 | Right |
| SUB3 | Left |
| SUB4 | Left |
| SUB7 | Left |

All subjects are anonymized.
No personally identifiable or clinical information is included.

---

## Sensor Description

### IMU (Thigh-mounted)
- 3-axis linear acceleration
- 3-axis angular velocity
- Thigh pitch angle
- Sampling rate: 100 Hz

### FSR (Heel)
- Single-channel force-sensitive resistor
- Sampling rate: 100 Hz

IMU and FSR signals are time-synchronized using timestamps.

---

## Notes

- The shared data are raw signals only.
