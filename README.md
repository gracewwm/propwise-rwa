# PropWise RWA

PropWise RWA is a Web3 platform that enables Indonesian Gen Z to access residential property ownership without taking on decades-long mortgage debt. Users can browse tokenized residential properties, review AI-generated analysis on valuation, rental yield, and risk, and purchase fractional ownership on-chain starting from small amounts. By combining real-world asset tokenization with AI-driven due diligence, PropWise RWA makes property investing more accessible, transparent, and liquid for a generation priced out of traditional homeownership.

## Problem Statement

Indonesian Gen Z faces a severe housing affordability crisis. Residential property prices have climbed into the billions of Rupiah, while average incomes have not kept pace. For most young adults, the only path to ownership is a traditional mortgage (KPR), which requires large down payments and locks them into decades of debt. At the same time, property investment is difficult to evaluate because buyers often lack transparent, trustworthy analysis of valuation, rental yield, and long-term risk. PropWise RWA addresses this by turning residential properties into fractional on-chain assets and pairing them with AI-driven investment analysis, allowing young buyers and retail investors to access real estate in a more affordable, transparent, and flexible way.

## Student Founder Proof

- Name: Grace Olivia Panjaitan
- University: Prasetiya Mulya University
- Telegram Handle: [@geotril](https://t.me/geotril)

## Technical Architecture

This section will be expanded with the full system design, including:

- Smart contract architecture for property tokenization on Base
- Fractional ownership model and investor flows
- AI analysis pipeline for valuation, yield, and risk assessment
- Frontend application flow built with Next.js
- Deployment and infrastructure components

  ## 🤖 AI Agent Roles (The "PropWise Copilot")
To ensure Gen Z investors make data-driven decisions without needing a background in real estate, PropWise RWA utilizes autonomous AI agents deployed on the Base ecosystem:

1. **Yield & Valuation Analyst Agent:** * Continuously scans macro-economic data and local property trends in emerging markets (like Indonesia).
   * Calculates projected Annual Percentage Yield (APY), ROI, and fair market value for each tokenized asset.
2. **Risk & Due Diligence Agent:**
   * Acts as an automated auditor. It cross-references legal documents, developer track records, and historical price volatility to assign a dynamic "Risk Score" (A+ to C) to every property.
3. **Personalized Wealth Matchmaker:**
   * Conversational AI that interacts with users to understand their risk appetite and budget, recommending the perfect fractional RWA portfolio.

## 🏗️ Technical Architecture (High-Level)
PropWise RWA is designed to be secure, scalable, and fully integrated with the **Base Mainnet**:

* **Smart Contracts (Base Mainnet):** * **Fractionalization:** Utilizing ERC-1155 / ERC-3643 standards to tokenize real-world properties into affordable fractional shares.
  * **Payment & Escrow:** Seamless integration with **USDC** for low-fee, instantaneous property share purchases and yield distribution.
* **AI Integration Layer:**
  * Off-chain AI agents fetch real-time market data, process it, and feed the verified analytical data back to the platform to guide user investments.
* **User Experience:**
  * A mobile-first, Web2-friendly interface with Account Abstraction (ERC-4337) to remove the friction of gas fees and seed phrases for mainstream Gen Z users.
