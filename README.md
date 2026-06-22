# CVG Storm Surge Wizard

Real-time storm surge analysis and coastal inundation modeling.

## Overview

The CVG Storm Surge Wizard provides API-driven storm surge analysis for coastal areas, combining:

- NOAA tidal datum data
- SLOSH (Sea, Lake, and Overland Surges from Hurricanes) model outputs
- Digital Elevation Models (DEM)
- Real-time meteorological data

## Status

This repository is under active development. Core modules are being migrated from the internal CVG platform.

## Architecture

```
storm-surge-wizard/
├── api/           # FastAPI REST API
├── models/        # Storm surge computation models
├── data/          # Data acquisition and processing
├── tests/         # Test suite
└── deploy/        # Deployment scripts
```

## Related Repositories

- [CVG-Neuron](https://github.com/cleargeo/CVG-Neuron) -- AI orchestration platform
- [CVG-Rainfall-Wizard](https://github.com/cleargeo/CVG-Rainfall-Wizard) -- Rainfall flood analysis
- [CVG-SLR-Wizard](https://github.com/cleargeo/CVG-SLR-Wizard) -- Sea level rise modeling

## License

Proprietary -- Clearview Geographic LLC
