# Safety Guidelines

## Introduction
This file describes safety measures for the platform, users, and data.  
All recommendations are based on our internal security policy.

## Core Principles
- **Access Control:** only authorized curators and audits can interact with the core.  
- **Curator Role:** review scenarios and maintain core/data safety; they also act as scenario routers.  
- **Logging:** all operations are logged for review.  
- **Intervention Limitation:** critical modules are protected from external interference.  
- **Data Protection:** personal and confidential information is encrypted and isolated.  
- **Scenario Control:** new scenarios are reviewed before being executed in the simulator.  

## Security Metrics
| Object Checked              | Metric                     | Purpose                               |
|------------------------------|---------------------------|---------------------------------------|
| Core access                  | Authorization, roles      | Prevent unauthorized access           |
| Data handling                | Encryption, anonymization | Protect confidential information      |
| Scenarios                     | Curator review            | Exclude unsafe scenarios              |
| Logs and audits              | Completeness & continuity | Enable incident investigation         |

## Continuous Integration (Text Description)
- All changes and new scenarios are reviewed by curators.  
- Once approved, they are recorded in the repository and checked textually for correctness.  
- Any deviations are returned to the curator for review.  
- The cycle repeats continuously, ensuring integration of new scenarios and safe platform operation.

## Links
- [Platform Simulator](#)  
- [Anomaly Model](anomaly-model.md)  
- [Friendly Scenarios](friendly-scenarios.md)