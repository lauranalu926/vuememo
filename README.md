# vuememo

> 基于 Vue.js 的简单记事本 SPA

## Build Setup

``` bash
# 安装依赖
npm install
# 开发模式localhost:8080
npm run dev
# 打包构建
npm run build
```

## 主要功能

- v1
  - ✔️创建、删除、修改笔记
  - 标记笔记是否完成
  - 对不同尺寸的桌面端和移动端响应适配
  - 按类别、标题、内容或时间进行过滤
  - 按创建时间或标题排序
- v2
  - 实时保存笔记
  - 通过localStorage对象的数据本地持久化
  - 支持Markdown格式
- v3
  - 通过base64支持保存图片
  - 通过Canvas支持绘图