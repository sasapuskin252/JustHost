# Vultr 使用全攻略：购买、设置与登录教程

Vultr 是一款深受开发者欢迎的 VPS 云服务器，凭借按小时付费、全球多达 20 多个机房的选择以及极具竞争力的价格，吸引了大量国内外用户。然而，由于 Vultr 是国外服务商，其官网为英文界面，对国内新手用户而言可能不太友好。本文将为您提供详尽的 Vultr 购买、配置与使用指南。

---

## Vultr 优缺点概览

在购买前，先快速了解 Vultr 的优缺点：

### 优点
- **按小时计费**：按实际使用时间收费，灵活可控。
- **多数据中心选择**：包括日本、韩国等靠近中国的节点。
- **价格亲民**：提供适合小型项目的经济套餐。

### 缺点
- **速度不佳**：国内访问速度受限，晚高峰时可能出现丢包现象。
- **IP 封禁问题**：部分分配的 IP 可能被中国大陆屏蔽，需要手动更换。

如果对速度要求较高，也可以考虑其他替代方案，如搬瓦工（BandwagonHost）。

---

## 1. 创建 Vultr 账号

访问 [Vultr 官网](https://bit.ly/bewildcard)，点击右上角“注册”。输入您的邮箱和密码（密码需包含大小写字母，且不少于 10 位）。

![注册 Vultr 账号](https://zhidao91.oss-cn-shanghai.aliyuncs.com/Content/2022/2022-11-28/1.jpg)

完成注册后，前往邮箱验证账户。如果未收到邮件，请检查垃圾邮件或更换邮箱重新尝试。

---

## 2. 充值余额

验证邮箱后，登录 Vultr 后台，点击左侧菜单中的 **Billing** 进行充值。新用户需要至少充值 10 美元以激活账户（尽管官方提供 100 美元试用，但需完成充值后才会生效）。

您可以选择通过 PayPal 或支付宝付款：

![充值 Vultr 账户](https://zhidao91.oss-cn-shanghai.aliyuncs.com/Content/2022/2022-11-28/2.jpg)

- 支付宝支持无理由退款，按小时计费的未使用余额可随时退回。
- 充值后，账户激活，即可开始部署您的云服务。

---

## 3. 创建 VPS

充值完成后，点击左侧 **Products** 菜单，再点击右上角的“+”号新增实例。

![创建 Vultr 服务](https://zhidao91.oss-cn-shanghai.aliyuncs.com/Content/2022/2022-11-28/3.jpg)

### 选择数据中心与配置

1. **数据中心**：建议选择日本或韩国节点，它们延迟相对较低。但需注意，某些区域（如美国）提供更便宜的套餐。
2. **操作系统**：推荐使用 **CentOS 7 x64**，文档资源丰富。若需使用 Windows 系统，需额外支付 License 费用。
3. **IPv6 支持**：如果需要启用 IPv6，可勾选对应选项。

![选择 Vultr 配置](https://zhidao91.oss-cn-shanghai.aliyuncs.com/Content/2022/2022-11-28/4.jpg)

完成配置后，点击 **Deploy Now** 开始部署。系统将自动完成安装，通常需要 5-10 分钟。

---

## 4. 管理您的 VPS

当 **Status** 显示为 **Running** 时，说明 VPS 已安装完成。

![VPS 安装完成](https://zhidao91.oss-cn-shanghai.aliyuncs.com/Content/2022/2022-11-28/9.jpg)

点击服务器名称进入管理界面，在 **Overview** 中获取以下信息：
- **IP 地址**
- **用户名**
- **密码**

您可以使用这些信息通过 Xshell、Putty 等 SSH 工具登录 VPS。

---

## 5. 销毁与重建 VPS

如果分配到的 IP 被封，可销毁 VPS 并重新部署以获取新 IP。操作步骤：
1. 点击 **Server Destroy** 按钮。
2. 勾选 **Yes, destroy this server**，并确认销毁。

![销毁 Vultr 服务](https://zhidao91.oss-cn-shanghai.aliyuncs.com/Content/2022/2022-11-28/12.jpg)

注意：暂停服务不会停止计费，只有销毁服务才能完全停止费用扣除。

---

## 6. 登录 VPS

在拿到 IP、端口、用户名和密码后，使用 SSH 工具连接服务器即可完成登录。

推荐参考教程：[Linux VPS 远程连接指南](https://www.vps234.com/xshell-connect-linux-vps-guide/)

若分配的 IP 无法访问，可以使用 **[IPChecker](https://www.vps234.com/ipchecker/)** 工具检测其状态。

---

👉 **[WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)**

无论是支付工具还是部署流程，WildCard 都是简化流程的绝佳选择！

---

## 结语

通过以上步骤，您已掌握 Vultr 的注册、充值、部署和管理流程。作为一款高性价比的云服务器平台，Vultr 非常适合个人开发者和小型企业。如果您对速度和可靠性有更高要求，可进一步选择高频实例或其他服务商。

开始您的云服务器之旅吧！
