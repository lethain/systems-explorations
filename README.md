# systems-explorations

This is a collection of system models developed
using the [systems](https://github.com/lethain/systems) library,
and explorable via [Binder](https://mybinder.org/) or locally runnable.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lethain/systems-explorations/master)

## Explorations

The current explorations are:

* **Hiring** ([github](./hiring.ipynb)) - model of a hiring funnel
* **Reliability** ([github](./reliability.ipynb)) - model of reliability

## Installation

Installation instructions are:

    git clone https://github.com/lethain/systems-explorations.git
    cd systems-explorations
    python3 -m venv ./env
    source ./env/bin/activate
    pip install -r requirements.txt

Using the graphviz extensions will require also install `dot` for your
operating system.

Then you run Jupyter via:

    jupyter notebook

Then click into the notebooks and get started.