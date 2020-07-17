# Introduction

The [AER Line Parameter Database](http://rtweb.aer.com/line_param_frame.html) includes line parameters for molecules that contribute to radiative transfer (RT), if these parameters are available. However, but many molecules only have associated absorption coefficients for the bands and temperatures where they are active. These coefficients are stored f in the files underneath this repository's `xs` directory. The `FSCDXS` file is used by LBLRTM as a lookup table.

The only AER model currently in this repository that uses this databse is [LBLRTM](https://github.com/AER-RC/LBLRTM),so it has been added as a submodule to that repository.
