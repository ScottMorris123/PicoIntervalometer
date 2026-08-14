Pico Intervalometer - Web Bluetooth control

Quick static web app to pair with the Pico intervalometer firmware over Web Bluetooth.

How to use

- Host this repository on GitHub Pages (branch `main` or `gh-pages`).
- Open the page on an Android phone using Chrome or Edge (Web Bluetooth requires HTTPS; GitHub Pages provides HTTPS).
- Tap `Connect`, choose the `PicoIntervalometer` device, then use the controls to read/write the interval, delay, and enable state.

Notes and troubleshooting

- Web Bluetooth is supported in Chrome/Edge on Android and Chromium-based desktop browsers with secure context (HTTPS).
- If `Connect` fails, ensure Bluetooth is enabled on your phone and the Pico is advertising.
- The app uses the BLE service UUID `fa2c6001-1203-4806-af25-075a06539f45` and characteristics for enable/interval/delay matching the device firmware.

Files

- `index.html` – single-file web app you can deploy to GitHub Pages.
