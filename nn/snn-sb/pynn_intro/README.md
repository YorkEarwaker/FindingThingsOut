# PyNN Intro

Gettiing to know pine

### Status

PyNN on Windows has not been tested.

Can't use NEST on MS Win straightaway will require real effort. See NEST Intro for details.

Neuron install not working first instance. 

Neuron JupiterLab option? 

IDE. VS Code extension option? Eclipse plugin option?

TODO
* <todo: download simulator, Arbor, Brain 2, NEST, or Neuron, . Must a sim be installed? likely yes. >
* <todo: read Neuron docs re MS Win install options, if any, >
* <todo: determine if any of the optional installs are necessary for simulator choice, >
* <todo: PyNN introductory code samples,  >

DONE
* <done: install pynn in local dev environment, 06/12/2024, >
* <done: evaluated install of NEST on MS Win no simple options, > 

### PyNN install 

<todo: how to format/comment md content so that it CR NL are recongnised, >

pip install PyNN
Collecting PyNN
  Downloading PyNN-0.12.3-py3-none-any.whl.metadata (5.5 kB)
Collecting numpy>=1.18.5 (from PyNN)
  Downloading numpy-2.1.3-cp312-cp312-win_amd64.whl.metadata (60 kB)
Collecting lazyarray>=0.5.2 (from PyNN)
  Downloading lazyarray-0.6.0-py3-none-any.whl.metadata (2.7 kB)
Collecting neo>=0.11.0 (from PyNN)
  Downloading neo-0.13.4-py3-none-any.whl.metadata (8.9 kB)
Collecting quantities>=0.12.1 (from PyNN)
  Downloading quantities-0.16.1-py3-none-any.whl.metadata (8.4 kB)
Collecting morphio (from PyNN)
  Downloading morphio-3.4.0-cp312-cp312-win_amd64.whl.metadata (3.7 kB)
Collecting packaging (from neo>=0.11.0->PyNN)
  Downloading packaging-24.2-py3-none-any.whl.metadata (3.2 kB)
Collecting numpy>=1.18.5 (from PyNN)
  Downloading numpy-1.26.4-cp312-cp312-win_amd64.whl.metadata (61 kB)
Collecting h5py<4,>=3 (from morphio->PyNN)
  Downloading h5py-3.12.1-cp312-cp312-win_amd64.whl.metadata (2.5 kB)
Downloading PyNN-0.12.3-py3-none-any.whl (344 kB)
Downloading lazyarray-0.6.0-py3-none-any.whl (9.1 kB)
Downloading neo-0.13.4-py3-none-any.whl (655 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 655.1/655.1 kB 1.8 MB/s eta 0:00:00
Downloading numpy-1.26.4-cp312-cp312-win_amd64.whl (15.5 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 15.5/15.5 MB 1.8 MB/s eta 0:00:00
Downloading quantities-0.16.1-py3-none-any.whl (102 kB)
Downloading morphio-3.4.0-cp312-cp312-win_amd64.whl (599 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 599.7/599.7 kB 2.4 MB/s eta 0:00:00
Downloading h5py-3.12.1-cp312-cp312-win_amd64.whl (3.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.0/3.0 MB 1.7 MB/s eta 0:00:00
Downloading packaging-24.2-py3-none-any.whl (65 kB)
Installing collected packages: packaging, numpy, quantities, lazyarray, h5py, neo, morphio, PyNN
Successfully installed PyNN-0.12.3 h5py-3.12.1 lazyarray-0.6.0 morphio-3.4.0 neo-0.13.4 numpy-1.26.4 packaging-24.2 quantities-0.16.1

### Neuron install

<todo: troubleshoot error, read the docs, >

pip install neuron
ERROR: Could not find a version that satisfies the requirement neuron (from versions: none)
ERROR: No matching distribution found for neuron

### Simulators
* Arbor, [WS](https://arbor-sim.org/), PyNN compatible
* Brain, [WS](https://briansimulator.org/), PyNN compatible
* NEST, [GH](https://github.com/nest/nest-simulator), PyPi <todo: find it>, institute [WS](https://nest-initiative.org/), simulator [WS](https://nest-simulator.org/), PyNN compatible, No MS Win binary download, 
* Neuron, PyPi [WS](https://pypi.org/project/NEURON/), [WS](https://www.neuron.yale.edu/neuron/), PyNN compatible

## References

PyNN links
* PyNN Docs [WS](https://neuralensemble.org/docs/PyNN/index.html)

PyNN lib dependencies default
* h5py
* lazyarray
* morphio, [GH](https://github.com/BlueBrain/MorphIO), Blue Brain project,
* neo
* numpy
* packaging
* quantities

Test
* 
