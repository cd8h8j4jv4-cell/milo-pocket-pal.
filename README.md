# Milo — Pocket Pal (first prototype)

This is the first visual prototype: a pixel-art Milo, animated idle state, speech bubble, mood lines and a small chat panel.

## Important
This first build is a **front-end prototype**. The chat currently uses a placeholder reply. It is not connected to an AI model, does not send messages anywhere, and does not yet have persistent memory, notifications, or background monitoring.

## Put it on your iPhone
To install it as a Home Screen web app, the files need to be hosted at an HTTPS address. Once hosted:
1. Open the HTTPS link in Safari.
2. Tap Share.
3. Choose **Add to Home Screen**.
4. Enable **Open as Web App** if that option appears, then tap Add.

## Next build steps
1. Refine Milo's sprite and expressions.
2. Add a secure server-side AI connection (never put an API key in browser code).
3. Add opt-in memory and privacy controls.
4. Add supported iPhone notifications / home-screen affordances.

iOS does not allow a normal third-party app to float an arbitrary character over every other app. A Home Screen web app, widgets and supported notifications are the realistic first route.
