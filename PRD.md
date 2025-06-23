**Product Requirements Document (PRD): Orbis AI**

---

## 1. Executive Summary

**Product Name:** Orbis AI
**Description:** A cross-platform mobile/web platform enabling retail traders to copy professional traders, access AI-driven signals and auto-trading, learn trading via interactive AI tutorials, backtest and generate Expert Advisors, and participate in a social/community hub with tokenized rewards.
**Founder:** Solo, non-programmer using AI coding tools (Cursor AI with Claude Code)

---

## 2. Objectives & Goals

* **Deliver Core Functionality:** Enable secure account linking, one-click copy trading, AI signals, and AI-auto trading.
* **Drive Engagement:** Offer social/community features with gamification and token rewards to boost retention.
* **Ensure Scalability:** Build on no-code/low-code platforms (Expo, Supabase, MetaApi, CCXT) and integrate AI for rapid iteration.
* **Streamline Development:** Use GitHub for version control and Cursor AI (with Claude Code) for contextual code generation directly from the PRD.

---

## 3. Target Users

* **Retail Forex & Crypto Traders:** Seek professional strategies and automation without technical overhead.
* **Beginners:** Pursue interactive AI tutorials and guided learning.
* **Strategy Providers:** Share track records, attract followers, and monetize via CopyCoin rewards.
* **Tech Enthusiasts:** Explore blockchain tokens, AI-generated trading bots, and gamified experiences.

---

## 4. Scope & MVP Features

### 4.1. Must-Have (MVP)

1. **Version Control Integration:** GitHub repo linked to Cursor AI for code generation.
2. **User Authentication & Profile** (Supabase)
3. **MT4/MT5 Account Connectivity** via MetaApi
4. **Crypto Account Connectivity** via CCXT
5. **One-Click Copy Trading** (MetaApi CopyFactory)
6. **AI Trade Signals** (GPT-4 API)
7. **AI Auto-Trading** (rule-based execution via API)
8. **AI Advisor Chat** (GPT-4/Claude)
9. **Education Hub:** AI-driven Q\&A and foundational lessons
10. **Community Chat Room** (Supabase real-time)
11. **Leaderboard & Points System:** Simulated CopyCoin rewards

### 4.2. Nice-to-Have (Future Enhancements)

* Backtesting tool with basic strategy simulator
* AI-generated Expert Advisor code
* Token staking interface
* On-chain performance verification
* Gamified contests and badge system
* Push notifications for market events

---

## 5. User Stories

1. **As a trader**, I want to link my MT5 account so I can automatically mirror expert trades.
2. **As a beginner**, I want an AI tutor I can ask questions to deepen my understanding.
3. **As an advanced user**, I want AI-generated market insights to inform my decisions.
4. **As a community member**, I want to engage in chat rooms and compare performance on a leaderboard.
5. **As a contributor**, I want to earn CopyCoin tokens for completing actions and milestones.
6. **As a developer**, I want to reference the PRD in Cursor AI to ensure consistent, high-quality code.

---

## 6. Functional Requirements

| ID    | Requirement                                                          | Priority |
| ----- | -------------------------------------------------------------------- | -------- |
| FR-0  | GitHub repo connected to Cursor AI (Claude Code) for code generation | High     |
| FR-1  | User authentication and profile management                           | High     |
| FR-2  | Secure MT4/MT5 account linking                                       | High     |
| FR-3  | Secure crypto account linking                                        | High     |
| FR-4  | Real-time copy trading execution                                     | High     |
| FR-5  | AI-powered trade signal generation                                   | High     |
| FR-6  | Interactive AI advisor chat interface                                | High     |
| FR-7  | Community chat with real-time messaging                              | Medium   |
| FR-8  | Leaderboard displaying user performance and CopyCoin balance         | Medium   |
| FR-9  | Educational module with AI-driven Q\&A                               | Medium   |
| FR-10 | Simulated CopyCoin rewards and basic staking UI                      | Low      |

---

## 7. Non-Functional Requirements

* **Performance:** Trades copy within seconds.
* **Security:** Encrypt all sensitive credentials; enforce fine-grained access controls.
* **Scalability:** Support a growing user base with minimal maintenance.
* **Availability:** Aim for high uptime for critical trading functions.
* **Usability:** Simplify onboarding with clear guidance and intuitive UI.
* **Maintainability:** Adhere to coding standards and document conventions in `CONTRIBUTING.md`.

---

## 8. Tech Stack & Services

* **Version Control & CI:** GitHub with PRD-driven Cursor AI workflows.
* **Frontend:** React Native (Expo) + React Navigation
* **Backend:** Supabase (Auth, Database, Edge Functions)
* **Forex API:** MetaApi for MT4/MT5 connectivity
* **Crypto API:** CCXT via serverless functions
* **AI Services:** OpenAI GPT-4 / Anthropic Claude
* **Hosting:** Vercel or Netlify for web, Expo EAS for mobile
* **Smart Contracts:** OpenZeppelin for ERC-20 token definitions

---

## 9. Success Metrics

* **User Adoption:** Number of signups and linked trading accounts.
* **Feature Engagement:** Usage rates of AI signals, auto-trading, and advisor chat.
* **Community Activity:** Volume of messages and leaderboard participation.
* **Retention:** Percentage of returning users over time.
* **User Satisfaction:** Feedback ratings and qualitative reviews.

---

*Prepared by Orbis AI Founder*
