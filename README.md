# secure-autofill

Local-only Chrome extension for encrypted job-application autofill. No backend, no tracking — credentials stay on your device.

## Status

Early scaffold. Manifest and docs are in place; UI and encryption logic are not implemented yet.

## Planned features

- Encrypt profile data at rest in `chrome.storage`
- Autofill common job-board form fields from the popup
- Options page for managing saved profiles

## Load unpacked (development)

1. Open `chrome://extensions`
2. Enable **Developer mode**
3. Click **Load unpacked** and select the `src/` folder
4. *(Stub files required before the extension loads — see roadmap in issues)*

## Security model

- All data stored locally in the browser
- No network calls for profile data
- Encryption keys never leave the device

## License

MIT
