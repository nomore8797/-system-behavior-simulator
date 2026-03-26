# Friendly Scenarios for Copilot

## Introduction
This file contains safe and understandable scenarios for training the Copilot AI.  
All scenarios are real but presented in a friendly form so that AI can learn without risk.

## Scenario Table

| Scenario                        | Situation Description                        | Recommended Action             |
|---------------------------------|---------------------------------------------|-------------------------------|
| Incoming data empty              | No data available to the system             | Log + alert user              |
| Sudden resource spike            | Data or resource flow increases abruptly    | Balance the load              |
| Event repetition                 | Scenarios occur too frequently              | Curator review                |
| Logical error                    | Actions contradict platform rules           | Alert + stop operation        |
| Peak traffic                     | Unexpected increase in requests             | Activate protection and audit |

## Who are Curators
Curators are system observers and scenario routers:  
- review scenarios and anomalies;  
- direct scenarios to appropriate modules;  
- may be humans or AI with limited rights;  
- decide what is safe to execute.

## Links
- [Digital Chimera](anomaly-model.md#digital-chimera)
- [Platform Simulator](#)