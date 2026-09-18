# Biodiversity Discovery Trail — Prototype

A phone-friendly proof of concept for the Gothenburg Natural History Museum group project.

## Demo
Open `index.html` in a browser. Complete each of the five tasks using its **Scan QR** button. The prototype stores progress locally and unlocks a digital Biodiversity Explorer certificate after 5/5 tasks.

## Real museum version
Replace the simulated scan buttons with camera-based QR scanning. Each physical exhibit QR should contain a server-issued, signed token. A backend (for example Firebase or Supabase) validates the token and records completion. The certificate can then be rendered as a 1080×1920 image for sharing.

## Prototype features
- Five biodiversity challenges
- Progress bar and local persistence
- Simulated QR verification
- Completion certificate
- Optional visitor name
- Native phone share sheet
- Reset button

This is intentionally install-free: the final experience can run as a mobile web app/PWA reached from a START QR at the museum entrance.
