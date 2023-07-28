# AI based crypto trading bot
Recognize signals on social media and automatically open trading positions on CEX.

Currently used AI-engine:
 - openAI gpt-3.5-turbo

Currently supported social media:
- [x] Telegram
- [ ] Twitter (planned)
- [ ] Reddit (planned)

Currently supported CEX:
- [x] Binance
- [ ] OKX (planned)
- more integrations are planned to be added along the way

The bot is designed the pick the best CEX to open a position depending on trading pairs, liquidity/spread and user-set priorities.

Settings:
- Social media channels/accounts to listen
- CEX priorities
- Deposit amount
- Margin type (isolated or cross)
- Maximum risk/reward ratio
- Stop-loss based position amount (fixed or % of deposit)
- Maximum drawdown
- Customizable leverage and other trading position settings

Featues roadmap:
- [x] Telegram integration
- [x] Binance integration
- [x] Position history
- [ ] GPT-4 upgrade
- [ ] PnL reports
- [ ] SMS notifications
- [ ] Isolated margin
- [ ] Risk-reward ratio
- [ ] Cryprocurrency-level customizable settings
- [ ] Paper-trading
- [ ] OKX integration
- [ ] CEX priorities
