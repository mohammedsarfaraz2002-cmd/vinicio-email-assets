# Vinicio Email Assets

Public assets for Vinicio email signatures.

This repository stores the image assets and HTML files used for Gmail-safe email signatures.

## Folder Structure

```text
vinicio-email-assets/
├── images/
│   ├── vinu-photo.jpeg
│   ├── vinicio-logo-arabic.png
│   ├── vinu-contact-qr.png
│   ├── signature-reference.png
│   ├── linkedin.svg
│   ├── facebook.svg
│   ├── instagram.svg
│   └── calendar.svg
│
├── html/
│   └── final Gmail-safe signature HTML files will go here
│
└── README.md
```

## File Purpose

| File | Purpose |
|---|---|
| `vinu-photo.jpeg` | CEO profile photo |
| `vinicio-logo-arabic.png` | Vinicio logo with Arabic text |
| `vinu-contact-qr.png` | Contact QR code |
| `signature-reference.png` | Approved full email signature design reference |
| `linkedin.svg` | LinkedIn icon, used for both CEO LinkedIn and Company LinkedIn |
| `facebook.svg` | Facebook icon |
| `instagram.svg` | Instagram icon |
| `calendar.svg` | Book a Meeting calendar icon |

## Important Notes

- Keep this repository public so Gmail can load the images.
- Do not delete or rename image files after the HTML signature is created, unless the HTML is updated too.
- The images are only visual assets. The actual clickable links are added inside the HTML file.
- The same `linkedin.svg` file can be used twice with two different links.
- `signature-reference.png` is only a reference image. The final Gmail signature should use HTML tables and real linked icons, not invisible overlays.

## Future Updates

For a new email signature design, add a new HTML file inside the `html/` folder.

Example:

```text
html/
├── wavy-arabic-clickable-gmail-final.html
├── simple-clean-signature.html
└── future-design.html
```

