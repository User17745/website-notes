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
The new Technical PM should be aware of the internal divisions that handle various stages of project lifecycles:

*   **Technology Management:** Focuses on technology selection, ICT strategy, security policies, and architectural appraisal.
*   **Infrastructure (Mobile & Cloud):** Manages the deployment environments (GI Cloud / MeghRaj) and mobile service delivery gateways.
*   **Standards & Appraisals:** Ensures projects adhere to national e-governance standards, interoperability frameworks, and security audits.
*   **Capacity Building:** Focuses on training and skill development for government officials to handle digital transitions.

## 4. Key Considerations for the Technical PM
*   **Interoperability:** Most NeGD projects are designed to be "interoperable" via API Setu.
*   **Scalability:** Systems like UMANG and DigiLocker handle millions of usersDaily; performance engineering is critical.
*   **Security:** Adherence to STQC (Standardisation Testing and Quality Certification) and CERT-In guidelines is mandatory for all projects.
*   **UI/UX:** The **UX4G** initiative aims to standardize and improve the user experience across all government portals.

## 5. Technical Stack & Infrastructure
For the incoming Technical PM, understanding the underlying technology is crucial for maintenance and scaling:

*   **Content Management System (CMS):** WordPress (Core platform for content delivery).
*   **Infrastructure & Hosting:**
    *   **Cloud Provider:** Amazon Web Services (AWS) - EC2 instances.
    *   **Traffic Management:** Amazon Application Load Balancer (ALB) with Sticky Session support.
    *   **CDNs:** Amazon S3 CDN and Cloudflare for optimized global delivery.
*   **Front-end Development:**
    *   **Framework:** Foundation (Responsive front-end framework).
    *   **Libraries:** jQuery (3.7.1), jQuery UI, Slick JS (Carousels), and Popper.js.
*   **Security & Accessibility:**
    *   **Encryption:** SSL by Default with HSTS (Strict Transport Security).
    *   **Email Security:** DMARC (Reject policy for high security) and SPF.
    *   **Authentication:** Integration with Google Identity Platform for secure sign-ins.
*   **Analytics & SEO:**
    *   **SEO:** Yoast SEO Premium.
    *   **Insights:** Google Webmaster Tools and CrUX (Chrome User Experience) dataset.
    *   **Data Visualization:** Microsoft Power BI integration for rich visuals.

## 6. Traffic & Engagement Analysis
Based on recent traffic audits (Dec 2025):

*   **Reach:** ~114,826 monthly visits, with total visits exceeding 341K in the audit period.
*   **Engagement:**
    *   **Avg Visit Duration:** 03:21 minutes.
    *   **Pages per Visit:** 2.83.
    *   **Bounce Rate:** ~41.12%.
*   **Demographics:** Primarily Indian audience (>95%), with secondary traffic from the US, Singapore, and UK.
*   **Top Channels:** High "Direct" and "Organic Search" traffic, indicating strong brand recall and SEO performance.

## 7. Reference Links
*   **Official Website:** [https://negd.gov.in/](https://negd.gov.in/)
*   **DigiLocker:** [https://www.digilocker.gov.in/](https://www.digilocker.gov.in/)
*   **UMANG:** [https://web.umang.gov.in/](https://web.umang.gov.in/)
*   **API Setu:** [https://apisetu.gov.in/](https://apisetu.gov.in/)
