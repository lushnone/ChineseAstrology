# 中国玄学资源志 · Chinese Astrology

**Readme：** [简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

社区共同维护的 **App / 网站收集清单**：记名字、链接、平台、能做什么，按八字、紫微、奇门等分类存放。

**我们不是：** 写教程、做解读、立权威、教你怎么算命。  
**我们是：** 像名录一样把公开工具收集起来，方便自己查、方便别人补充；信息尽量可核对（`last_verified`）。

---

## 仓库里有什么

| 区域 | 用途 |
|------|------|
| **[catalog/](catalog/entries/)** | **核心**：一条 YAML = 一个 App 或网站（名称、URL、功能要点） |
| **[docs/](docs/zh-CN/)** | 按主题分的**索引页**，链到 catalog，不写长文科普 |
| **[meta/](meta/zh-CN/)** | 收录格式、标签怎么填 |

**会收集：** 排盘/计算器类 App、相关网站、桌面小工具、公开 API 页。  
**不收集：** 本仓库内的个案算命服务；也不把某家吹成「唯一正确」。

---

## 文档语言

| 语言 | 角色 | 入口 |
|------|------|------|
| 简体中文 | **主** | [`docs/zh-CN/`](docs/zh-CN/) |
| English | 次 | [`docs/en/`](docs/en/) |
| 日本語 | 次 | [`docs/ja/`](docs/ja/) |
| 한국어 | 次 | [`docs/ko/`](docs/ko/) |

条目里的 `i18n.zh-CN.summary`、`features` 等优先用简体写；其它语言能填则填。

---

## 快速开始

1. 直接翻 **[catalog/entries/](catalog/entries/)** 看已收录名单。  
2. 按分类浏览 **[docs/zh-CN/](docs/zh-CN/)** 里的主题索引。  
3. 要加一条 App/站：复制 [`catalog/entries/_template.yaml`](catalog/entries/_template.yaml)，看 **[CONTRIBUTING.md](CONTRIBUTING.md)** 后提 PR。

---

## 分类（`disciplines`）

| Slug | 用来装什么 |
|------|------------|
| `bazi` | 八字类 App、网站 |
| `ziwei` | 紫微斗数 |
| `qimen` | 奇门遁甲 |
| `liuyao` | 六爻 |
| `fengshui` | 风水相关工具站 |
| `calendar` | 万年历、节气、农历转换 |
| `glossary` | 仅 [`docs/…/glossary`](docs/zh-CN/topics/glossary/README.md)：App 名/功能描述用的中英日韩对照，不是术数教材 |

---

## 免责

列出的名称与功能来自公开页面或贡献者填写，可能有遗漏或变更，以官方为准。许可待定（建议 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)）。**非医疗、法律或投资建议。**

---

## 联系

GitHub Issue / PR。改条目请更新 `last_verified` 和 `changelog`。
