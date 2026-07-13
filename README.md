# TechNext Email Signatures

Self-serve email signature generator for TechNext Pte Ltd. staff.

**Live page:** https://technextsg.github.io/email-signature/

Fill in your name, job title, phone, and email, click **Copy Signature**, and paste it into Gmail (Settings → General → Signature). The page includes step-by-step Gmail instructions.

## ⚠️ Do not delete or move `sig/`

Every copied signature hot-links the images in `sig/` from this repo's GitHub Pages URL on **every email load**. Deleting or moving them instantly breaks the logo and banner in all staff signatures already deployed in Gmail. (This happened once before when the assets lived in the main website repo and were removed in a cleanup — that's why they now live in this dedicated repo.)

## Contents

- `index.html` — the generator page (displays local `sig/` images; the Copy button rewrites image URLs to the hosted GitHub Pages ones)
- `sig/` — signature assets: horizontal logo, banner, animated logo GIF, and social/contact icons
