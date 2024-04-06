# Fish Watch System

## Introduction
This README provides an overview of the Fish Watch system, detailing its requirements, team members, approach, and architectural decisions. Fish Watch is designed to facilitate monitoring and management of fish farms, catering to varying needs and challenges encountered in the aquaculture industry.

## Team Members - Legends
- Deepak Bansal
- Zia Tahir
- Chandramouli Vashisth
- Vishal Kumar
- Gaurav Kumar

## Requirement
Fish Watch aims to provide comprehensive monitoring and management solutions for fish farms, considering the diverse requirements of its customers. The key requirements include:
- Operation of fish farms across different geographical locations by customers.
- Customizable dashboards for farmers to visualize collected information.
- Specification of thresholds for triggering alerts based on various factors.
- Tracking of fish harvest information for analysis and modeling.
- Provision for insights.
- Timely generation of alerts to address sudden changes in water quality or adverse weather events.
- Accessibility from various devices, including rugged industrial devices used in remote locations.

## Approach
- [General Architecture](./Solution/README.md)

## Architectural Decision Records (ADR)
- [ADR-001: Use of Satellites for Data Transfer in Remote Fish Farms](ADR/ADR-001:%20Use%20of%20Satellites%20for%20Data%20Transfer%20in%20Remote%20Fish%20Farms.md)
- [ADR-001: Use of Mobile Devices for Data Transfer in Remote Fish Farms](ADR/ADR-001:%20FUse%20Fof%20FMobile%20FDevices%20Ffor%20FData%20FTransfer%20Fin%20FRemote%20FFish%20FFarms.md)
- [ADR-003: Use of MQTT for Data Fetching from IoT Sensors](ADR/ADR-003:%20Use%20of%20MQTT%20for%20Data%20Fetching%20from%20IoT%20Sensors.md)
- [ADR-004: Adoption of Google Cloud Platform as the Choice of Cloud Provider](ADR/ADR-004:%20Adoption%20of%20Google%20Cloud%20Platform%20as%20the%20Choice%20of%20Cloud%20Provider.md)