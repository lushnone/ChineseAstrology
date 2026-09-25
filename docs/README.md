# Docs 目录说明

## 定位：分类索引，不是教程

`docs/` **不写**术数讲义、不断事、不做人身「大师课」。  
每个主题页只做两件事：

1. 说明「这类收集框里装什么」  
2. 指向 [`catalog/entries/`](../catalog/entries/) 里 `disciplines` 对应的条目（以后可加自动生成的列表）

**正文与字段以 catalog YAML 为准**；docs 避免重复粘贴 URL 和长功能说明。

## 语言

**`zh-CN` 为主。** `en` / `ja` / `ko` 同 slug；未译则链到简体索引页。

## 主题页模板（`topics/*/README.md`）

1. **收集范围** — 这类 App/网站通常带什么功能（列举用，非教学）  
2. **已收录** — 链到 catalog（或「暂无，欢迎 PR」）  
3. **（可选）** 填写 `features` 时常见关键词，方便贡献者统一写法  

不要写：流派争论、解读步骤、书单式「必学权威」。

## 新分类

1. 在 `docs/zh-CN/topics/{slug}/README.md` 建索引 stub  
2. 根 [README.md](../README.md) 分类表加一行  
3. 如需新 `disciplines` 值，改 schema + [`meta/zh-CN/tags.md`](../meta/zh-CN/tags.md)
