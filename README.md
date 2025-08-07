## 高擎机电学习笔记(指令篇)

#### 查看进程
```
ps aux | grep ros
```
#### 终止进程
```
kill -9 进程端口号
```
#### 解压缩指令：
```
tar -xzvf 文件名.tar.gz
```
#### 删除虚拟环境：
```
conda remove --name zixaing --all env
```
#### 关闭虚拟环境：
```
conda deactivate.
```
#### 把issa gym载入虚拟环境记着要:
```
pip install -e.
```
#### 列出所有conda虚拟环境：
```
conda env list
```
#### 新建工作空间：
```
mkdir -p catkin_ws/src
```
```
cd catkin_ws/src
```
```
catkin_init_workspace
```
```
cd .. 	
```
```
catkin_make
```
```
catkin_make install
```
#### 将下载下来的deb安装指令：
```
sudo dpkg -i xxxx.deb
```
#### 删除软件指令：
```
sudo apt remove 软件包名
```
#### 如果依赖有问题，运行：
```
sudo apt --fix-broken install
```
#### 创建虚拟环境：
```
conda create -n zixiang python=3.8
```
#### 清除参与输入：
```
conda clean --all
```
#### 克隆env环境：
```
conda create --name env_new --clone env_isaaclab --copy
```
#### 删除软件包：
```
sudo rm -rf sim2real_master
```
#### 观测训练收敛情况：
```
tensorboard --logdir=logs/hi_mimic/ --port=6006
```
#### 截图快捷键：

###### Ctrl + Shift + PrtSc 截取自定义区域，复制到剪贴板（不保存）

#### 检查 TensorBoard 是否已安装:
```
pip list | grep tensorboard
```
#### 压缩命令：
```
tar -czvf 压缩包名称.tar.gz 文件夹名称/
```
#### 解压缩指令：
```
tar -zxvf 压缩包名称.tar.gz 文件夹名称/
```
#### 解压缩指令：
```
tar -Jxvf 压缩包名称.tar.gz 文件夹名称/
```
#### 局域网传输指令：
```
scp 压缩包名称.tae.gz 用户名@1992.168.xxx.xxx:~/
```


