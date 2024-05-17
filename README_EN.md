 # Intro
ChainXim is a blockchain simulator developed by XinLab, which is used to simulate and verify blockchains under different networks and different consensus protocols, and can be designed to assist network attackers in evaluating the security performance of the blockchain. The simulator is currently in the beta version.

# Deployment 
 **Dependency**
 - python >= 3.7
 - graphviz
 - scipy
 - matplotlib > 3.5.1
 - networkx > 2.8.7
 - pandas

# Operation
After adjusting the simulation parameters and configurations in the .ini file,
```shell
cd <project_directory>
python main.py
```
Simulation data will be generated in the Results folder, including each miner's blockchain record, blockchain visualization vector diagram, blockchain attacker log, routing history, network vector diagram, block propagation diagram.

# Architecture
- main.py: The main program of the simulator
- Environment.py: Environment class and related functions
- Miner.py: Miner class and related functions
- chain.py: Includes block classes, blockchain classes, and related functions
- consensus.py: Abstract consensus classes, Pow classes, and related functions
- BitcoinBackboneProtocol.py: Core consensus function
- Network.py: Network class, including network topology and propagation-related functions
- Attack.py: Attacker class and associated functions
- functions.py: Some functions that include calculating hashes(SHA256)
- external.py: Some external functions

# Download
Please visit the website below and fill in your relevant information, we promise to keep all the results collected confidential. After you have completed the questionnaire, we will send you the complete simulator program via the email address you have filled in.

https://www.wjx.cn/vm/t689cqs.aspx
