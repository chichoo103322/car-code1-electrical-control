# car-code1 electrical control

车载 STM32 电控工程，包含底盘运动、路线通信、IMU、机械臂及托盘相关代码与调试资料。

## 工程入口

- STM32CubeMX：`car_code1.ioc`
- Keil MDK：`MDK-ARM/car_code1.uvprojx`
- 应用源码：`Core/`
- 上位机工具：`tools/`
- 主机侧测试：`tests/`

各模块的协议、调试方式和当前限制见仓库根目录下对应的 `README_*.md` 与 `DEBUG_GUIDE_*.md`。
