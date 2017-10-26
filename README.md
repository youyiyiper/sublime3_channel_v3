# sublime3 channel_v3.json

## 解决sublime3 无法安装插件问题

### 原来package Control 默认设置的地址偶尔会挂
```
"channels": [
    "https://packagecontrol.io/channel_v3.json"
]
```

### 添加package Control 用户设置
```
"channels": [
    "your_domain_path/channel_v3.json"
]
```
