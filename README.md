# china-archives

中国各地市档案馆公开的**开放档案目录**，整理为可离线检索、排序的单页应用，并附原始 CSV 数据。

Open archive catalogs from Chinese municipal archives, packaged as offline-searchable single-page apps with the raw CSV alongside.

## 目录 / Catalogs

| 档案馆 | 目录 | 记录数 | 链接 |
|---|---|---|---|
| 南昌市档案馆 (Nanchang) | 开放档案目录 · 2000年（含）前 | 89,879 | [`nanchang/`](nanchang/) |

## 说明 / Notes

- 每个目录页是一个自包含的 HTML 文件，数据内嵌，**无需联网即可检索/排序**（关键词搜索、按全宗号/年份筛选、点击表头排序）。
- 每个目录同时提供原始 CSV（`nanchang/nanchang_archives_full.csv`），供进一步分析。
- 字体（IBM Plex Sans / Mono）按 SIL Open Font License 1.1 分发，见 `nanchang/fonts/OFL.txt`。

## 本地部署 / GitHub Pages

页面为纯静态文件，可直接通过 GitHub Pages 访问，或任意静态服务器托管：

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000/nanchang/
```
