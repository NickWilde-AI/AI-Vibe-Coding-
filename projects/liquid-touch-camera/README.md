# Liquid Touch Camera

实时摄像头画面上的**液体玻璃**效果：手指划过或手势移动时，水面会起伏、折射并产生高光。支持 **LIQUID** / **CRYSTAL** 两种视觉模式，可切换前/后置摄像头。

## 功能亮点

- WebGL 水面高度场模拟（256×256 仿真纹理）
- 触摸轨迹与 MediaPipe Hands 手势双重扰动
- 色差折射、菲涅尔边缘、动态高光
- 移动端友好（`viewport-fit`、安全区、触控优化）

## 运行

```bash
# 在仓库根目录
open projects/liquid-touch-camera/index.html
```

或使用本地静态服务（推荐，便于调试）：

```bash
npx --yes serve projects/liquid-touch-camera
# 浏览器访问终端提示的 http://localhost 地址
```

## 环境要求

- 支持 WebGL 的现代浏览器（Safari / Chrome 等）
- 摄像头权限；手势模式需能访问 `cdn.jsdelivr.net`（MediaPipe）
- **HTTPS** 或 `localhost`（`getUserMedia` 安全限制）

## 操作

1. 点击「开启摄像头」并授权
2. 在画面上滑动手指，或伸出手掌让手势驱动水面
3. 底部切换 LIQUID / CRYSTAL；右上角切换摄像头

---

Made with Vibe Coding · part of [AI-Vibe-Coding-](https://github.com/NickWilde-AI/AI-Vibe-Coding-)
