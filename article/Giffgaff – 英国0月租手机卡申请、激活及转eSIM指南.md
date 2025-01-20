# Giffgaff – 英国0月租手机卡申请、激活及转eSIM指南

## 一、关于 Giffgaff

Giffgaff 是一家新兴的低成本移动运营商，成立于 2009 年，隶属于英国的 O2 运营商。与传统运营商不同，Giffgaff 没有实体营业网点和热线客服，而是通过灵活的套餐设计和低廉的服务费用来吸引短期游客及留学生用户。Giffgaff 支持全球漫游，并允许在中国收发短信、接听电话及上网。

**Giffgaff 的主要特点：**
- **性价比高**：提供 0 月租、免费接收短信，只需充值一次即可保持 20 年以上的号码（每半年保号一次）。
- **安全性高**：无需担心因号码被风控，还可换号两次，比 Google Voice 更加灵活。
- **支持漫游**：可以在中国大陆激活并支持漫游。
- **稳定性强**：无限有效期，每半年发一条短信即可保号。
- **兼容性广**：支持众多海外 APP 和银行，如 TikTok、Twitter、Instagram、WhatsApp、PayPal 等。

![Giffgaff](https://img.goasis.online/i/2024/11/04/qsibq9.png)

## 二、如何申请 Giffgaff 卡

### 2.1 官网申请实体卡（免费）

您可以通过 Giffgaff 官网申请实体卡，大部分国家地区都可以免费邮寄（平邮）。如果您确定地址能够顺利接收平邮，可以尝试申请，平均邮寄时间为 20 天左右。注意，邮寄过程中有可能会丢件。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)

### 2.2 国内购买

如果不想等待邮寄，您还可以通过国内的电商平台购买 Giffgaff 卡。国内购买速度较快，但可能会绑定某些套餐，建议选择未激活的白板卡。

## 三、如何激活 Giffgaff 卡

激活网址：[Giffgaff 激活页面](https://www.giffgaff.com/activate)

1. 输入您的激活码。
2. 提交电子邮件地址并设置密码（用于登录 Giffgaff 网站/APP）。
3. 选择是否接收信息（建议选择“不”）。
4. 注册完成后，您会收到确认邮件。

接着，您需要选择一个套餐，选择 **Pay as you go（无月租）** 套餐。

### 激活过程截图

![激活过程1](https://img.goasis.online/i/2024/11/04/r5phr3.png)

## 四、实体卡转 eSIM

如果您的手机支持 eSIM，可以通过 Giffgaff App 直接操作切换至 eSIM。如果您的手机不支持 eSIM，可以参考以下步骤通过 Postman 工具进行手动操作：

### 4.1 下载 Postman

[下载 Postman](https://www.postman.com/downloads/) 并安装。

### 4.2 导入配置

从网友提供的链接下载配置脚本，并导入到 Postman。

### 4.3 获取 Access Token

通过 Postman 获取授权的 Access Token，您需要使用 Giffgaff 账号进行登录并授权。

### 4.4 进行二次验证

接着，系统会要求您进行邮箱验证。输入收到的验证码并确认。

### 4.5 获取会员资讯

执行获取会员资讯的操作，成功后返回包含用户信息的 JSON。

### 4.6 生成新的 eSIM 空卡

通过 Postman 预留一个新的 eSIM 卡编号。

### 4.7 换卡操作

使用 Postman 执行换卡操作，将旧的实体卡切换为新的 eSIM。

### 4.8 生成 eSIM 配置文件

成功生成 eSIM 配置文件后，您可以将其下载并使用。

### 4.9 获取 eSIM 下载地址

获取到 eSIM 配置的下载地址后，可以用支持 eSIM 的设备进行激活。

### 4.10 生成二维码（可选）

通过 Postman 生成 eSIM 激活二维码，直接用支持 eSIM 的手机扫描即可。

## 五、如何保号

每 6 个月只需进行一次话费变动（如发短信、打电话或进行一次漫游）即可保号。

**漫游资费**（查询详细资费请访问 [Giffgaff 漫游资费](https://www.giffgaff.com/roaming-charges)）：
- 发短信：30P/条
- 打电话：1￡/分钟
- 接电话：1￡/分钟
- 数据流量：20P/MB

**保号小提示**：关闭流量设置，并确保每 6 个月发送一条短信以保号。

## 六、国内 iPhone 开启 Wifi-Calling

目前 Giffgaff 只为英国本地开启 Wifi-Calling，在国内使用时仍会走本地运营商的网络。因此，您需要使用梯子进行操作，才能正常享受服务。

开启 Wifi-Calling 后，短信和通话将按英国本土费率收费。

![Giffgaff Wifi-Calling](https://img.goasis.online/i/2024/11/08/kb9uai.png)

## 附：羊毛福利

如果您在成功激活 Giffgaff 的英国号码后，还可以尝试注册英国的汇款 App [LemFi](https://lemonadefi.app.link/ULivdVYmTOb)，使用 Giffgaff 的 +44 手机号注册并接收验证码，注册即送 5 英镑，填写推荐码 GUOGOQB7 后还能获得 15 英镑的额外奖励。

此外，您还可以将这些奖励提现至 [Wise](https://wise.com/invite/ihpc/gus6) 钱包或其他英国/欧洲银行账户。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)
