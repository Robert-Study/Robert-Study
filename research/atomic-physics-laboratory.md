# Atomic Physics Laboratory

**Doppler-free laser spectroscopy on rubidium · 77% — First-Class mark**

[Read the Atomic Physics Laboratory report](https://1drv.ms/b/c/4a8cd531de3d2eb8/IQCydZCXEyXXRYGX54IusWuyAX9yCW92tuoZgfGBUgo1yqQ?e=XzBLd3) · [Back to profile](../README.md)

The experiment used saturated-absorption spectroscopy to resolve hyperfine features in the rubidium D₂ transition near 780 nm. Counter-propagating pump and probe beams reduced Doppler broadening, while a Fabry–Pérot cavity provided a frequency reference for the laser sweep.

## Analysis

I converted the recorded time axis into frequency, fitted Gaussian profiles to the Doppler-broadened features and Lorentzian profiles to the Doppler-free resonances, then used the fitted separations to estimate hyperfine coupling constants.

![Doppler-broadened rubidium spectrum with Gaussian fits, extracted from the laboratory report](../assets/atomic-spectrum.png)

*The Gaussian fitting stage from Figure 5 of the report.*

| Reported quantity | Estimate |
| --- | ---: |
| ⁸⁵Rb ground-state magnetic-dipole constant | 1005.7 ± 15.1 MHz |
| ⁸⁷Rb ground-state magnetic-dipole constant | 3416.1 ± 5.1 MHz |
| ⁸⁵Rb excited-state magnetic-dipole constant | 25.9 ± 1.3 MHz |
| ⁸⁷Rb excited-state magnetic-dipole constant | 86.7 ± 2.7 MHz |
| ⁸⁵Rb excited-state electric-quadrupole constant | 28.4 ± 2.8 MHz |
| ⁸⁷Rb excited-state electric-quadrupole constant | 14.6 ± 2.9 MHz |

The report compares these estimates with literature values and examines departures from a linear laser-frequency sweep. It reports a sweep nonlinearity estimate of approximately **1.5 ± 0.3%**.

## What I would carry into a further experiment

The precision returned by a curve fit is only one part of the uncertainty. Frequency calibration, beam alignment and power broadening can affect the extracted parameters even when a fitted waveform looks convincing. A fuller analysis would propagate calibration uncertainty jointly with the resonance-fit covariance and distinguish statistical from systematic contributions.

This page summarises the original report. The raw oscilloscope records and the full analysis code are not included here, so these values are reported experimental results rather than a newly reproduced benchmark. The report credits the laboratory partner separately.
