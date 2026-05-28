# Fear Nation 音频数据与转录文稿

## 项目说明

这里整理的是 Fear Nation 频道的音频数据和转录文稿，主要用于资料归档、检索和后续校对整理。

目前仓库中的内容以转录文稿为主，按单期节目分别存放在 `FearNation_transcription_text/` 目录下。

音频文件已整理到 Hugging Face 数据集：[Pixelber/fear_nation_aduio](https://huggingface.co/datasets/Pixelber/fear_nation_aduio)。

音频数据来源日期截止到 2026 年 5 月 28 日。

## 数据结构

仓库目前的主要数据目录是 `FearNation_transcription_text/`。该目录下按照单期节目标题建立子文件夹，每个子文件夹对应一条视频或音频内容。

单期节目文件夹中通常包含以下文件：

- `节目标题.md`：适合直接阅读的 Markdown 转录文稿。
- `节目标题.json`：结构化转录数据，便于后续用脚本检索、清洗或转换。
- `节目标题_metadata.json`：节目相关的元数据信息，用于记录来源、标题等辅助字段。

整体结构示意：

```text
FearNation_transcription_text/
└── 单期节目标题/
    ├── 单期节目标题.md
    ├── 单期节目标题.json
    └── 单期节目标题_metadata.json
```

现阶段 GitHub 仓库主要保存转录文本和元数据；音频文件统一托管在 Hugging Face 数据集中。使用时可以通过节目标题把本仓库中的转录文稿、结构化数据和 Hugging Face 中的音频文件对应起来。

## 更新日志

- 音频文件已更新到 Hugging Face 数据集：[Pixelber/fear_nation_aduio](https://huggingface.co/datasets/Pixelber/fear_nation_aduio)。
- 音频数据来源日期截止到 2026 年 5 月 28 日。
