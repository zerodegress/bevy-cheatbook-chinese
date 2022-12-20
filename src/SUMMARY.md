# Summary

[介绍](./introduction.md)
[章节总览](./overview.md)

---

[初学Bevy？ 指导教程！](./tutorial.md)

---

[Bevy内设列表](./builtins.md)

---

- [Bevy安装小贴士](./setup.md)
  - [起步](./setup/getting-started.md)
  - [使用最新的Bevy（主分支）](./setup/bevy-git.md)
  - [文本编辑器/集成式开发环境](./setup/editor.md)
  - [为Bevy设计的开发工具和编辑器](./setup/bevy-tools.md)
  - [社区插件生态](./setup/unofficial-plugins.md)
  - [客制化Bevy（特性，模块化）](./setup/bevy-config.md)

- [常见问题](./pitfalls.md)
  - [来自Bevy和依赖的奇怪编译错误](./pitfalls/build-errors.md)
  - [性能缓慢](./pitfalls/performance.md)
  - [添加函数为系统时的错误](./pitfalls/into-system.md)
  - [2D对象不显示](./pitfalls/2d-camera-z.md)
  - [3D对象不显示](./pitfalls/3d-not-rendering.md)
  - [从结构体借用多个字段](./pitfalls/split-borrows.md)
  - [时间跳动（动作/动画不流畅）](./pitfalls/time.md)
  - [贴图/图像反了](./pitfalls/uv-coordinates.md)

- [一般游戏引擎特性](./features.md)
  - [坐标系统](./features/coords.md)
  - [变换](./features/transforms.md)
  - [可见性](./features/visibility.md)
  - [时间和计时器](./features/time.md)
  - [日志，命令行消息](./features/log.md)
  - [父/子层次结构](./features/parent-child.md)
  - [固定时间间隔](./features/fixed-timestep.md)
  - [音频](./features/audio.md)

- [资产管理](./assets.md)
  - [句柄](./assets/handles.md)
  - [从文件加载资产](./assets/assetserver.md)
  - [访问资产数据](./assets/data.md)
  - [用资产事件对变化做出反应](./assets/assetevent.md)
  - [跟踪加载进度](./assets/ready.md)
  - [资产热重载](./assets/hot-reload.md)

- [输入处理](./input.md)
  - [键盘](./input/keyboard.md)
  - [鼠标](./input/mouse.md)
  - [文本/字符](./input/char.md)
  - [游戏手柄（控制器，摇杆）](./input/gamepad.md)
  - [触摸屏](./input/touch.md)
  - [拖放（文件）](./input/dnd.md)
  - [MIDI（乐器）](./input/midi.md)

- [窗口管理](./window.md)
  - [[WIP] 窗口属性](./window/props.md)
  - [改变背景颜色](./window/clear-color.md)
  - [抓取/捕获光标](./window/mouse-grab.md)
  - [设置窗口图标](./window/icon.md)

- [使用2D](./2d.md)
  - [[WIP] 安装2D摄像机](./2d/camera.md)
  - [[WIP] 精灵和图集](./2d/sprites.md)

- [使用3D](./3d.md)
  - [[WIP] 安装3D摄像机](./3d/camera.md)
  - [3D模型和场景(GLTF)](./3d/gltf.md)

- [Bevy编程框架](./programming.md)
  - [ECS简介](./programming/ecs-intro.md)
  - [实体和组件](./programming/ec.md)
  - [资源](./programming/res.md)
  - [系统](./programming/systems.md)
  - [查询](./programming/queries.md)
  - [指令](./programming/commands.md)
  - [事件](./programming/events.md)
  - [应用构建器（主函数）](./programming/app-builder.md)
  - [退出应用](./programming/quit.md)
  - [本地资源](./programming/local.md)
  - [插件](./programming/plugins.md)
  - [系统执行顺序](./programming/system-order.md)
  - [系统集](./programming/system-sets.md)
  - [变更检测](./programming/change-detection.md)
  - [状态](./programming/states.md)
  - [运行准则](./programming/run-criteria.md)
  - [标签](./programming/labels.md)
  - [阶段](./programming/stages.md)
  - [移除检测](./programming/removal-detection.md)
  - [ParamSet（参数集）](./programming/paramset.md)
  - [系统管线](./programming/system-piping.md)
  - [直接的ECS世界访问](./programming/world.md)
  - [独占系统](./programming/exclusive.md)
  - [[WIP]子应用](./programming/sub-apps.md)
  - [Non-Send](./programming/non-send.md)
  - [编写系统测试](./programming/system-tests.md)

- [编程范式](./patterns.md)
  - [泛型系统](./patterns/generic-systems.md)
  - [组件存储（表格/稀疏集）](./patterns/component-storage.md)
  - [手动事件清理](./patterns/manual-event-clear.md)

- [[WIP] Bevy渲染（GPU）框架](./gpu.md)
  - [渲染架构概述](./gpu/intro.md)
  - [渲染阶段](./gpu/stages.md)

- [Bevy实例](./cookbook.md)
  - [在命令行显示帧率](./cookbook/print-framerate.md)
  - [将光标转换为世界坐标](./cookbook/cursor2world.md)
  - [定制摄像机投影](./cookbook/custom-projection.md)
  - [摇晃+环绕摄像机](./cookbook/pan-orbit-camera.md)
  - [列出所有资源类型](./cookbook/print-resources.md)

- [不同平台上的Bevy](./platforms.md)
  - [Linux桌面](./platforms/linux.md)
  - [macOS桌面](./platforms/macos.md)
  - [Windows桌面](./platforms/windows.md)
  - [交叉编译](./setup/cross.md)
    - [从Linux到Windows](./setup/cross/linux-windows.md)
  - [浏览器（WebAssembly）](./platforms/wasm.md)
    - [惊诧消息](./platforms/wasm/panic-console.md)
    - [优化大小](./platforms/wasm/size-opt.md)
    - [在Github Pages上托管](./platforms/wasm/gh-pages.md)

---

[参与人员名单](./credits.md)

---

[联系我](./contact.md)

---

[为Bevy做贡献](./contributing-bevy.md)
[为本指南做贡献](./contributing.md)

