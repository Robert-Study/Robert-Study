# Gibbs–Marangoni Effect: Summer Research Project

**Capillary-wave attenuation measured with laser interferometry**

[Read the Gibbs–Marangoni Effect Summer Research Project report](https://1drv.ms/b/c/4a8cd531de3d2eb8/IQB8Hye49FXSR7A0i2hvo-G8Ab0BsuLALmtz2v9vtYWGD7U?e=uABOP4) · [Back to profile](../README.md)

This summer project investigated how a thin surface film changes the decay of capillary waves. I used laser interferometry to measure wave motion at different distances from the source and fitted the amplitude decay in Python.

The analysis included correcting laser-intensity fluctuations, modelling the detector response, fitting wave motion and estimating attenuation with uncertainty-weighted fits.

## Reported results at 100 Hz

| Sample | Attenuation coefficient |
| --- | ---: |
| Water | 9.72 ± 1.61 m⁻¹ |
| 5% acetone solution | 10.51 ± 1.79 m⁻¹ |
| Water with a thin olive-oil film | 18.54 ± 6.19 m⁻¹ |

![Reported capillary-wave attenuation coefficients with their quoted uncertainties](../assets/capillary-wave-summary.png)

*Plot reconstructed from the report's summary values. Error bars show the quoted uncertainties; they are not newly estimated confidence intervals.*

The oil-covered sample's point estimate is approximately **91% higher** than that for water. The uncertainty is substantial, however, so that percentage should not be read as a precise measurement of a separate damping mechanism.

## Interpretation and limits

The observations suggest increased attenuation in the presence of a surface film, consistent with the motivation for investigating Gibbs–Marangoni damping. The experiment did not directly measure surface tension with a tensiometer or establish a precisely controlled monolayer. It therefore could not cleanly separate the contributions of surface elasticity, surface tension and other experimental effects.

A useful follow-up would combine controlled surfactant coverage with independent surface-tension measurements and repeat the attenuation experiment across several frequencies. That would make the physical interpretation less dependent on assumptions about the liquid surface.

The linked report documents the original experiment and acknowledges the supervision and laboratory support. Raw time traces are not included here; the figure above is a transparent summary of reported estimates, not a reanalysis of those traces.
