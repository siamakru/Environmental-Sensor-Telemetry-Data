# Environmental Sensor Telemetry Data Analysis

## Overview

This repository contains Python code for analyzing Environmental Sensor Telemetry Data. The dataset includes various environmental parameters recorded by different sensors, such as carbon monoxide (CO) levels, humidity, light detection, liquid petroleum gas (LPG) levels, motion detection, smoke levels, and temperature.

### Dataset Description

The dataset consists of the following columns:

| Column   | Description             | Units      |
|----------|-------------------------|------------|
| ts       | Timestamp of event      | Epoch      |
| device   | Different sensors       | String     |
| co       | Carbon monoxide         | ppm (%)    |
| humidity | Humidity                | Percentage |
| light    | Light detected?         | Boolean    |
| lpg      | Liquid petroleum gas    | ppm (%)    |
| motion   | Motion detected?        | Boolean    |
| smoke    | Smoke                   | ppm (%)    |
| temp     | Temperature             | Celsius    |

### Assumptions

The following assumptions are made for this analysis:

- **Dependent Attributes:** LPG (Product)
- **Independent Attributes:** Humidity, Temperature, Light, Motion, Smoke

### Goals

1. Optimizing the LPG production.
2. System alert for deviant behavior.

