# Changelog

## v4.2.0

- Added a global AI Output Language sidebar preference for Chinese and English.
- Removed language selection from AI Preferences; AI output language now follows the global app preference.
- Wired document discovery for Daily Market Review, Ticker Detail, and AI markdown context to request English document variants when English output is selected.
- Added document API parsing for language, requestedLanguage, and fallbackLanguage so the app can track backend fallback behavior.
- Documented the `.en` document naming convention and discovery fallback rules.

Distribution note: this build is Developer ID signed but not notarized.
