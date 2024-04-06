# ADR-001: Use of Satellites for Data Transfer in Remote Fish Farms

## Status: Rejected

## Context
Fish farms are often located in remote areas where cellular signal strength is poor or nonexistent. This poses a significant challenge for real-time data transfer from these farms to the central monitoring system. Traditional methods relying on cellular networks may not be reliable in such environments, leading to data transmission failures and delayed alerts. 

## Decision
The decision not to use satellite communication was based on several factors:-
- Implementation of satellite communication may incur additional costs for equipment, installation, and ongoing service subscriptions.
- Integration with existing data collection devices and systems will be necessary to enable seamless data transmission via satellites.
- Satellite communication may introduce latency compared to terrestrial networks, which should be taken into account when designing real-time monitoring and alerting systems.
- Training may be required for personnel responsible for managing and maintaining satellite communication equipment.

## Implication
By rejecting the use of satellite communication, we acknowledge that alternative solutions will need to be explored to address the challenge of poor cellular signal coverage in remote fish farm locations. This may involve investing in alternative communication technologies or optimizing existing infrastructure to ensure reliable data transfer from these locations to the central Fish Watch system


## Alternatives
Alternative approaches considered for addressing poor cellular signal in remote fish farms included:
1. Deploying long-range radio frequency (RF) communication systems.
2. Employing offline data collection and periodic data transfer when connectivity is available.

## Notes
- The decision not to use satellite communication is based on the current assessment of cost, complexity and techincal feasibility. Future advancements in satellite communication  techology or changes in project requirements may nessiciate a reassessment of this decision.