# mujoco_py

mujoco125

更改环境变量


```
#export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/zhifeishen/.mujoco/mujoco200/bin
export LD_LIBRARY_PATH=~/.mujoco/mjpro150/bin${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}
export MUJOCO_KEY_PATH=~/.mujoco${MUJOCO_KEY_PATH}
export MUJOCO_PY_MJKEY_PATH=~/.mujoco/mjkey.txt
export MUJOCO_PY_MUJOCO_PATH=~/.mujoco/mjpro150

export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/zhifeishen/.mujoco/mjpro150/bin
```

测试

```
./simulate ../model/humanoid.xml
```

安装mujoco_py

更换Cython版本
```
pip install Cython==3.0.0a10
```

安装mujoco_py
pip install mujoco_py==1.50.1.68

