# Create-Airwaves-zh_cn
Create: Airwaves 完整简体中文汉化，支持 MC 1.21.1 / NeoForge。覆盖语言文件、29 章手册、全部 Ponder、GUI 与护目镜提示；内置中文资源的完整 JAR。安装前请移除原模组，欢迎 Star


# Create: Airwaves 简体中文汉化

> 让每一次调频、每一句广播，都变成熟悉的中文。

本项目为 NeoForge 1.21.1 模组 **Create: Airwaves** 的完整简体中文汉化，基于原模组 `0.1.1` 制作。

![Ponder 中文场景](https://raw.githubusercontent.com/no-have-name/Create-Airwaves-zh_cn/main/runtime_ponder_zh_cn.png)
![创造模式物品栏](https://raw.githubusercontent.com/no-have-name/Create-Airwaves-zh_cn/main/runtime_inventory_zh_cn.png)

## 汉化范围

不是只翻译物品名称，而是对玩家可见文本做了完整处理：

- 428 条语言键全量覆盖
- 29 章《无线电波野外手册》
- 全部 Ponder 场景标题、步骤说明与动态文本
- 调谐台、磁带播放器、电路工作台、语音菜单等 GUI
- 工程师护目镜、快捷栏、聊天提示与物品工具提示
- JEI 电路板页面
- 原模组中直接写死在 Java 类里的界面文本
- Create: Power Grid / Create: Electro Energetics 兼容提示

## 为什么发布的是完整 JAR？

原模组有大量文本直接写在代码中，单独的语言资源包无法覆盖这些内容。

因此本汉化以**完整汉化 JAR** 的形式发布，已经内置：

- `assets/airwaves/lang/zh_cn.json`
- `assets/airwaves/manual/zh_cn.json`
- 必要的界面文本本地化

没有删除配方、没有禁用功能、没有改动注册名与网络协议。除文本外，模组逻辑保持原样。

## 安装方法

1. 备份原文件：`mods/airwaves-1.21.1-0.1.1.jar`
2. 从 `mods` 中移除原 Airwaves JAR
3. 放入本仓库 Release 中的：
   `airwaves-1.21.1-0.1.1-zh_cn.jar`
4. 启动游戏，将语言设置为**简体中文**
5. 如果之前使用过其他 Airwaves 汉化资源包，请先禁用，避免文本重复覆盖

> `mods` 中只能保留一个 Airwaves JAR。文件名可以改，但不要同时放原版和汉化版。

## 实测环境

| 项目 | 版本 |
|---|---|
| Minecraft | 1.21.1 |
| NeoForge | 21.1.262 |
| Create | 6.0.10 |
| Create: Aeronautics | 1.3.2 |
| Sable | 2.0.6 |
| Airwaves | 0.1.1 |

已在上述环境实机验证：物品栏、工具提示、Ponder 场景均可正常显示中文。

## 联机说明

单人游戏只需客户端安装。

联机时建议客户端与服务端使用同一个汉化 JAR。部分护目镜状态文本由服务端同步，双端一致才能保证所有提示都是中文。

## 常见问题

**Q：为什么模组列表里显示版本 0.1.0？**  
A：原模组元数据写的是 `0.1.0`，文件名为 `0.1.1`，这是原作者留下的版本显示差异，不影响使用。

**Q：可以和其他汉化资源包一起用吗？**  
A：不建议。本 JAR 已包含完整中文资源，再叠加旧资源包可能造成文本覆盖冲突。

**Q：安装后游戏报错怎么办？**  
A：请先确认 NeoForge、Create、Aeronautics、Sable 版本匹配，并确保 `mods` 中没有重复的 Airwaves JAR。汉化只修改文本，不改变玩法逻辑；原模组本身的问题仍需以原模组日志为准。

## 文件校验

```text
SHA-256:
5F6FF530BC721E810C6A838C8BD00E2AFE923DC3F85B95B33FA311A833B6F382
```

## 致谢

- 原模组作者与 Create 团队
- Create 中文社区长期积累的术语与译名
- 所有愿意尝试并反馈问题的玩家

如果这个汉化帮你更快搭起第一座电台，欢迎点一个 **Star**。  
Star 不会让你多花一分钱，但能让更多玩 Create 的朋友找到它。
