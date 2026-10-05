# AI Race Engineer

An AI race engineer for sim racing telemetry analysis and race strategy.

## Project Goal

The goal of this project is to build a personal AI Race Engineer that can analyze sim racing telemetry, identify where lap time is gained or lost, explain driver performance, and eventually simulate race strategy decisions.

The project will initially focus on sim racing and will be developed entirely in Python.

## Current Status

### Phase 1 — Telemetry Foundation

The first phase focuses on building the data analysis foundation:

- Load telemetry data
- Validate and clean telemetry
- Detect individual laps
- Calculate lap times
- Analyze speed, throttle, brake and steering inputs
- Compare laps
- Align telemetry by track distance
- Identify where time is gained or lost
- Generate race engineer style analysis

## Planned Roadmap

### Phase 1 — Telemetry Foundation

Build the core telemetry analysis pipeline.

### Phase 2 — Machine Learning

Use telemetry-derived features to predict performance and detect anomalies.

### Phase 3 — Race Strategy Simulation

Develop what-if simulations for pit stops, tyres, fuel and race pace.

### Phase 4 — AI Race Engineer

Create an intelligent interface that can explain telemetry and strategy decisions in natural language.

### Phase 5 — Validation

Test the system across different sessions, tracks and drivers.

## Project Structure

```text
ai-race-engineer/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── sample/
│
├── notebooks/
├── reports/
│
├── src/
│   ├── cleaning.py
│   ├── data_loader.py
│   ├── laps.py
│   ├── metrics.py
│   └── visualization.py
│
├── tests/
│
├── main.py
├── README.md
├── requirements.txt
└── .gitignore