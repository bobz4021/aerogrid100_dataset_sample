# AeroGrid100 Dataset Sample

This repository provides a sample from the **AeroGrid100** dataset, a structured aerial imagery collection designed for tasks such as Neural Radiance Field (NeRF) training and 3D scene reconstruction.

##  Repository Contents

- `DJI_001_EX1TLCO/`: Sample image data captured using a DJI Air 3 drone.
- `transforms.json`: Camera pose file with extrinsic matrices aligned to NeRF’s OpenGL coordinate system.

##  Completed

- **Sample Data Collection**: Images captured with a DJI Air 3 drone over a defined urban area.
- **Camera Pose Conversion**: Generated `transforms.json` with 6-DoF camera-to-world transformations.
- **OpenGL Alignment**: Poses conform to NeRF coordinate conventions for immediate use in common frameworks.

## To Be Completed

- [ ] **Full Dataset Upload**: Add all 100 grid point locations across 5 altitudes with full yaw-pitch sampling.
- [ ] **Metadata Expansion**: Include GPS, altitude, timestamp, and full drone flight logs.
- [ ] **Scripts**: Provide utilities for pose computation, JSON formatting, and NeRF-ready data conversion.
- [ ] **Documentation**: Add usage instructions and a data collection methodology overview.
- [ ] **Citation Information**: Add BibTeX entry and paper reference once published.

## Citation

If you use this dataset in your work, please cite our forthcoming publication (to be added).

## Contact

For questions or collaboration inquiries, contact this github user.
