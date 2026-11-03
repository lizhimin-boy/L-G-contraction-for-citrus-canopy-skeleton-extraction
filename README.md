# LGWTO
### L-G Contraction for Citrus Canopy Skeleton Extraction

A citrus canopy skeleton extraction tool based on learning-guided L-G contraction, with Chinese and English interfaces.

[Download v1.1.0](https://github.com/lizhimin-boy/L-G-contraction-for-citrus-canopy-skeleton-extraction/releases/tag/v1.1.0) · [Report an Issue](https://github.com/lizhimin-boy/L-G-contraction-for-citrus-canopy-skeleton-extraction/issues)

---
## Software Preview

### Main Interface

<img width="1442" height="757" alt="软件主页图1" src="https://github.com/user-attachments/assets/b613664a-46a5-4b09-9528-b96b09dabc10" />



### Skeleton Extraction Results

<img width="763" height="674" alt="测量角度2" src="https://github.com/user-attachments/assets/6229e98b-16bf-43f0-a567-f3040226606d" />



## Overview

LGWTO is designed to extract skeleton structures from citrus canopy point clouds. It combines learning-guided contraction with topology-aware refinement to obtain clearer branching structures.

The Windows application provides Chinese and English interfaces.

## Download

The Windows installer is available on the release page:

**[Download LGWTO v1.1.0 for Windows](https://github.com/lizhimin-boy/L-G-contraction-for-citrus-canopy-skeleton-extraction/releases/tag/v1.1.0)**

Under **Assets**, download:

`LGWTO_v1_1_CN_EN_Setup.exe`

The automatically generated **Source code (zip)** and **Source code (tar.gz)** archives are repository snapshots, not application installers.

> Version v1.1.0 is currently provided as a pre-release for testing and feedback.

## System Requirements

| Item | Requirement |
| --- | --- |
| Platform | Windows, 64-bit |
| Runtime | MATLAB Runtime R2024a |
| Interface languages | Chinese and English |

A full MATLAB installation is not required.

## Installation

### 1. Install MATLAB Runtime

Download and install the latest update of **MATLAB Runtime R2024a for Windows (64-bit)**:

[MATLAB Runtime — Official Download](https://www.mathworks.com/products/compiler/matlab-runtime.html)

If a compatible MATLAB Runtime R2024a is already installed, this step can be skipped.

### 2. Install LGWTO

1. Open the release page linked above.
2. Download `LGWTO_v1_1_CN_EN_Setup.exe` from **Assets**.
3. Run the installer and follow the installation wizard.
4. Launch LGWTO.

## Installer Verification

SHA256 checksum for `LGWTO_v1_1_CN_EN_Setup.exe`:

```text
D42CD95AF5B8AF4A45B76A713A62A6AE1B4B31CACCEA35312E785B2F700BAD57
```

To verify the downloaded installer, open PowerShell in its folder and run:

```powershell
Get-FileHash -Algorithm SHA256 .\LGWTO_v1_1_CN_EN_Setup.exe
```

The calculated value should match the checksum above.

## Feedback

Please report installation problems, errors, or suggestions through [GitHub Issues](https://github.com/lizhimin-boy/L-G-contraction-for-citrus-canopy-skeleton-extraction/issues).

When reporting a problem, please include:

- Your Windows version.
- Your MATLAB Runtime version.
- Steps to reproduce the problem.
- The error message or a screenshot.
