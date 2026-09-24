# Hn38videoAItool

Windows desktop automation tool by **Hoainguyenstudio**.

## Functions

- Meta AI: create video through the user's own logged-in browser session.
- Google Flow: create **images only** through the user's own logged-in browser session.
- Separate persistent browser profiles for Meta AI and Google Flow.
- Manual login in Chrome/Edge or user-pasted session cookie validation.
- Real file verification: the app does not report generation success from a generic HTML video/image element alone.
- Video library with preview, play, stop, delete and open-folder actions.
- Detailed local log.
- Neon glass UI with configurable themes and animations.

## Security

- The application does not read the user's normal Chrome profile.
- Do not share cookies/session tokens with anyone.
- Cookie text is used only for session validation and is not written to the application log.

## Build

GitHub Actions builds the Windows portable package and publishes:

`Hn38videoAItool-Windows.zip`

The build uses the Chrome/Edge browser already installed on the user's Windows machine instead of downloading a Playwright browser bundle.
