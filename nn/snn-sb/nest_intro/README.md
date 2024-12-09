# NEST Intro

NEST (Neural Simulaiton Tool) introduction. Spiking Neural Netowrk SNN simulation.

### Status
Have downloaded NEST source code. But don't know if it will compile on MS Windows. There are no other good download options for native execution on Windows environments. No Windows binary. Shame. So trying to set up a separate standalone NEST only development environment will be a big time effort. So will likely choose another simulator for intro to PyNN. For ease of use Python pip install option. Which probably means the Neuron simulator. But it will be a start to coding in PyNN. Will try to install NEST into the PyNN dev environment at a later date. What a shame.

Only supported options for MS WIN appear to be; Docker image, or Linux environment simualtor.

NEST JupiterLab option?

IDE. VS Code extension option. Eclipse plugin option?

try conda python env? Probably not possible due to lack of MS Win binary.
* conda install -c conda-forge nest
* conda install -c conda-forge pynest

TODO
* <todo: consider, Ubuntu WSL, linux OS simulation env for NEST install, >
* <todo: consider, WSL2 comparision to WSL, WSL2 a fully fledged light weight virtual machine? WSL layer over Win linux compatible kernel interface? >
* <todo: contact NEST team, enquire re conda, enquire re compilation on MS Win, >
* <todo: install conda, use conda as NEST python env, try conda install, may fail due to no MS Win binary? worth a try?>
* <todo: go through the documentation and implement some of the code examples. >
* <todo: likely PyNN over NEST. >
* <todo: consider also NEST Cpp api. Good excuse for some fun with Cpp code! >

DONE
* <done: downloaded NEST source code, as zip file, don't know if it will compile on MS Windows, >

# Libraries

Simulator - modeling, execution
* NEST v3.7, code [GH](https://github.com/nest/nest-simulator/releases/tag/v3.7), 
* NEST docs [WS](https://nest-simulator.readthedocs.io/en/stable/),
* NEST MS Win [WS](https://nest-simulator.readthedocs.io/en/stable/installation/user.html#windows-install), no good install options for windows users
* NEST compile instructions [WS](https://nest-simulator.readthedocs.io/en/stable/installation/noenv_install.html), cmake options [WS](https://nest-simulator.readthedocs.io/en/stable/installation/cmake_options.html#cmake-options), can nest be compiled for windows? requires C++ 17 compiler.

Desktop - GUI, Web user interface, over NEST simulator, requires seperate NEST install?
* Nest Desktop, code [GH](https://github.com/nest-desktop/nest-desktop/),
* Nest Desktop, docs [WS](https://nest-desktop.readthedocs.io/en/latest/),
* Nest Desktop, PyPi [WS](https://pypi.org/project/nest-desktop/),
* Nest Desktop, Zenodo [WS](https://zenodo.org/records/6320318), 
* Nest Desktop, Ebrains [WS](https://www.ebrains.eu/tools/nest-desktop), requires Ebrains account, free

Linux simulator
* Ubuntu WSL, [WS](https://documentation.ubuntu.com/wsl/en/latest/), recomended by NEST, [WS](https://www.reddit.com/r/bashonubuntuonwindows/) subreddit WSL/WSL2,

## References
Terms
* Adjacency list, [WP](https://en.wikipedia.org/wiki/Adjacency_list), graph theory
* Adjacency matrix, [WP](https://en.wikipedia.org/wiki/Adjacency_matrix), graph theory
* Locality of reference, memory space, memory time, 
* NEST, [WP](https://en.wikipedia.org/wiki/NEST_(software)),
* PyNEST Python API for NEST,

News Papers
* Is there any advantage to WSL over Cygwin? [WS](https://www.reddit.com/r/linux/comments/10x8mcw/is_there_any_advantage_to_wsl_over_cygwin/?rdt=48034), Reddit, 
