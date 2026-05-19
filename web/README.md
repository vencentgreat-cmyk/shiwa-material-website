# 深圳市时外材料科技有限公司官网 v1

这是一个 Netlify + GitHub 可部署的静态官网版本。

## 项目结构

```text
shiwa-material-website/
├── netlify.toml
└── web/
    ├── index.html
    └── assets/
        ├── docs/
        └── images/
```

## Netlify 设置

- Base directory: `web`
- Build command: 留空
- Publish directory: `.`
- Functions directory: 留空

也可以直接依赖根目录的 `netlify.toml`。

## 更新方式

修改 `web/index.html` 或替换 `web/assets` 内图片后，Commit + Push 到 GitHub，Netlify 会自动部署。
