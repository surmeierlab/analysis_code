# Neurphys

Neurphys (pronounced "nervous") is an IO and analysis package built to streamline and standardize the data handling, analysis, and visualization of electrophysiology and calcium imaging data for the members of the [Surmeier lab](http://physio.northwestern.edu/).

## Dependencies

- [neo](https://pythonhosted.org/neo/)


## Installation

Download [Anaconda](https://www.continuum.io/downloads) which will come with
most required libraries. Then clone or download the repository using `git`.

```bash
git clone https://github.com/surmeierlab/neurphys
```

You can to download more dependencies. We provide `requirements.txt` that you can use
`pip` to install the rest.


```bash
pip install -r requirements.txt
```

For now, to add the module into python environment, you have to add path to `.bash_profile` or
`.bashrc` in order to import and use `neurphys` library.

```python
export PYTHONPATH=$PYTHONPATH:/PATH/TO/neurphys
```


## Usage

```python
import neurphys as nu
```

Check out the [tutorials page](https://github.com/surmeierlab/tutorials) for jupyter notebooks showing specific use cases.
