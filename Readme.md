# Carousell Internal Strategy Investment Memo 

## Project Overview
This project presents an internal strategy proposal for **Carousell**, focused on strengthening its payment ecosystem (CarouPay) by addressing trust, transaction safety, and monetization challenges in Southeast Asia’s second-hand marketplace.

The proposal reframes CarouPay from a passive payment option into a trust-as-a-service platform, integrating escrow, credit scoring, and premium protection to unlock suppressed demand in high-value C2C transactions.

## Business Problem
Despite strong growth in Southeast Asia’s recommerce market, high-value transactions (>USD 100) remain constrained by:
- Payment and transaction risk
- Product authenticity and quality concerns
- Low trust in peer-to-peer trades conducted off-platform

These frictions suppress GMV, penalize legitimate sellers, and limit Carousell’s ability to monetize premium categories such as luxury goods and electronics.

## Strategic Solution
The proposal introduces a two-layer FinTech trust framework:

### 1. Mandatory Escrow via CarouPay (High-Value Transactions)
- Funds held securely until delivery and verification
- Reduces buyer–seller transaction risk
- Increases platform stickiness and payment penetration

### 2. Premium Protection (Trust-as-a-Service)
- Third-party authentication and quality inspection
- Extended warranties and insured returns
- Monetizes trust while enabling higher-priced listings

Together, these features convert “authenticity anxiety” into a confident, retail-like purchase experience.

## Quantitative Analysis
The strategy is supported by rigorous financial modeling:

- **Discounted Cash Flow (DCF)** valuation
  - NPV: S$7.5M
  - IRR: 27.8%
- **Monte Carlo Simulation (10,000 runs)**
  - Mean NPV: S$9.4M
  - Mean IRR: 27.5%
  - Positively skewed payoff profile with limited downside

Key drivers analyzed:
- GMV growth
- CarouPay penetration
- High-value goods attach rate
- Discount rate sensitivity

## Technical Proof of Concept
A modular, event-driven architecture is proposed to support escrow, trust scoring, and protection services:

- API Gateway with authorization and rate limiting
- Event Bus (Pub/Sub) for transaction state orchestration
- PostgreSQL and Redis for transactional integrity
- Immutable audit logs for reconciliation and compliance
- Asset-light integration with third-party authentication partners

This design ensures scalability, regulatory readiness, and minimal operational overhead.

## Tools & Skills Demonstrated
- FinTech strategy & embedded finance
- Financial modeling (DCF, Monte Carlo)
- Risk and trust analytics
- Event-driven system design
- Marketplace economics
- SEA fintech and regulatory awareness
