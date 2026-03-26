# Anomaly Model

## Digital Chimera
The **Digital Chimera** is our metric for comprehensive scenario evaluation:  
- assesses logical, resource, and temporal indicators;  
- considers impact on the core and related modules;  
- helps curators and audits properly filter anomalies.

## Anomaly Metrics
- **Signal/Noise** — ratio of abnormal value to norm.  
- **Repetition Frequency** — how often a similar deviation occurs.  
- **Deviation Strength** — how much the value differs from expectations.  
- **Core Impact** — the effect of an event on module/core operations.

## Logic and Architecture
- **Simulator Core** — receives input data and calculates metrics.  
- **Equilibrium** — stabilizes core response to anomalies.  
- **Audit** — monitors correctness of anomaly classification.  

## Curators and Routers
**Curators** are observers and scenario routers:  
- check new scenarios and anomalies;  
- filter false positives;  
- direct scenarios to the appropriate core modules according to Digital Chimera metrics;  
- authorize scenario execution in the simulator.  

**Origin:** appointed by platform administration or automatically via core rules.  

> 🔹 Demonstrates our **open philosophy and transparency**: all curator routes and decisions are logged and can be audited.

## Scenario Examples (Table)

| Scenario                        | Anomaly Type       | Metric | Deviation Strength | Model Action                       |
|---------------------------------|------------------|--------|------------------|-----------------------------------|
| Incoming data empty              | Missing data      | 0      | Max              | Log + alert audit                 |
| Sudden resource spike            | Peak load         | 0.8    | High             | Activate core load balancing      |
| Unexpected event repetition      | Repetition        | 0.5    | Medium           | Curator checks, audit monitors    |
| Actions contradict rules         | Logical error     | 1      | Critical         | Stop module + log in core         |

## Continuous Integration (Text Description)
1. All scenarios are reviewed by curators.  
2. Approved scenarios are recorded in the repository.  
3. Scenario, log, and metric correctness is verified textually — without automated execution.  
4. Any deviations are returned to the curator for review.  
5. The cycle repeats continuously, ensuring integration of new scenarios and core safety.

## Links
- [Platform Simulator](#)
- [Friendly Scenarios](friendly-scenarios.md)