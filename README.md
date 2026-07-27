# grill-me + grilling

[简体中文](#简体中文) | [English](#english)

## 简体中文

本仓库镜像 [mattpocock/skills](https://github.com/mattpocock/skills) 中相互配套的两个技能：

- [`skills/productivity/grill-me`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me)
- [`skills/productivity/grilling`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling)

镜像目录结构：

```text
skills/
├── grill-me/
└── grilling/
```

`grill-me` 是调用 `/grilling` 的入口，`grilling` 提供实际的逐题访谈流程，因此两个目录会一起同步。

### 自动同步

GitHub Actions 每天自动检查一次上游更新，也可以在仓库的 **Actions** 页面手动运行
`Sync productivity skills from upstream`。

同步规则：

- 只同步上游的 `skills/productivity/grill-me` 和 `skills/productivity/grilling`。
- 上游新增、修改或删除的文件会同步到本仓库。
- 只有内容发生变化时才会产生新提交。
- `README.md`、工作流和许可证文件不会被同步任务覆盖。
- 请勿直接修改 `skills/grill-me/` 或 `skills/grilling/` 中的镜像文件，因为下一次同步会覆盖这些改动。

### 来源与许可证

原始内容来自 [Matt Pocock](https://github.com/mattpocock) 的
[mattpocock/skills](https://github.com/mattpocock/skills)，并依照 MIT License 分发。
详情请参阅 [UPSTREAM_LICENSE](UPSTREAM_LICENSE)。

---

## English

This repository mirrors two companion skills from
[mattpocock/skills](https://github.com/mattpocock/skills):

- [`skills/productivity/grill-me`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me)
- [`skills/productivity/grilling`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling)

Mirrored directory structure:

```text
skills/
├── grill-me/
└── grilling/
```

`grill-me` is the entry point that invokes `/grilling`, while `grilling` provides the
actual one-question-at-a-time interview flow. Both directories are synchronized together.

### Automatic synchronization

GitHub Actions checks the upstream repository once per day. The
`Sync productivity skills from upstream` workflow can also be started manually from the repository's
**Actions** page.

Synchronization behavior:

- Only `skills/productivity/grill-me` and `skills/productivity/grilling` are synchronized.
- Upstream file additions, modifications, and deletions are mirrored.
- A new commit is created only when the mirrored content changes.
- `README.md`, the workflow, and the license file are not overwritten.
- Do not edit files under `skills/grill-me/` or `skills/grilling/` directly because the
  next sync will overwrite them.

### Source and license

The original content comes from [Matt Pocock](https://github.com/mattpocock)'s
[mattpocock/skills](https://github.com/mattpocock/skills) repository and is distributed
under the MIT License. See [UPSTREAM_LICENSE](UPSTREAM_LICENSE) for details.
