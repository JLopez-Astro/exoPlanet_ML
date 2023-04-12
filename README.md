# exoPlanet_ML, test
A machine learning project involving exoplanet data from Kepler telescope.
This is a playground project to help me better understand machine learning.

Cumulative KOI: 9564
Kepler Confirmed Planets: 2733
Kepler Candidate Planets: 2054
Kepler False Positive Planets: 4839

Two datasets:
- Kepler dataset for supervised classification
- Confirmed Exoplanets dataset for unsupervised clustering

Kepler Cumulative dataset Columns:
 kepid:          KepID
 koi_disposition: Exoplanet Archive Disposition
 koi_pdisposition: Disposition Using Kepler Data
 koi_period:     Orbital Period [days]
 koi_time0bk:    Transit Epoch [BKJD]
 koi_time0:      Transit Epoch [BJD]
 koi_eccen:      Eccentricity
 koi_impact:     Impact Parameter
 koi_duration:   Transit Duration [hrs]
 koi_depth:      Transit Depth [ppm]
 koi_ror:        Planet-Star Radius Ratio
 koi_prad:       Planetary Radius [Earth radii]
 koi_teq:        Equilibrium Temperature [K]
 koi_steff:      Stellar Effective Temperature [K]
 koi_slogg:      Stellar Surface Gravity [log10(cm/s**2)]
 koi_srad:       Stellar Radius [Solar radii]
 koi_smass:      Stellar Mass [Solar mass]
 ra:             RA [decimal degrees]
 dec:            Dec [decimal degrees]
 koi_kepmag:     Kepler-band [mag]


Confirmed Exoplanet dataset columns:
 tic_id:         TIC ID
 gaia_id:        GAIA ID
 pl_orbper:      Orbital Period [days]
 pl_radj:        Planet Radius [Jupiter Radius]
 pl_massj:       Planet Mass [Jupiter Mass]
 pl_dens:        Planet Density [g/cm**3]
 pl_orbeccen:    Eccentricity
 pl_eqt:         Equilibrium Temperature [K]
 pl_trandep:     Transit Depth [%]
 pl_trandur:     Transit Duration [hours]
 pl_ratdor:      Ratio of Semi-Major Axis to Stellar Radius
 pl_ratror:      Ratio of Planet to Stellar Radius
 st_teff:        Stellar Effective Temperature [K]
 st_rad:         Stellar Radius [Solar Radius]
 st_mass:        Stellar Mass [Solar mass]
 st_lum:         Stellar Luminosity [log(Solar)]
 ra:             RA [deg]
 dec:            Dec [deg]
 sy_pmra:        Proper Motion (RA) [mas/yr]
 sy_pmdec:       Proper Motion (Dec) [mas/yr]
 sy_dist:        Distance [pc]

