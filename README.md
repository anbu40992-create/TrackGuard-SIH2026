# TrackGuard – Electromagnetic Flux-Based Real-Time Railway Track Crack Detection System

## Problem Statement
Manual railway track patrolling is slow, risky, and covers only limited stretches per day. Undetected cracks — especially those caused by summer heat-induced thermal expansion — pose a serious derailment risk across India's vast rail network.

## Proposed Solution
TrackGuard is a hardware-based system that turns every running train into a real-time, GPS-tagged rail-crack scanner.

- A horseshoe-shaped electromagnetic coil, mounted on a moving inspection unit, generates a continuous magnetic flux through the rail.
- A crack or discontinuity disturbs this flux pattern, which is picked up by a flux sensor.
- An ESP32 microcontroller compares the live reading against a healthy-rail baseline and flags abnormal deviations.
- A GPS module tags the exact location, and an alert is sent to maintenance personnel via a wireless module.

## Tech Stack
**Hardware:** Horseshoe electromagnetic flux coils, Hall-effect/flux sensors, ESP32 microcontroller, GPS module, signal conditioning circuit, GSM/wireless communication module

**Software:** Arduino IDE / Embedded C, real-time signal processing, threshold-based anomaly detection, GPS data logging

## Theme
Transportation & Logistics — Hardware Category

## Team
FLUXON — Smart India Hackathon 2026
