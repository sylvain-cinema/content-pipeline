<div align="center">

<img src="https://img.shields.io/badge/SYLVAIN-CONTENT_PIPELINE-000000?style=for-the-badge&labelColor=f59e0b&color=000000" alt="CONTENT PIPELINE" height="40"/>

### Content Mastering

**Ingest · Transcode · Certify · Distribute**

<br/>

[![CI](https://github.com/sylvain-cinema/content-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/sylvain-cinema/content-pipeline/actions/workflows/ci.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-f59e0b?style=flat-square)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)

<br/>

*Transform any film into a Sylvain Certified immersive experience.*
*16K upscaling · HDR grading · WFS audio spatialization · Multi-tier packaging.*

</div>

<br/>

---

<br/>

## Pipeline

```mermaid
graph LR
    A[Ingest] --> B[Analyze]
    B --> C[Upscale]
    C --> D[Grade HDR]
    D --> E[Spatialize Audio]
    E --> F[Generate Metadata]
    F --> G[Certify]
    G --> H[Distribute]
```

<br/>

## Output Formats

| Tier | Resolution | HDR | Audio |
|:-----|:-----------|:----|:------|
| **SANCTUM** | 16K | PQ 10,000 nits | Sonora Elite |
| **VISIONNAIRE** | 16K × 16K | PQ 10,000 nits | Sonora WFS |
| **ÉTOILÉE** | 8K | PQ 4,000 nits | Sonora WFS |
| **ATELIER** | Variable | PQ / HLG | Sentio Suite |

<br/>

## Quick Start

```bash
pip install sylvain-pipeline

sylvain-pipeline master input.mov --tier visionnaire
sylvain-pipeline certify ./mastered/ --tier visionnaire
```

<br/>

## License

Licensed under the [Apache License, Version 2.0](LICENSE).

<br/>

---

<div align="center">
<br/>

<img src="https://img.shields.io/badge/SYLVAIN-The_Future_of_Cinematic_Storytelling-000000?style=for-the-badge&labelColor=f59e0b&color=111111" alt="Sylvain"/>

<sub>Every Seat is the Best Seat</sub>

</div>
