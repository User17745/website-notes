---
layout: default
title: NeGD Study Notes
---
# National e-Governance Division (NeGD) - Project Introduction Notes

This document provides a technical and operational overview of the National e-Governance Division (NeGD) to assist the incoming technical Project Manager.

## 1. Overview & Mission
NeGD was established in 2009 by the Ministry of Electronics & Information Technology (MeitY) as an Independent Business Division within the Digital India Corporation.

*   **Core Role:** NeGD serves as the central agency for providing strategic direction and framing policies for the **Digital India Programme**.
*   **Support Mandate:** It offers technical and advisory support to Central and State Government departments for 'Mission Mode' Projects (MMPs).
*   **Goal:** To transform India into a digitally empowered society and knowledge economy by streamlining government service delivery through technology.

## 2. Key Projects & Platforms
NeGD manages some of the largest digital public infrastructure (DPI) projects in the world:

| Project | Description | Technical Significance |
| :--- | :--- | :--- |
| **DigiLocker** | Digital document issuance and verification. | Eliminates physical document dependency; uses secure URI-based access. |
| **UMANG** | Unified Mobile Application for New-age Governance. | Aggregates 1,500+ services; high-concurrency mobile/web architecture. |
| **API Setu** | Open API platform for Gov-to-Gov and Gov-to-Business data exchange. | Foundation for interoperability in the Indian digital ecosystem. |
| **MeriPehchaan** | National Single Sign-On (NSSO). | Centralized authentication service (SAML/OAuth based concepts). |
| **myScheme** | e-Marketplace for government schemes. | Search and discovery engine for eligibility-based schemes. |
| **OpenForge** | Collaborative development platform for e-Gov software. | Promotes open-source and code sharing across government departments. |

## 3. Technical & Operational Divisions

| Division | Focus & Responsibility |
| :--- | :--- |
| **Technology Management** | Technology selection, ICT strategy, security policies, and architectural appraisal. |
| **Infrastructure (Mobile & Cloud)** | Deployment environments (GI Cloud / MeghRaj) and mobile service delivery gateways. |
| **Standards & Appraisals** | Adherence to national e-governance standards, interoperability frameworks, and security audits. |
| **Capacity Building** | Training and skill development for government officials for digital transitions. |

## 4. Key Considerations for the Technical PM

| Consideration | Details |
| :--- | :--- |
| **Interoperability** | Most NeGD projects are designed to be "interoperable" via API Setu. |
| **Scalability** | Systems like UMANG and DigiLocker handle millions of users daily; performance engineering is critical. |
| **Security** | Adherence to STQC and CERT-In guidelines is mandatory for all projects. |
| **UI/UX** | The UX4G initiative aims to standardize and improve user experience across all government portals. |

## 5. Technical Stack & Infrastructure

| Category | Component | Details |
| :--- | :--- | :--- |
| **CMS** | WordPress | Core platform for content delivery. |
| **Cloud Provider** | AWS | EC2 instances for hosting. |
| **Traffic Mgmt** | Amazon ALB | Application Load Balancer with Sticky Session support. |
| **Storage & CDN** | Amazon S3 & Cloudflare | Optimized global delivery and storage. |
| **Front-end** | Foundation Framework | Responsive front-end toolkit. |
| **JS Libraries** | jQuery (3.7.1), Slick JS, Popper.js | Interaction, animation, and UI widgets. |
| **Security** | SSL/HSTS, DMARC, SPF | Encrypted communication and email security (Reject policy). |
| **Authentication** | Google Identity Platform | Secure sign-in integrations. |
| **Analytics/SEO** | Yoast SEO, Google Webmaster | SEO optimization and performance insights. |
| **Insights** | Power BI, CrUX | Data visualization and real user experience data. |

## 6. Traffic & Engagement Analysis

| Metric | Value / Detail |
| :--- | :--- |
| **Monthly Reach** | ~114,826 visits (Audit period total: >341K). |
| **Avg. Visit Duration** | 03:21 minutes. |
| **Pages per Visit** | 2.83. |
| **Bounce Rate** | ~41.12%. |
| **Demographics** | Primarily India (>95%), followed by US, Singapore, and UK. |
| **Top Channels** | Direct and Organic Search (Strong brand recall and SEO). |

## 7. Reference Links

| Resource | URL |
| :--- | :--- |
| **Official Website** | [https://negd.gov.in/](https://negd.gov.in/) |
| **DigiLocker** | [https://www.digilocker.gov.in/](https://www.digilocker.gov.in/) |
| **UMANG** | [https://web.umang.gov.in/](https://web.umang.gov.in/) |
| **API Setu** | [https://apisetu.gov.in/](https://apisetu.gov.in/) |
