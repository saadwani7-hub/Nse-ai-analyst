# NSE AI Analyst — phone-build package

This is a native Android project designed to be built in GitHub Actions so the user can create the APK from an Android phone without Android Studio.

## Included
- Indian market dashboard
- NIFTY / Bank Nifty / India VIX context
- Watchlist scanner
- BUY / STRONG BUY / HOLD / SELL technical signals
- EMA20/50/200, RSI14, MACD, ATR, volume and breakout logic
- Reference entry / invalidation / target zones and risk sizing
- Recent market-news headline checker
- AI market copilot
- Android Keystore-backed API-key storage
- No automatic broker order execution

## Phone build
Read `PHONE_BUILD_GUIDE.txt`.

The GitHub Actions workflow builds `app-debug.apk` and uploads it as the artifact `nse-ai-analyst-debug-apk`.

## Important data limitation
The public quote/history source can be delayed, rate-limited or unavailable. This build should be treated as a research/paper-trading assistant, not an exchange-certified real-time terminal. Verify prices, corporate actions, liquidity and news with a licensed source before trading.
