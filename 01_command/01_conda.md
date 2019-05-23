```
conda env list 或 conda info -e 查看当前存在哪些虚拟环境
conda update conda 检查更新当前conda3. conda update --all 更新本地已安装的包
conda create -n your_env_namepython=X.X（2.7、3.6等） anaconda 命令创建python版本为X.X、名字为your_env_name的虚拟环境。your_env_name文件可以在Anaconda安装目录envs文件下找到。
Windows: activate your_env_name(虚拟环境名称) 激活虚拟环境
conda install -n your_env_name [package] 安装package到your_env_name中
linux: source deactivate           Windows: deactivate     关闭虚拟环境
conda remove -n your_env_name(虚拟环境名称) --all 删除虚拟环境
conda remove --name your_env_name  package_name  删除环境中的某个包
```
