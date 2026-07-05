# FaceForge Public Alpha Quickstart

This guide is for public testers using the FaceForge v0.1.0 Alpha Windows ZIP.

## Install

1. Go to the
   [GitHub Releases page](https://github.com/CalvinSturm/FaceForge-Releases/releases).

2. Download the v0.1.0 Alpha ZIP.

3. Extract the ZIP to a normal folder, for example:

   ```text
   C:\Users\YourName\Apps\FaceForge\
   ```

4. Open the extracted folder.

5. Run `FaceForge.exe`. If your ZIP includes `run.bat` or
   `Launch FaceForge.bat`, you can use that instead.

## Windows SmartScreen

The alpha is currently unsigned. Windows may show a SmartScreen warning for an
unknown publisher. Only continue if you downloaded FaceForge from the official
GitHub Releases page.

## Basic Blur Workflow

1. Add a target video.
2. Leave the workflow set to `Blur Faces / Privacy`.
3. Preview the video if needed.
4. Adjust blur strength if the default is too light or too strong.
5. Choose the output location if prompted.
6. Start the export.
7. When export finishes, open the output file from the app or from the selected
   output folder.

Face replacement is an advanced, consent-based Pro workflow. Public alpha
testing should start with the default blur workflow.

## Troubleshooting

### Missing Models

If FaceForge reports missing models, see `MODEL_SETUP_PUBLIC_ALPHA.txt`.
App-local model files belong under:

```text
FaceForge\models\
```

Do not redistribute third-party model weights unless you have confirmed
redistribution rights.

### CUDA or GPU Issues

- Confirm you are using a Windows system with an NVIDIA RTX GPU.
- Update your NVIDIA driver.
- Restart the app after driver updates.
- If the app falls back to CPU processing, export may be much slower.

### App Does Not Launch

- Make sure the ZIP was fully extracted before running `FaceForge.exe`.
- Try running from a simple path such as `C:\Apps\FaceForge\`.
- Check that antivirus or SmartScreen did not quarantine files.
- Re-download the ZIP from the official GitHub Releases page if extraction
  failed.
- Open a GitHub issue using the template in `SUPPORT.md`.
