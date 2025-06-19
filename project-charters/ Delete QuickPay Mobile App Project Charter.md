# Project Charter: QuickPay Mobile App

**Project Title:**  
QuickPay Mobile App – Phase I: Peer-to-Peer and Merchant Wallet

**Project Sponsor:**  
Rahul Verma, Chief Product Officer

**Project Manager:**  
Kritik Mathur, Associate Project Manager (APM Candidate)

**Date of Authorization:**  
June 20, 2025

---

## 1. Project Purpose & Background  
The digital payments market in India is projected to grow by 20 % annually through 2027. To capitalize on this, our organization will launch **QuickPay**, a secure, intuitive mobile wallet enabling P2P transfers, bill splitting, and QR-code merchant check-out. This app will position us competitively and drive 15 % growth in our core payments volume within 12 months of launch.

---

## 2. Objectives & Success Criteria  

| Objective                                                                 | Success Criteria (KPI)                                          |
|---------------------------------------------------------------------------|-----------------------------------------------------------------|
| 1. Deliver a stable cross-platform iOS/Android application by Aug 7, 2025 | • Crash rate < 1 % in first 30 days;<br>• App Store rating ≥ 4.0 |
| 2. Acquire 50,000 registered users within first 3 months                   | • 50 k sign-ups;<br>• 30 % monthly active user (MAU) rate       |
| 3. Process ₹200 M in transaction volume by Q1 2026                        | • ₹200 M processed;<br>• Average transaction success ≥ 98 %     |
| 4. Achieve PCI-DSS compliance and complete all security audits            | • Passed external audit;<br>• Zero critical findings           |

---

## 3. Scope  

### In Scope  
- **Platforms:** Native iOS and Android (React Native framework)  
- **Features:**  
  - User registration, KYC, biometric login  
  - P2P transfers and bill splitting  
  - QR-code scanning for merchant payments  
  - Transaction history and receipts  
  - Push notifications and in-app alerts  
- **Integrations:**  
  - Payment gateway API (PayGateX)  
  - Bank account linking via UPI, IMPS, NEFT  
  - Push notification service (Firebase Cloud Messaging)  
- **Testing:**  
  - Unit and integration tests (> 80 % code coverage)  
  - Usability testing with 200 beta users  
  - Performance load testing up to 5,000 concurrent sessions  

### Out of Scope  
- Cryptocurrency or NFC payments  
- Web or desktop client  
- Loyalty or rewards program (Phase II)  
- International payments  

---

## 4. Key Stakeholders & Roles  

| Role                   | Name / Team                 | Responsibilities                                      |
|------------------------|-----------------------------|-------------------------------------------------------|
| **Project Sponsor**    | Rahul Verma (CPO)           | Budget approval, strategic oversight                 |
| **Project Manager**    | Kritik Mathur (APM Candidate)| Schedule, resource allocation, risk management       |
| **Product Owner**      | Kriti Sharma (PMO)          | Feature backlog, prioritization, acceptance criteria  |
| **Lead Architect**     | Aman Singh (Dev Team)       | Technical design, API specification                   |
| **UX/UI Lead**         | Neha Patel (Design Team)    | Wireframes, prototypes, UI guidelines                 |
| **QA Lead**            | Vikram Das (QA Team)        | Test planning, defect triage, release sign-off        |
| **Security Officer**   | Dr. Rohit Mehra (InfoSec)   | Security requirements, PCI-DSS compliance             |
| **Marketing Manager**  | Priya Kapoor (Marketing)    | Go-to-market strategy, launch communications           |
| **Operations Lead**    | Sunil Rao (Ops Team)        | Customer support readiness, fraud monitoring          |

---

## 5. Milestones & Timeline  

| Milestone                                  | Planned Date   |
|--------------------------------------------|---------------:|
| Charter Approval & Kickoff                 | June 20, 2025  |
| Completion of UX/UI Prototypes             | June 27, 2025  |
| Backend & API Development Start            | June 30, 2025  |
| Alpha Release (Internal QA)                | July 10, 2025  |
| Beta Launch to 200 Users                   | July 24, 2025  |
| Security & Performance Testing Complete    | July 31, 2025  |
| Final UAT & Sign-off                       | August 4, 2025 |
| Go-Live (App Stores)                       | August 7, 2025 |

---

## 6. Budget Estimate  

| Category                      | Estimated Cost (₹)    |
|-------------------------------|----------------------:|
| UX/UI Design & Prototyping    | 150,000               |
| Development (iOS, Android)    | 600,000               |
| QA, Testing & Security Audit  | 200,000               |
| Infrastructure & Licenses     | 100,000               |
| Marketing & Launch Campaign   | 250,000               |
| **Total**                     | **1,300,000**         |

---

## 7. Assumptions & Constraints  

- **Assumptions:**  
  - PayGateX API remains stable and available.  
  - Beta users provide timely feedback.  
  - No major regulatory changes occur before launch.  
- **Constraints:**  
  - Fixed budget cap of ₹1.3 M.  
  - Must comply with RBI guidelines and PCI-DSS.  
  - Team availability limited due to other projects.

---

## 8. High-Level Risks  

| Risk ID | Description                                       | Likelihood | Impact | Mitigation Strategy                              |
|---------|---------------------------------------------------|-----------:|-------:|--------------------------------------------------|
| R1      | Payment gateway integration delays                | Medium     | High   | Early API sandbox testing; backup gateway vendor |
| R2      | UX rework after beta feedback                     | High       | Medium | Schedule additional sprint; involve UX early     |
| R3      | Security audit findings critical                  | Low        | High   | Engage InfoSec in design; pre-audit checkpoints  |
| R4      | Regulatory changes affecting KYC requirements     | Medium     | Medium | Monitor RBI updates; maintain legal counsel      |
| R5      | Performance bottlenecks under peak load           | Medium     | High   | Capacity testing; auto-scaling infrastructure    |

---

## 9. Communication Plan  

| Audience            | Communication Type       | Frequency         | Owner               |
|---------------------|--------------------------|------------------:|---------------------|
| Executive Sponsor   | Steering Committee Report| Bi-weekly         | Project Manager     |
| PMO Office          | Status Dashboard         | Weekly            | Project Manager     |
| Development Team    | Daily Stand-up           | Daily (15 min)    | Scrum Master        |
| QA & Security       | Defect Review Meeting    | 2× per week       | QA Lead             |
| Marketing & Ops     | Launch Readiness Review  | Weekly            | Marketing Manager   |
| All Stakeholders    | Project Newsletters      | Monthly           | Project Manager     |

---

## 10. Approval  

By signing below, the Project Sponsor formally authorizes the start of Phase I for the QuickPay Mobile App project:

| Name             | Role             | Signature  | Date         |
|------------------|------------------|------------|--------------|
| Rahul Verma      | Project Sponsor  | __________ | June 20, 2025|
| Kritik Mathur    | Project Manager  | __________ | June 20, 2025|

