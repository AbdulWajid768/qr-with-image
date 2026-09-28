<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║  ░▒▓  QR WITH IMAGE  ▓▒░                                        ║
║  Branded QR codes · logo overlay · scannable by design           ║
╚══════════════════════════════════════════════════════════════════╝
```

[![Python](https://img.shields.io/badge/Python-3.8+-00d4aa?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![QR](https://img.shields.io/badge/QR-ecosystem-111827?style=for-the-badge)](https://github.com/AbdulWajid768/qr-with-image)
[![Status](https://img.shields.io/badge/Status-experimental-ff006e?style=for-the-badge)](https://github.com/AbdulWajid768/qr-with-image)

**Generate QR codes that carry your brand—center logo, high error correction, still readable.**

[Roadmap](#-roadmap) · [Concept](#-concept) · [Planned usage](#-planned-usage)

</div>

---

## ◈ Signal

Flat QR codes work; **branded** QR codes get scanned. This project is the home for tooling that embeds a logo or icon inside a QR matrix while preserving decode reliability via elevated error correction (typically **QR version H**).

Repository is in **early setup**—implementation landing here next.

---

## ◈ Concept

```text
  Payload URL/text
        │
        ▼
  QR matrix (high error correction)
        │
        ├── reserve center modules for logo "quiet zone"
        ├── composite brand image (PNG/SVG)
        └── export PNG / SVG / PDF
        │
        ▼
  Scanner-friendly branded asset
```

| Design choice | Why |
| --- | --- |
| High error correction | Logo obscures data modules; redundancy keeps scans working |
| Center placement + padding | Avoids alignment patterns; improves read rate |
| Vector + raster export | Web, print, and slide decks |

---

## ◈ Planned usage

```python
# Target API (illustrative — coming soon)

from qr_with_image import generate

generate(
    data="https://mariashoaib.com",
    logo_path="assets/logo.png",
    output="qr-branded.png",
    error_correction="H",
    fill_color="#0f172a",
    back_color="#ffffff",
)
```

```bash
# CLI (planned)
qr-with-image --url "https://example.com" --logo ./logo.png -o out.png
```

---

## ◈ Roadmap

- [ ] Core generator (`qrcode` / `segno` + Pillow compositing)
- [ ] CLI entrypoint
- [ ] Configurable colors, margin, and logo scale
- [ ] Batch generation from CSV
- [ ] PyPI package publish

---

## ◈ Contributing

Ideas and PRs welcome. Fork **[qr-with-image](https://github.com/AbdulWajid768/qr-with-image)**, open an issue for larger changes, and keep docs in sync.

---

## ◈ Maintainer

**[Abdul Wajid](https://github.com/AbdulWajid768)** · Software Engineer · Lahore, PK

[![GitHub](https://img.shields.io/badge/@AbdulWajid768-181717?style=flat&logo=github)](https://github.com/AbdulWajid768)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-wajid-amin/)

---

<div align="center">

<sub>Encode the link. Imprint the brand.</sub>

</div>
