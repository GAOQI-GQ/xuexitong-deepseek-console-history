# 学习通 DeepSeek 助手 · 历史版本归档

本仓库保存「学习通自动刷课 G版」每个历史提交的完整源码快照，方便回看、对比或下载旧版本。

- 当前版本（持续更新）：[GAOQI-GQ/xuexitong-deepseek-console](https://github.com/GAOQI-GQ/xuexitong-deepseek-console)
- 本仓库只归档源码，不含 EXE（EXE 始终只保留在本机）。
- 旧版本仅供存档，可能包含已经修复的问题，请优先使用当前版本。
- 桌面上的旧文件 `学习通自动刷课 G版.cmd` 对应 `dba8985` 快照。

## 版本列表

| 日期 | 提交 | 说明 | 快照目录 |
| --- | --- | --- | --- |
| 2026-10-25 | [`09939c3`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/09939c3432b2743bb5ef06fa820d43e48bc3ec47) | 多段视频页面的视频弹题按所属视频暂停与恢复 | [multi-video-quiz-binding](versions/2026-10-25_09939c3_multi-video-quiz-binding) |
| 2026-10-25 | [`4cb0744`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/4cb07445cdbaf18fd0386d1abad930f1e15a6b0a) | 修复播放完第一段视频后误点下一节的问题 | [task-dialog-prefer-learn](versions/2026-10-25_4cb0744_task-dialog-prefer-learn) |
| 2026-10-25 | [`07a0ac9`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/07a0ac97364ec58b4c24c123efdeca6ba8b17940) | 多视频支持覆盖任意段数，并增加切换前的加载确认 | [multi-video-load-confirm](versions/2026-10-25_07a0ac9_multi-video-load-confirm) |
| 2026-10-25 | [`ffff6b1`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/ffff6b138c14a41b7eeec839c78b7bc2152e2f3d) | 支持同一学习页面的多段视频依次播放 | [multi-video-step](versions/2026-10-25_ffff6b1_multi-video-step) |
| 2026-10-25 | [`c10695b`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/c10695bc70b6b83f0f4e0535797e4c73b6d18c65) | 修复答错面板被误判成通过后不再重答的问题 | [wrong-panel-retry](versions/2026-10-25_c10695b_wrong-panel-retry) |
| 2026-10-24 | [`8d546b0`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/8d546b011c2f264d097242c6e8cf71c1d9a28fee) | README 增加搜索关键词，便于在 GitHub 搜到学习通相关仓库 | [readme-search-keywords](versions/2026-10-24_8d546b0_readme-search-keywords) |
| 2026-10-24 | [`83eec6f`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/83eec6f5713bcd034a381dacf3afc52fc6a8de4a) | 放宽“继续学习”判定条件的误判防护 | [continue-guard-refine](versions/2026-10-24_83eec6f_continue-guard-refine) |
| 2026-10-24 | [`a1f20f9`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/a1f20f9b7577c224d8be6f8e57ea015cba51782c) | 修复弹题答对后不点击“继续学习”的问题 | [continue-button-robust](versions/2026-10-24_a1f20f9_continue-button-robust) |
| 2026-10-24 | [`1b05a95`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/1b05a9593c617251ffe6aa113275f867e01a73ec) | 修复视频停在结尾但未触发结束事件时不切换下一节的问题 | [near-end-fallback](versions/2026-10-24_1b05a95_near-end-fallback) |
| 2026-10-24 | [`ad61a63`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/ad61a63074b81210482e1ed4eb93c2f327bb621a) | 修复多题视频弹题答对后不点“继续学习”、误点“下一节”的问题 | [multiquestion-continue](versions/2026-10-24_ad61a63_multiquestion-continue) |
| 2026-10-24 | [`581b507`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/581b5078c6ef5a03e3ff2b9174b6df2ac788ca94) | 修复多选题答错后不重答、不点下一节的问题 | [multiselect-retry](versions/2026-10-24_581b507_multiselect-retry) |
| 2026-10-24 | [`96f4760`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/96f476014b66125099b01d4bad83357673050f9c) | 修复章节任务点弹窗与视频弹题答错后的重答和跳过逻辑 | [dialog-quiz-retry](versions/2026-10-24_96f4760_dialog-quiz-retry) |
| 2026-10-23 | [`dba8985`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/dba8985b0ec056ed957e33abfdb6521fb57c8b69) | 重命名启动器为“学习通自动刷课 G版.cmd”并更新说明 | [rename-g-version](versions/2026-10-23_dba8985_rename-g-version) |
| 2026-10-23 | [`9729850`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/97298507d86ab507de46a6f18b8a0b5e75bd6120) | Update bookmark-only messages in the single-file build | [bookmark-message-update](versions/2026-10-23_9729850_bookmark-message-update) |
| 2026-10-23 | [`5451ea2`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/5451ea219ac7ddc11a4254c0680c0994e440959c) | Merge everything into one self-contained CMD and use bookmark-only injection | [single-file-bookmark-only](versions/2026-10-23_5451ea2_single-file-bookmark-only) |
| 2026-10-23 | [`b490396`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/b4903969312116de4d96f8db638927c26ebf7b4b) | Prefix the helper window message with a GQ reminder | [gq-reminder-prefix](versions/2026-10-23_b490396_gq-reminder-prefix) |
| 2026-10-23 | [`1e0b78a`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/1e0b78a3bf21737d0067d4dc31b286372fcec31a) | Open Chaoxing in Edge and minimize the launcher window | [edge-minimize](versions/2026-10-23_1e0b78a_edge-minimize) |
| 2026-10-23 | [`6339369`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/6339369f18abd5d02254819f7b2d6acd5b9c5f8d) | Document the bookmarklet launch method | [bookmarklet-docs](versions/2026-10-23_6339369_bookmarklet-docs) |
| 2026-10-23 | [`58ed2cf`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/58ed2cffe5556bbb559b1896fcfe1451d3157837) | Add visual API key setup with encrypted key memory | [visual-key-setup](versions/2026-10-23_58ed2cf_visual-key-setup) |
| 2026-10-23 | [`a673fc9`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/a673fc9ee63405bc99133b10bd0cc0d12f37a03b) | Click the continue button after a correct in-video quiz answer | [quiz-continue-button](versions/2026-10-23_a673fc9_quiz-continue-button) |
| 2026-10-22 | [`493aa76`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/493aa76497fbe440b5dec3b802660f1724be4afa) | Fix launcher failing when folder path contains parentheses | [path-parentheses-fix](versions/2026-10-22_493aa76_path-parentheses-fix) |
| 2026-10-22 | [`c7a5d9c`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/c7a5d9c5f1d574e41ca6aa27ced23db8ebb7a4dc) | Add xuexitong DeepSeek console assistant | [initial-multifile](versions/2026-10-22_c7a5d9c_initial-multifile) |

## 使用方式

进入对应快照目录即可查看或下载当次提交的全部源码；单文件版本只需 `学习通自动刷课 G版.cmd`。
