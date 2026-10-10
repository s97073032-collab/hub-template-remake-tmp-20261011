---
cursor:
  subagentId: "bc-6e986b5a-de81-5445-9f3f-bf992d5d5078"
---

# Hub 模版族重制计划（3 主题 × 9 成片）

> 源仓浅克隆：`https://github.com/zhuyansen/agent-skills-hub.git`（本机 `/tmp/agent-skills-hub-remake/agent-skills-hub`）  
> 门禁：[final-video-craft-standard.md](./final-video-craft-standard.md)  
> 两线：[two-tracks-selflove-boundary.md](./two-tracks-selflove-boundary.md)  
> **弃用：** v1 cream 圆角字卡；v2 深 slate + 青轨切层 + 下三分墨条（`consent-enthusiastic-*.mp4` 保留对照，不覆盖）

---

## 1. 为何换模版族

用户反馈上一轮「skills 重制」与旧片几乎同款。本轮从 Hub **真实目录**另选 9 条生产套路，视觉语言互相可区分，且与 v1/v2 一眼不同。

Hub 本身是 skill 目录站；「模版」取自仓内：

- 运营制作配方：`ops/youtube/*`、`ops/ppt-runs/in/*`、`ops/design-runs/in/*`
- 视频 skill 分型与代表仓：`ops/jev-review/state/claude-video-skills/types.json` + `ops/awesome/build_video_list.py` 的 `VIDEO_BLURB` 分区

---

## 2. 主题池（3 条独立口播）

| 主题 slug | 品类线 | 主张（合上手机能复述） | 口播轨 | 时长目标 |
|---|---|---|---|---|
| **consent** | 边界 · kinkref | 没说不 ≠ 同意；积极同意要听得见、可具体、可收回 | `media/consent-enthusiastic-cloned.wav` + `media/consent-enthusiastic-koubo.srt` | ≈56.7s（复用，不重克隆） |
| **harass** | 边界 · 骚扰识别 | 不舒服不是太敏感；三点判断 + 三句拒绝 + 留证求助 | `media/suqi-harassment-cloned.wav` + `media/suqi-harassment-koubo.srt` | ≈62.7s（复用，不重克隆） |
| **kepu** | 两性科普 · 自爱入口 | 性健康不必羞耻；媒介素养；卫生护理；不确定先停 | `media/hub-kepu-selflove-cloned.wav` + `media/hub-kepu-selflove.srt`（加长稿重新克隆） | ≈40s（过 30s 短档门禁） |

线不混：consent/harass 不用いらすと科普皮肤；kepu 不用 NDL 墨栏 / 骚扰 cream 字卡。

---

## 3. 主题 × 模版矩阵（9 条互不相同）

| # | 成片文件 | 主题 | Hub 模版锚点（仓内路径或 types 代表仓） | 镜头差（相对 v1/v2） |
|---|---|---|---|---|
| 1 | `media/hub-consent-ppt-deck-a.mp4` | consent | **`ops/ppt-runs/in/brief.md`**（PPT 教学页配方；对标前端 slides / consulting PPT 族） | 冰蓝咨询幻灯：页码、左色条、浅灰底；非 cream、非深切层 |
| 2 | `media/hub-consent-shotcraft-a.mp4` | consent | **`ops/jev-review/state/claude-video-skills/types.json` → `Vincentwei1021/video-shotcraft`（promo）** | 电影感 letterbox + 镜头配方卡；琥珀主光 / 炭灰底 |
| 3 | `media/hub-consent-onetake-a.mp4` | consent | **types → `feitangyuan/onetake`（promo）** | 单画布连续生长：块面从上一拍长出，无幻灯硬切 |
| 4 | `media/hub-harass-listicle-a.mp4` | harass | **`ops/youtube/video-skills-top10.md` + cues 倒计时章节套路（对标 hypit 榜单片）** | 白底海军榜单卡 / 序号倒计时；非墨条 |
| 5 | `media/hub-harass-livepanel-a.mp4` | harass | **types → `ythx-101/live-panel-skill`（motion）** | 终端架构面板：磷光绿字 + 黑底流程图节点 |
| 6 | `media/hub-harass-hyperframes-a.mp4` | harass | **types → `heygen-com/hyperframes`（general；Hub top10 #2）** | HTML/浏览器框 + 组件叠层渲染感；薄荷绿 UI |
| 7 | `media/hub-kepu-lottie-a.mp4` | kepu | **types → `diffusionstudio/lottie`（motion；Hub top10 #4）** | 几何 morph 形变 + 动能主词；浅薄荷/珊瑚，非深底 |
| 8 | `media/hub-kepu-collage-a.mp4` | kepu | **types → `pyang5166/gbro-collage-broll`（motion）** | 半调拼贴撕边 B-roll；杂志拼贴感 |
| 9 | `media/hub-kepu-handdrawn-a.mp4` | kepu | **types → `gnipbao/story-to-handdrawn-video`（story）** | 冷灰手绘日记风（**不用**暖米黄 `#F5EBD7` 白板） |

另参考（未单独出片，防撞车）：`ops/design-runs/in/brief.md` 设计落地页节奏；`ops/youtube/video-skills-top10.cues.json` 章节 ≥10s 规则。

---

## 4. 明确弃用

| 弃用项 | 原因 |
|---|---|
| cream 圆角 pill / 白半透明幻灯字卡 | v1；用户已否 |
| 深 slate + 青轨切层 + 下三分墨条 | v2；用户认为无差异 |
| 骚扰样片 `media/harassment-sample/slide*.png` 皮肤 | cream 底，禁止套到新模版 |
| HeyGen 数字人主声 | 主声固定苏琪克隆 |
| 把 Hub 整仓当产线 | Hub 只供模版发现；本轮终端合成见下 |

---

## 5. 合成路径（剪映优先 · 本轮例外）

- **优先：** 剪映成片。本机可生成 `jianying-headless` 草稿，但批量 9 条原生导出需 GUI/引擎抢键，**本轮禁止抢键**。
- **本轮例外：** 终端 Python（PIL 帧）+ ffmpeg 合成 H.264 yuv420p + AAC `+faststart`；脚本在 `artifacts/hub-remake/render_hub_nine.py`。
- 规格：1920×1080 · 30fps · 时长对齐各自主声。

---

## 6. 验证清单

- [ ] 9 条文件名前缀 `hub-{theme}-{template}-a.mp4`，不覆盖 `consent-enthusiastic-*`
- [ ] 每条时长 30–120s（kepu 加长后 ≥30s）
- [ ] 首 3–5s 钩子可读；中段信息 ≤3 点；尾有收束
- [ ] 视觉与 v1/v2 可区分；三线互不串皮肤
- [ ] 副本进 Project `media/` 与 `~/cursor/artifacts/`

---

## 7. 产出索引（已渲 · 2026-10-11）

合成例外：终端 `artifacts/hub-remake/render_hub_nine.py`（未开剪映抢键）。  
校验帧：`artifacts/hub-remake/verify/` · 清单：`artifacts/hub-remake/manifest.json`  
副本：`~/cursor/artifacts/hub-*.mp4` + `hub-kepu-selflove-cloned.wav`

| # | 模版 | 路径 | size | 时长 |
|---|---|---|---|---|
| 1 | ppt-deck | `media/hub-consent-ppt-deck-a.mp4` | 833794 | 56.70s |
| 2 | shotcraft | `media/hub-consent-shotcraft-a.mp4` | 934516 | 56.70s |
| 3 | onetake | `media/hub-consent-onetake-a.mp4` | 936569 | 56.70s |
| 4 | listicle | `media/hub-harass-listicle-a.mp4` | 1012390 | 62.71s |
| 5 | livepanel | `media/hub-harass-livepanel-a.mp4` | 1108569 | 62.71s |
| 6 | hyperframes | `media/hub-harass-hyperframes-a.mp4` | 994182 | 62.71s |
| 7 | lottie | `media/hub-kepu-lottie-a.mp4` | 528733 | 33.90s |
| 8 | collage | `media/hub-kepu-collage-a.mp4` | 743039 | 33.90s |
| 9 | handdrawn | `media/hub-kepu-handdrawn-a.mp4` | 504387 | 33.90s |

口播：consent / harass 复用既有苏琪克隆；kepu 新克隆 `media/hub-kepu-selflove-cloned.wav`（33.90s）+ `media/hub-kepu-selflove.srt`。
