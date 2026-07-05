# FaceForge v0.1.0 Alpha

FaceForge v0.1.0 Alpha is an early Windows desktop bundle for local AI face
blur, video redaction, and consent-based advanced face replacement workflows.

This is an alpha release. Expect rough edges, unsigned-app warnings, and
possible missing model setup depending on the ZIP contents.

## Release Type

- Windows portable desktop bundle
- Current target artifact: `FaceForge-Free-NVIDIA.zip`
- Intended tag: `v0.1.0-alpha`
- Intended release title: `FaceForge v0.1.0 Alpha`
- Intended GitHub Release setting: prerelease

## Highlights

- **Blur Faces / Privacy** is the default workflow.
- Local desktop processing is the main product path.
- Free mode includes a visible watermark.
- Free exports are limited to 60 seconds.
- Face replacement is treated as an advanced, consent-based Pro workflow.
- Face replacement includes a consent gate.
- Windows app icon and packaging use FaceForge branding.
- The public bundle is aimed at Windows users with NVIDIA RTX hardware.

## Free and Pro Behavior

- Free users can use the privacy blur workflow with alpha limitations.
- Free exports include a watermark.
- Free exports are limited to short clips.
- Pro behavior is present as a gated workflow foundation.
- Face replacement requires upgrade gating and explicit consent review.

## Known Limitations

- This is an alpha build, not a final production release.
- The app is currently unsigned, so Windows SmartScreen may show an
  unknown-publisher warning.
- The current public bundle is focused on Windows/NVIDIA systems.
- CPU-only systems may be slow or unsupported depending on the bundle.
- Free 720p export cap may not be fully enforced yet.
- The watermark is a simple visible text overlay.
- Some optional model or runtime features may require local setup.
- Third-party model weights may be excluded until redistribution rights are
  confirmed.
- Public support issues should not include private, sensitive, or identifying
  videos.

## Model Weights

Some third-party model weights may not be bundled with the alpha. If the app
reports missing model files, see `MODEL_SETUP_PUBLIC_ALPHA.txt`.

Do not redistribute third-party model weights unless you have confirmed
redistribution rights.

## Safety

FaceForge is primarily for privacy-preserving blur and redaction. Face
replacement should only be used with consent and rights to the relevant source
and target media.

Do not use FaceForge for nonconsensual media, impersonation, harassment,
public-figure deception, sexual content involving real people, minors, fraud,
scams, or misleading identity use.

## Checksums

See `SHA256SUMS.txt` for the release ZIP checksum.
