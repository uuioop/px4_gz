# px4_gz

## 模型和世界文件配置

### 模型替换
将 `models/` 目录下的新模型文件替换或添加到 PX4-Autopilot 的对应目录：
```
PX4-Autopilot/Tools/simulation/gz/models/
```

### 世界文件替换  
将 `worlds/` 目录下的新世界文件替换或添加到 PX4-Autopilot 的对应目录：
```
PX4-Autopilot/Tools/simulation/gz/worlds/
```

### 文件说明
- **models/**: 包含无人机模型、相机模型、ArUco标记和门牌模型
- **worlds/**: 包含仿真世界配置文件