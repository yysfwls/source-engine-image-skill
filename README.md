# Source Engine Low Poly

将照片或文字场景重塑为早期 Source 引擎风格的低多边形游戏截图，重点模拟 2000 年代 PC 游戏中的低面数模型、低分辨率贴图、粗糙 lightmap 和生硬实时光影。

## 能做什么

- 把人物、动物、街景、室内或物品照片转换成早期 Source 引擎画面
- 默认保留原图主体、数量、姿势、构图、视角和关键环境关系
- 避免结果滑向现代 PBR、电影级 3D、像素画、体素或黏土玩具风格
- 根据人物、室内、室外和恐怖氛围自动调整具体提示词

## 安装

将整个 `source-engine-low-poly` 文件夹放入 Codex 的 Skills 目录：

```text
~/.codex/skills/source-engine-low-poly/
```

保持以下结构：

```text
source-engine-low-poly/
├── SKILL.md
├── README.md
└── agents/
    └── openai.yaml
```

## 使用

上传照片后直接调用：

```text
使用 $source-engine-low-poly 调整这张照片。
```

也可以附加要求：

```text
使用 $source-engine-low-poly 调整这张照片，保留人物和镜头位置，强化低清贴图与粗糙室内 lightmap，不要添加 HUD。
```

没有参考照片时，可以从文字生成场景：

```text
使用 $source-engine-low-poly 生成一张废弃地铁站的早期 Source 引擎游戏截图，冷灰色灯光，不要人物和怪物。
```
