# 隐私、安全与密码管理工具

> 整理密码管理、加密通信、隐私邮箱、浏览器、安全检查和数据泄露查询入口。

<p align="left">
  <a href="https://github.com/StaryMoon/cn-privacy-security-toolbox"><img alt="stars" src="https://img.shields.io/github/stars/StaryMoon/cn-privacy-security-toolbox?style=flat&label=stars"></a>
  <img alt="category" src="https://img.shields.io/badge/%E5%AE%89%E5%85%A8%20%20%2F%20%20%E9%9A%90%E7%A7%81-curated-blue">
  <img alt="language" src="https://img.shields.io/badge/language-中文-brightgreen">
</p>

![preview](assets/preview.png)

<sub>图片来源：公开入口预览图，[https://github.com/bitwarden/clients](https://github.com/bitwarden/clients)，截取/整理日期：2026-07-02。</sub>

## 定位

本仓库是一份面向中文用户的主题索引，重点整理常用、稳定、值得优先了解的工具入口，并补充适用场景、选型建议和风险边界。目标不是追求数量，而是降低第一次检索和筛选的成本。

- **主题**：安全 / 隐私
- **适合人群**：学生、开发者、远程办公和注重隐私的人
- **首批重点**：Privacy Guides / Bitwarden / KeePassXC / Proton Mail / Signal
- **为什么值得整理**：账号安全和隐私工具是长期刚需，尤其适合中文用户做基础安全教育。

## 使用方式

1. 先看 [精选资源](#精选资源)，按自己的场景挑 2-3 个入口试用。
2. 再看 [选型建议](#选型建议)，避免一上来把同类工具全装一遍。
3. 如果用于课程、论文、开源项目或生产环境，务必看 [风险提醒](#风险提醒)。

## 收录口径

先解决普通用户最容易出事的密码、2FA、邮箱、文件加密，再谈进阶隐私。

优先收录：

- 官方文档、官网、活跃 GitHub 仓库；
- 免费可试用或开源项目；
- 中文用户高频搜索、收藏、复用的工具；
- 入口稳定、说明清楚、维护状态可判断的资源。

暂不收录：

- 破解软件、灰色下载、账号代认证、返利推广；
- 长期不可访问或入口频繁变化的镜像；
- 只有营销话术、没有清晰文档的产品；
- 与本主题关系很弱的泛泛工具。

## 精选资源

| 名称 | 适合场景 | 入口 |
| --- | --- | --- |
| Privacy Guides | 隐私工具和建议总入口。 | [访问](https://www.privacyguides.org/) |
| Bitwarden | 密码管理器。 | [访问](https://bitwarden.com/) |
| KeePassXC | 本地开源密码库。 | [访问](https://keepassxc.org/) |
| Proton Mail | 注重隐私的邮箱服务。 | [访问](https://proton.me/mail) |
| Signal | 端到端加密通讯。 | [访问](https://signal.org/) |
| Tor Browser | 匿名网络浏览器。 | [访问](https://www.torproject.org/) |
| Have I Been Pwned | 数据泄露查询。 | [访问](https://haveibeenpwned.com/) |
| age | 简单现代的文件加密工具。 | [访问](https://github.com/FiloSottile/age) |
| 2FAS | 双因素认证 App。 | [访问](https://2fas.com/) |
| Ente Auth | 开源 2FA 认证器。 | [访问](https://ente.io/auth/) |
| SimpleLogin | 邮箱别名和隐私转发。 | [访问](https://simplelogin.io/) |
| Cryptomator | 云盘文件加密。 | [访问](https://cryptomator.org/) |
| Mullvad | 隐私导向 VPN 服务。 | [访问](https://mullvad.net/) |

## 选型建议

- 先启用密码管理器和两步验证。
- 重要账号使用独立邮箱和独立密码。
- 定期查泄露并轮换密码。

## 风险提醒

- 避免复用密码。
- 2FA 恢复码不应与账号密码存放在同一云笔记中。

## 维护说明

- 本仓库会优先更新失效链接、官方入口变更和明显过时的描述。
- 新增资源请尽量给出官网、GitHub 仓库、文档页或可验证的公开说明。
- 推荐新资源时，请说明具体场景和选择理由，避免只写泛泛评价。

## 数据文件

结构化数据见 [`data/links.json`](data/links.json)，可用于脚本生成网页、表格或个人导航页。

## Contributing

欢迎提交 PR 修正链接、补充官方文档、更新截图或改进中文说明。请保持描述短、准、可验证。

## License

MIT。第三方商标、截图、网页内容和产品名称归各自权利方所有，本仓库只做索引和学习整理。
