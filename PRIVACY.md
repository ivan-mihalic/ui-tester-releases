# UI Tester injector — Privacy Policy

*Chrome Web Store item ID: `lmcchhljhohlchdbkpnkelldkpdamcmm`. Last updated: 2026-08-12.*

The UI Tester Chrome extension captures browsing activity (visited URLs,
clicks, and page screenshots) **only on domains you explicitly add** in
your UI Tester project.

Captured data is sent **only** to the UI Tester server address you
configure in the extension's options page — a server you run yourself,
either locally or on your own infrastructure. The extension developer has
no access to this data; it never leaves your own server.

The extension does not sell, share, or transmit data to any third party,
and does not use collected data for advertising, credit scoring, or any
purpose unrelated to the extension's testing functionality.

## What is stored in the browser

Extension settings only — the UI Tester server address and the list of
domains you enabled. Nothing else is persisted by the extension.

## Permissions and why they are needed

| Permission | Why |
|---|---|
| `scripting`, host access | Injecting the UI Tester widget into the domains you configured |
| `debugger` | Capturing full-page screenshots via the Chrome DevTools Protocol |
| `storage` | Storing the server address and the domain list |
| `webNavigation` | Re-injecting the widget after in-page navigation |

## Contact

ivan@mihalic.cz
