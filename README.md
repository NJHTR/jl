# JL 企业协作工作台原型

基于 GooseHyperGlass 液态玻璃组件构建的企业内部协作界面原型，包含消息、邮件、工作台、搜索和界面设置等交互场景。

## 功能概览

- 可拖动的纵向液态玻璃导航栏
- 消息、邮件与工程项目工作台视图
- 居中搜索弹窗及输入状态保留
- 动态视频背景与静帧降级
- 桌面端、平板端和窄屏自适应布局
- 工程监理品牌视觉与真实项目素材

## 本地运行

项目是无构建依赖的静态页面，需要通过 HTTP 服务访问：

```powershell
python -m http.server 4173
```

浏览器打开：

```text
http://127.0.0.1:4173/
```

## 目录结构

```text
.
├─ index.html
└─ assets/
   ├─ brand-engineering/
   └─ goose-hyper-glass/
```

第三方组件与图片来源见 [assets/SOURCES.md](assets/SOURCES.md)。
