# 残杀千足虫 · 动态补丁

《杀戮尖塔 2》残杀千足虫娘化皮肤的免费动画扩展。为头、中、尾三段添加待机、攻击、受击、瘫倒和锁链复苏，包含同回合接力复苏及图鉴预览。

**[下载 v0.4.14 动态补丁 ZIP](https://github.com/MarchsYu/STS2-DecimillipedeMotion/releases/download/v0.4.14/DecimillipedeMotion-0.4.14.zip)** · [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3843247845)

## 安装

可以在 Steam 创意工坊订阅原皮肤和本补丁，也可以手动安装。已有工坊版补丁时，无需再装一份 ZIP。

1. 安装或启用 Kiteseven 的原版娘化皮肤，要求版本为 0.0.1 或更新。可在 [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3842855066) 订阅，或从 [原作者的 GitHub 发布页](https://github.com/kiteseven/decimillipede-feminization/releases/latest) 手动下载。
2. 下载 v0.4.14 的 ZIP 附件。退出游戏后，在 Steam 库中右键《杀戮尖塔 2》，选择「管理 → 浏览本地文件」。
3. 解压 ZIP，把里面的 `DecimillipedeMotion` 文件夹放入游戏的 `mods` 目录。手动安装的旧版可以覆盖同目录中的 DLL 和 JSON。
4. 启动游戏，在「模组」中启用原皮肤和本补丁，按游戏提示重启。

手动安装后，补丁文件位于 `mods/DecimillipedeMotion/DecimillipedeMotion.dll` 和 `mods/DecimillipedeMotion/DecimillipedeMotion.json`。如果补丁提示缺少前置，请手动安装或启用原皮肤后重启。卸载手动版时，退出游戏后移走 `mods/DecimillipedeMotion`。

## v0.4.14 更新

- 修复图鉴里倒地和复苏时的锁链抖动，拉紧和放松的过渡更平滑。
- 相比 GitHub 上的 v0.4.8，攻击收招与待机衔接更连贯，连续复苏中各段的接力动作更清楚。
- 新增完整、轻损和破损三档战斗衣装差分，均为 SFW。衣装会随受击和倒地变化，复苏后保留本场的破损。

### 战斗衣装差分

差分默认开启。关闭后，三段都保持完整衣装，待机和战斗动作照常播放。战斗中重新开启会恢复本场已经出现的污损或破损。设置会在重启后保留。

- 使用 [模组配置 ModConfig](https://steamcommunity.com/sharedfiles/filedetails/?id=3749062616) 时，按 F10，在「残杀千足虫 · 动态皮肤」中切换。
- 使用 [Better Mod Menu](https://steamcommunity.com/sharedfiles/filedetails/?id=3748029698) 和 [RitsuLib](https://steamcommunity.com/sharedfiles/filedetails/?id=3747602295) 时，在模组列表中选中本补丁，点击「配置」。

两个入口共用同一个开关，均为可选。

## 素材来源

原皮肤和立绘由 **Kiteseven（kiteseven77）** 制作。动态补丁在原立绘基础上制作了分层动画图集和骨骼动画。

- [原作者的 B 站视频](https://www.bilibili.com/video/BV1QiLY6DEEs/)
- [原皮肤 GitHub 仓库](https://github.com/kiteseven/decimillipede-feminization)
- [上游 Apache-2.0 许可证](LICENSE-Upstream-Apache-2.0.txt)
