# grill-me

[简体中文](#简体中文) | [English](#english)

## 简体中文

本仓库仅镜像 [mattpocock/skills](https://github.com/mattpocock/skills) 中的
[`skills/productivity/grill-me`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me)。

镜像内容保存在：

```text
skills/grill-me/
```

### 自动同步

GitHub Actions 每天自动检查一次上游更新，也可以在仓库的 **Actions** 页面手动运行
`Sync grill-me from upstream`。

同步规则：

- 只同步上游的 `skills/productivity/grill-me`。
- 上游新增、修改或删除的文件会同步到本仓库。
- 只有内容发生变化时才会产生新提交。
- `README.md`、工作流和许可证文件不会被同步任务覆盖。
- 请勿直接修改 `skills/grill-me/` 中的镜像文件，因为下一次同步会覆盖这些改动。

### 依赖说明

上游的 `grill-me` 是一个入口技能，其 `SKILL.md` 会调用 `/grilling`。本仓库按照设计只镜像
`grill-me`，不会同步或安装 `grilling`。如需完整运行该流程，请另外安装上游的
[`grilling`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling) 技能。

### 来源与许可证

原始内容来自 [Matt Pocock](https://github.com/mattpocock) 的
[mattpocock/skills](https://github.com/mattpocock/skills)，并依照 MIT License 分发。
详情请参阅 [UPSTREAM_LICENSE](UPSTREAM_LICENSE)。

---

## English

This repository mirrors only
[`skills/productivity/grill-me`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me)
from [mattpocock/skills](https://github.com/mattpocock/skills).

The mirrored content is stored at:

```text
skills/grill-me/
```

### Automatic synchronization

GitHub Actions checks the upstream repository once per day. The
`Sync grill-me from upstream` workflow can also be started manually from the repository's
**Actions** page.

Synchronization behavior:

- Only `skills/productivity/grill-me` is synchronized.
- Upstream file additions, modifications, and deletions are mirrored.
- A new commit is created only when the mirrored content changes.
- `README.md`, the workflow, and the license file are not overwritten.
- Do not edit files under `skills/grill-me/` directly because the next sync will overwrite them.

### Dependency notice

The upstream `grill-me` skill is a lightweight entry point whose `SKILL.md` invokes
`/grilling`. As intended, this repository mirrors only `grill-me`; it does not mirror or
install `grilling`. Install the upstream
[`grilling`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling)
skill separately to use the complete workflow.

### Source and license

The original content comes from [Matt Pocock](https://github.com/mattpocock)'s
[mattpocock/skills](https://github.com/mattpocock/skills) repository and is distributed
under the MIT License. See [UPSTREAM_LICENSE](UPSTREAM_LICENSE) for details.
