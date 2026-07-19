# AI-Investment-Copilot-for-Groww

Groww has over **50 million registered users**, but only **around 13 million (approximately 28%)** are active investors. This highlights a significant gap between user acquisition and user activation.

A large portion of Groww's user base consists of **young, first-time investors**, with **45% of users under the age of 30** and **81% coming from Tier-2 and Tier-3 cities**. Many users sign up as soon as they start earning because they want to begin investing and building wealth. However, after registration, a considerable number do not make their first investment.

One of the primary reasons is a lack of financial knowledge and unfamiliarity with investment terminology. Concepts such as SIP, NAV, CAGR, expense ratio, asset allocation, and risk profiling can feel overwhelming for beginners. This uncertainty often leads to hesitation, causing users to postpone or completely abandon their investment journey.

To bridge this activation gap, I propose introducing an **AI Investment Copilot**. The feature would act as a personalized financial assistant that simplifies complex investment concepts, answers users' questions in plain language, provides portfolio and goal-based guidance, and builds confidence throughout the investing journey. By reducing confusion and increasing trust, the AI Copilot can help convert registered users into active investors while improving engagement and long-term retention.

Prototype link: https://ai-investment-copilot-for-groww.lovable.app/

# 1. Document Information

| Field | Details |
| --- | --- |
| Product | Groww |
| Feature | AI Investment Copilot |
| Author | Kanha Pal |
| Version | 1.0 |
| Priority | P0 |
| Status | Draft |

# 2. Executive Summary

Groww has made investing simple, but many users, especially first-time investors, still hesitate because they don't know:

- Where to invest
- Whether a stock is worth buying
- How much should they invest
- Whether they're taking too much risk (Risk analysis as per their Age, Income, Goals etc.)

The **AI Investment Copilot** introduces a conversational assistant that provides personalized, explainable, and context-aware investment guidance. It helps users understand their risk taking capabilities, analyze portfolios, set goals, and navigate the platform more confidently while making it clear that the final investment decision rests with the user.

# 3. Problem Statement

### User Problems

- New investors don't understand financial terminology.
- Users leave the app to search on Google or YouTube.
- Users feel anxious during market volatility.
- Portfolio insights are difficult to interpret.
- Financial planning is fragmented.

### Business Problems

- Lower conversion from account creation to first investment.
- Low engagement during non-transaction periods.
- Higher customer support volume.
- Limited opportunities for personalized cross-selling.
- Users may migrate to competitors offering richer guidance.

# 4. Opportunity

India has millions of first-time investors entering the market every year.

Most don't need more data.

They need:

- Simpler explanations
- Personalized insights
- Confidence before investing
- Education embedded within the investment journey

AI can deliver this at scale.

# 5. Goals

### User Goals

- Help users make informed investment decisions.
- Explain financial concepts in simple language.
- Improve investment confidence as per their Risk taking capabilities.
- Reduce research effort as AI will do it for them.
- Increase financial literacy.

### Business Goals

- Increase first investment conversion.
- Increase SIP creation.
- Improve user retention.
- Increase Assets Under Management (AUM).
- Reduce support tickets.
- Increase session duration (As they will getting the knowledge).

# 6. Success Metrics (North Star & KPIs)

### North Star Metric

**Monthly Active Investors using AI Copilot**

### Primary KPIs

| KPI | Current | Target |
| --- | --- | --- |
| First investment conversion | 34% | 42% |
| Monthly AI adoption | 0 | 45% |
| SIP creation rate | +0% | +20% |
| User retention (90 days) | 52% | 60% |
| Average session duration | 8 min | 11 min |
| Support queries | Baseline | -25% |

### Guardrail Metrics

- Hallucination rate
- User-reported incorrect responses
- Investment complaint rate
- Regulatory violations
- Response latency (<2 seconds target)

# 7. Target Users

### Primary

**First-time Investors (18–35 years)**

Pain Points

- Fear of losing money
- No investment knowledge
- Information overload

### Secondary

Experienced Investors

Pain Points

- Portfolio analysis
- Tax planning
- Diversification
- Market research

# 8. User Personas

## Persona 1

**Rahul**

Age: 24

Occupation: Software Engineer

Goal:

Start investing ₹5,000/month

Problem:

Doesn't know which mutual fund to choose.

## Persona 2

**Priya**

Age: 33

Occupation: Marketing Manager

Goal:

Build wealth for retirement.

Problem:

Portfolio is scattered across multiple funds.

# 9. User Stories

### Investment Guidance

**As a new investor**

I want AI to recommend suitable investment options as per my age, income & Goals

So that I can begin investing confidently.

### Portfolio Explanation

As an investor

I want AI to explain why my portfolio increased or decreased as per my risk taking capabilities

So that I understand market movements.

### Financial Education

As a beginner

I want AI to explain financial terms in simple language

So I can learn while investing.

### Goal Planning

As a user

I want AI to calculate how much I need to invest monthly

So I can achieve my financial goals.

# 10. Feature Scope

## Feature 1

### AI Chat

Users can ask:

- Where should I invest ₹10,000?
- What is an SIP?
- Explain ETF.
- Is this mutual fund suitable for beginners?

## Feature 2

Portfolio Analysis

AI analyzes:

- Risk
- Sector allocation
- Diversification
- Concentration
- Asset allocation
- Performance trends

## Feature 3

Personalized Recommendations

Example:

"You have a conservative risk profile.

You may consider diversified equity mutual funds instead of individual small-cap stocks."

Recommendations are educational and aligned with the user's profile, not guaranteed outcomes.

## Feature 4

Market Summary

Instead of generic news:

> Your portfolio fell 2.3% today mainly because your banking holdings declined after sector-wide weakness.
> 

## Feature 5

Goal Planning

Input:

- Goal amount
- Timeline
- Risk appetite

Output:

- Suggested monthly SIP
- Estimated returns
- Probability ranges under different market scenarios

## Feature 6

Learning Assistant

AI explains:

- NAV
- CAGR
- Expense Ratio
- Market Cap
- ETF
- ELSS

# 11. Functional Requirements

### AI Chat

- Conversational interface
- Context retention within a session
- Voice input
- Suggested prompts
- Follow-up questions
- Multi-language support

### Portfolio Analyzer

Display:

- Risk score
- Diversification score
- Asset allocation
- Sector exposure
- Performance attribution
- Suggested educational actions

### Goal Calculator

Input:

- Target amount
- Monthly income
- Current investments
- Time horizon

Output:

- Monthly SIP
- Future value estimates
- Inflation-adjusted target
- Progress tracking

### AI Explain

For every recommendation:

AI must explain:

- Why
- Benefits
- Risks
- Assumptions
- Alternatives

# 12. Non-Functional Requirements

| Requirement | Target |
| --- | --- |
| Response Time | <5 sec |
| Uptime | 99.9% |
| Availability | 24×7 |
| Encryption | AES-256 |
| Scalability | 20M+ users |
| Concurrent Sessions | 500K |

# 13. User Flow

<img width="2720" height="2504" alt="groww_ai_copilot_user_flow" src="https://github.com/user-attachments/assets/044b09ba-c467-4dcf-aeed-0deae96f2cf9" />


# 14. UX Requirements

### Home Screen

New Floating Button

Ask Groww AI

#### Chat Screen

Welcome message:

"Hi! I'm your Investment Copilot. I can help explain investments, analyze your portfolio, and guide you toward your financial goals."

Quick actions:

- Analyze Portfolio
- Compare Funds
- Start SIP
- Explain Stock
- Goal Planning
- Tax Help

# 15. AI Architecture (High Level)

<img width="2720" height="2960" alt="groww_ai_copilot_architecture" src="https://github.com/user-attachments/assets/84af09a6-95f0-46ba-a19d-d1c08bb0948f" />


# 16. Risks & Mitigation

| Risk | Mitigation |
| --- | --- |
| Hallucinated financial advice | Retrieval-Augmented Generation (RAG) using verified Groww knowledge, market data, and portfolio context |
| Regulatory issues | Educational guidance with clear disclosures; recommendations reviewed against compliance policies |
| User overreliance | Show rationale, risks, and encourage independent decision-making |
| Slow responses | Response caching and streaming |
| Incorrect personalization | Use only consented, up-to-date user profile and portfolio data |

# 17. Analytics Events

Track:

- AI Opened
- Prompt Clicked
- Question Asked
- Portfolio Analysis Viewed
- Recommendation Viewed
- Recommendation Accepted
- Investment Initiated
- Investment Completed
- AI Feedback Submitted
- Session Duration

# 18. A/B Testing Plan

### Experiment

**Control**

Existing Groww experience

#### **Variant A**

AI Copilot available on the Home Screen

#### **Variant B**

AI Copilot integrated into every investment flow

### Success Metrics

- First investment conversion
- SIP creation
- AI engagement
- Average order value
- 30-day retention
- Customer Satisfaction (CSAT)

# 19. Rollout Strategy

**Phase 1 (Internal Alpha)**

- Employees and selected beta users
- Portfolio explanations and educational Q&A only

**Phase 2 (Beta)**

- 5% of new users
- Goal planning and personalized insights

**Phase 3 (Public Launch)**

- 100% rollout
- Multi-language support
- Voice interaction
- Advanced portfolio analytics

# 20. Future Enhancements

- Voice-based investing with secure authentication
- WhatsApp-style AI assistant
- Smart tax optimization suggestions
- Family financial planning
- AI-powered portfolio rebalancing
- Predictive cash flow and SIP reminders
- Personalized market alerts based on user holdings

## Expected Business Impact

| Metric | Expected Impact |
| --- | --- |
| First investment conversion | +20–25% |
| SIP creation | +15–20% |
| 90-day retention | +10–15% |
| Average session duration | +25–35% |
| Customer support queries | −20–30% |
| Assets Under Management (AUM) growth | Positive long-term uplift through increased engagement |
