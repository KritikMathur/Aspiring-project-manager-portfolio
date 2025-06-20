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
| Deliver a stable cross-platform iOS/Android app                           | • Crash rate ≤ 0.8 % in first 30 days<br>• App Store rating ≥ 4.2 |
| Acquire 50 000 registered users within first 3 months                     | • 50 000 sign-ups by Nov 7, 2025<br>• 35 % MAU retention         |
| Process ₹ 200 M in transaction volume by Q1 2026                          | • ₹ 200 M processed<br>• Transaction success ≥ 98 %              |
| Achieve PCI-DSS compliance and complete all security audits               | • Passed external audit by Aug 1, 2025<br>• Zero critical findings|

---

## 3. Scope  

### In Scope  
- **Platforms:** Native iOS & Android (React Native)  
- **Features:**  
  - User registration, KYC (Aadhaar OTP), biometric login  
  - P2P transfers, bill splitting, QR-code merchant payments  
  - Transaction history, receipts, real-time push notifications  
- **Integrations:**  
  - PayGateX payment-gateway API  
  - UPI/IMPS/NEFT bank linking  
  - Firebase Cloud Messaging for notifications  
- **Testing:**  
  - Unit/integration tests (≥ 80 % coverage)  
  - Usability testing with 200 beta users  
  - Performance load testing up to 5 000 concurrent sessions  

### Out of Scope  
- Cryptocurrency or NFC payments  
- Web/desktop client (Phase II)  
- Loyalty/rewards program  

---

## 4. Key Stakeholders & Roles  

| Role                   | Name / Team                 | Responsibilities                                      |
|------------------------|-----------------------------|-------------------------------------------------------|
| **Project Sponsor**    | Rahul Verma (CPO)           | Budget approval & strategic oversight                 |
| **Project Manager**    | Kritik Mathur               | Schedule, resource allocation, risk management        |
| **Product Owner**      | Kriti Sharma (PMO)          | Backlog prioritization & acceptance criteria          |
| **Lead Architect**     | Aman Singh (Dev Team)       | Technical design & API specifications                 |
| **UX/UI Lead**         | Neha Patel (Design Team)    | Wireframes, prototypes & UI guidelines                |
| **QA Lead**            | Vikram Das (QA Team)        | Test plans, defect triage & release sign-off         |
| **Security Officer**   | Dr. Rohit Mehra (InfoSec)   | Security requirements & PCI-DSS compliance            |
| **Marketing Manager**  | Priya Kapoor (Marketing)    | Go-to-market strategy & launch communications          |
| **Operations Lead**    | Sunil Rao (Ops Team)        | Support readiness & fraud-monitoring                  |

---

## 5. Milestones & Timeline  

| Milestone                                  | Planned Date   |
|--------------------------------------------|---------------:|
| Charter Approval & Kickoff                 | June 20, 2025  |
| UX/UI Prototype Complete                   | June 27, 2025  |
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
| UX/UI Design & Prototyping    | 150 000               |
| Development (iOS, Android)    | 600 000               |
| QA, Testing & Security Audit  | 200 000               |
| Infrastructure & Licenses     | 100 000               |
| Marketing & Launch Campaign   | 250 000               |
| **Total**                     | **1 300 000**         |

---

## 7. Assumptions & Constraints  

- **Assumptions:**  
  - PayGateX API available in sandbox by June 22.  
  - Beta users test on both Android & iOS.  
  - No major regulatory changes before launch.  
- **Constraints:**  
  - Budget capped at ₹ 1.3 M.  
  - Must comply with RBI guidelines & PCI-DSS.  
  - Team availability limited by other programs.

---

## 8. High-Level Risks  

| Risk ID | Description                        | Likelihood | Impact | Mitigation                         |
|---------|------------------------------------|-----------:|-------:|------------------------------------|
| R1      | Delay in Payment Gateway integration | Medium     | High   | Early sandbox testing & backup vendor |
| R2      | Major UX rework post-beta feedback   | High       | Medium | Schedule a buffer sprint            |
| R3      | Critical issues in Security Audit    | Low        | High   | Conduct internal pre-audit          |
| R4      | Regulatory changes on KYC requirements | Medium     | Medium | Ongoing legal counsel & monitoring  |
| R5      | Performance bottlenecks at peak load  | Medium     | High   | Capacity testing & auto-scaling      |

---

## 9. Communication Plan  

| Audience           | Method                    | Frequency       | Owner             |
|--------------------|---------------------------|----------------:|-------------------|
| Executive Sponsor  | Steering Committee Report | Bi-weekly       | Project Manager   |
| Dev Team           | Daily Stand-up (15 min)   | Daily           | Scrum Master      |
| QA & Security      | Defect Triage Meeting     | 2× per week     | QA Lead           |
| Marketing & Ops    | Launch Readiness Review   | Weekly          | Marketing Manager |
| All Stakeholders   | Project Newsletter        | Monthly         | Project Manager   |

---

## 10. Approval  

By signing below, the Project Sponsor formally authorizes Phase I:

| Name           | Role            | Signature | Date         |
|----------------|-----------------|-----------|-------------:|
| Rahul Verma    | Project Sponsor | __________| June 20, 2025 |
| Kritik Mathur  | Project Manager | __________| June 20, 2025 |
