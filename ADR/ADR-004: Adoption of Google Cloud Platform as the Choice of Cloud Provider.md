# ADR-004: Adoption of Google Cloud Platform as the Choice of Cloud Provider

## Status: Accepted

## Context
In Fish Watch, a robust and scalable cloud infrastructure is required to support data storage, processing, analysis, and predictive modeling. The choice of cloud provider is critical to ensure reliability, performance, and availability of services. Additionally, access to advanced predictive AI services is desirable to enhance fish farm monitoring and management capabilities.

## Decision
We have decided to adopt Google Cloud Platform (GCP) as the choice of cloud provider for Fish Watch. GCP offers a comprehensive suite of cloud services, including data storage, computing, analytics, and machine learning, making it well-suited for our requirements. Furthermore, GCP's advanced predictive AI services, such as Google Cloud AI, provide powerful tools for analyzing data and deriving actionable insights, which can significantly enhance fish farm monitoring and management capabilities.

## Rationale
The decision to choose GCP is based on the following factors:
- Comprehensive Services: GCP offers a wide range of cloud services, including Google Cloud Storage for data storage, Google Compute Engine for computing resources, and BigQuery for data analytics, providing a scalable and integrated platform for building and deploying applications.
- Predictive AI Services: GCP's predictive AI services, such as Google Cloud AI Platform and AutoML, provide powerful tools for analyzing data, building machine learning models, and generating predictions, enabling advanced analytics and decision-making in fish farm management.
- Reliability and Performance: GCP's global infrastructure ensures high reliability, performance, and availability of services, with data centers located strategically around the world to minimize latency and ensure seamless operation.
- Integration with Google Ecosystem: GCP integrates seamlessly with other Google services and products, such as Google Cloud IoT Core for IoT device management, Google Maps for geospatial analysis, providing a cohesive ecosystem for developing and deploying applications.

## Implications
- Integration with GCP's predictive AI services will necessitate training and upskilling of team members to leverage these capabilities effectively.
- Consideration should be given to security and compliance requirements when storing and processing sensitive data on GCP.

## Alternatives
Alternative cloud providers considered for hosting Fish Watch infrastructure included Amazon Web Services (AWS) and Microsoft Azure. However, GCP was chosen for its comprehensive services, advanced predictive AI capabilities, and seamless integration with the Google ecosystem.

## Related ADRs
None

## Notes
- Regular evaluation of GCP services and pricing options will be important to ensure alignment with Fish Watch requirements and budget constraints.
- Continuous monitoring of GCP infrastructure performance and security will be essential to maintain operational excellence.


