# NEST Intro

NEST (Neural Simulaiton Tool) introduction. Spiking Neural Netowrk SNN simulation.

## Goals & Objective

* Neuromorphic Computing

## Status
TODO
* <todo: consider, go through the documentation and implement some of the code examples. >
* <todo: consider, likely PyNN over NEST. >
* <todo: consider also NEST Cpp api. Good excuse for some fun with Cpp code! >
* <todo: consider, NEST install into dual boot Ubuntu Linux. decision 16 December 2024. completed tbd? >

DONE
* <done: downloaded NEST source code, as zip file, don't know if it will compile on MS Windows, >
* <done: there appear to be issues with Ubuntu WSL and Eclipse win install compatability, are there work arounds? >
* <done: not contacted NEST team, not enquired re conda, not enquired re compilation on MS Win, askubuntu and other sources indicate no Win compile options, so other points moot. >
* <done: rejected as likely too slow due to proformance issues, Ubuntu WSL, linux OS simulation env for NEST install, keep under review if dual boot not feasable >
* <done: rejected due to performance and other issues, WSL2 comparision to WSL, WSL2 a fully fledged light weight virtual machine? WSL layer over Win linux compatible kernel interface? >
* <done: rejected conda as a solution for NEST install due to no MS binaries, install conda, use conda as NEST python env, try conda install, may fail due to no MS Win binary? worth a try?>
* <done: rejectd no NEST support, can nest be compiled for windows? requires C++ 17 compiler. NEST GitHub issues re compliation for Win suggest not possible with any ease, would require large investment in time. >

## Notes
Only supported options for MS WIN appear to be ; firstly WSL Linux environment simualtor and/or Docker image, secondly dual boot Linux.
* Option 1, WSL(1&2); NEST in WSL Ubuntu, or NEST in Docker in WSL Ubuntu, is NEST in Docker in Win possible? This option has ease of use as main advantage. Disadvantage use of Eclipse IDE is difficult or impossible? Other similar MS vendor lockin unknown constraints. Negative performance issues. 
* Option 2, dual boot system Ubuntu. Install NEST into Ubuntu linux partition. This is currently looking like the better option due to; performance, ability to use Eclipse IDE, . Steeper learning curve. More risk due to; disk resizing and partitioning, two OS's network security and other risks. See Dual boot [GH](https://github.com/YorkEarwaker/Operating-System/wiki/Dual-boot),

Have downloaded NEST source code. But don't know if it will compile on MS Windows. There are no other good download options for native execution on Windows environments. No Windows binary. Shame. So trying to set up a separate standalone NEST only development environment will be a big time effort. So will likely choose another simulator for intro to PyNN. For ease of use Python pip install option. Which probably means the Neuron simulator. But it will be a start to coding in PyNN. Will try to install NEST into the PyNN dev environment at a later date. What a shame.

NEST JupiterLab option?

IDE. VS Code extension option. Eclipse plugin option?

try conda python env? Probably not possible due to lack of MS Win binary.
* conda install -c conda-forge nest
* conda install -c conda-forge pynest

## Libraries

Neural Simulation Technology - modeling, execution
* NEST v3.7, code [GH](https://github.com/nest/nest-simulator/releases/tag/v3.7), 
* NEST docs [WS](https://nest-simulator.readthedocs.io/en/stable/),
* NEST MS Win [WS](https://nest-simulator.readthedocs.io/en/stable/installation/user.html#windows-install), no good install options for windows users
* NEST compile instructions [WS](https://nest-simulator.readthedocs.io/en/stable/installation/noenv_install.html), cmake options [WS](https://nest-simulator.readthedocs.io/en/stable/installation/cmake_options.html#cmake-options), requires C++ 17 compiler.
* NEST Mailing list, [WS](https://www.nest-simulator.org/mailinglist/postorius/lists/users.nest-simulator.org/), register, log in,

NEST Modelling Language
* NESTML [WS](https://nestml.readthedocs.io/en/latest/), modelling language, C++, Python

NEST GPU
* NESTGPU [WS](https://nest-gpu.readthedocs.io/en/latest/), MPI, snn,
* NESTGPU [GH](https://github.com/nest/nest-gpu), was NeuroGPU discontinued as legacy project, integration into NESTGPU, 

Nest Desktop - GUI, Web user interface, over NEST simulator, requires seperate NEST install?
* Nest Desktop, code [GH](https://github.com/nest-desktop/nest-desktop/),
* Nest Desktop, docs [WS](https://nest-desktop.readthedocs.io/en/latest/),
* Nest Desktop, PyPi [WS](https://pypi.org/project/nest-desktop/),
* Nest Desktop, Zenodo [WS](https://zenodo.org/records/6320318), 
* Nest Desktop, Ebrains [WS](https://www.ebrains.eu/tools/nest-desktop), requires Ebrains account, free

Library ecosystem
* PyNN, Python, simulation
* Elephant, Python, ELEctroPHysiology ANalysis Toolkit, 

## References
Terms
* Adjacency list, [WP](https://en.wikipedia.org/wiki/Adjacency_list), graph theory
* Adjacency matrix, [WP](https://en.wikipedia.org/wiki/Adjacency_matrix), graph theory
* Locality of reference, memory space, memory time, 
* NEST, [WP](https://en.wikipedia.org/wiki/NEST_(software)),
* PyNEST Python API for NEST,

News Papers
* Is there any advantage to WSL over Cygwin? [WS](https://www.reddit.com/r/linux/comments/10x8mcw/is_there_any_advantage_to_wsl_over_cygwin/?rdt=48034), 2022, Reddit,
* Eclipse-WSL, [WS](https://learn.microsoft.com/en-us/answers/questions/1181705/eclipse-wsl), 17 February 2023, learn MS,

NEST GitHub, issues WSL
* NEST on Windows subsystem for Linux (WSL) #1520, [GH]([https://github.com/nest/nest-simulator/issues/1520), 8 June 2020, 
* Installing nest on Windows or WSL #2185, [GH](https://github.com/nest/nest-simulator/issues/2185), 11 Oct 2021,
* Testsuite error in windows subsystem for linux (ubuntu) #1048, [GH](https://github.com/nest/nest-simulator/issues/1048), 15 October 2018,
* AST-based root module importmap, static typehints, and CI check #2598, [GH](https://github.com/nest/nest-simulator/issues/2598), 30 Jan 2023,
* nest.NodeCollection([0]) aborts the process #2636, [GH](https://github.com/nest/nest-simulator/issues/2636), 14 March 2023,
* Unsorted node collection indices lead to unclear error message #2639, [GH](https://github.com/nest/nest-simulator/issues/2639), 14 March 2023,

NEST GitHub, issues windows
* nest-simulator on windows. #889, [GH](https://github.com/nest/nest-simulator/issues/889), 3 February 2028
* More to review and list, ...
