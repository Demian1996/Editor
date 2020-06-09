# 富文本编辑器

## 介绍

基于 slate.js 开发富文本编辑器

## 原因

1. 现有项目中使用的是基于百度 UEditor 开发的编辑器，由于技术栈落后，结合 React 使用时维护成本较高。
2. 数学公式编辑器现已解耦，做成了独立的插件，可集成到其他编辑器上。最大的限制已被移除。
3. slate 灵活，且已在各大公司中使用。

综上所述，现在基于 slate 库调研新型富文本编辑器，为后续抽离文档服务铺垫。

### TODO：

- [x] 加粗
- [x] 代码块
- [x] 斜体
- [x] 下划线
- [ ] 左对齐右对齐等布局
- [ ] 粘贴事件处理
- [ ] 改用option，控制功能启用
- [ ] 接入公式编辑器
- [ ] 设置文本颜色
- [ ] 插入图片
- [ ] 单元测试100%覆盖
- [ ] 埋点api
      ...

### 运行：

```js
npm install
npm run start
```
