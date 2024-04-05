# ADR-001: Use of Mobile Devices for Data Transfer in Remote Fish Farms

## Status: Proposed

## Context
Fish farms are frequently situated in remote areas with poor cellular signal coverage, posing challenges for real-time data transfer from IoT devices to the central monitoring system. Traditional methods relying solely on cellular networks may not be reliable in such environments, leading to potential data transmission failures and delayed alerts. To address this issue, an alternative approach is proposed, utilizing mobile devices such as smartphones or tablets as intermediary data transfer points.

## Decision
We have decided to utilize mobile devices as movable data transfer points in remote fish farms. Data collected by IoT devices within the farm enclosures will be synced to mobile devices when within range, leveraging any available cellular signal. Subsequently, when mobile devices are in locations with better cellular network coverage, data will be synced from the mobile devices to the central monitoring system.

## Rationale
Using mobile devices as intermediary data transfer points offers several advantages:
- Flexibility: Mobile devices can be moved around the farm, allowing data transfer from areas with poor cellular signal to locations with better connectivity.
- Redundancy: Mobile devices provide an additional layer of redundancy, ensuring data is not lost even if IoT devices experience connectivity issues.
- Cost-effectiveness: Leveraging existing mobile devices reduces the need for additional infrastructure investment, minimizing costs associated with data transfer solutions.

## Implications
- Mobile devices will need to be equipped with appropriate storage capacity and security measures to handle and safeguard sensitive data.
- Regular maintenance and monitoring of mobile devices will be necessary to ensure reliable operation and data integrity.
- Training may be required for farm personnel responsible for managing and operating the mobile devices.

## Alternatives
Alternative approaches considered for addressing poor cellular signal in remote fish farms included:
1. Satellite communication: Utilizing satellites for data transfer, as discussed in ADR-001.

However, the proposed approach of using mobile devices was chosen for its flexibility, redundancy, and cost-effectiveness.

## Related ADRs
None

## Notes
- Careful consideration should be given to security measures to protect data during transfer and storage on mobile devices.

