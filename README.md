# 📚 参考文献自动排版工具 V25

纯浏览器运行的参考文献批量排版工具，无需安装，打开网页即可使用。

👉 在线使用：

https://moonjunjie.github.io/moon/

## 核心功能

- 粘贴一条标准参考文献，自动识别目标排版格式
- 上传目标格式文档
- 上传原始参考文献 DOCX、PDF、TXT 等文件
- 识别 Word 自动编号列表
- 普通文本编号自动分条
- 无编号文献保守智能拆分
- 多数据源联网检索
- 低置信度结果保留原文并提示复核
- 重复文献检测
- 实时进度条与任务统计
- 作者截断规则
- 期刊完整名称与缩写切换
- 常用格式模板收藏
- 下载 TXT
- 下载参考文献 Word 文档
- 导出联网匹配检查表 Word 文档

## V25 修复

修复上传原始 DOCX 时出现：

```text
读取失败：parseEntries is not defined
```

V25 已恢复缺失函数。

对于用户提供的测试 DOCX：

```text
Word 自动编号列表项：141
解析结果：141
第一条编号：1
最后一条编号：141
```

## GitHub Pages 部署

把仓库根目录中的文件保持为：

```text
index.html
README.md
.nojekyll
```

Pages 设置：

```text
Settings
→ Pages
→ Deploy from a branch
→ main
→ /(root)
```
