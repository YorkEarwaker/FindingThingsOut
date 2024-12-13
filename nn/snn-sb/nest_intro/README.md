# NEST Intro

NEST (Neural Simulaiton Tool) introduction. Spiking Neural Netowrk SNN simulation.

### Status
Only supported options for MS WIN appear to be; Docker image, or WSL Linux environment simualtor. 
* Option 1, WSL(1&2); NEST in WSL Ubuntu, or NEST in Docker in WSL Ubuntu, is NEST in Docker in Win possible? This option has ease of use as main advantage. Disadvantage use of Eclipse IDE is difficult or impossible?
* Option 2, dual boot system Ubuntu. Install NEST into Ubuntu linux partition. This is currently looking like the better option due to; performance, ability to use Eclipse IDE, . Steeper learning curve. More risk due to; disk resizing and partitioning, two OS's network security and other risks.

TODO
* <todo: consider, dual boot Ubuntu linux, root partition ~30G more?, home partition ~1G more?, swap partition ~8G more?, >
* <todo: Brave VPN, dual boot Ubuntu linux, licensing, Ubuntu compatible? >
* <todo: consider, Ubuntu WSL, linux OS simulation env for NEST install, >
* <todo: determine, Ubuntu WSL and Eclipse win install compatability, >
* <todo: consider, WSL2 comparision to WSL, WSL2 a fully fledged light weight virtual machine? WSL layer over Win linux compatible kernel interface? >
* <todo: contact NEST team, enquire re conda, enquire re compilation on MS Win, >
* <todo: install conda, use conda as NEST python env, try conda install, may fail due to no MS Win binary? worth a try?>
* <todo: go through the documentation and implement some of the code examples. >
* <todo: likely PyNN over NEST. >
* <todo: consider also NEST Cpp api. Good excuse for some fun with Cpp code! >

DONE
* <done: downloaded NEST source code, as zip file, don't know if it will compile on MS Windows, >

### Notes
Have downloaded NEST source code. But don't know if it will compile on MS Windows. There are no other good download options for native execution on Windows environments. No Windows binary. Shame. So trying to set up a separate standalone NEST only development environment will be a big time effort. So will likely choose another simulator for intro to PyNN. For ease of use Python pip install option. Which probably means the Neuron simulator. But it will be a start to coding in PyNN. Will try to install NEST into the PyNN dev environment at a later date. What a shame.

NEST JupiterLab option?

IDE. VS Code extension option. Eclipse plugin option?

try conda python env? Probably not possible due to lack of MS Win binary.
* conda install -c conda-forge nest
* conda install -c conda-forge pynest

### Libraries

Simulator - modeling, execution
* NEST v3.7, code [GH](https://github.com/nest/nest-simulator/releases/tag/v3.7), 
* NEST docs [WS](https://nest-simulator.readthedocs.io/en/stable/),
* NEST MS Win [WS](https://nest-simulator.readthedocs.io/en/stable/installation/user.html#windows-install), no good install options for windows users
* NEST compile instructions [WS](https://nest-simulator.readthedocs.io/en/stable/installation/noenv_install.html), cmake options [WS](https://nest-simulator.readthedocs.io/en/stable/installation/cmake_options.html#cmake-options), can nest be compiled for windows? requires C++ 17 compiler.
* NEST Mailing list, [WS](https://www.nest-simulator.org/mailinglist/postorius/lists/users.nest-simulator.org/), register, log in, 

Nest Desktop - GUI, Web user interface, over NEST simulator, requires seperate NEST install?
* Nest Desktop, code [GH](https://github.com/nest-desktop/nest-desktop/),
* Nest Desktop, docs [WS](https://nest-desktop.readthedocs.io/en/latest/),
* Nest Desktop, PyPi [WS](https://pypi.org/project/nest-desktop/),
* Nest Desktop, Zenodo [WS](https://zenodo.org/records/6320318), 
* Nest Desktop, Ebrains [WS](https://www.ebrains.eu/tools/nest-desktop), requires Ebrains account, free

<todo: consider moving below to another page/article/readme  . Not NEST specific >

WSL Windows Subsystem for Linux 
* Ubuntu WSL, docs [WS](https://documentation.ubuntu.com/wsl/en/latest/), recomended by NEST,
* Ubuntu WSL/WSL2 subreddit, [WS](https://www.reddit.com/r/bashonubuntuonwindows/)
* WSL Basic Commands, docs [WS](https://learn.microsoft.com/en-us/windows/wsl/basic-commands), Microsoft,

Ubuntu, linux, dual boot
* Ubuntu desktop, help [WS](https://help.ubuntu.com/), Official Ubuntu Documentation, developed and maintained by the Ubuntu Documentation Project
* Ubuntu docs, Canonical, [WS](https://docs.ubuntu.com/), Ubuntu documentation. The docs directory for all Ubuntu operating systems and products.
* Ubuntu wiki, [WS](https://wiki.ubuntu.com), 
* 

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

<todo: consider moving below to another page/article/readme . Not NEST specific >

WSL Windows Subsystem for Linux 
* Can Windows 10 have WSL1 & WSL2? [WS](https://superuser.com/questions/1697133/can-windows-10-have-wsl1-wsl2), StackExchange, SuperUser,
* Do I need to reinstall Ubuntu after installing WSL 2?, [WS](https://superuser.com/questions/1582347/do-i-need-to-reinstall-ubuntu-after-installing-wsl-2), StackExchange, SuperUser,
* Does Windows Subsystem for Linux consume resources (CPU/memory/HD) when I don't use it?, [WS](https://superuser.com/questions/1298844/does-windows-subsystem-for-linux-consume-resources-cpu-memory-hd-when-i-dont), 27 February 2018, Stackexchange, Superuser, 

Dual boot, benchmarking, WSL & Ubuntu linux dual boot
* Running a simulation on pure Ubuntu vs on Ubuntu in Windows (WSL), [WS](https://askubuntu.com/questions/1035568/running-a-simulation-on-pure-ubuntu-vs-on-ubuntu-in-windows-wsl), 13 May 2018, Stackexchange, askubuntu,
* Windows 10 WSL vs. Linux Performance For Early 2018, [WS](https://www.phoronix.com/review/wsl-february-2018), 22 February 2018, Michael Larabel, Operating Systems, phoronix
* Dual booting Windows and Ubuntu: is it even worth it with WSL?, [WS](https://dev.to/proman4713/dual-booting-windows-and-ubuntu-is-it-even-worth-it-with-wsl-576o), 30 Aug 2044, short answer yes! #linux, #ubuntu, #bash, #archlinux, 

Dual boot, partitioning, installing, 
* What Is the Recommended Size for Boot Partition, [WS](https://www.baeldung.com/cs/boot-partition-ideal-size), 6 July 2024, Baeldung,
* Can I have both Windows dynamic disk partition and some other non-Windows partition on the same disk?, [WS](), 31 August 2012, Stackexchange, Superuser 
* <todo: Windows 10 Dynamic Partitioning, check for issues re partitioning for Ubuntu standalone, >

Dual boot, - networking, security, vpn, firewall
* Connect to a VPN, [WS](https://help.ubuntu.com/stable/ubuntu-help/net-vpn-connect.html.en), Networking, Ubuntu,
* Uncomplicated Firewall ufw, [WS](https://wiki.ubuntu.com/UncomplicatedFirewall), wiki, Ubuntu
* UFW & VPN : How to allow reconnection, [WS](https://askubuntu.com/questions/627622/ufw-vpn-how-to-allow-reconnection), 24 May 2015, askubuntu, Stackexchange,
* 
