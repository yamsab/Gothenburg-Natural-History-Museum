# Biodiversity Discovery Trail — Version 2

A GitHub Pages prototype for the Gothenburg Natural History Museum Biodiversity Discovery Trail.

Live base URL:
https://yamsab.github.io/Gothenburg-Natural-History-Museum/

## What changed in Version 2
- Real QR workflow: each printed QR opens a unique task URL.
- Scanning a QR automatically records that challenge on the visitor's device.
- Optional in-app camera scanner using `html5-qrcode`.
- Progress persists in the browser with `localStorage`.
- Completing all 5 challenges unlocks a certificate.
- Certificate can be generated as a 1080×1920 PNG and shared using the phone's native share sheet.
- Includes a START QR plus five task QR images.

## Prototype security note
The task tokens are validated in client-side JavaScript, so this is suitable for a classroom/prototype demonstration, not for production security. A real deployment should validate signed/rotating tokens on a backend such as Firebase, Supabase, or another server-side service.

## Files
- `index.html` — replace the current GitHub Pages file with this one.
- `qr-codes/00-start.png` — opens the trail.
- `qr-codes/01-bird.png`
- `qr-codes/02-fish.png`
- `qr-codes/03-insect.png`
- `qr-codes/04-conservation.png`
- `qr-codes/05-gothenburg.png`
- `print-qr-sheet.html` — printable QR sheet for your demonstration.
