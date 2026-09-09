# User Stories — Dealer Evaluation Modernization

Written as part of planning the modernization of the Dealer Evaluation application, following Agile/Scrum practices.

## Epic: Modernize Dealer Evaluation for Cloud Deployment

A large, high-level piece of work covering the transition of Dealer Evaluation from a locally-run, hardcoded-data application to a cloud-hosted, containerized, data-driven application.

---

### User Story 1: Containerizing the Application

**As a** Developer,
**I want to** containerize the application using Docker
**so that** it can be easily deployed, scaled, and managed in different environments.

So that the application runs consistently across different environments (development, testing, production). Dependencies are managed efficiently without conflicts. And deployment and scaling become easier.

---

### User Story 2: Deploying on IBM Cloud

**As a** Developer,
**I want to** deploy the application on IBM Cloud using IBM Cloud Code Engine
**so that** the application can run in a scalable, managed cloud environment instead of relying on self-managed or in-house virtual machines.

So that the application benefits from cloud-native scaling and availability without the overhead of managing physical or virtual infrastructure. Deployment becomes faster and more repeatable. And the application can be accessed reliably from anywhere without depending on in-house hardware.

---

### User Story 3: Read Products and Dealers from JSON

**As a** Developer,
**I want to** load product and dealer data from an external JSON file instead of hard-coded values
**so that** the application's data can be updated without modifying and redeploying the source code.

So that new products and dealers can be added or changed without a code change. The application becomes more maintainable and flexible. And the codebase follows better separation between data and logic, which is standard practice for real-world applications.
