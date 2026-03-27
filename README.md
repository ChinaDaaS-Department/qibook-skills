# QiBook Skills

[企百科](https://skill.qibook.com) 官方提供的 AI Skill 工具包，支持企业工商查询与企业深度研究。

## Skills

| Skill | 说明 |
|-------|------|
| **qibook-company-profile** | 查企业查老板 — 快速查询企业工商信息（照面、股东、高管、对外投资）和人员关联 |
| **qibook-company-wiki-deepresearch** | 企业百科深度研究 — 基于 20+ 维度数据，自动识别主体类型，生成专业企业洞察报告 |

## 安装

### 1. 安装依赖

```bash
pip install requests
```

### 2. 安装 Skill

通过 skills 命令安装：

```bash
# 查企业查老板
npx skills add https://github.com/ChinaDaaS-Department/qibook-skills.git --skill qibook-company-profile

# 企业百科深度研究
npx skills add https://github.com/ChinaDaaS-Department/qibook-skills.git --skill qibook-company-wiki-deepresearch
```

或将对应目录复制到本地 skills 目录。

### 3. 配置凭证

到 [企百科](https://skill.qibook.com) 获取 API 凭证：

```bash
export QIBOOK_ACCESS_KEY="your_access_key"
export QIBOOK_BASE_URL="your_base_url"
```

## 使用

安装并配置后，在智能体中用自然语言直接交流。支持 Claude Code、OpenClaw、Trae 等通用智能体。

### 查企业查老板

```
帮我查一下华为
华为的股东有哪些
查一下张三名下有几家公司
```

### 企业百科深度研究

```
帮我了解一下比亚迪
给我做个安踏的企业报告
这家公司靠不靠谱
```

## 许可

本项目仅供学习和研究使用。使用时请遵守企百科的使用条款。
