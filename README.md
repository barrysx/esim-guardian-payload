# eSIM Guardian Payload

This public repository is the static payload source for the eSIM Guardian Android app.

- `payload.txt` is inert plain text and is never executed.
- The Android app reads it as bytes only and discards the content.
- Requests use cache-busting query parameters.
- Actual per-session usage is measured with Android `TrafficStats` for the app UID.
- Whether a data session satisfies number-retention rules depends on the eSIM carrier.

Stable URL: `https://barrysx.github.io/esim-guardian-payload/payload.txt`