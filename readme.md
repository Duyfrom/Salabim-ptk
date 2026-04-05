<p align="center">
  <img src="https://www.salabim.org/salabim_logo_payoff.png" alt="salabim logo" width="400"/>
</p>

<h1 align="center">SalabimPtk</h1>

<p align="center">
  <strong>Production Simulation powered by salabim</strong>
</p>

<p align="center">
  <a href="https://pypi.org/project/salabim/"><img src="https://img.shields.io/pypi/v/salabim" alt="PyPI"></a>
  <a href="https://pypi.org/project/salabim/"><img src="https://img.shields.io/pypi/pyversions/salabim" alt="Python Version"></a>
  <img src="https://img.shields.io/pypi/l/salabim" alt="License">
  <img src="https://img.shields.io/badge/code%20style-black-000000.svg" alt="Code Style">
</p>

---

## About

SalabimPtk is a production simulation project built on [salabim](https://github.com/salabim/salabim), a discrete event simulation (DES) library for Python. The project focuses on modeling and analyzing production systems -- identifying bottlenecks, evaluating throughput, and optimizing manufacturing workflows.

## Why salabim?

Salabim provides an intuitive, process-oriented approach to discrete event simulation without requiring `yield` statements for process control. It includes:

| Feature | Description |
|---|---|
| **Components** | Model machines, operators, conveyors, and other production entities |
| **Queues** | Track WIP, buffers, and waiting lines |
| **Resources** | Represent shared equipment, tools, and personnel |
| **Stores** | Model inventory and material storage |
| **States** | Capture machine states, shift patterns, and system modes |
| **Monitors** | Collect and visualize KPIs like cycle time, utilization, and throughput |
| **Animation** | 2D/3D visualization and video export for presentations and analysis |

For full salabim documentation, visit [www.salabim.org/manual](https://www.salabim.org/manual).

## Getting Started

### Prerequisites

- Python 3.8+

### Installation

```bash
pip install salabim
```

### Quick Example

```python
import salabim as sim

env = sim.Environment()
# Your production model here
env.run()
```

## Project Status

> This project is under active development.
> Features, models, and documentation will be expanded as the project grows.

## Acknowledgements

Built on [salabim](https://github.com/salabim/salabim) by Ruud van der Ham. Salabim is licensed under the MIT License.

## License

See [LICENSE](LICENSE) for details.
