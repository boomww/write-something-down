# vite 使用 github pages 部署 react

## 步骤

1. 在`vite.config.js`中设置`base`为仓库名

```
base: "/restarting-react"
```

2. 在 github 上仓库下点击`Actions`，使用 Vite 提供的模板创建工作流程。或者直接在本地创建，目录为`.github/workflows/xxx.yml`

3. 仓库 Setting 下`Pages`中的生成源选择`GitHub Actions`

## 参考

- [Vite 部署 GitHub Pages](https://cn.vitejs.dev/guide/static-deploy.html#github-pages)
