# 实验目录规范

> 每个实验一个子目录，目录名格式：`exp<编号>_<简短说明>`（Baseline 固定为 `baseline/`）。

## 每个实验目录必须包含

```
<exp_id>/
├── config.yaml     实验配置（环境、参数、变量）
├── command.txt     复现命令
├── notes.md        实验记录
└── metrics.csv     结果指标
```

## 实验记录模板（notes.md）

```markdown
# Experiment ID
EXP-001

## Purpose
验证……

## Compared with
Baseline

## Configuration
……

## Dataset
……

## Random seed
……

## Command
……

## Result
……

## Conclusion
……

## Problems
……
```

## 命名建议

| 编号 | 说明 |
|---|---|
| `baseline/` | 基础链路 |
| `exp01_reliability/` | 可靠性（重连/补传） |
| `exp02_latency/` | 时延测试 |
| `exp03_security/` | 安全/异常场景 |
| `exp04_ablation/` | 消融实验 |

## 记录原则

- 一次实验 = 一个目录，结果可复现；
- `metrics.csv` 使用统一列名，便于汇总；
- 失败的实验也要保留，写入 `Problems`，不得删除。
