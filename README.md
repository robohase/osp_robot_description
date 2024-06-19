# osp_robot_description

## how to build 

### 1. パッケージをインストール
```  bash
git clone https://github.com/robohase/osp_robot_description.git
```

### 2. 依存パッケージをインストール
``` bash
cd osp_robot_description
rosdep install -r -y -i --from-paths .
```

### 3. ビルド
``` bash
colcon build --symlink-install
source install/setup.bash
```


## 実行
``` bash
ros2 launch osp_robot_description display.launch.py
```
