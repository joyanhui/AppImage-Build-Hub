# AppImage Build Hub

自动构建多个应用的 AppImage 版本，每两天更新一次，保留最新 10 个版本。

## 构建的应用

### VSCode

- **来源**: https://github.com/valicm/VSCode-AppImage
- **文件名**: `VSCode-x86_64.AppImage`
- **发布标签**: `vscode-latest`

### Zed Editor

- **来源**: https://github.com/lavilao/Zed-AppImage
- **文件名**: `zed-x86_64.AppImage`
- **发布标签**: `zed-latest`


## 构建特性

- **自动更新**: 每两天检查并构建新版本
- **手动触发**: 支持手动触发构建
- **版本管 理**: 自动保留最新 10 个 releases，删除旧版本
- **依赖修复**: 针对 Redis Manager 修复 Linux 发行版兼容性问题
- **并行构建**: 三个应用同时构建，提高效率
### fork

- vscode https://github.com/valicm/VSCode-AppImage
- zeditor https://github.com/lavilao/Zed-AppImage
