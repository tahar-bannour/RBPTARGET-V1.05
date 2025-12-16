RBPTarget EA – ORB Sydney Session (MT5)
Overview

RBPTarget is a MetaTrader 5 Expert Advisor developed to automate a structured session-based trading approach during the Sydney market hours.
The EA emphasizes discipline, rule enforcement, and visual transparency, making it suitable for both research and live-market observation.

General Concept

RBPTarget focuses on price interaction with an initial session reference range formed at the beginning of the Sydney session.
Once this range is established, the EA evaluates market conditions and manages trades using predefined technical confirmations and strict daily limits.

How the EA Works
1. Daily Initialization

Automatically resets all internal states at the start of each new trading day

Recalculates reference levels and contextual market data

2. Sydney Session Reference Range

Establishes a reference price range during the Sydney session opening window

Uses this range as the primary decision framework for the trading day

3. Market Condition Monitoring

Continuously monitors price behavior after the range is defined

Applies momentum and optional trend confirmation before allowing trades

4. Trade Execution Control

Executes trades only when all internal conditions are met

Enforces strict daily trade limits to prevent overtrading

Optional trend filtering ensures alignment with broader market direction

5. Trade Management

Fully automated position management

Rule-based exit conditions

Configurable take-profit handling

6. Visual Feedback

Real-time on-chart dashboard displaying system status and conditions

Session range plotted directly on the chart

Pivot point table for additional market context

Optimized Trading Instrument

RBPTarget is compatible with multiple symbols; however, it has been primarily optimized and tested on XAUUSD (Gold).

Due to its volatility characteristics and session behavior, XAUUSD has shown the most consistent performance with this EA.

Recommended Setup

Symbol: XAUUSD

Timeframe: M30

Platform: MetaTrader 5

Session Timing: Broker server time aligned with Sydney session

Key Features

Session-based trading structure

Automated daily reset and state control

Momentum confirmation using RSI

Optional trend filtering with moving averages

Strict daily trade limits

Fully automated trade management

On-chart dashboard and visual tools

Clean object and resource handling

Input Parameters Overview

The EA includes configurable inputs to adapt to different broker environments while preserving core behavior.

Session Settings

Configure Sydney session start time (broker server time)

Indicator Settings

Control momentum indicator parameters and timeframes

Trade Settings

Define lot size, slippage tolerance, and trade identification

Take Profit Mode

Choose between pivot-based targets or fixed risk-reward logic

Trend Filter (Optional)

Enable or disable trend alignment using moving averages

Intended Use

RBPTarget is designed for:

Session-based market analysis

Educational purposes

Structured automated trading experimentation

Demo testing is strongly recommended before any live use.
