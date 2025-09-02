This project aims to design and implement a smart lighting system that automates indoor and outdoor lighting control in an apartment environment, with the ability to seamlessly extend to larger homes or residential complexes.

The system integrates IoT hardware, Node-RED flows, and a cloud backend on AWS to deliver real-time, secure, and energy-efficient lighting automation. Both motion-based triggers and time-based rules will be supported, alongside manual overrides via a web interface or voice assistant.

Key features:
1) Motion and ambient light sensing for occupancy-based lighting.
2) Gradual dimming during night hours for comfort.
3) Outdoor light automation based on motion and time of day.
4) Cloud integration with AWS IoT Core, Lambda, and DynamoDB for data logging, scalability, and analytics.
5) User controls through Node.js dashboard and optional voice integration.

Success Metrics:
The project will be considered successful if it achieves the following measurable outcomes:
1) Low-Latency Response
Light actuation occurs within ≤500 ms of a motion or lux event being detected.

2) Scalability
The system can simulate and handle at least 100+ sensor messages per second without failures, demonstrating AWS Lambda auto-scaling and SQS buffering.

3) Reliability
Lights correctly follow automation rules (on/off, dimming, overrides) with a >95% success rate in test scenarios.

4) Security
All device-to-cloud communication is encrypted with TLS.
IoT devices use unique X.509 certificates and least-privilege access policies.

5) User Experience
Residents can manually override automation via the dashboard or voice assistant.
Clear visibility into device states and event logs is provided.

6)Energy Efficiency
Automated rules demonstrate measurable savings by reducing unnecessary light usage (tracked via test reports or simulated energy data).

Deliverables:
1) GitHub repository with source code, Node-RED flows, and documentation.

2) Working prototype (Raspberry Pi + ESP32 + sensors + smart bulbs).

3) Cloud backend with AWS IoT Core, Lambda, DynamoDB, and SQS.

4) Video demonstration of end-to-end system operation.

5) Security and performance validation report.
