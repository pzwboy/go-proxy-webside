# go-proxy-vercel
用 Vue3 和 Go 搭建镜像站点，可用于大部分网站

## 本项目修改于[go-proxy-bingai](https://github.com/adams549659584/go-proxy-bingai)

## 镜像展示(以谷歌为例）

![](./demo/demo.png)
## 部署

> 需 https 域名
### Vercel

一键部署，点这里 => [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/pzwboy/go-proxy&project-name=go-proxy&repository-name=go-proxy-vercel)
### Render

一键部署，点这里 => [![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/pzwboy/go-proxy)

## 设置镜像网站

修改项目的`common/proxy.go`

将

`	BING_URL, _        = url.Parse("")`

的`("")`中添加需要被制作镜像的网站域名即可