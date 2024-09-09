# Applying PASTA Threat Modeling Framework for a Shopping Application

## Project Overview

This project involves using the Process of Attack Simulation and Threat Analysis (PASTA) framework to assess the risk profile of a mobile shopping application for a sneaker company. The objective is to identify potential security vulnerabilities, threats, and necessary controls to protect the app before its launch.

## Objectives

- Threat Modeling: Perform a comprehensive threat model for the sneaker company’s new mobile shopping app using the PASTA framework.
- Risk Assessment: Identify vulnerabilities and threats, and map them to potential attacks that may exploit these weaknesses.
- Mitigation Strategies: Propose security controls to reduce the likelihood and impact of potential security incidents.

### Skills Learned

- Threat Modeling: Gained experience using the PASTA framework to perform in-depth risk analysis of a mobile application.
- Risk Identification: Developed the ability to assess the security risks posed by various technologies, processes, and attack vectors.
- Vulnerability Assessment: Learned how to identify system vulnerabilities based on real-world threats and potential attacks.
- Security Control Implementation: Acquired knowledge in proposing security measures that reduce the likelihood of exploitation.

### Tools Used

- PASTA Threat Model Framework
- OWASP Top Ten
- PCI-DSS
- PowerPoint

## Steps

### Part 1: Preparation

- Access the Template and Supporting Materials: Downloaded the PASTA worksheet to guide the threat model process and opened the PASTA data flow diagram and attack tree resources to assist in understanding the app’s processes and potential attack vectors.

### Part 2: Complete the PASTA Stages

#### Stage I – Identify Business Objectives: 
- Reviewed the app's objectives, such as enabling smooth transactions, ensuring data privacy, and handling payments securely.

#### Stage II – Evaluate App Components: 
- Evaluated key technologies like APIs, PKI, SHA-256, and SQL used by the app, prioritizing encryption and data handling for security assessment.

#### Stage III – Review Data Flow Diagram: 
- Analyzed how data flows through the app and considered how encryption and API interactions secure sensitive user information.
  
  <div align="center">
    <img src="https://github.com/user-attachments/assets/c5b81f51-da9c-435c-b86e-ac24eb30bdc2" alt="image" width="800"/>
</div>


#### Stage IV – Analyze Potential Threats: 
- Identified threats like API misuse and weak encryption, which could lead to unauthorized access or data breaches.

#### Stage V – Identify Vulnerabilities: 
- Listed vulnerabilities such as improper encryption implementation in payment systems or inadequate authentication mechanisms.

#### Stage VI – Map to Attack Tree: 
- Mapped identified threats and vulnerabilities to attack vectors, visualizing how they could be exploited through an attack tree.

  <div align="center">
    <img src="https://github.com/user-attachments/assets/3fa5cd89-d681-4a6f-8484-8652a174f155" alt="image" width="800"/>
</div>

#### Stage VII – Propose Security Controls: 
- Suggested four security controls, including multi-factor authentication (MFA), improved encryption standards, regular security audits, and implementing secure coding practices to reduce risks.
