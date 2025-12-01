### 原文链接：https://seotoprofit.com/t/topic/4298

---

:rocket: seoToProfit - 克隆机器人使用教程
—— 从账号获取、登录配置到频道内容克隆全流程讲解
本篇为 seoToProfit - 克隆机器人（@ClonedroBot） 的完整使用指南，包括：

如何启动机器人
如何获取后台登录账号与密码
如何登录后台
如何配置克隆机器人
如何进行频道内容克隆
常见提示与注意事项
如果你是第一次使用，此文能帮助你无障碍完成整个流程 :rocket:

:pushpin: 一、启动克隆机器人 @ClonedroBot
首先使用官方的：

:backhand_index_pointing_right: seoToProfit - 克隆机器人
机器人用户名： @ClonedroBot

image
image
1200×935 23.2 KB
打开机器人后点击 START 启动：

image
image
1200×932 50.2 KB

image
image
1200×931 63.3 KB

image
image
1200×933 64.3 KB
:pushpin: 二、预览登录地址（后台演示入口）
机器人会给出一个后台预览登录地址，主要用于查看功能界面：

image
image
1920×1054 24.6 KB

image
image
1920×1049 55 KB
出现 404 页面无需理会，点击左侧菜单即可浏览后台功能。

:warning: 注意
等你后续获取到专属账号密码后，也可以通过此入口进行“一键登录”。

image
image
1200×937 69.9 KB

image
image
771×750 31.1 KB
:pushpin: 三、获取后台登录账号与密码
在机器人中点击命令：

:backhand_index_pointing_right: /recover

即可自动获取首次登录后台所需的：

登录地址
登录账号
登录密码
若后续忘记密码，也能用同样方式重置，非常方便。

image
image
771×750 34.3 KB

image
image
1920×1049 19.8 KB
:pushpin: 四、登录后台与首次更改密码
打开后台链接 ➜ 输入账号与密码即可进入后台：

image
image
1920×1054 39.2 KB
首次登录系统会要求你修改密码以保障账号安全，按提示完成即可。

image
image
1920×1049 37.3 KB
:pushpin: 五、机器人管理：创建并配置 Telegram Bot
进入后台后，第一步是配置你的 Telegram 机器人。

:one: 到 BotFather 创建机器人
打开官方 BotFather：

:backhand_index_pointing_right: @BotFather

image
image
771×940 46.8 KB

image
image
771×869 46.3 KB
使用命令：

/newbot
然后设置：

机器人名称
用户名（必须以 _bot 结尾）
即可获得机器人 Token：

image
image
1920×1049 51.7 KB

image
image
1920×1049 52.2 KB
:two: 在后台添加机器人
输入：

机器人名称
Token
轮询方式选择：Webhook

添加成功后即可在列表看到：

image
image
1920×1049 65.4 KB
:pushpin: 六、账号管理：登录克隆采集账号
进入 账号管理 功能：

image
image
1920×1049 65.8 KB
输入 Telegram 账号绑定的手机号 → 点击发送验证码：

image
image
1200×935 91.7 KB

image
image
1920×1049 72.9 KB

image
image
1920×1049 77.4 KB
验证码会发送到 Telegram（飞机），复制填入即可完成登录。

:warning: 若账号有两步验证，也需输入两步验证码。

:pushpin: 七、账号登录注意事项（非常重要）
克隆功能对账号安全影响极小，不会改变账号信息
不建议登录太多账号，一个小号足够使用
无需登录自己的主账号
目前 TData/Session 上传还在优化中，暂不建议使用
登录后可能出现：

登录失败: mtproto_not_configured
无需担心，这是后台配置问题，刷新后即可看到账号。

image
image
1920×1049 73 KB

image
image
1920×1049 75.2 KB

image
image
1920×1049 75.4 KB
:pushpin: 八、账号详情：测试消息功能
可点击账号右侧「详情」进行消息测试：

image
image
1920×1049 41.4 KB

image
image
1200×933 51.4 KB
只要能正常收到消息，账号即可正常用于克隆。

image
image
1200×935 81.8 KB

image
image
1200×928 74.4 KB
:pushpin: 九、设置机器人为管理员（必须）
在要克隆的目标频道或群组中，将你创建的机器人设置为 管理员：

image
image
1920×1049 72.5 KB

image
image
1920×1049 78.3 KB
否则机器人没有权限发送克隆内容。

:pushpin: 十、配置内容克隆（核心功能）
进入 转发设置，刷新后即可看到登录的采集账号：

image
image
1920×1049 78.8 KB

image
image
1920×1049 79.4 KB
:sparkles: 克隆方式说明（两种）
你可以根据需求选择使用方式：

① 克隆别人频道内容 → 同步到自己的频道
源频道：填写对方频道链接
目标频道：填写自己的频道
适合采集外部内容、新闻源等。

② 一主多副频道同步（常用）
源频道：填写自己一个主要频道
目标频道：填写自己多个频道（几百 / 几千都行）
你只需要在源频道发一条内容，所有其他频道都会自动同步。

:pushpin: 十一、创建克隆规则
下面示例为克隆一个币圈类新闻频道：

image
image
1920×1049 75.2 KB

image
image
1920×1050 76.3 KB
在克隆内容规则中：

选择 全部复制
时间选择 不限制（可按个人需求调整）
image
image
1920×1049 87.5 KB

image
image
1200×932 179 KB
创建规则后：

系统会自动加入源频道
自动采集内容
通过机器人“无转发痕迹”发布到你的频道
源频道有新内容时会实时同步
:tada: 结语
以上就是“seoToProfit 克隆机器人”的完整配置流程。
祝大家使用愉快，效率翻倍！:bullseye:

如果使用过程中遇到任何问题，或希望新增功能，欢迎随时在论坛发帖反馈，我们会持续更新优化。
