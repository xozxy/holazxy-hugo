# Avery Lin Studio (Demo Hugo Site)

这是一个基于 Hugo 的个人作品集站点模板，内容已替换为**虚拟示例数据**，用于演示站点结构与排版效果。

## 主要特性

- Hugo 静态站点结构（主题位于 `themes/hola`）
- About / Work / Project 三个主要内容区
- 统一的案例展示页与图文内容模板
- 社交链接与作者信息可在配置中替换

## 快速开始

> 需要安装 Hugo（推荐 Hugo Extended 版本以支持 SCSS）。

本地预览：

```bash
hugo server -D
```

构建静态文件：

```bash
hugo
```

## 目录结构

- `config.toml`：站点配置与作者信息
- `content/about/_index.md`：关于页内容（已虚拟化）
- `content/work/*.md`：作品案例页（已虚拟化）
- `content/project/*.md`：项目文章页（已虚拟化）
- `static/images/`：案例用图
- `data/Socials.toml`：社交链接配置（示例占位）

## 数据说明

仓库中的姓名、联系方式、项目名称与描述均为虚构内容，用于占位展示。如果要上线真实站点，请将这些信息替换为你自己的内容。
