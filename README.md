# 残杀千足虫 · 动态补丁

《杀戮尖塔 2》残杀千足虫娘化皮肤的免费动画扩展。为头、中、尾三段添加分层待机、攻击、受击、瘫倒和锁链复苏，包含同回合接力复苏及图鉴预览。

**[下载 0.4.8 动态补丁 ZIP](https://github.com/MarchsYu/STS2-DecimillipedeMotion/releases/download/v0.4.8/DecimillipedeMotion-0.4.8.zip)**

## 安装

已在 Windows Steam 版 **v0.113.1** 验证。原皮肤和本补丁均可用游戏自带的模组加载器安装。

1. 先手动安装 Kiteseven 的 [原版娘化皮肤](https://github.com/kiteseven/decimillipede-feminization/releases/latest)，需要 `decimillipede-feminization` 0.0.1 或更新。已经安装并启用的玩家可以跳过这一步。
2. 退出游戏。在 Steam 库中右键《杀戮尖塔 2》，选择「管理 → 浏览本地文件」。
3. 解压动态补丁 ZIP，把其中的 `DecimillipedeMotion` 文件夹整个放入游戏的 `mods` 文件夹。升级时覆盖同一目录里的 DLL 和 JSON。
4. 启动游戏，确认「模组」中两项均已启用。如游戏提示重启，重启后生效。

```text
Slay the Spire 2/
└─ mods/
   ├─ decimillipede Feminization/
   │  ├─ decimillipede-feminization.json
   │  └─ decimillipede-feminization.pck
   └─ DecimillipedeMotion/
      ├─ DecimillipedeMotion.dll
      └─ DecimillipedeMotion.json
```

如果游戏在「模组」中将动态补丁标红并提示缺少 `decimillipede-feminization`，请打开补丁详情，按提示手动安装或启用原皮肤后重启游戏。

遇到残杀千足虫可查看实战动画，已解锁图鉴条目时也可以预览。卸载补丁时，退出游戏后移走 `mods/DecimillipedeMotion`。

## 0.4.8 版本记录

- 活动锁链补回原画的过渡色，平滑缩放时的硬边并保留手绘轮廓。
- 清理中段颈部的重复项圈和左侧发束上的项圈残片。
- 锁链根据角色层级绘制在三段角色前方，适配改变角色层级的 RegentFX。

## 素材来源

原皮肤和立绘由 **Kiteseven（kiteseven77）** 制作。动态补丁在原立绘基础上制作了分层动画图集。原项目的发布页和许可证见下方。

- [原作者的 B 站视频](https://www.bilibili.com/video/BV1QiLY6DEEs/)
- [原皮肤 GitHub 仓库](https://github.com/kiteseven/decimillipede-feminization)
- [上游 Apache-2.0 许可证](LICENSE-Upstream-Apache-2.0.txt)
