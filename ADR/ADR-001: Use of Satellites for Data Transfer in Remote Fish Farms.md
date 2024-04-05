# ADR-001: Use of Satellites for Data Transfer in Remote Fish Farms

## Status: Proposed

## Context
Fish farms are often located in remote areas where cellular signal strength is poor or nonexistent. This poses a significant challenge for real-time data transfer from these farms to the central monitoring system. Traditional methods relying on cellular networks may not be reliable in such environments, leading to data transmission failures and delayed alerts. 

## Decision
TODO

## Rationale
Satellite communication provides global coverage, making it suitable for remote areas where terrestrial networks are unavailable or unreliable. It offers high bandwidth and low latency, allowing for efficient data transfer even in challenging environments. By using satellites, we can overcome the limitations of cellular networks and ensure seamless connectivity for real-time monitoring of water quality, fish health, and environmental conditions in remote fish farms.

## Implications
- Implementation of satellite communication may incur additional costs for equipment, installation, and ongoing service subscriptions.
- Integration with existing data collection devices and systems will be necessary to enable seamless data transmission via satellites.
- Satellite communication may introduce latency compared to terrestrial networks, which should be taken into account when designing real-time monitoring and alerting systems.
- Training may be required for personnel responsible for managing and maintaining satellite communication equipment.

## Alternatives
Alternative approaches considered for addressing poor cellular signal in remote fish farms included:
1. Deploying long-range radio frequency (RF) communication systems.
2. Employing offline data collection and periodic data transfer when connectivity is available.

Satellite communication can  chosen as the preferred solution due to its global coverage, reliability, and independence from terrestrial infrastructure.


## Notes
- Careful consideration should be given to selecting satellite communication providers and equipment vendors to ensure compatibility, reliability, and cost-effectiveness.
- Regular monitoring and maintenance of satellite communication equipment will be essential to ensure uninterrupted operation.


