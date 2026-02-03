# Speckle Size Calculator

A web-based tool for calculating optimal speckle pattern sizes for Digital Image Correlation (DIC) applications.

## Features

- **Camera Selection**: Choose from 35+ pre-configured CSI camera models
- **Custom Resolution**: Enter any camera resolution manually
- **Calibration File Support**: Upload VIC-3D `.z3d` calibration files to auto-populate settings
- **Unit Flexibility**: Work in inches or millimeters
- **Kit Matching**: Automatically recommends the closest Correlated Solutions Speckle Kit size

## Speckle Kit Sizes

| Size (in) | Size (mm) | Band Color |
|-----------|-----------|------------|
| 0.007"    | 0.18 mm   | Black      |
| 0.013"    | 0.33 mm   | Yellow     |
| 0.026"    | 0.66 mm   | Green      |
| 0.05"     | 1.27 mm   | Red        |
| 0.10"     | 2.54 mm   | White      |
| 0.20"     | 5.08 mm   | Blue       |

## Usage

1. Select your camera or enter custom resolution
2. Enter your field of view dimensions, OR upload a `.z3d` calibration file
3. Click "Calculate" to get the recommended speckle size

## Embedding

Embed this calculator in your website using an iframe:

```html
<iframe src="https://YOUR-USERNAME.github.io/speckle-calculator-web/"
        width="100%" height="900" frameborder="0"></iframe>
```

## Support

For questions about the Speckle Kit, contact:
- Email: support@correlatedsolutions.com
- Phone: 1.803.926.7272

---

*Correlated Solutions - Measure with Confidence*
