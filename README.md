# Charybdis Mini ZMK Configuration

ZMK configuration for a wireless 3x6 Charybdis Mini with a PMW3610 trackball.
The right half is the split central and owns the pointing device; the left half
is the peripheral.

## Firmware targets

- `charybdis_left` on `nice_nano//zmk`
- `charybdis_right` on `nice_nano//zmk`, with ZMK Studio over USB UART
- `settings_reset` on `nice_nano//zmk`

GitHub Actions builds all targets from [build.yaml](build.yaml). Downloaded
firmware artifacts can be kept under `firmware/`, which is intentionally ignored
by Git.
