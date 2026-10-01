# Animal Rescue and Aid Platform - Project Documentation

## 1. Project Overview
The **Animal Rescue and Aid Platform** is a comprehensive software solution designed to bridge the gap between stray/injured animals, rescuers, veterinarians, volunteers, and adopters. It integrates AI-driven injury assessment, geolocation-based veterinary services, real-time tracking, donation crowdfunding, and an adoption portal.


---

## 2. Estimation & Software Metrics
Based on project estimation calculations:
- **Expected lines of code (LOC):** $6000 = 6 \text{ KLOC}$
- **Effort Calculation (COCOMO / Custom Formula):**
  $$\text{PM} = 2.4 \times \left(\frac{6000}{1000}\right)^{1.05} = 15.74 \text{ Person-Months}$$
- **Development Time ($T_{dev}$):**
  $$\text{TDM} = 2.50 \times (15.74)^{0.38} = 7.19 \text{ Months}$$
- **Staffing Estimation:**
  $$\text{Staffing (ST)} = \frac{\text{PM}}{\text{TDM}} = \frac{15.74}{7.19} \approx 2.19 \approx 3 \text{ members}$$

---

## 3. Project Risk Management Table

| Risks | Category | Probability | Impact | RMMM / Mitigation |
| :--- | :---: | :---: | :---: | :--- |
| Size estimate may be significantly low | PS | 60% | 2 | Refine scope iteratively during sprint planning |
| Larger number of users than planned | PS | 30% | 3 | Design scalable cloud infrastructure |
| Less reuse than planned | PS | 70% | 2 | Enforce modular architecture and component libraries |
| End-users resist system | BU | 40% | 3 | Focus on intuitive UX/UI design and easy onboarding |
| Delivery deadline will be tightened | BU | 50% | 2 | Prioritize MVP features via Agile Scrum methodology |
| Funding will be lost | CU | 40% | 1 | Diversify funding streams and secure initial grants |
| Customer will change requirements | PS | 80% | 2 | Use Agile backlog prioritization and regular feedback loops |
| Technology will not meet expectations | TE | 30% | 1 | Conduct early proof-of-concept tests for AI tools |
| Lack of training on tools | DE | 80% | 3 | Provide comprehensive tutorials and documentation |
| Staff inexperienced | ST | 30% | 2 | Implement paired programming and workshops |
| Staff turnover will be high | ST | 60% | 2 | Maintain transparent documentation and cross-training |
| Inadequate testing leading to bugs | PR | 50% | 2 | Automate unit and integration testing pipelines |
| Insufficient project documentation | PR | 60% | 3 | Mandate documentation sprints throughout development |
| Delays in resource allocation | DE | 50% | 2 | Establish early resource procurement plans |

*Impact scale:* 1—Catastrophic, 2—Critical, 3—Marginal, 4—Negligible.

---

## 4. Key Test Cases Summary

- **FR_1 (User Registration):** Verify registration with valid name, email, and password. (Priority: High)
- **FR_2 (Login Functionality):** Verify login redirect for registered users. (Priority: High)
- **FR_3 (Search Functionality):** Filter adoptable pets by location and type. (Priority: Medium)
- **FR_4 (Rescue Request):** Submit rescue reports for injured animals with location data. (Priority: High)
- **FR_5 (Volunteer Management):** Register volunteers and update profiles. (Priority: Medium)
- **FR_6 (Donation Feature):** Process donations for specific rescue causes and generate receipts. (Priority: Medium)
- **FR_7 (Adoption Application):** Submit digital adoption applications for pets. (Priority: Medium)
- **FR_8 (Password Recovery):** Secure token-based password reset flow. (Priority: Medium)

---

## 5. Software Development Life Cycle (SDLC)
- **Model Selected:** **Scrum (Agile)**
- **Justification:** Ideal for dynamic requirements, small teams (4-6 members), iterative progress, and regular stakeholder feedback loops compared to rigid models like Waterfall.
