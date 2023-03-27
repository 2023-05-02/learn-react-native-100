# 3-6 配置环境变量

|本期版本|上期版本
|:---:|:---:
`Mon Mar 27 14:41:39 CST 2023` |


```bash
set -Ux ANDROID_HOME ~/Library/Android/sdk
fish_add_path $ANDROID_HOME/emulator
fish_add_path $ANDROID_HOME/platform-tools
```

