# 重建展示发布包

这个目录是 GitHub Pages 发布版，可以直接作为仓库根目录上传。

## 本地预览

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

然后访问：

```text
http://127.0.0.1:8765/gallery_publish_v1/index.html
```

## GitHub Pages

- 上传本目录内的全部文件。
- Pages Source 选择仓库根目录，或把本目录内容放到 `docs/` 后选择 `/docs`。
- 不需要后端服务。

## 包内容

- `index.html`: 展示页面。
- `app.js`: WebGL 点云查看器。
- `viewerZoom.js`: 缩放逻辑。
- `pointclouds/`: 页面加载的点云和 manifest。
- `previews_recon/`: 场景预览图。
- `inputs/`: 每个场景的输入帧。
