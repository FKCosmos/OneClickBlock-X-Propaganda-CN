# OneClickBlock-X-Propaganda-CN

> **一键屏蔽中国 IP 直连“狱友”与大外宣账号**  
> A one-click solution to mass-block CN IP-linked propaganda and "prison-mate" accounts on Twitter/X.

---

## 📖 项目介绍 / Introduction

本项目提供一个专门针对 **中国 IP 直连的大外宣与“狱友”账号** 的 Twitter/X 大规模屏蔽方案。  
你只需下载本仓库提供的 **账号列表 JSON 文件**，并配合 **Mass Block Twitter 插件**，即可一键拉黑这些账号，有效清理时间流与评论区环境。

---

## 🚀 快速上手 / Quick Start

### ✅ **步骤 1：下载屏蔽名单**

直接从本仓库下载最新屏蔽名单（格式已匹配 Mass Block Twitter 插件要求）：  
**👉 [点击下载 Accounts_based_in_China-block-list.json](./block-lists/Accounts_based_in_China-block-list.json)**

> 保存到本地电脑，文件内容无需修改。

---

### ✅ **步骤 2：安装 Mass Block Twitter 插件**

根据你的浏览器选择对应的安装地址：

- **Chrome 用户**  
  👉 [Mass Block Twitter - Chrome Web Store](https://chromewebstore.google.com/detail/mass-block-twitter/eaghpebepefbcadjdppjjopoagckdhej)

- **Firefox 用户**  
  👉 [Mass Block Twitter - Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/mass-block-twitter/)

安装完成后，浏览器工具栏会出现插件图标。  
**更多信息请查看插件的官方 GitHub 项目主页：**  
👉 [rxliuli/mass-block-twitter (GitHub)](https://github.com/rxliuli/mass-block-twitter)

---

### ✅ **步骤 3：创建审核列表并导入 JSON**

1. **点击浏览器的 Mass Block Twitter 插件图标**，进入主界面  
2. 找到 **“Moderation Lists”（审核列表）** 栏目，点击 **“Create new list”（新建审核列表）**  
3. **自定义列表名称**（如 `中国IP账号黑名单`）及描述  
4. 在新建的审核列表界面，选择 **“Import”**  
5. **选择本地已下载的 `Accounts_based_in_China-block-list.json` 文件进行导入**  
6. 插件会自动识别并加载所有待屏蔽账号

---

### ✅ **步骤 4：批量屏蔽**

- 导入完成后，页面将显示全部名单并支持批量操作  
- 可一键 **“Block All”** 或分批拉黑所有账号（**建议分批处理防止 API 限制，单批不超过 500 账号**）  
- 后续更新：只需下载最新 JSON 文件并重新导入即可

---

## ❓ 常见问题 / FAQ

- **API 限制**：Twitter/X 每 15 分钟有拉黑速率限制，如名单较多建议分批操作  
- **格式问题**：务必保证导入文件为标准 JSON 格式，推荐直接使用本仓库文件  
- **插件升级**：如遇导入失败或功能异常请先更新插件版本  
- **安全提醒**：所有名单均人工筛选，拉黑前可自行浏览确认是否有误伤  

---

## 📂 仓库结构 / Repository Structure

```
.
├─ block-lists/
│  └─ Accounts_based_in_China-block-list.json   # 核心屏蔽名单
├─ docs/                                        # 使用说明与截图
├─ README.md
└─ LICENSE
```

---

## 🔗 相关资源

- [Mass Block Twitter - Chrome Web Store](https://chromewebstore.google.com/detail/mass-block-twitter/eaghpebepefbcadjdppjjopoagckdhej)
- [Mass Block Twitter - Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/mass-block-twitter/)
- [Mass Block Twitter 官方 GitHub 项目主页](https://github.com/rxliuli/mass-block-twitter)
- [Twitter/X 官方帮助中心](https://help.twitter.com/)
- [JSON 文件格式规范](https://www.json.org/json-en.html)

---

## 📄 许可 / License

本项目使用 **MIT License**，详情请查看 [LICENSE](./LICENSE)。

---

## ⚠️ 免责声明 / Disclaimer

本项目仅用于信息过滤与个人信息环境管理，不涉及对平台的非正常使用。  
请遵守 **Twitter/X 平台服务条款**及当地法律法规，自行承担使用风险。
