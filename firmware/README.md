# firmware/ — 嵌入式固件

存放 STM32 终端固件源码。

## 计划功能

- [ ] 设备状态数据采集（传感器读取）
- [ ] MQTT 客户端连接与发布
- [ ] 断网缓存
- [ ] 自动重连
- [ ] 数据补传
- [ ] 设备身份认证（如 Token / 证书）

## 约定

- 目录约定：`stm32/`（HAL/寄存器工程，含 Keil/CubeMX 工程文件）；
- 固件版本号与 `experiments/*/config.yaml` 中的 `firmware.version` 保持一致。
