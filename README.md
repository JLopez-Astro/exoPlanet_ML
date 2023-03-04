# exoPlanet_ML
A machine learning project involving exoplanet data from Kepler telescope.
This is a playground project to help me better understand machine learning.

Cumulative KOI: 9564
Kepler Confirmed Planets: 2733
Kepler Candidate Planets: 2054
Kepler False Positive Planets: 4839

Two datasets:
- Kepler dataset for supervised classification
- Confirmed Exoplanets dataset for unsupervised clustering

Columns:
# COLUMN kepid:          KepID
# COLUMN koi_disposition: Exoplanet Archive Disposition
# COLUMN koi_pdisposition: Disposition Using Kepler Data
# COLUMN koi_score:      Disposition Score
# COLUMN koi_period:     Orbital Period [days]
# COLUMN koi_period_err1: Orbital Period Upper Unc. [days]
# COLUMN koi_period_err2: Orbital Period Lower Unc. [days]
# COLUMN koi_time0bk:    Transit Epoch [BKJD]
# COLUMN koi_time0bk_err1: Transit Epoch Upper Unc. [BKJD]
# COLUMN koi_time0bk_err2: Transit Epoch Lower Unc. [BKJD]
# COLUMN koi_time0:      Transit Epoch [BJD]
# COLUMN koi_time0_err1: Transit Epoch Upper Unc. [BJD]
# COLUMN koi_time0_err2: Transit Epoch Lower Unc. [BJD]
# COLUMN koi_impact:     Impact Parameter
# COLUMN koi_impact_err1: Impact Parameter Upper Unc.
# COLUMN koi_impact_err2: Impact Parameter Lower Unc.
# COLUMN koi_duration:   Transit Duration [hrs]
# COLUMN koi_duration_err1: Transit Duration Upper Unc. [hrs]
# COLUMN koi_duration_err2: Transit Duration Lower Unc. [hrs]
# COLUMN koi_depth:      Transit Depth [ppm]
# COLUMN koi_depth_err1: Transit Depth Upper Unc. [ppm]
# COLUMN koi_depth_err2: Transit Depth Lower Unc. [ppm]
# COLUMN koi_prad:       Planetary Radius [Earth radii]
# COLUMN koi_prad_err1:  Planetary Radius Upper Unc. [Earth radii]
# COLUMN koi_prad_err2:  Planetary Radius Lower Unc. [Earth radii]
# COLUMN koi_teq:        Equilibrium Temperature [K]
# COLUMN koi_teq_err1:   Equilibrium Temperature Upper Unc. [K]
# COLUMN koi_teq_err2:   Equilibrium Temperature Lower Unc. [K]
# COLUMN koi_insol:      Insolation Flux [Earth flux]
# COLUMN koi_insol_err1: Insolation Flux Upper Unc. [Earth flux]
# COLUMN koi_insol_err2: Insolation Flux Lower Unc. [Earth flux]
# COLUMN koi_model_snr:  Transit Signal-to-Noise
# COLUMN koi_steff:      Stellar Effective Temperature [K]
# COLUMN koi_steff_err1: Stellar Effective Temperature Upper Unc. [K]
# COLUMN koi_steff_err2: Stellar Effective Temperature Lower Unc. [K]
# COLUMN koi_slogg:      Stellar Surface Gravity [log10(cm/s**2)]
# COLUMN koi_slogg_err1: Stellar Surface Gravity Upper Unc. [log10(cm/s**2)]
# COLUMN koi_slogg_err2: Stellar Surface Gravity Lower Unc. [log10(cm/s**2)]
# COLUMN koi_srad:       Stellar Radius [Solar radii]
# COLUMN koi_srad_err1:  Stellar Radius Upper Unc. [Solar radii]
# COLUMN koi_srad_err2:  Stellar Radius Lower Unc. [Solar radii]
# COLUMN ra:             RA [decimal degrees]
# COLUMN dec:            Dec [decimal degrees]
# COLUMN koi_kepmag:     Kepler-band [mag]

