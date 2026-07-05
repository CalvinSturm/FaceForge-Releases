# FaceForge Releases

FaceForge is a privacy-first, local-only Windows desktop app for AI face blur
and video redaction.

The default workflow is **Blur Faces / Privacy**. Face replacement is an
advanced, consent-based Pro workflow and is not the main public alpha focus.

## Download

Download the latest ZIP from
[GitHub Releases](https://github.com/CalvinSturm/FaceForge-Releases/releases).

Current release target: **v0.1.0-alpha**

Website: [FaceForge](https://www.calvinsturm.com/faceforge)

## Requirements

- Windows 10 or Windows 11
- NVIDIA RTX GPU recommended for the current NVIDIA alpha bundle
- Recent NVIDIA driver recommended
- 16 GB RAM minimum, 32 GB recommended
- Enough free disk space for the extracted portable app and local model files

## Unsigned Alpha Warning

FaceForge v0.1.0 Alpha is currently unsigned. Windows SmartScreen may warn that
the app is from an unknown publisher. Only run FaceForge if you downloaded it
from the official GitHub Releases page above.

## Model Setup

Some third-party model weights may not be bundled with the alpha until
redistribution rights are confirmed. If the app reports missing models, see:

[MODEL_SETUP_PUBLIC_ALPHA.txt](MODEL_SETUP_PUBLIC_ALPHA.txt)

App-local model files belong under:

```text
FaceForge\models\
```

## Safety

FaceForge is primarily for privacy-preserving face blur and redaction. Use face
replacement only with consent and rights to both the source and target media. Do
not use FaceForge for impersonation, harassment, nonconsensual media, minors,
fraud, or misleading identity use.

See [SAFETY.md](SAFETY.md).

## Privacy

The core video processing workflow is local-first and runs on your Windows
desktop. Do not upload private or sensitive videos to public GitHub issues.

See [PRIVACY.md](PRIVACY.md).

## Support

Open an issue in this repository:
[FaceForge Releases issues](https://github.com/CalvinSturm/FaceForge-Releases/issues)

Include your FaceForge version, Windows version, GPU model, what you tried, and
what happened. Do not upload private videos, faces, IDs, or sensitive footage.

See [SUPPORT.md](SUPPORT.md).
