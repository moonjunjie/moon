# 联网参考文献自动排版工具

这是一个可以直接在浏览器中运行的参考文献格式转换网页。

## 在线使用

启用 GitHub Pages 后，请在这里填写你的在线网址：

`https://你的GitHub用户名.github.io/你的仓库名称/`

## 功能

- 根据一条标准参考文献，自动识别目标格式。
- 批量转换参考文献格式。
- 自动识别题名大小写规则。
- 自动判断期刊缩写是否保留句点。
- 根据题名、作者、年份或 DOI 联网搜索文献。
- 低可信度时展示多个候选文献，供用户手动选择。
- 支持生成 GB/T 7714—2015、APA 7 和 IEEE 三种常用格式。
- 使用 Crossref、OpenAlex、Semantic Scholar 和 DataCite 的公开接口。

## 部署到 GitHub Pages

1. 新建一个 GitHub 仓库，例如：`reference-formatter`。
2. 将本项目中的 `index.html` 和 `README.md` 上传到仓库根目录。
3. 进入仓库的 `Settings`。
4. 在左侧菜单中选择 `Pages`。
5. 在 `Build and deployment` 下，将 `Source` 设置为 `Deploy from a branch`。
6. 选择 `main` 分支和 `/(root)` 目录，然后点击 `Save`。
7. 等待片刻后，在 Pages 设置页面查看公开访问网址。

## 注意事项

- 搜索功能需要连接互联网。
- 某些校园网、单位网络或浏览器扩展可能会拦截部分公开接口。
- 中文文献在公开数据库中的覆盖仍然有限，匹配结果应人工检查。
