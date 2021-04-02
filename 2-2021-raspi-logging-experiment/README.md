# 2/2021 Raspi Logging Experiment
This repository contains data and analysis from a CPC logging experiment
conducted in February 2021 in which we ran the [logger](https://github.com/airpartners/logger) setup
as of 2/17/2021 for 24 hours and recorded data on both the CPC itself
and the Raspberry Pi.

It ran on the AC first floor with the `b` section attached to a HEPA filter
cartridge and the `a` section filtering 3D printer adjacent air. The period was
set to switch the valve the sensor sampled air from every 300 seconds.

The [validation notebook](https://github.com/airpartners/logger-data-analysis/blob/main/2-2021-raspi-logging-experiment/logging-validation.ipynb)
contains both codes and some frameworks around thinking about the data, and the [data/](https://github.com/airpartners/logger-data-analysis/tree/main/2-2021-raspi-logging-experiment/data)
folder contains raw CPC data, raw raspberry pi data, and combined CPC data.
