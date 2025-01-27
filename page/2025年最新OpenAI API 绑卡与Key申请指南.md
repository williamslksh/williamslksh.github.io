OpenAI API Key 是使用 OpenAI API 进行开发的必要凭证。本教程将详细讲解如何为 OpenAI API 绑定虚拟信用卡以及申请 API Key 的步骤。

## 登录 OpenAI 平台

在登录之前，您需要安装相关插件并确保拥有稳定的海外网络环境。具体的操作步骤可以参考以下指导：[使用海外家庭网络环境的浏览器设置](https://bit.ly/bewildcard)。

## 绑定虚拟信用卡

在 OpenAI 进行绑卡操作前，请确保您的卡上 **至少有 5 美元的余额**，否则会导致绑卡失败。

1. 访问 [OpenAI 账户设置](https://platform.openai.com/account/billing/overview)，点击「Add payment details」。
2. 选择「Set up paid account」，并决定是个人使用还是公司账户。

接下来，输入您的信用卡信息，包括卡号、有效期、CVV 以及邮政编码。接下来输入您的姓名和 **ACCPAY** 提供的账单地址，然后点击「continue」。

完成绑卡后，您将需要选择充值金额，金额可以在 5 美元到 50 美元之间。充值后，即可开始使用 GPT-4 的 API。

您还可以设置自动充值功能，当余额低于指定金额时，系统会自动从您的绑定卡中扣款。

## 申请 API Key

点击菜单中的「API Keys」，即可看到已创建的 API Key 列表以及添加新 API Key 的按钮。您也可以直接通过 [创建 API Keys 的链接](https://platform.openai.com/api-keys) 进行创建。

在选择完毕后，点击「Start verification」，需要验证您的海外手机号。

登录 **ACCPAY**，在页面中找到「海外手机号」服务申请您的手机号。申请成功后，复制分配的手机号。

回到 OpenAI 验证手机号的页面，选择英国 United Kingdom，并将号码粘贴到输入框中，点击「发送验证码」。

登陆 **ACCPAY** 页面，点击「刷新」按钮，您将看到验证码，复制并返回 OpenAI 填写验证码。完成验证后，您将成功注册 OpenAI 账户。

请注意，每个海外手机号仅可验证两个 API，如需重复使用，该手机号可能会提示已绑定，但不会影响使用。

## 创建与复制 API Key

完成上述步骤后，您可以正常创建和复制您的 API Key。

## API 消费与扣费

OpenAI 会根据您的充值金额设置消费限额。例如，如果您充值了 5 美元，那么调用 API 的费用也最多为 5 美元。如果连续两次扣费失败（例如余额不足），OpenAI 将可能封禁您的开发者账户及对应银行卡，因此，请确保 **卡内余额足够支付**。

👉 [野卡 | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)