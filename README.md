# Marlin 2.* from Kingroon KP3S Titan no-bltouch

Target platform - stock KP3S with Titan head.

## Key differences:

- Linear advance enabled by default
- Fast print start
- Automated release builds

## Install and start-up:

- Download latest build from [Releases](https://github.com/gmelikov/kingroon_kp3s_marlin/releases)
- Flash it via microsd card
- [Calibrate Linear advance](https://marlinfw.org/tools/lin_advance/k-factor.html)
- Set Linear advance in your slicer as start G-code: `M900 K0.22; LINEAR_ADVANCE`, replace `0.22` with your best factor

#### Optional:

- Reset EEPROM
- Calibrate PID

#### Notes

- Based on https://github.com/bdwilson/KP3S/tree/main/releases/2.1.1/no-bltouch , [initial diff](https://github.com/gmelikov/kingroon_kp3s_marlin/commit/44e1ab8b7cf8206eea1ec07960c5b797d5a45da0)
