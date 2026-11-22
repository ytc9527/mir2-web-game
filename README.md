# mir2-web-game

一个把《热血传奇》（Legend of Mir 2）味道做进浏览器的单文件网页 ARPG：纯 HTML5 Canvas + 原生 JS，无框架、无后端、无外部依赖，下载一个 `index.html` 双击就能玩。

> 仅用于学习、研究与技术演示。游戏美术素材版权归原权利方所有，详见文末「版权与素材」。

## 直接开玩

- 在线：仓库启用 GitHub Pages 后访问 Pages 地址，或直接打开仓库里的 `index.html`
- 本地：下载 `index.html`，用 Chrome / Edge 打开即可（存档写在浏览器 localStorage）

## 已实现

- **三职业**：战士（近身高血防）、法师（远程火球、脆皮高爆发）、道士（施法自疗、攻守兼顾）
- **技能体系**：刺杀剑术、烈火剑法、火球术、治愈术、召唤骷髅、回城术，可升级
- **装备与掉落**：武器 / 衣服 / 戒指六槽，自动穿戴更强装备；沃玛、祖玛套装 BOSS 掉落
- **地图**：比奇城、西荒原、东荒原、北岭、兽人古墓、沃玛寺庙
- **刷怪与重生**：分区域刷怪点、仇恨追击、击杀经验与金币
- **BOSS 副本**：兽人古墓骷髅王（1800 HP）、沃玛教主（3600 HP），带小怪环与掉落
- **NPC 与商店**：杂货商、药店老板、首饰商、服装商、传送员、马倌、仓库管理员、村民
- **引导地图**：左上角常驻小地图（NPC 彩点 / 刷怪区红点 / 玩家白点），`M` 键打开大地图，点 NPC 条目自动寻路并对话；被屋顶遮挡的 NPC 显示虚影与金色名牌
- **坐骑赶路**：马倌处购买灵鹿，`H` 键上/下坐骑，移动速度提升
- **存档**：每 8 秒自动存档，关闭页面也会存；死亡不覆盖旧档。开始页有「继续征程 / 新建角色 / 重开新档」
- **战斗表现**：飘字伤害、目标红圈、技能扇形范围、死亡与回城复活（损失一半金币）

## 操作

| 按键 | 功能 |
| --- | --- |
| 点击地面 | 移动 |
| 点击怪物 | 攻击 |
| B | 背包 |
| C | 状态 / 装备 |
| S | 技能 |
| H | 坐骑 |
| M | 大地图 |
| T | 回城 |

## 存档说明

存档键 `mir2_web_save_v1`，保存在浏览器 localStorage，不联网、不上传。清空浏览器站点数据即等于删档。

## 版权与素材

- **代码**：MIT License，见 `LICENSE`。
- **美术素材**：角色、地图、界面等图像素材版权归《热血传奇》/ Legend of Mir 2 原权利方所有，本项目不主张其权利，仅作学习与技术演示之用，禁止商用。若权利人认为使用不当，提交 Issue 即可，会立即移除相关内容。

---

### English

A single-file, dependency-free Legend of Mir 2 style browser ARPG built with HTML5 Canvas and vanilla JS: three classes, skills, equipment drops, dungeons with bosses, NPCs and shops, a minimap / world map with NPC auto-pathing, a mount for faster travel, and localStorage auto-save. Code is MIT licensed; all game art remains the property of its original rights holders and is used for study and demo purposes only.
