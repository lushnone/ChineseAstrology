# 贡献说明 · Contributing

帮助**多记一条、改准一条** App 或网站即可。不必写长文。

## 加一条收录（最常见）

1. 复制 [`catalog/entries/_template.yaml`](catalog/entries/_template.yaml) → `catalog/entries/{id}.yaml`（`id` 小写英文+连字符）。  
2. 必填：`name`、`urls.primary`、`type`、`disciplines`、`status`、`last_verified`。  
3. 尽量写 **`features`**（字符串列表）：例如「八字排盘」「真太阳时可选」「iOS」。  
4. 用 **`i18n.zh-CN.summary`** 一句话描述（你观察到的功能，不要写吉凶评价）。  
5. 对照 [`meta/zh-CN/evaluation-criteria.md`](meta/zh-CN/evaluation-criteria.md) 的收录门槛（能访问、主题相关、非纯 spam）。

`scores` 整块可选；我们不搞官方排行榜。

## 改已有条目

- 更新 `last_verified`  
- `changelog` 加一行说明改了什么  
- 产品下架：`status: archived`，保留文件

## PR

- 一次 PR 多条同类收录可以（例如「3 个八字网站」）  
- 联盟链接须 `affiliate: true`  
- 不接受隐蔽的付费置顶

## 翻译

- 条目字段优先 **简体**；`i18n.en` / `ja` / `ko` 有则填  
- `docs/` 主题页保持**短索引**；不要往 docs 里搬整本教程

## 态度

只陈述公开信息（名称、链接、功能）。不攻击厂商或门派；主观感受放 `notes`，别当事实写。
