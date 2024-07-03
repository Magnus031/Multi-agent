# Multi-agent


> Here is my 2024_ZJU_summer_Term Multi-agent project repo.

**Please run the project with conda!** 

- Here is the example:

  - `conda create -n mylab python=3.8` TA suggests to build the conda experiment in python3.8.
  - `conda activate mylab` Here `mylab` is the  conda experiment I build.
  - `python3 ../experiment1/experiment1.py` 

## Environment 

### Exp01:

#### Goal:
1. 安装gym
2. 利用hill climbing 方法完成案例CartPole-v0环境的测试
3. 根据hill climbing解决CartPole方法完成Acrobot-v1

- `numpy` 1.24
- `gym` 0.21.0

### Exp02:

#### Goal:
1. 运行 gym 中的 Cliff Walking 环境
2. 基于 Cliff Walking 实现表格型 Q-learning 和 SARSA 算法
3. 测试 Q-learning 和 SARSA 算法的表现与区别

- `numpy` \>=1.21.0 but <=2.0.0
- `gym` 0.24.0
- `matplotlib` no version requirement
- `tqdm` no version requirement

### Exp03:
This experiment is to familiarize yourself with the use of PyTorch

#### Goal:

- 利用RNN的二元分类网络区分不同函数 
- 熟悉PyTorch
- `pip3 install pytorch -i https://pypi.tuna.tsinghua.edu.cn/simple` 使用清华源下载的更快！
