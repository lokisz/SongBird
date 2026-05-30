# Changelog

## v4.3.2

- Added strict previous/next quarter navigation for Ticker Detail earnings documents without skipping missing natural quarters.
- Kept Ticker AI markdown context aligned with the currently selected earnings document.
- Added Kline Snapshot sorting controls on Earning Analysis and shortened the Technical Changes download button label.

Distribution note: this build is Developer ID signed but not notarized.

## v4.3.1

- Added per-market data source controls for MyWatch and MyPortfolio so Trial users can switch US data from Auto/Polygon to yfinance.
- Kept Auto as the default data source behavior while allowing valid market-specific overrides.
- Updated Portfolio market availability to consider any entitled source with local scan data.

Distribution note: this build was not published separately; changes are included in v4.3.2.

## v4.3.0

- Added a Home sidebar EOD auto update option under Data Maintenance, scoped to the current market and current data source.
- The schedule supports daily run time and timezone settings, runs only while the app is open, and catches up once if the app opens after the configured time.
- Persisted EOD auto update settings in config/eod_auto_update.json and run state in logs/eod_auto_update_state.json, so page navigation does not reset the selection.
- Added packaging support for a clean disabled-by-default EOD auto update seed config for new users.

Distribution note: this build is Developer ID signed but not notarized.

## v4.2.0

- Added a global AI Output Language sidebar preference for Chinese and English.
- Removed language selection from AI Preferences; AI output language now follows the global app preference.
- Wired document discovery for Daily Market Review, Ticker Detail, and AI markdown context to request English document variants when English output is selected.
- Added document API parsing for language, requestedLanguage, and fallbackLanguage so the app can track backend fallback behavior.
- Documented the `.en` document naming convention and discovery fallback rules.

Distribution note: this build is Developer ID signed but not notarized.
