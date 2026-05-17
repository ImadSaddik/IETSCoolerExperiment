# IETS GT500 cooler experiment

[![GitHub license](https://img.shields.io/github/license/ImadSaddik/IETSCoolerExperiment)](https://github.com/ImadSaddik/IETSCoolerExperiment/blob/main/LICENSE)

This repository contains the raw data, visualization scripts, and generated graphs for my article on eliminating laptop thermal throttling using high static pressure.

The project analyzes thermal data collected during heavy gaming workloads on an `Intel i7-13650HX` and `RTX 4070` laptop. We compare standard setups against the `IETS GT500` cooler to see if high static pressure is a viable solution for severe thermal limits.

In this repository, you will find:

- `data/`: Raw CSV logs exported from HWiNFO during the Cinebench and gaming tests.
- `images/`: The final SVG graphs used in the article.
- `notebooks/`: Jupyter notebooks containing the Python code used to load, clean the data and generate the graphs.

In short, the experiment shows that using a high static pressure cooler drops CPU temperatures by nearly 30°C and completely stops thermal throttling under heavy loads.

![CPU package temperature during the test](./images/iets_gt_500/cpu_package_temperature_smoothed.svg)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact

You can reach me through:

- **Email:** [simad3647@gmail.com](mailto:simad3647@gmail.com)
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/imadsaddik/)
