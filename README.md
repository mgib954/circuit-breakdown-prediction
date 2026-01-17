# Predicting Circuit Breakdown Using Data Science

This project predicts electronic circuit failure **before breakdown**
using sensor data, signal analysis, and machine learning.

## Problem
Electronic circuits fail gradually due to thermal, electrical, and
component aging. Traditional systems detect failure too late.

## Solution
A smart monitoring system that:
- Collects voltage, current, temperature, ripple data
- Detects early degradation using anomaly detection
- Predicts failure probability and health score

## Hardware
- ESP32
- INA219 (Current & Voltage)
- DS18B20 (Temperature)
- LM2596 Buck Converter

## Data Science
- Time-series analysis
- Feature engineering
- Isolation Forest
- Health index estimation

## Results
- Early warning before failure
- Degradation trend visualization
- Remaining useful life estimation
