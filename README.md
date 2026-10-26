# 学习通 DeepSeek 助手 · 历史版本归档

本仓库保存「学习通自动刷课 G版」每个历史提交的完整源码快照，方便回看、对比或下载旧版本。

- 当前版本（持续更新）：[GAOQI-GQ/xuexitong-deepseek-console](https://github.com/GAOQI-GQ/xuexitong-deepseek-console)
- 本仓库只归档源码，不含 EXE（EXE 始终只保留在本机）。
- 旧版本仅供存档，可能包含已经修复的问题，请优先使用当前版本。
- 桌面上的旧文件 `学习通自动刷课 G版.cmd` 对应 `dba8985` 快照。

## 版本列表

| 日期 | 提交 | 说明 | 快照目录 |
| --- | --- | --- | --- |
| 2026-10-26 | [`7972254`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/7972254afd3efcb8f5db5672332270540a3c54ef) | 切到视频任务点先等视频加载，不再误当纯图文去滚动 | [video-task-load-wait](versions/2026-10-26_7972254_video-task-load-wait) |
| 2026-10-26 | [`fe06999`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/fe069994d522e2f70617ace820ebd1bb3e2c4750) | 图文滚动加进度心跳，避免自检把长篇图文误判成卡住 | [doc-scroll-heartbeat](versions/2026-10-26_fe06999_doc-scroll-heartbeat) |
| 2026-10-26 | [`e8f3ff4`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/e8f3ff41bce936662b7bf531a975d085f1e5abbe) | 修复三处跨作用域 ReferenceError：停滞自检与自动最高倍速此前从未真正生效 | [scope-referenceerror-fix](versions/2026-10-26_e8f3ff4_scope-referenceerror-fix) |
| 2026-10-26 | [`dbde6d7`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/dbde6d70e8b58a61a71bef594a5a7ea97671302c) | 清理重复与死代码，文件净减 88 行 | [dead-code-cleanup](versions/2026-10-26_dbde6d7_dead-code-cleanup) |
| 2026-10-26 | [`8d436d1`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/8d436d14a2106a5053025ac26d4b6ba6beb4faf6) | 减轻浏览器负担并修复启动变慢 | [perf-and-fast-start](versions/2026-10-26_8d436d1_perf-and-fast-start) |
| 2026-10-26 | [`9233676`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/92336767a5211e909d393d2e18844e652cb08d82) | 视频加载失败时自动切换备用线路（公网1/公网2） | [alternate-video-line-retry](versions/2026-10-26_9233676_alternate-video-line-retry) |
| 2026-10-26 | [`36681c2`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/36681c288370131f81bc6377e5fbdf4d6205a17a) | 加停滞自检：卡住也能自己恢复，不再静静停住 | [stall-self-check](versions/2026-10-26_36681c2_stall-self-check) |
| 2026-10-25 | [`201771a`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/201771a764e2bd1b48917bc5555d9840f4dc04f5) | 图文多篇时加完成情况保险，避免跳着做漏做 | [document-completion-insurance](versions/2026-10-25_201771a_document-completion-insurance) |
| 2026-10-25 | [`7ec41da`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/7ec41da4343154656a4807c509160564ee3eeac6) | 视频自动调到最高倍速，不支持则放弃 | [auto-max-playback-rate](versions/2026-10-25_7ec41da_auto-max-playback-rate) |
| 2026-10-25 | [`63f6729`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/63f672986e2ce300a4c595e2c15174d788480cbb) | 内容优先识别试卷页：一上来就是题目也能自动作答 | [quiz-content-detection](versions/2026-10-25_63f6729_quiz-content-detection) |
| 2026-10-25 | [`1b8dad4`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/1b8dad46dc5d4ff0be31290696d28ee1d9c00b2a) | 图文/视频混排：按页面任务统一调度，不再依赖固定顺序 | [mixed-media-sequencing](versions/2026-10-25_1b8dad4_mixed-media-sequencing) |
| 2026-10-25 | [`538dd71`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/538dd717c717b1e5197a6a1825c9bfa27072af7d) | 支持一个任务点里叠着多篇图文，并修掉图文页误判章节测验 | [stacked-article-reading](versions/2026-10-25_538dd71_stacked-article-reading) |
| 2026-10-25 | [`c6626b9`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/c6626b9670bf9660a50b45bacba9b975fa4e981b) | 自动完成阅读/图文任务点：滚动到底部后继续下一节 | [document-reading-scroll](versions/2026-10-25_c6626b9_document-reading-scroll) |
| 2026-10-25 | [`9ff0938`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/9ff093814b9e542066ac015667bb71c86229cd4d) | 章节测验判定叠加多重依据，避免把第二个视频当测验 | [quiz-signal-guards](versions/2026-10-25_9ff0938_quiz-signal-guards) |
| 2026-10-25 | [`df3e55d`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/df3e55da00d5eecce20a04c1f005132f4e9fcc99) | 修复章节测验误判导致脚本停住的问题 | [quiz-misdetect-fix](versions/2026-10-25_df3e55d_quiz-misdetect-fix) |
| 2026-10-25 | [`54e90ac`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/54e90ac63d5756f69684ec9f9f0a196ff7a3a23c) | 全量审查后的稳定性加固 | [stability-hardening](versions/2026-10-25_54e90ac_stability-hardening) |
| 2026-10-25 | [`e677607`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/e677607a26a9602ba132545a43a6e61f551fe443) | 启动版本号更新为 V800 | [version-v800](versions/2026-10-25_e677607_version-v800) |
| 2026-10-25 | [`0cc5d1f`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/0cc5d1f90e3f1c2b8b8ecb2310aa7d14eb27e992) | 补充多场景修复：弹窗关闭兜底、切换过渡防重入与播放器跟随 | [all-scenarios-fixes](versions/2026-10-25_0cc5d1f_all-scenarios-fixes) |
| 2026-10-25 | [`ae606a9`](https://github.com/GAOQI-GQ/xuexitong-deepseek-console/commit/ae606a9c7e390e2921f61fc36b6079f8fa6f147b) | 弹题多次失败后限制自动跳节次数，避免反复触发任务点弹窗 | [quiz-skip-guard](versions/2026-10-25_ae606a9_quiz-skip-guard) |
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
