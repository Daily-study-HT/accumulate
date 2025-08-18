###  sim2real代码中yaml文件的关节urdf_dof_pos_offset说明:机器人实际姿态与 URDF 模型显示的姿态不一致&&仿真与实际机器人行为存在系统性位置偏移
```
urdf_dof_pos_offset: [0.0, 0.0, 0.0, 0.0 ,0.0, 0.0, #左腿
                      0.0, 0.0, 0.0, 0.0, 0.0, 0.0, #右腿
                      0.0, 0.0, 0.0, 0.64, 0.0,     #左手                    
                      0.0, 0.0, 0.0, 0.64, 0.0,     #右手                     
                      0.0                           #腰 ]
```


### 部署代码封装指令
```
```
catkin clean -y
```
```
catkin build -DCMAKE_CXX_FLAGS="-DRELEASE"
```
```
catkin config --install
```
```
