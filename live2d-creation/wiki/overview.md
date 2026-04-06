# Live2D 创作 — 概览

> 最后更新：2026-04-06

## 方向定位
将静态 2D 插画转化为 Live2D 动态角色的工具和工作流。

## 当前收藏（3 条）

### 核心工具：See-through 生态
- [[see-through-live2d|See-through + ComfyUI]] — 原始方案，AI 自动拆层 + Live2D 模板，15-20 分钟出活
- [[comfyui-seethrough-plugin|ComfyUI SeeThrough Plugin]] — 插件版，将 2D 角色图拆分为独立组件
- [[seethrough-webui|See-through WebUI]] — 独立 WebUI 版，简化环境搭建，输出 PSD

## 知识图谱
```
单张插画 → See-through（AI 拆层+补全）→ PSD/图层 → Live2D 模板绑定 → 动态角色
```

## 关联方向
- [[video-creation]] — 视频创作中的动画部分
- [[agent-ecosystem]] — ComfyUI 作为 AI 工具链的一环

## 趋势观察
1. **See-through 是核心技术** — 所有 3 条收藏都围绕它
2. **多形态适配** — ComfyUI 插件版、独立 WebUI 版、原始流程版
3. **硬件门槛** — RTX 2060+ 起步，消费级可用
4. **产出格式** — PSD 输出可与 Photoshop/Live2D Cubism 无缝衔接
