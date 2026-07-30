# video-scripts 目录说明

用于沉淀教程视频脚本相关的可复用模板，  
本身不存放任何一期具体视频的内容。

## 结构

- `guides/script-format.md` — 脚本格式的取舍说明。
- `guides/tutorial-video-workflow.md` — 完整录制工作流说明。
- `templates/script.md` — 每期视频脚本的模板。
- `templates/script.decision.md` — script.md 各部分的设计理由。
- `templates/metadata.md` — 每期视频发布信息的模板。
- `templates/metadata.decision.md` — metadata.md 各字段的设计理由。
- `episodes/` — 每期视频的实际内容存放在这里，  
  具体新建步骤见 `episodes/README.md`。

## 使用方式

正式录制某一期视频时，在 `episodes/` 下新建  
`episode-NN/` 子目录，把 `templates/` 下的两个模板  
复制进去，比如 `episodes/episode-01/script.md`、  
`episodes/episode-01/metadata.md`。

脚本里的片段按 `## 片段 01`、`## 片段 02` 这样依次  
复制模板里的片段块即可，编号和录制、剪辑用的文件编号保持一致。

## 背景

这套模板配套的整体工作流说明见  
`guides/tutorial-video-workflow.md`，  
脚本格式的取舍见 `guides/script-format.md`。  
给 AI 会话看的完整背景说明见 `CLAUDE.md`。
