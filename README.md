# OpenTone

OpenTone 是一个可部署到 GitHub Pages 的开源吉他音色适配器原型，用少量公开音色数据验证三件事：音色搜索、设备映射和浏览器实时分析。

## 本地运行

无需安装依赖。直接用浏览器打开 `index.html`，或启动任意静态服务器：

```bash
python -m http.server 8080
```

然后访问 `http://localhost:8080`。实时分析需要 HTTPS 或 localhost，并需要用户授予麦克风权限。

## GitHub Pages

将仓库推送到 GitHub，在 Settings → Pages 中选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/ (root)` 即可。

## 数据与许可

演示数据仅用于原型验证。项目代码采用 MIT License；音色信息应在正式发布前补充准确来源和各自内容许可。
