# Zygisk-Il2CppDumper
Il2CppDumper with Zygisk, dump il2cpp data at runtime, can bypass protection, encryption and obfuscation.

中文说明请戳[这里](README.zh-CN.md)

## How to use
1. Install [Magisk](https://github.com/topjohnwu/Magisk) v24 or later and enable Zygisk
2. Install module in Magisk
3. Set package name to property `adb shell su -c setprop persist.il2cpp_dumper.pkg <GamePackageName>`
4. Start the game, `dump.cs` will be generated in the `/data/data/GamePackageName/files/` directory