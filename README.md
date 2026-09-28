<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:ff006e,100:00d4aa&height=200&section=header&text=QR%20with%20Image&fontSize=38&fontColor=ffffff&animation=twinkling&desc=Branded+matrix+%7C+logo+overlay+%7C+scan-optimized&descSize=15&descAlignY=72&descAlign=62"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=16&duration=2900&pause=900&color=FF006E&center=true&vCenter=true&multiline=true&repeat=true&width=680&height=92&lines=Encode+URLs+%2B+deep+links;Embed+logos+without+killing+scans;Error+correction+level+H;Experimental+%E2%80%94+core+landing+soon" alt="Typing animation"/>
</a>

<br/>

### ⟡ Live telemetry ⟡

[![GitHub stars](https://img.shields.io/github/stars/AbdulWajid768/qr-with-image?style=for-the-badge&logo=starship&logoColor=white&labelColor=0f172a&color=ff006e)](https://github.com/AbdulWajid768/qr-with-image/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AbdulWajid768/qr-with-image?style=for-the-badge&logo=git&logoColor=white&labelColor=0f172a&color=00d4aa)](https://github.com/AbdulWajid768/qr-with-image/network/members)
[![Open issues](https://img.shields.io/github/issues/AbdulWajid768/qr-with-image?style=for-the-badge&logo=githubissues&logoColor=white&labelColor=0f172a&color=f472b6)](https://github.com/AbdulWajid768/qr-with-image/issues)
[![Repo status](https://img.shields.io/badge/phase-genesis-ff006e?style=for-the-badge&logo=rocket&logoColor=white&labelColor=0f172a)](https://github.com/AbdulWajid768/qr-with-image)

[![Last commit](https://img.shields.io/github/last-commit/AbdulWajid768/qr-with-image?style=for-the-badge&logo=git&logoColor=white&labelColor=0f172a&color=ff006e)](https://github.com/AbdulWajid768/qr-with-image/commits/main)
[![Commit activity](https://img.shields.io/github/commit-activity/m/AbdulWajid768/qr-with-image?style=for-the-badge&logo=pulse&logoColor=white&labelColor=0f172a&color=00d4aa)](https://github.com/AbdulWajid768/qr-with-image/graphs/commit-activity)
[![Repo size](https://img.shields.io/github/repo-size/AbdulWajid768/qr-with-image?style=for-the-badge&logo=harddrive&logoColor=white&labelColor=0f172a&color=7c3aed)](https://github.com/AbdulWajid768/qr-with-image)

<br/>

<img src="assets/stats-pin.svg" alt="Repo stats" width="48%"/>
<img src="assets/stats-top-langs.svg" alt="Top languages" width="48%"/>

<br/><br/>

[🧠 Concept](#-concept) · [🔮 Roadmap](#-roadmap) · [🛠 Planned API](#-planned-api)

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=30,31,32&height=2&section=footer" width="100%"/>

</div>

---

## ◈ Transmission

Flat QR codes **function**. Branded QR codes **get scanned**. This repo is the launch pad for tooling that composites a **logo inside the matrix** while keeping cameras happy—high error correction, quiet-zone padding, and export paths for web + print.

```text
        ╔═══════════════════════════╗
        ║ ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ ║
        ║ ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ ║
        ║ ▓▓▓▓▓  ┌─────────┐  ▓▓▓▓▓ ║  ← logo island (EC level H)
        ║ ▓▓▓▓▓  │  BRAND   │  ▓▓▓▓▓ ║
        ║ ▓▓▓▓▓  └─────────┘  ▓▓▓▓▓ ║
        ║ ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ ║
        ╚═══════════════════════════╝
              payload → PNG / SVG
```

**Status:** experimental — implementation landing here next. Star the repo to ride the build log.

---

## ◈ Concept

| Decision | Rationale |
| --- | --- |
| Error correction **H** | Logo occludes modules; redundancy preserves decode |
| Center logo + margin | Avoids alignment patterns; higher read success |
| Raster + vector export | Web, merch, slides |

---

## ◈ Planned API

```python
# Target surface (illustrative)

from qr_with_image import generate

generate(
    data="https://example.com",
    logo_path="assets/logo.png",
    output="qr-branded.png",
    error_correction="H",
    fill_color="#0f172a",
    back_color="#ffffff",
)
```

```bash
qr-with-image --url "https://example.com" --logo ./logo.png -o out.png
```

---

## ◈ Roadmap

- [ ] Core generator (`qrcode` / `segno` + Pillow compositing)
- [ ] CLI entrypoint
- [ ] Colors, margin, logo scale controls
- [ ] Batch mode (CSV → zip)
- [ ] PyPI publish

---

<div align="center">

### ⟡ Watch momentum ⟡

<a href="https://star-history.com/#AbdulWajid768/qr-with-image&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=AbdulWajid768/qr-with-image&type=Date&theme=dark"/>
    <img alt="Star history" src="https://api.star-history.com/svg?repos=AbdulWajid768/qr-with-image&type=Date"/>
  </picture>
</a>

<br/>

<a href="https://github.com/AbdulWajid768">
  <img src="assets/github-activity-graph.svg" alt="Contribution activity graph" width="100%"/>
</a>


<br/><br/>

**[Abdul Wajid](https://github.com/AbdulWajid768)** · Software Engineer · Lahore, PK

[![GitHub](https://img.shields.io/badge/@AbdulWajid768-181717?style=flat&logo=github)](https://github.com/AbdulWajid768)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-wajid-amin/)


<sub>Encode the link · Imprint the brand.</sub>

</div>
