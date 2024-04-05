# ADR-003: Use of MQTT for Data Fetching from IoT Sensors

## Status: Accepted

## Context
In Fish Watch, data from IoT sensors installed in fish farm enclosures needs to be fetched and transmitted to the central monitoring system for analysis and visualization. The choice of communication protocol is critical to ensure efficient and reliable data transfer, especially in remote locations with limited network connectivity.

## Decision
We have decided to use MQTT (Message Queuing Telemetry Transport) as the communication protocol for fetching data from IoT sensors. MQTT is a lightweight, publish-subscribe messaging protocol widely used in IoT applications due to its efficiency, low bandwidth requirements, and support for reliable communication in challenging network conditions.

## Rationale
The decision to use MQTT is based on the following considerations:
- Lightweight: MQTT's minimal overhead makes it well-suited for resource-constrained IoT devices, enabling efficient data transfer without excessive bandwidth consumption.
- Publish-Subscribe Model: MQTT's publish-subscribe architecture allows for asynchronous communication between IoT sensors and the central monitoring system, facilitating scalable and decoupled data exchange.
- Reliability: MQTT supports quality of service (QoS) levels for message delivery, ensuring reliable communication even in unreliable network environments.
- Flexibility: MQTT's topic-based messaging model provides flexibility in organizing and routing data streams, enabling efficient data filtering and distribution.


## Alternatives
Alternative communication protocols considered for fetching data from IoT sensors included HTTP, CoAP (Constrained Application Protocol), and AMQP (Advanced Message Queuing Protocol). However, MQTT was chosen for its lightweight nature, reliability, and suitability for IoT applications.

## Notes
- Careful consideration should be given to MQTT broker selection, considering factors such as scalability, reliability, and support for QoS levels.
- Security measures such as encryption and authentication should be implemented to protect MQTT communication from unauthorized access and data breaches.
- Regular monitoring and performance tuning of MQTT infrastructure will be essential to ensure optimal operation and responsiveness.
