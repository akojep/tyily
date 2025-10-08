# Voice QR (GitHub Pages)

This repo hosts a simple web page that plays an audio message — perfect for a tattoo QR code.

## How to use
1. Put your audio file in the repo root and name it `voice.mp3` (recommended size ≤ 25 MB).
2. Commit the changes.
3. Enable **Settings → Pages → Build and deployment → Source: Deploy from a branch** (branch: `main`, folder: `/ (root)`).
4. Your site will be available at `https://<username>.github.io/<repo>/`.
5. Point your QR code to that URL. For the most reliable scan, keep the QR at least 1.5″ square and use error-correction **H**.

> You can change the audio anytime without changing the QR. Just replace `voice.mp3`.
