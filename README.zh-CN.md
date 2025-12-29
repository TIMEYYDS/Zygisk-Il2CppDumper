# Zygisk-Il2CppDumper
Zygisk版Il2CppDumper，在游戏运行时dump il2cpp数据，可以绕过保护，加密以及混淆。

## 如何食用
1. 安装[Magisk](https://github.com/topjohnwu/Magisk) v24以上版本并开启Zygisk 
2. 在Magisk里安装模块
3. 设置包名到 property `adb shell su -c setprop persist.il2cpp_dumper.pkg <GamePackageName>`
4. 启动游戏，会在`/data/data/GamePackageName/files/`目录下生成`dump.cs`