# Sync GitHub Repository with Aliyun OSS

这是一个通过 GitHub Action 将 GitHub 仓库与阿里云 OSS 完全同步的脚本。

## 使用方法

1. 将 YAML 文件放置到自己仓库的 `.github/workflows` 目录下，并修改脚本中带有注释的部分。
2. 在自己仓库的设置中，新建 Repository Secrets，添加 `ACCESS_KEY_ID` 和 `ACCESS_KEY_SECRET`，并填入对应的值（可以在阿里云右上角头像那里找到）。
3. 在 GitHub Action 中，查看是否运行成功。
