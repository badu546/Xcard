# Xcard
Xcard项目概述：

类型: 实时的礼品卡交易应用。
前端技术: Flutter。
后端技术: 尚未确定。
前端功能：

首页 (Home):

以卡片形式展示三个主要模块。
显示钱包余额，下方有充值和提取两个按钮。
显示通知，与后台连接，可以通过后台发布通知或活动。
显示卡片类型，点击礼品卡会弹出窗口，用户可以选择国家，填写面值，系统会自动计算价格。价格下方有一个“sell”按钮，点击后跳转到sell页面，该页面会自动填写已知信息，并要求用户上传图片和收据（收据为可选）。
卖卡 (Sell):

功能与首页的卡片类型显示相似，但具有更具体的功能。
用户可以选择国家，填写面值，并选择上传图片（1-10张）。
钱包 (Wallet):

最上方是一个卡片，显示钱包余额，下方有充值和提取两个按钮。
下方显示个人信息资料。
右下角有实时聊天按钮。
后端功能：

可以实时修改不同礼品卡的价格和汇率。
可以接收用户上传的礼品卡图片和其他信息。
可以发送通知。
可以实时聊天，可能通过其他平台的API实现。
