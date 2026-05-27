# Lab 01: Wazuh and The Observer Architecture

## 1. Objective
This laboratory focuses on the implementation of **Wazuh** as the core surveillance mechanism. The objective is to establish a unified observation point to achieve full-spectrum visibility, detect anomalies in real-time, and analyze potential security incidents within the network infrastructure.

## 2. Methodology: The Triad of Defensive Intelligence
Our operational framework is built upon the **Triad of Defensive Intelligence**, ensuring a holistic approach to incident detection and response:

* **Visibility:** Establishing full-spectrum observability by centralizing logs and endpoint data through Wazuh agents. We ensure no shadow remains unlit.
* **Correlation:** Transforming raw data into actionable intelligence. By applying custom decoders and rules, we isolate the signal (malicious behavior) from the noise (normal system operations).
* **Response:** Translating detection into mitigation. This stage focuses on automating containment protocols and refining our security posture based on observed threat vectors.

## 3. Operational Setup
* **Centralized Analysis:** Wazuh Manager
* **Endpoint Monitoring:** Wazuh Agent (Deployed on critical assets)
* **Intelligence Stack:** Elastic Stack integration for visual intelligence and dashboarding.

## 4. Configuration & Rules
* **Deployment:** [Briefly describe how you deployed the Manager/Agent]
* **Custom Rules:** *Detailed rules are documented in the `/config` directory.*
    * Example: [Mention one key rule, e.g., Brute-force detection rule]

## 5. Analysis & Observations
* **Initial Findings:** [Summarize what you observed upon successful deployment]
* **Anomalies Detected:** [List significant alerts or patterns identified during the initial monitoring phase]

---
*The logs do not lie; they only wait for a mind capable of reading them.*
