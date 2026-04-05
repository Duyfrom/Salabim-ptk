<p align="center">
  <img src="https://www.salabim.org/salabim_logo_payoff.png" alt="salabim" width="480"/>
</p>

<p align="center">
  <a href="https://pypi.org/project/salabim/"><img src="https://img.shields.io/pypi/v/salabim" alt="PyPI version"></a>&nbsp;
  <a href="https://pypi.org/project/salabim/"><img src="https://img.shields.io/pypi/pyversions/salabim" alt="Python versions"></a>&nbsp;
  <img src="https://img.shields.io/pypi/implementation/salabim" alt="Implementation">&nbsp;
  <img src="https://img.shields.io/pypi/l/salabim" alt="License">&nbsp;
  <img src="https://img.shields.io/badge/code%20style-black-000000.svg" alt="Code style: black">
</p>

<p align="center"><em>Production simulation built on salabim -- a Python library for object-oriented discrete event simulation and animation.</em></p>

---

## Introduction

Discrete event simulation (DES) finds applications in various logistical domains including production facilities, warehousing, airports, hospitals, mining, materials handling, steel mills, and computer network analysis.

This project applies salabim to **production simulation** -- modeling manufacturing workflows, identifying bottlenecks, and optimizing throughput. Salabim follows a well-proven and intuitive process description method, and the package provides:

- **Components** -- model machines, operators, conveyors, and production entities
- **Queues** -- track WIP, buffers, and waiting lines
- **Resources** -- represent shared equipment, tools, and personnel
- **Stores** -- model inventory and material storage
- **States** -- capture machine states, shift patterns, and system modes
- **Monitors** -- collect and present data, KPIs, cycle times, and utilization
- **2D and 3D animation** -- visualization and video production for analysis
- **Tracing facilities** -- debug and verify simulation logic
- **Advanced statistical sampling** -- drive stochastic process modeling

In contrast to some other Python DES packages, salabim does not require the use of `yield` statements for process control, making it more straightforward to use. Salabim has minimal requirements, especially when animation is disabled.

## Features and Documentation

- **Cross-platform**: runs on Windows, macOS, Linux, iOS/iPadOS (Pythonista), and even "Python In Excel"
- **Comprehensive documentation**: [www.salabim.org/manual](https://www.salabim.org/manual)

## Getting Started

**Prerequisites:** Python 3.8+

```bash
pip install salabim
```

To learn more about salabim, visit [www.salabim.org](https://www.salabim.org) for installation details and tutorials.

## Project Status

> **This project is under active development.**
> Models, tooling, and documentation will be expanded as the project grows.

## Contributing

Contributions are welcome. You can open a pull request or submit an issue on [GitHub](https://github.com/Duyfrom/Salabim-ptk).

For questions and discussions about the salabim library itself, see the upstream repo at [salabim/salabim](https://github.com/salabim/salabim) or the [salabim Google user group](https://groups.google.com/g/salabim).

## License

Salabim is licensed under the MIT License. See [LICENSE](LICENSE) for details.
