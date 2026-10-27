# FUNCEME Radar QPE

Processing, calibration and validation of radar-derived
quantitative precipitation estimates using FUNCEME
radar observations and rain gauges.

## Objectives

1. Inspect radar observations and metadata.
2. Verify radar geometry and temporal sampling.
3. Produce a baseline radar rainfall product.
4. Compare radar estimates against rain gauges.
5. Calibrate and independently validate the QPE.

## Tools

- Python
- PACHA
- Xarray
- Jupyter notebooks
- Conda

## Repository organization

- `config/`: processing and calibration configurations
- `notebooks/`: scientific exploration and analysis
- `scripts/`: reproducible processing scripts
- `data/`: local radar and gauge data (excluded from Git)
- `results/`: calibration results and figures
- `tests/`: automated checks

## Environment

Development currently uses the existing `pacha`
Conda environment, with PACHA installed from
`WORK/code/PACHA`.

See `environment.yml` for the initial Conda
dependency specification.

## Progress

- [x] Initialize Git repository
- [x] Verify PACHA environment
- [ ] Inspect FUNCEME radar data
- [ ] Produce baseline QPE
- [ ] Compare radar with gauges
- [ ] Calibrate rainfall estimates
- [ ] Independent validation
