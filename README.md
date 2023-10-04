# 虎口逃脱 Run From The Beast

## 首先
非常感谢您购买了这个 Minecraft 服务端。我在制作这个端的时候还只是一个中学生，所以可能并没有非常多的时间来维护这个端，所以如果您有任何问题，可以提出，我如果有时间回复您的问题。

## 配置
请查阅各个服务端文件夹下的`README.md`文件。

本端已经将部分涉及宣传的内容进行了统一化，如有需要请对照下表进行文本替换操作。
| 种类 | 端内使用的名称 |
| --- | --- |
| 服务器的名称 | `虎口逃脱` |
| 服务器的地址 | `www.servername.com` |

需要修改的文件有：
- `server.properties`
- `plugins/GuardianRFTB/items.yml`
- `plugins/GuardianRFTB/kits.yml`
- `plugins/GuardianRFTB/menus.yml`
- `plugins/GuardianRFTB/scoreboards.yml`
- `plugins/HolographicDisplays/database.yml`
- `plugins/TAB/config.yml`
- `plugins/TitleManager/config.yml`

## mcEULA
为保障您的使用体验，本端已经默认允许并且遵守了[Minecraft 最终用户许可协议](https://www.minecraft.net/zh-hans/eula)。
> 即将`eula.txt`文件中将`eula=false`改为`eula=true`。

出于对 Mojang Studios 的尊重和对 网易游戏涉外法务维权中心 的重视，我希望各位在实际使用过程中也可以遵守[该 EULA](https://www.minecraft.net/zh-hans/eula)。

## 服务条款
### 权限

- 托管/使用
> 您可以将该服务端上传到安全可靠的服务器。

- 商业用途
> 您可以通过使用该服务端来赚钱。

- 修改
> 如果需要，你可以对你拥有的该服务端的副本进行更改。

### 限制

- 转售/倒卖
> 您不得转售该服务端，并获取利益。

- 再许可
> 您不得再许可该服务端给其他人。

- 退款
> 除非该服务端无法按描述工作并且作者在联系时未能提供修复，否则不予退款。

- 再分配
> 您不得让无访问权限的任何人访问该服务端以从事需要该服务端的项目，如果在您的项目之外共享该服务端，您将承担责任。
---
## 相关链接
- [作者B站](https://space.bilibili.com/32539465)
- [交流群](https://jq.qq.com/?k=Hh0K6s7S)

## 常见问题
### 如何设置新地图

1. `/mv create NameMode normal -g VoidGen` - 创建地图所在的世界
2. `/mv tp NameMode` - 传送到你刚刚创建的世界
3. `/mv modify set monsters false` - 消除世界中的怪物
4. 加载一个结构或者建造你自己的地图
5. `/rftb admin create NameMode` - 在插件配置中创建竞技场
6. `/rftb admin setName NameMode Name` - 输入用户可见的名称
7. `/rftb admin setWaiting NameMode` - 在你的地图等待大厅中定位并输入此命令
8. `/rftb admin setSelectedBeast NameMode` - 在选择野兽时它出现的位置上定位并输入此命令
9. `/rftb admin setBeastSpawn NameMode` - 在游戏开始时野兽出现的位置上定位并输入此命令
10. `/rftb admin setRunnerSpawn NameMode` - 在游戏开始时奔跑者出现的位置上定位并输入此命令
11. `/rftb admin setMin NameMode 2` - 自定义参数后输入此命令
12. `/rftb admin setMax NameMode 12` - 自定义参数后输入此命令
13. `/rftb admin setMode NameMode Mode` - 自定义你想在地图上使用的游戏模式（游戏模式：`/rftb admin modes`）
14. `/rftb admin addChest NameMode armor` - 自定义参数后输入此命令
15. `/rftb admin addChest NameMode attack` - 自定义参数后输入此命令
16. `/rftb admin addChestLocation NameMode armor` - 在地图末尾的箱子上看一眼并输入此命令
17. `/rftb admin addChestLocation NameMode attack` - 在地图末尾的箱子上看一眼并输入此命令
18. `/rftb admin enable NameMode` - 启用你刚刚配置的地图
19. 完成！无需重启。

### 欢迎图片自定义

可以通过模板 PSD 文件自定义。

文件位于`plugins/BannerBoard/images/模板.psd`。

修改完后可以在`plugins/BannerBoard/config.yml`中设置。

### 设置禁用指令

在`plugins/BlockedCmds/config.yml`中设置，一行一个。

### 设置全息文字

在`plugins/HolographicDisplays/database.yml`中设置。