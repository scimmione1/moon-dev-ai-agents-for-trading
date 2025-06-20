# 🤖 AI AGENTS FOR TRADING

<p align="center">
  <a href="https://www.moondev.com/"><img src="moondev.png" width="300" alt="Moon Dev"></a>
</p>

This project explores the potential of [artificial financial intelligence](https://www.afi.xyz) - a focused implementation of AI for trading and investing research.


**⚠️ IMPORTANT: This is an experimental project. There are NO guarantees of profitability. Trading involves substantial risk of loss.**

## 🎯 Vision
We're researching AI agents for trading that will eventually leverage [AFI](https://www.afi.xyz). With 4 years of experience training humans through our [bootcamp](https://algotradecamp.com), we're exploring where AI agents might complement human trading operations, and later replace trading human operations. This is experimental research, not a profitable trading solution.

## 🧠 Hypothesis
AI agents will be able to build a better quant portfolio than humans. i've spent the last 4 years building quant systems & training others to do so. 2025 is about replicating that success but with ai agents doing it instead of me. on jan 1, 2026 i will release a paper of my findings after a full year of testing ai agents in quant vs the last 4 years of humans.

## 💡 Concept
AI agents might help address common trading challenges:
- Emotional reactions
- Ego-driven decisions
- Inconsistent execution
- Fatigue effects
- Impatience
- Fear & Greed cycles

While we use the RBI framework for strategy research, we're exploring AI agents as potential tools. We're in early stages with LLM technology, investigating possibilities in the trading space.

*There is no token associated with this project and there never will be. any token launched is not affiliated with this project, moon dev will never dm you. be careful. don't send funds anywhere*

## Video Updates & Training
i will place video updates here as often as possible. i'll also be working on making shorter written and video documentation as features get solidified.
- [1/1/25] [day 1: building The AI Agent Infastructure](https://www.youtube.com/watch?v=0-UfinNUfrI)
- [1/2/25] [building out first trading agent, the risk agent](https://www.youtube.com/watch?v=Grg2Sir5vOY)
- [1/3/25] [building a trading agent that makes decisions based on data](https://www.youtube.com/watch?v=uharK1SxXB0)

## 🗺️ Research Roadmap

### 1. Risk Control Agents
Exploring AI agents that could assist with risk management. This is purely experimental research into risk oversight possibilities.

### 2. Exit Agents
Researching potential exit timing assistance. This overlaps with risk management research but focuses on position management concepts.

### 3. Entry Agents
Investigating entry-focused concepts after risk management research.

### 4. Sentiment Collection Agents
Exploring ways to gather market sentiment from Twitter, Discord, and Telegram for research purposes.

### 5. Strategy Execution Agents
Researching concepts like:
- Multi-agent consensus
- Strategy validation
- Dynamic trade filtering

## ⚠️ Critical Disclaimers

*There is no token associated with this project and there never will be. any token launched is not affiliated with this project, moon dev will never dm you. be careful. don't send funds anywhere*

**PLEASE READ CAREFULLY:**

1. This is an experimental research project, NOT a trading system
2. There are NO plug-and-play solutions for guaranteed profits
3. We do NOT provide trading strategies
4. Success depends entirely on YOUR:
   - Trading strategy
   - Risk management
   - Market research
   - Testing and validation
   - Overall trading approach

5. NO AI agent can guarantee profitable trading
6. You MUST develop and validate your own trading approach
7. Trading involves substantial risk of loss
8. Past performance does not indicate future results

## 👂 Looking for Updates?
Project updates will be posted in discord, join here: [moondev.com](http://moondev.com) 

## 📜 Detailed Disclaimer
The content presented is for educational and informational purposes only and does not constitute financial advice. All trading involves risk and may not be suitable for all investors. You should carefully consider your investment objectives, level of experience, and risk appetite before investing.

Past performance is not indicative of future results. There is no guarantee that any trading strategy or algorithm discussed will result in profits or will not incur losses.

**CFTC Disclaimer:** Commodity Futures Trading Commission (CFTC) regulations require disclosure of the risks associated with trading commodities and derivatives. There is a substantial risk of loss in trading and investing.

I am not a licensed financial advisor or a registered broker-dealer. Content & code is based on personal research perspectives and should not be relied upon as a guarantee of success in trading.

## 🔗 Links
- Free Algo Trading Roadmap: [moondev.com](https://moondev.com)
- Algo Trading Education: [algotradecamp.com](https://algotradecamp.com)
- Business Contact [moon@algotradecamp.com](mailto:moon@algotradecamp.com)


## Live Agents
- Trading Agent (`trading_agent.py`): Example agent that analyzes token data via LLM to make basic trade decisions
- Strategy Agent (`strategy_agent.py`): Manages and executes trading strategies placed in the strategies folder
- Risk Agent (`risk_agent.py`): Monitors and manages portfolio risk, enforcing position limits and PnL thresholds

## 🚀 Project Progress & Roadmap
### Phase 1: Foundation ✅
- [x] Project structure setup
- [x] Environment variable configuration
- [x] API key management
- [x] Basic OHLCV data collection
- [x] Multi-token monitoring setup
- [x] Temporary data storage system
- [x] Token display improvements
- [x] Market Data API Integration (OI, Liquidations, Funding)

### Phase 2: Core Trading Infrastructure 🚧
- [x] ezbot.py that allows hand traders bot functions
- [x] Market buy/sell functionality
- [x] Position management
- [x] Slippage control
- [x] Transaction retry logic
- [x] Risk management system
- [ ] Portfolio-wide analysis
- [ ] Advanced order types

### Phase 3: Launch A Bunch of Agents to Learn 🤖
- [x] Basic AI model setup
- [x] Trading Agent Example
- [x] Risk assessment agent
- [ ] Entry/exit strategy agent - build a buying agent to optimize slippage etc and easy to implement into any agents
- [ ] Sentiment analysis agent - use twikit package
- [ ] Multi-agent coordination 
- [ ] Portfolio optimization agent 

### Phase 4: Advanced Features 🔮
- [ ] Social sentiment integration
- [ ] Hyperliquid Perp Trading
- [ ] Hyperliquid Spot Trading 

### Phase 5: Optimization & Scaling 🚀
- [ ] Performance optimization
- [ ] Multi-chain support
- [ ] Emergency protocols

### Shipped Features 📦

- [x] 1/6 - Market Data API: Added comprehensive API for liquidations, funding rates, open interest, and copybot data
- [x] 1/5 - created a documentation training video with a full walkthrough of this github (releasing jan 7th)
- [x] 1/4 - strategy_agent.py: an ai agent that has last say on any strategy placed in strategies folder
- [x] 1/3 - risk_agent.py: built out an ai agent to manage risk
- [x] 1/2 - trading_agent.py: built the first trading agent 
- [x] 1/1 - first lines of code written

## 🚀 Quick Start Guide

1. ⭐ **Star the Repo**
   - Click the star button to save it to your GitHub favorites

2. 🍴 **Fork the Repo**
   - Fork to your GitHub account to get your own copy
   - This lets you make changes and track updates

3. 💻 **Open in Your IDE**
   - Clone to your local machine
   - Recommended: Use [Cursor](https://www.cursor.com/) or [Windsurfer](https://codeium.com/) for AI-enabled coding

4. 🔑 **Set Environment Variables**
   - Check `.env.example` for required variables
   - Create a copy of above and name it `.env` file with your keys:
     - Anthropic API key
     - Other trading API keys
   - ⚠️ Never commit or share your API keys!

5. 🤖 **Customize Agent Prompts**
   - Navigate to `/agents` folder
   - Modify LLM prompts to fit your needs
   - Each agent has configurable parameters

6. 📈 **Implement Your Strategies**
   - Add your strategies to `/strategies` folder
   - Remember: Out-of-box code is NOT profitable
   - Thorough testing required before live trading

7. 🏃‍♂️ **Run the System**
   - Execute via `main.py`
   - Toggle agents on/off as needed
   - Monitor logs for performance

---
*Built with love by Moon Dev - Pioneering the future of AI-powered trading*

## 🔌 API Features
The Moon Dev Market Data API provides real-time access to:
- 📊 Liquidation Data
- 💰 Funding Rates
- 📈 Open Interest (Symbol & Total Market)
- 🆕 New Token Launches
- 🤖 CopyBot Data & Follow Lists
- 📝 Recent Market Transactions

Check out [API Documentation](docs/api.md) for detailed usage instructions.
