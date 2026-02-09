<!-- markdownlint-disable -->
<h1 align="center">
    Best-of PES-AI: Open Source AI/ML for Power & Energy Systems
    <br>
</h1>

<p align="center">
    <strong>A weekly-updated, ranked list of open-source AI and machine learning projects for IEEE Power & Energy Society domains.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/martymcenroe/best-of-pes-ai/main/.meta/mainlist/shield.json&style=flat"></a>
    <a href="#contents" title="Project Count"><img src="https://img.shields.io/badge/projects-38-blue.svg?color=5ac4bf"></a>
    <a href="https://github.com/martymcenroe/best-of-pes-ai/blob/main/CONTRIBUTING.md" title="Contributions Welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="#contents" title="Last Updated"><img src="https://img.shields.io/github/last-commit/martymcenroe/best-of-pes-ai?label=updated"></a>
</p>

This list tracks open-source projects at the intersection of **artificial intelligence** and **power & energy systems engineering**. Categories align with [IEEE PES](https://ieee-pes.org) strategic focus areas including grid modernization, renewable integration, resilience, and electrification.

Maintained as a resource for the **PES Long Range Planning Committee (LRPC)** and the broader power systems research and engineering community. Projects are ranked by a composite quality score based on GitHub activity, package downloads, and community engagement — updated automatically every week.

> Curated by **Marty McEnroe, PE** | IEEE PES LRPC SC-5

## Contents

- [Load & Demand Forecasting](#load--demand-forecasting) _4 projects_
- [Grid Optimization & Operations](#grid-optimization--operations) _7 projects_
- [Renewable Energy Forecasting](#renewable-energy-forecasting) _3 projects_
- [Fault Detection & Diagnostics](#fault-detection--diagnostics) _5 projects_
- [Grid Stability & Reinforcement Learning](#grid-stability--reinforcement-learning) _5 projects_
- [DER & Microgrid Intelligence](#der--microgrid-intelligence) _4 projects_
- [NLP for Energy & Standards](#nlp-for-energy--standards) _1 projects_
- [Synthetic Data & Benchmarks](#synthetic-data--benchmarks) _5 projects_
- [Computer Vision for Infrastructure](#computer-vision-for-infrastructure) _2 projects_
- [Energy Market & Price Forecasting](#energy-market--price-forecasting) _2 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Python
- <img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/julia.ico" style="display:inline;" width="13" height="13">&nbsp; Julia
- <img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13">&nbsp; Jupyter Notebook examples
- <img src="https://www.gstatic.com/devrel-devsite/prod/v0d244f667a3683225cca86d0ecf9b9b81b1e734e55a030dcd3f3b3decd3a0b72/tensorflow/images/favicon.png" style="display:inline;" width="13" height="13">&nbsp; TensorFlow
- <img src="https://pytorch.org/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; PyTorch
- <img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/university.ico" style="display:inline;" width="13" height="13">&nbsp; University project
- <img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/lab.ico" style="display:inline;" width="13" height="13">&nbsp; National laboratory project

<br>

## Load & Demand Forecasting

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_AI/ML models for electrical load prediction, demand response, and consumption pattern analysis._

<details><summary><b><a href="https://www.lfenergy.org/projects/openstef/">OpenSTEF</a></b> (🥇23 ·  ⭐ 130) - Automated ML pipelines for short-term energy forecasting. LF.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenSTEF/openstef) (👨‍💻 43 · 🔀 39 · 📦 17 · 📋 170 - 23% open · ⏱️ 12.12.2025):

	```
	git clone https://github.com/OpenSTEF/openstef
	```
- [PyPi](https://pypi.org/project/openstef) (📥 6K / month):
	```
	pip install openstef
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/dafrie/lstm-load-forecasting">LSTM Load Forecasting</a></b> (🥈9 ·  ⭐ 200 · 💀) - LSTM-based load forecasting with TBATS and ARIMA.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/sarajcev/STLF">Short-Term Load Forecasting</a></b> (🥉6 ·  ⭐ 10 · 💀) - Substation-level short-term load forecasting using.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Helmholtz-AI-Energy/electric-generation-forecasting">Electric Generation Forecasting</a></b> (🥉6 ·  ⭐ 7 · 💀) - LSTM-CNN models for German electricity generation mix.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://pytorch.org/favicon.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Grid Optimization & Operations

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_ML-driven optimal power flow, unit commitment, grid scheduling, and dispatch._

<details><summary><b><a href="https://pypsa.org">PyPSA</a></b> (🥈32 ·  ⭐ 1.8K) - Python for Power System Analysis - optimization and simulation of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/PyPSA) (👨‍💻 110 · 🔀 600 · 📦 320 · 📋 490 - 18% open · ⏱️ 06.02.2026):

	```
	git clone https://github.com/PyPSA/PyPSA
	```
- [PyPi](https://pypi.org/project/pypsa) (📥 21K / month):
	```
	pip install pypsa
	```
- [Conda](https://anaconda.org/conda-forge/pypsa) (📥 200K · ⏱️ 14.01.2026):
	```
	conda install -c conda-forge pypsa
	```
</details>
<details><summary><b><a href="https://github.com/PowerGridModel/power-grid-model">Power Grid Model</a></b> (🥈30 ·  ⭐ 210) - High-performance C++/Python distribution grid.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PowerGridModel/power-grid-model) (👨‍💻 33 · 🔀 54 · 📥 1.6K · 📦 38 · 📋 290 - 34% open · ⏱️ 02.02.2026):

	```
	git clone https://github.com/PowerGridModel/power-grid-model
	```
- [PyPi](https://pypi.org/project/power-grid-model) (📥 97K / month):
	```
	pip install power-grid-model
	```
- [Conda](https://anaconda.org/conda-forge/power-grid-model) (📥 4.4M · ⏱️ 03.02.2026):
	```
	conda install -c conda-forge power-grid-model
	```
</details>
<details><summary><b><a href="https://pypsa.org">PyPSA-USA</a></b> (🥉16 ·  ⭐ 120) - Open-source power systems model of US bulk transmission... <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/university.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/pypsa-usa) (👨‍💻 13 · 🔀 39 · 📋 380 - 25% open · ⏱️ 11.09.2025):

	```
	git clone https://github.com/PyPSA/pypsa-usa
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://www.pandapower.org/">pandapower</a></b> (🥇33 ·  ⭐ 1.1K) - Power system modeling and analysis. Pandas-based,.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://pypsa-meets-earth.github.io/">PyPSA-Earth</a></b> (🥉19 ·  ⭐ 320) - First open-source global cross-sectoral energy system.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ShaohuiLiu/GNN_OPF_electricity_market">GNN Optimal Power Flow</a></b> (🥉5 ·  ⭐ 35 · 💀) - Topology-informed GNN for AC-OPF and LMP prediction... <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://pytorch.org/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mukhlishga/gnn-powerflow">GNN Power Flow</a></b> (🥉4 ·  ⭐ 110 · 💀) - Graph neural networks for AC power flow prediction.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://pytorch.org/favicon.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Renewable Energy Forecasting

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Solar irradiance, wind power, and distributed generation prediction models._

<details><summary><b><a href="https://github.com/PyPSA/atlite">Atlite</a></b> (🥇22 ·  ⭐ 370) - Calculating renewable power potentials from weather data. Part of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/atlite) (👨‍💻 43 · 🔀 120 · 📦 110 · 📋 150 - 28% open · ⏱️ 19.09.2025):

	```
	git clone https://github.com/PyPSA/atlite
	```
- [PyPi](https://pypi.org/project/atlite) (📥 3.5K / month):
	```
	pip install atlite
	```
- [Conda](https://anaconda.org/conda-forge/atlite) (📥 120K · ⏱️ 11.08.2025):
	```
	conda install -c conda-forge atlite
	```
</details>
<details><summary><b><a href="https://github.com/PowerGenome/PowerGenome">PowerGenome</a></b> (🥉17 ·  ⭐ 230 · 💤) - Create inputs for power systems models including renewable.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PowerGenome/PowerGenome) (👨‍💻 18 · 🔀 73 · 📋 190 - 48% open · ⏱️ 21.03.2025):

	```
	git clone https://github.com/PowerGenome/PowerGenome
	```
- [PyPi](https://pypi.org/project/PowerGenome) (📥 120 / month):
	```
	pip install PowerGenome
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/Duvey314/austin-green-energy-predictor">Austin Green Energy Predictor</a></b> (🥉5 ·  ⭐ 20 · 💀) - Wind and solar energy prediction for Austin, Texas.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Fault Detection & Diagnostics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_AI for power system fault detection, classification, protective relaying, and anomaly detection._

<details><summary><b><a href="https://pyod.readthedocs.io/">PyOD</a></b> (🥇37 ·  ⭐ 9.7K) - 50+ anomaly detection algorithms. 26M+ downloads. Widely used for grid.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yzhao062/pyod) (👨‍💻 65 · 🔀 1.4K · 📦 5.5K · 📋 360 - 56% open · ⏱️ 05.01.2026):

	```
	git clone https://github.com/yzhao062/pyod
	```
- [PyPi](https://pypi.org/project/pyod) (📥 970K / month):
	```
	pip install pyod
	```
- [Conda](https://anaconda.org/conda-forge/pyod) (📥 180K · ⏱️ 02.12.2025):
	```
	conda install -c conda-forge pyod
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/drivendataorg/power-laws-anomalies">Power Laws Anomalies</a></b> (🥈7 ·  ⭐ 32 · 💀) - Competition winning code for building energy anomaly.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mile888/anomaly_identification">Power System Anomaly Identification</a></b> (🥉6 ·  ⭐ 22 · 💀) - WLS-EKF state estimation combined with ML for power.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/oneapi-src/powerline-fault-detection">Powerline Fault Detection</a></b> (🥉5 ·  ⭐ 3 · 💀) - Intel-optimized partial discharge detection using.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/AgHarsh/Fault-Detection-in-Power-Microgrid">Microgrid Fault Detection</a></b> (🥉4 ·  ⭐ 47 · 💀) - ANN-based fault detection and location in power.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Grid Stability & Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_RL agents and ML models for voltage control, frequency regulation, and dynamic stability._

<details><summary><b><a href="https://l2rpn.chalearn.org/">Grid2Op</a></b> (🥇23 ·  ⭐ 410) - RL testbed for power grid operations. RTE France. L2RPN.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Grid2op/grid2op) (👨‍💻 32 · 🔀 130 · 📋 380 - 14% open · ⏱️ 04.02.2026):

	```
	git clone https://github.com/Grid2op/grid2op
	```
- [PyPi](https://pypi.org/project/grid2op) (📥 2.9K / month):
	```
	pip install grid2op
	```
</details>
<details><summary><b><a href="https://github.com/Grid2op/lightsim2grid">LightSim2Grid</a></b> (🥇23 ·  ⭐ 62) - Fast C++ backend for Grid2Op power flow computations... <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Grid2op/lightsim2grid) (👨‍💻 9 · 🔀 14 · 📥 300 · 📦 74 · 📋 60 - 23% open · ⏱️ 05.02.2026):

	```
	git clone https://github.com/Grid2op/lightsim2grid
	```
- [PyPi](https://pypi.org/project/LightSim2Grid) (📥 23K / month):
	```
	pip install LightSim2Grid
	```
</details>
<details><summary><b><a href="https://github.com/Grid2op/l2rpn-baselines">L2RPN Baselines</a></b> (🥉13 ·  ⭐ 90 · 💤) - Baseline RL agents for L2RPN power grid competitions... <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://pytorch.org/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Grid2op/l2rpn-baselines) (👨‍💻 15 · 🔀 44 · 📋 30 - 43% open · ⏱️ 25.07.2025):

	```
	git clone https://github.com/Grid2op/l2rpn-baselines
	```
- [PyPi](https://pypi.org/project/l2rpn-baselines) (📥 72 / month):
	```
	pip install l2rpn-baselines
	```
</details>
<details><summary><b><a href="https://github.com/Grid2op/chronix2grid">Chronix2Grid</a></b> (🥉13 ·  ⭐ 23) - Synthetic time series generation for Grid2Op environments... <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Grid2op/chronix2grid) (👨‍💻 16 · 🔀 9 · 📦 9 · 📋 59 - 69% open · ⏱️ 09.10.2025):

	```
	git clone https://github.com/Grid2op/chronix2grid
	```
- [PyPi](https://pypi.org/project/chronix2grid) (📥 250 / month):
	```
	pip install chronix2grid
	```
</details>
<details><summary><b><a href="https://github.com/emarche/RL2Grid">RL2Grid</a></b> (🥉6 ·  ⭐ 40) - RL benchmark for power grid operations. Built on Grid2Op... <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/emarche/RL2Grid) (🔀 7 · 📋 3 - 33% open · ⏱️ 05.01.2026):

	```
	git clone https://github.com/emarche/RL2Grid
	```
</details>
<br>

## DER & Microgrid Intelligence

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_AI for distributed energy resource management, microgrid control, and VPP optimization._

<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/Total-RD/pymgrid">pymgrid</a></b> (🥇16 ·  ⭐ 210 · 💀) - Python microgrid simulator with 25 pre-packaged.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/upb-lea/openmodelica-microgrid-gym">OpenModelica Microgrid Gym</a></b> (🥈14 ·  ⭐ 220 · 💀) - OpenAI Gym environment for microgrid control using.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tahanakabi/DRL-for-microgrid-energy-management">DRL Microgrid Energy Management</a></b> (🥉9 ·  ⭐ 240 · 💀) - Deep RL for microgrid energy management systems. 7.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/GitX123/microgrid-ems-drl">Microgrid EMS DRL</a></b> (🥉2 ·  ⭐ 48 · 💀) - Deep RL for battery management in microgrids with.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## NLP for Energy & Standards

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Large language models and NLP applied to energy documents, standards compliance, and knowledge extraction._

<details><summary><b><a href="https://github.com/statnett/Talk2PowerSystem">Talk2PowerSystem</a></b> (🥇10 ·  ⭐ 9) - Natural language interface for querying CIM-based.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/statnett/Talk2PowerSystem) (👨‍💻 6 · 🔀 2 · 📋 17 - 11% open · ⏱️ 05.02.2026):

	```
	git clone https://github.com/statnett/Talk2PowerSystem
	```
</details>
<br>

## Synthetic Data & Benchmarks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Test networks, synthetic grid data generators, and benchmark datasets for power AI research._

<details><summary><b><a href="https://www.gridstatus.io/">GridStatus</a></b> (🥇25 ·  ⭐ 380) - Uniform API for US/Canada ISO electricity data. CAISO, ERCOT,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gridstatus/gridstatus) (👨‍💻 36 · 🔀 70 · 📦 24 · 📋 130 - 32% open · ⏱️ 06.02.2026):

	```
	git clone https://github.com/gridstatus/gridstatus
	```
- [PyPi](https://pypi.org/project/gridstatus) (📥 34K / month):
	```
	pip install gridstatus
	```
</details>
<details><summary><b><a href="https://helics.org/">HELICS</a></b> (🥈21 ·  ⭐ 160) - Co-simulation framework for energy systems. NREL/LLNL/PNNL/ANL.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GMLC-TDC/HELICS) (👨‍💻 39 · 🔀 50 · 📥 31K · 📋 680 - 13% open · ⏱️ 16.08.2025):

	```
	git clone https://github.com/GMLC-TDC/HELICS
	```
- [PyPi](https://pypi.org/project/helics) (📥 7K / month):
	```
	pip install helics
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/e2nIEE/simbench">SimBench</a></b> (🥉17 ·  ⭐ 130) - Benchmark dataset of German LV/MV/HV grids for power.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://power-grid-lib.github.io/">PGLib-OPF</a></b> (🥉10 ·  ⭐ 380 · 💀) - Benchmark library for optimal power flow. IEEE test cases.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/power-grid-lib/pglib-uc">PGLib-UC</a></b> (🥉5 ·  ⭐ 110 · 💀) - Benchmark library for unit commitment problems. Standard test.. <code>❗Unlicensed</code>
</details>
<br>

## Computer Vision for Infrastructure

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Image/video AI for power line inspection, vegetation management, equipment monitoring._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/Grid2op/grid2viz">Grid2Viz</a></b> (🥇15 ·  ⭐ 55 · 💀) - Visualization tool for Grid2Op power grid environments. Agent.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/andreluizbvs/InsPLAD">InsPLAD</a></b> (🥉5 ·  ⭐ 130 · 💤) - Power Line Asset Inspection Dataset. 10,607 UAV.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://pytorch.org/favicon.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Energy Market & Price Forecasting

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_ML models for electricity price prediction, market simulation, and trading strategies._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/Carterbouley/ElectricityPricePrediction">Electricity Price Prediction</a></b> (🥇7 ·  ⭐ 73 · 💀) - Neural networks for day-ahead electricity price.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ps-wiki/best-of-ps/main/config/icons/jupyter.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://www2.econ.iastate.edu/tesfatsi/AMESMarketHome.htm">AMES Market</a></b> (🥉6 ·  ⭐ 30) - Agent-based wholesale power market test bed. Iowa State.. <code>❗Unlicensed</code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>
</details>

---

## Contribution

Contributions are encouraged and appreciated! If you know of an open-source AI/ML project relevant to power and energy systems that isn't listed here, please:

- **Add a project**: Edit the [projects.yaml](https://github.com/martymcenroe/best-of-pes-ai/edit/main/projects.yaml) file and submit a pull request
- **Suggest a category**: [Open an issue](https://github.com/martymcenroe/best-of-pes-ai/issues/new) describing the proposed category
- **Report a problem**: [Open an issue](https://github.com/martymcenroe/best-of-pes-ai/issues/new) with details

See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

## Related Resources

- [best-of-ps](https://github.com/ps-wiki/best-of-ps) — Sister list covering general open-source power systems tools (simulation, optimization, interfaces)
- [IEEE PES](https://ieee-pes.org) — IEEE Power & Energy Society
- [best-of-generator](https://github.com/best-of-lists/best-of-generator) — The framework that powers this list

## License

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
