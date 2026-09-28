# Experiment ID
EXP-B（baseline）

## Purpose
验证基础链路（终端 → MQTT → Spring Boot → 数据库 → Web）可正常跑通，得到第一组可复现的 Baseline 结果。

## Compared with
无（本实验作为后续实验的基准）

## Configuration
见 `config.yaml`。

## Dataset
本实验不使用公开数据集，使用终端实时采集的设备状态数据。

## Random seed
42（如不涉及随机过程可忽略）

## Command
见 `command.txt`。

## Result
| 指标 | 结果 | 说明 |
|---|---|---|
| 消息时延 | 待填写 | 均值 / P95 / 最大值 |
| 连续上报成功率 | 待填写 | % |
| 异常告警响应时间 | 不适用（Baseline 无告警） | |

## Conclusion
待填写。

## Problems
待填写（如：丢包、重连失败、时间戳不同步、数据库写入瓶颈等）。
