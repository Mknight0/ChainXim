 # 简介(Intro)
ChainXim是一款由XinLab开发的区块链仿真器,用于对不同网络、不同共识协议下的区块链进行仿真验证,可以通过设计网络攻击者辅助评估区块链的安全性能。目前仿真器还处于内部测试阶段。
(ChainXim is a blockchain simulator developed by XinLab, which is used to simulate and verify blockchains under different networks and different consensus protocols, and can be designed to assist network attackers in evaluating the security performance of the blockchain. The emulator is currently in the internal testing phase.)

# 安装(Deployment) 
 **Dependency**
 - python >= 3.7
 - graphviz
 - scipy
 - matplotlib > 3.5.1
 - networkx > 2.8.7
 - pandas

# 简单运行(Operation)
在.ini文件中调整仿真参数及有关配置后(After adjusting the simulation parameters and configurations in the .ini file),
```shell
cd <project_directory>
python main.py
```
将会在Results文件夹生成仿真区块数据，包括每个矿工的区块链记录、区块链可视化矢量图、区块链攻击者日志、路由历史、网络矢量图、区块传播示意图。
(Simulation data will be generated in the Results folder, including each miner's blockchain record, blockchain visualization vector diagram, blockchain attacker log, routing history, network vector diagram, block propagation diagram.)

# 文件结构(Architecture)
- main.py: 仿真器的主程序(The main program of the simulator)
- Environment.py: 环境类与相关函数(Environment class and related functions)
- Miner.py: 矿工类与相关函数(Miner class and related functions)
- chain.py: 包括块头、区块、区块链的类与相关函数(Includes block classes, blockchain classes, and related functions)
- consensus.py: 抽象共识类、PoW类与相关函数(Abstract consensus classes, Pow classes, and related functions)
- BitcoinBackboneProtocol.py: 核心共识函数(Core consensus function)
- Network.py: 网络类，包括网络拓扑与传播相关的函数(Network class, including network topology and propagation-related functions)
- Attack.py: 攻击者类与相关函数(Attacker class and associated functions)
- functions.py: 包含计算哈希（SHA256）在内的一些函数(Some functions that include calculating hashes(SHA256))
- external.py: 一些外部函数(Some external functions)

# 下载(Download)
请访问如下网址并填写您的相关信息，我们承诺对收集到的所有结果保密。在您填写完问卷之后，我们会将完整的仿真器文件通过您填写的邮箱发送给您。
(Please visit the website below and fill in your relevant information, we promise to keep all the results collected confidential. After you have completed the questionnaire, we will send you the complete simulator program via the email address you have filled in.)
