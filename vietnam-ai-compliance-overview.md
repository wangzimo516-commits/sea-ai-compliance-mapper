# Vietnam AI Compliance Overview (2026)

## 1. Core Legal Framework
Vietnam has entered a new era of digital governance in 2026. The **Personal Data Protection Law (PDPL)** (Law No. 91/2025/QH15) took effect on January 1, 2026, followed by the **Law on Artificial Intelligence** (Law No. 134/2025/QH15) on March 1, 2026. 

Together with Decree 356/2025/ND-CP (implementing PDPL), these laws establish a strict regulatory framework for AI training, data mining, and content generation.

## 2. Key Compliance Traps for Outbound Enterprises

### Trap 1: Missing "AI Generated" Labels
*   **Regulation:** Under the AI Law (Article 11, Clause 4), any AI-generated or edited audio, image, or video that simulates real people or events (Deepfakes) must have easily identifiable labels.
*   **Business Impact:** Providers must embed **machine-readable metadata**. Deployers must clearly indicate to users when they are interacting with an AI system. News media must label all AI-generated content.
*   **Penalties:** Non-compliance leads to severe administrative fines, suspension of operations, and potential criminal liability.

### Trap 2: Cross-Border Data Transfer Without TIA/DPIA
*   **Regulation:** Under the PDPL, using Vietnamese citizen data for AI model training requires explicit consent. If data is sent to offshore servers (e.g., servers in China) for training or inference, this is a regulated cross-border transfer.
*   **Business Impact:** Organizations must submit a **Data Protection Impact Assessment (DPIA)** and a **Transfer Impact Assessment (TIA)** to the A05 Authority (Cybersecurity and High-Tech Crime Prevention Department).
*   **Penalties:** Fines can reach up to **5% of annual revenue** for illegal cross-border data transfers.

### Trap 3: The "High-Risk" Localization Trap
*   **Regulation:** Vietnam released a list of 46 high-risk AI systems in June 2026 (Decision No. 33/2026/QD-TTg). This includes AI used in recruitment, credit scoring, education, medical diagnosis, and critical infrastructure.
*   **Business Impact:** High-risk AI systems must undergo mandatory conformity certification. Foreign providers must establish a **local commercial presence (physical entity)** or appoint an authorized representative in Vietnam.
*   **Timeline Grace Period:** 
    *   General AI: 12 months (until March 1, 2027)
    *   High-risk sectors (Healthcare, Education, Finance): 18 months (until September 1, 2027)

## 3. Action Checklist for Founders
- [ ] Audit your frontend UI: Add clear AI labels to all generated content.
- [ ] Map your cloud architecture: If Vietnamese user data leaves the country, immediately start the TIA/DPIA process.
- [ ] Check the 46 high-risk categories: Plan your local entity or authorized representative early.
- [ ] Implement 72-hour breach reporting protocols.

## Status: Week 0 — Vietnam Country Profile Initialized
