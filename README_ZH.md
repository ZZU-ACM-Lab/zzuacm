# [Hugo Group Theme](https://github.com/HugoBlox/theme-research-group)

# 官网

- 👉 [**开始**](https://hugoblox.com/templates/)
- 📚 [查看文档](https://docs.hugoblox.com/)
- ⬆️ **更新?** 阅读[引导](https://docs.hugoblox.com/)和[发布说明](https://github.com/HugoBlox/hugo-blox-builder/releases)

# PPL流程

# Vercel部署

- 注意 nodejs 版本为 18.x
- 需要配置正确的Hugo版本
- 构建命令 Build Command: `hugo --gc --minify` （在vercel中配置）
- 安装命令 Install Command: `yum install golang` （在vercel中配置）

## 本地编辑

Docs: https://docs.hugoblox.com/getting-started/customize/

> 如果有任何修改上的问题，可以查看文档。

Bootstrap docs: https://bootstrap.hugoblox.com/

Windows:

- 设置环境变量: Go, Hugo(最新版本), Git, nodejs

> 电脑中的环境变量包括go和Hugo
>
> 设置成功后，运行 `go version` 可以查看go版本, 我的版本是 `1.22.1 Windows/amd64`
> 
> 运行 `hugo version` 命令可以查看Hugo版本, 我的版本是 `0.124.1 + extended` （注意是扩展版的）

- 运行 `hugo --gc` 清理缓存

- 运行 `hugo server -D` 本地浏览网站

