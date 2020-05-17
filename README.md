# Introduction

AER does not maintain line parameters for all possible molecules that contribute to radiative transfer (RT). Spectral parameters have been added to the [AER Line Parameter Database](http://rtweb.aer.com/line_param_frame.html) where they have been measured, but others only have associated absorption coefficients for bands and temperatures where they are active. These coefficients are stored for applicable molecules in the files underneath this repository's `xs` directory. The `FSCDXS` is a used by LBLRTM as a kind of lookup table.

This database is of little use outside of [LBLRTM](https://github.com/AER-RC/LBLRTM) (unless other models have been designed to read this database), so it has been added as a submodule to that repository.
