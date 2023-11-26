<!-- markdownlint-disable MD033 MD041 -->

<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="./image/README/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="./image/README/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">
    ✨ 更人性化(拟人)的GPT聊天Ai插件! ✨<br/>
    🧬 支持多个人格自定义 / 切换 | 尽情发挥你的想象力吧！ ⚙️<br/>
    🧬 <a href="https://docs.google.com/spreadsheets/d/1JQNmVH-vlDn2uEPwkjv3iN-zn0PHpQ7RGbgA5T3fxOA/edit?usp=sharing">预设收集共享表(欢迎分享各种自定义人设)</a> 🧬 <br/>
    🎆 如果喜欢请点个⭐吧！您的支持就是我持续更新的动力 🎉<br/>
    💬 技术交流/答疑/讨论 -> ：<a href="https://jq.qq.com/?_wv=1027&k=71t9iCT7">加入插件交流群-636925153</a> 🗨️ <br/>
    👀 <a href="https://github.com/KroMiose/nonebot_plugin_naturel_gpt/tree/ng_for_claude">Claude 适配分支</a> <a href="https://github.com/238066asxsa">By: 238066asxsa</a> 👀 <br/>
    <a href="./LICENSE">
        <img src="https://img.shields.io/badge/license-Apache 2.0-6cg.svg" alt="license">
    </a>
    <a href="https://pypi.python.org/pypi/nonebot-plugin-naturel-gpt">
        <img src="https://img.shields.io/pypi/v/nonebot-plugin-naturel-gpt.svg" alt="pypi">
    </a>
    <img src="https://img.shields.io/badge/python-3.8+-6a9.svg" alt="python">
    <a href="https://jq.qq.com/?_wv=1027&k=71t9iCT7">
        <img src="https://img.shields.io/badge/加入交流群-636925153-c42.svg" alt="python">
    </a>
</div>

## 🎏 NG 进化史

### 🗺️ [2023/5/21] 文档站上线

插件文档站上线，欢迎访问 [ng.kro.zone](https://ng.kro.zone) 查看插件文档，感谢 [@lgc2333](https://github.com/lgc2333) 为文档站 建设/勘误/整理 提供的大力支持

### 🏠 [2023/4/14] v2.1 Minecraft 服务器接入与游戏指令扩展支持

本次更新后支持将 bot 接入 MC 服务器，并且支持 bot 使用游戏内指令扩展

### 🎉 [2023/3/16] v2.0 项目重构完成

感谢 [@Misaka-Mikoto-Tech](https://github.com/Misaka-Mikoto-Tech) 大佬对项目重构提供的大力支持

### ✏️ [2023/3/2] v1.4 更新: 支持 ChatGPT 模型

本次更新后插件开始支持官方 ChatGPT 模型接口，token 定价仅为 GPT3 的 1/10, 回复质量更高 响应速度更快

### 🧩 [2023/2/18] v1.3 更新: 自定义扩展支持

本次更新后插件开始支持自定义扩展，您可以直接通过自然语言直接调用多种扩展功能，包括 文本/图片/语音/邮件...

## 🎁 安装命令

请在 Bot 目录下执行此命令

```bash
nb plugin install nonebot-plugin-naturel-gpt
```

## 💡 功能列表

> 以下未勾选功能仅表示未来可能开发的方向，不代表实际规划进度，具体开发事项可能随时变动
> 勾选: 已实现功能；未勾选: 正在开发 / 计划开发 / 待定设计

- [x] 自动切换 api_key: 支持同时使用多个 openai_api_key，失效时自动切换
- [x] 自定义人格预设: 可自定义的人格预设，打造属于你的个性化的 TA
- [x] 聊天基本上下文关联: 群聊场景短期记忆上下文关联，尽力避免聊天出戏
- [x] 聊天记录总结记忆: 自动总结聊天记忆，具有一定程度的长期记忆能力
- [x] 用户印象记忆: 每个人格对每个用户单独记忆印象，让 TA 能够记住你
- [x] 数据持久化存储: 重启后 TA 也不会忘记你（使用 pickle 保存文件）
- [x] 人格切换: 可随时切换不同人格，更多不一样的 TA
- [x] 新增/编辑人格: 使用指令随时编辑 TA 的性格
- [x] 自定义触发词: 希望 TA 更主动一点？或者更有目标一点？
- [x] 自定义屏蔽词: 不想让 TA 学坏？需要更安全一点？
- [x] 随机参与聊天: 希望 TA 主动一些？TA 会偶然在你的群组中冒泡……
- [x] 异步支持：赋予 TA 更强大的消息处理能力！
- [x] 可扩展功能: 厌倦了单调的问答 AI？为 TA 解锁超能力吧！TA 能够根据你的语言主动调用扩展模块 (如:发送图片、语音、邮件等) TA 的上限取决于你的想象
- [x] 多段回复能力: 厌倦了传统一问一答的问答式聊天？TA 能够做得更好！
- [x] 主动欢迎新群友: 24 小时工作的全自动欢迎姬(?)
- [x] TTS 文字转语音: 让 TA 开口说话！(通过扩展模块实现)
- [x] 潜在人格唤醒机制: 当用户呼叫未启用的人格时，可自动切换人格 (可选开关)
- [x] 定时任务: 可以用自然语言直接定时，让 TA 提醒你该吃饭了！
- [x] 在线搜索/读链接: GPT3.5 的数据库过时了？通过主动搜索扩展让 TA 可以实时检索到最新的信息 (仿 newbing 效果)
- [x] 输出内容转图片: 使用 htmlrender 将 TA 的回复转换为图片，降低风控几率 (可选开关，感谢 @HMScygnet 提供 pr)
- [x] Minecraft 服务器接入，让她在游戏中为你服务，使用 GPT 的能力编写各种复杂的 NBT 指令
- [x] 消息节流机制，短时间内接受到大量消息时，只对最后一条消息进行回复 (可配置)
- [x] Stable Diffusion 绘画接入支持 (需自备绘图 API)
- [ ] 主动记忆和记忆管理功能: 让 TA 主动记住点什么吧！hmm 让我康康你记住了什么 (计划重构，为 bot 接入外置记忆库)
- [ ] 图片感知: 拟使用腾讯云提供的识图 api，协助 bot 感知图片内容
- [ ] 主动聊天参与逻辑: 尽力模仿人类的聊天参与逻辑，目标是让 TA 能够真正融入你的群组
- [ ] 回忆录生成: 记录你们之间的点点滴滴，获取你与 TA 的专属回忆

## 📄 使用文档

### > [点击前往 NG 文档站](https://ng.kro.zone)

## 🎢 更新日志

<details>
<summary>点击展开</summary>

### [2023/11/26] Stable Diffusion 绘图支持

- 新增 Stable Diffusion 绘图扩展，支持使用任意 SD 后端由 AI 自主绘图

### [2023/7/3] v2.1.8 token 计算优化 | 新增扩展和优化

- 文转图功能显示锚元素URL (感谢@student_2333 提供 pr)
- 新增扩展 ext_plaintext, 更新 lolicon_search 并调整扩展相关的 prompt (感谢@student_2333 提供 pr)
- 更换了 tiktoken 来进行 token 计算

### [2023/6/1] v2.1.7 扩展优化 | 新增扩展

- 新增 makemidi 扩展，允许 bot 进行 midi 创作（感谢@CCYellowStar 提供 pr）
- 新增 lolicon_search 扩展，搜索图片后会反馈图片信息（感谢@student_2333 提供 pr）
- 新增扩展 启用/禁用 命令，对于不需要额外配置的扩展，可使用指令安装后直接启用（感谢@student_2333 提供 pr）
- 新增 OpenAI API 的 base_url 配置，以便接入任何兼容 OpenAI API 格式的第三方接口
- 修复了一个 prompt 构建错误的问题

### [2023/5/24] v2.1.5 扩展优化 | 图片输出优化

> 强烈建议更新至此版本以上，否则可能会出现部分扩展加载失败的情况

- 优化聊天转图片输出样式，支持代码块高亮显示（感谢 @student_2333 提供 pr）
- 部分重构扩展管理和修改现有扩展，以支持异步请求（感谢 @student_2333 提供 pr）
- 修复读取链接扩展和搜索扩展 api，并为读取链接增加防重复机制（感谢@CCYellowStar 提供 pr）

### [2023/5/21] v2.1.4 逻辑优化 | 配置热重载

- 增加配置文件热重载功能（感谢 @Misaka-Mikoto-Tech 提供 pr）
- 增加消息丢弃机制，对于响应较慢的模型，如果在回复生成完成前收到了新的生成请求，将会丢弃旧的请求，避免重复响应
- 修正 bot 发送消息前带上时间和消息头的问题

### [2023/4/17] v2.1.3 响应节流功能 | 逻辑优化

- 增加了 bot 响应节流功能，可配置节流时间范围，短时间内的大量消息只会在最后一条响应一次
- 消除 pylance 提示的所有类型注解错误提示，进行模块拆分优化 (感谢 @Misaka-Mikoto-Tech 提供 pr)
- 优化 MC 指令执行扩展 prompt
- 为所有 图片/语音 相关扩展指定了生效会话类型，避免在 MC 服务器中执行指令时出现错误
- 修正 MC 服务器下 bot 错误断句导致发送空消息的问题
- 修改了进化(ext_evolution)扩展执行逻辑，仅允许 bot 部分更新人设
- 修正节流逻辑错误，避免 bot 无法响应消息的问题

### [2023/4/15] v2.1.1 Minecraft 服务器指令优化

- 为 `rg chats` 指令增加了 `-show` 参数，用于显示完整会话键以便 `-target` 参数使用
- 优化 MC 服务器指令执行反馈信息，便于 bot 自主纠错；优化 MC 服务器指令预处理避免 bot 添加多余的转义

### [2023/4/15] v2.1.0 Minecraft 服务器支持

- 增加了 Minecraft 服务器接入支持
- 增加了 Minecraft 服务器指令执行支持和相关扩展模块
- 为绘图扩展增加了代理配置项支持 (感谢 @tonato-01 提供 pr)

### [2023/4/6] v2.0.5 RENAME 指令 | json 导出支持

- 解析消息中的@时保持与用户看到的一致 (感谢 @Misaka-Mikoto-Tech 提供 pr)
- 优化日志输出的 DEBUG_LEVEL 限制 (感谢 @Misaka-Mikoto-Tech 提供 pr)
- 优化聊天消息 prompt 的换行生成逻辑 (感谢 @Misaka-Mikoto-Tech 提供 pr)
- 增加 `rg rename` 改名指令，用于修改人格名 (感谢 @Misaka-Mikoto-Tech 提供 pr) (感谢 @Misaka-Mikoto-Tech 提供 pr)
- 解析消息中的@时保持与用户看到的一致 (感谢 @Misaka-Mikoto-Tech 提供 pr)
- patch logger 使插件名称显示为中文 (感谢 @chenxuan353 提供 pr)
- 添加记忆文件(原.pkl)使用 JSON 读取与保存功能 (与原 pickle 兼容) (感谢 @chenxuan353 提供 pr)
- 优化部分代码类型注解 (感谢 @chenxuan353 提供 pr)
- 搜索扩展(ext_search.py) 优化，禁止 bot 短时间内反复搜索和搜索重复内容

### [2023/3/26] v2.0.4

- 修复 @全体成员 时解析报错问题
- 增加扩展更新人格支持，同时增加了一个 evolution 扩展模块，允许 bot 自主更新人格
- 响应规则中增加一条禁止复读规则

### [2023/3/26] v2.0.3 图片输出支持

- 输出内容转图片: 使用 htmlrender 将 TA 的回复转换为图片，降低风控几率 (可选开关，感谢 @HMScygnet 提供 pr)
- 等待 OpenAI 响应过程中切换人格预设或响应超时后停止处理消息 (感谢 @Misaka-Mikoto-Tech 提供 pr)
- 修正编辑和删除预设判断是否锁定以及是否是默认预设和正在使用的预设的逻辑 (感谢 @Misaka-Mikoto-Tech 提供 pr)
- 增加调用扩展时预检支持打断响应，优化搜索扩展执行效果，避免 bot 自行脑补搜索结果的情况
- 修正一些指令帮助信息的内容错误
- 修正通过指令安装扩展时的编码问题
- 修正纯符号过滤判断逻辑

### [2023/3/21] v2.0.2 扩展下载指令支持

- 切换人格时的聊天输出改为非 DEBUG 模式下也会发送
- 增加了扩展 安装/删除 指令，可直接从 GitHub 上获取到最新扩展
- 精简了非 DEBUG 模式下的控制台输出

### [2023/3/20] v2.0.1 VIOCEVOX 语音扩展

- 修正 `-global` 的控制权限和逻辑 (感谢 [@Misaka-Mikoto-Tech](https://github.com/) 提供 pr)
- 增加了一个新的语音扩展 `ext_VOICEVOX` 能够更便捷地实现本地部署 (感谢 @恋如雨止 提供技术支持)
- 修正回复内容首尾的空行问题；修正短纯符号回复内容未正常过滤的问题
- 修正私聊会话权限设定

### [2023/3/18] v2.0.0 项目重构 🎉

> ❗❗❗ 注意：本次更新需要删除原 bot 记忆文件重新生成(即./data/naturel_gpt 文件夹)，否则可能产生无法预计的错误，同时建议将配置文件一并删除重新生成；此操作会**丢失**所有编辑过的人格预设，如果你需要在更新后继续使用，请使用 `rg query` 查询并保存预设，更新后手动导入！

- 项目完全重构，感谢 [@Misaka-Mikoto-Tech](https://github.com/) 提供的大力支持，几乎重写了所有数据管理和代码逻辑，代码质量提升明显
- 会话人格预设集完全互相独立，每个会话可单独编辑人格互不影响
- 指令表重写，多数指令提供了 `-global` 可选项支持同时编辑所有会话设置和 `-target` 指定会话远程控制操作，新指令表更具完备性，未来可能作为 api 接口搭配前端页面实现插件管理可视化
- `lock` / `unlock` 指令修改为是否启用人格自动切换，lock 后将不会再自动唤醒不活跃人格
- 聊天消息记录改完以会话为单位分割，而不是人格，意味着每个人格都可能看到其他人格的发言信息，上下文语境理解能力增强，如果你开启了解锁人格切换，还可以体验到到"主持会议"的感觉
- 增加聊天所有消息的时间感知
- bot 对用户昵称从 qq 昵称改为群名片昵称，同时增加新成员入群通知的昵称获取
- @消息段解析重置成更合理的逻辑，而不是直接移除@消息段
- 修复 NG_ENABLE_MSG_SPLIT 为 false 的情况下无法正常回复的问题 (感谢 [@HyPerP](https://github.com/) 提供 pr)
- 优化 debug 输出，改为 debug 分级模式，prompt 输出保存到日志中
- 大量细节修改和错误修复

### [2023/3/9] v1.5.3 定时支持

- 从 bot 发送的信息中过滤掉纯符号短信息
- 修复记忆删除指令无法正常工作的 bug
- 增加了一个定时器扩展，并提供了相关支持

### [2023/3/8] v1.5.2 自动切换人格 | 限制解除开关

- 语音扩展增加接口返回 base64 支持
- 修复语音扩展默认启用翻译导致报错的问题
- 为 bot 增加了星期几的时间感知能力
- 增加了一个可选的内容解锁限制开关
- 增加了在 `提及` 时自动切换人格的配置开关

### [2023/3/6] v1.5.1 语音合成接入翻译

- 语音合成扩展提供接入腾讯翻译 api(可选开关) (感谢 [@tonato-01](https://github.com/) 提供 pr)
- 修复部分情况下 bot 回答时会带上自己的人称问题
- 修复插件调用次数限制不生效
- 优化 bot 调用扩展时的分段问题
- 修复记忆管理的编辑指令错误的问题
- 优化记忆强化功能的文本匹配规则

### [2023/3/5] v1.5.0 记忆模块更新

- 增加了 bot 记忆管理能力支持和记忆管理相关指令，允许 bot 主动 记忆/遗忘 信息，并且能自动对记忆信息进行增强以尽可能延长记忆有效时间
- 新增了两个主动记忆管理扩展(记忆和忘却模块，推荐组合使用)
- 根据 GPT3.5 对话模型的特点重写了 prompt 提示，提高 bot 对扩展指令识别率

### [2023/3/3] v1.4.4 邮件扩展

- 修复了修改配置文件目录后无法读取的问题 (感谢 [@he0119](https://github.com/) 提供 pr)
- 将获取响应实现将放入线程池，减少请求超时卡死 (感谢 [@he0119](https://github.com/) 提供 pr)
- 为群聊管理员增加了 bot 的会话管理权限 (感谢 [@HMScygnet](https://github.com/) 提供 pr)
- 优化多段回复预处理，减少了自动续写出后续无关对话的频率
- 调整指令生成匹配正则，略微放宽 bot 调用扩展的规范程度
- 更新代理服务器时将自动补充 http 协议头
- 优化对话提示 prompt，提高回复质量
- 新增了一个发送邮件扩展

### [2023/3/3] v1.4.3

- 禁用了 huggingface 的 tokenizer 的分支化，避免死锁问题

### [2023/3/3] v1.4.2

- 修复 ChatGPT 模型请求时间过长不会 timeout 的问题，提供一个配置项，可自行指定超时时间
- 增加了一个可控制是否记录参考非 bot 相关消息上下文的配置选项
- 为几种常见报错增加了更直观的提示
- 修复了一个扩展模块调用出错的问题
- 调整 prompt，优化 bot 回复质量

### [2023/3/2] v1.4.1

- 修复一个 prompt 描述错误
- 修复一个对话过长死循环卡死的 bug

### [2023/3/2] v1.4.0 ChatGpt 模型更新

> 本次更新后需要更新 OpenAi SDK 至 0.27.0 版本或以上才能使用 ChatGPT 系列模型

- 增加了 ChatGPT 系列模型的支持，并针对其特点优化了 prompt 设置
- 增加自动欢迎新成员可关闭的配置项
- 优化了聊天内容分段输出的逻辑
- 修复了一个聊天单条消息过长导致卡死循环的 bug
- 修复代理服务器配置异常(感谢 @HMScygnet 提供的修复代码)

### [2023/3/1] v1.3.7 勤俭持家 | 代理服务更新

- 优化 prompt 生成，为总结聊天记忆功能增加了可选开关，关闭后可降低约 30%的 token 消耗（经过反馈该功能在较多场景下适用性有限，总体上高成本低回报，故增加了可选关闭，用户印象总结仍然保留开启）
- 增加了扩展模块传递信息，扩展模块可获得原始请求触发信息、回复信息、bot 预设名，便于实现更复杂的扩展需求
- 增加了自动欢迎新入群成员的功能
- 增加代理服务器配置

### [2023/2/25] v1.3.6

- 修复了 `rg set` 指令出错的问题

### [2023/2/24] v1.3.5 黑名单 | 指令更新

- 修复了因唤醒词设置类型不规范问题导致偶发错误的问题
- 修复第一次启动自动创建数据文件夹目录失败的问题
- 为更换人格预设增加了批量操作 `-all` 指令（限管理员可用）
- 增加了 `chats` 指令，用于查看所有会话状态
- 优化 README.md 文档
- 增加了是否开启消息切分多条发送的配置项（默认开启）
- 增加了黑名单功能，在黑名单中的用户消息不会被记录和响应

### [2023/2/20] v1.3.3 扩展 | 多段发送更新

- 优化了不启用扩展模块时 bot 的回复质量，减少虚空调用扩展的情况
- 优化对话生成 prompt，增强了 bot 发送多段聊天的能力
- 增加了 bot 感知当前时间的能力
- 从 bot 的发言记录中将错误的调用指令去除，避免 bot 重复学习错误的扩展指令使用
- 将大多数文本生成的 prompt 改为英文描述，尽量降低部分 tokens 消耗
- 新增了一个表情包扩展模块

### [2023/2/19] v1.3.2

- 修复了 yaml 配置中设置禁用扩展不生效的问题
- 持续优化对话生成 prompt，提高 bot 理解使用扩展的能力
- 为 开启/关闭 会话的指令增加了 `-all` 选项，可一次性 开启/关闭 所有会话

### [2023/2/19] v1.3.1

- 优化扩展模块的参数传递
- 修改了一些扩展插件提示，更便于 bot 理解扩展使用方式

### [2023/2/18] v1.3.0 扩展模块功能更新

- \*扩展支持：增加了插件扩展支持(插件的插件？)，支持使用自然语言自定义扩展更多功能，提供了两个示例扩展
- 多处细节优化

### [2023/2/16] v1.2.0 异步更新

> 本次更新增加了异步能力，功能可能尚不稳定，如要继续使用旧版的记忆文件请做好备份

- 异步更新：bot 的回复生成开始支持异步请求，提高了消息处理速度
- 移除双回车符的停用词限制，优化了 ai 对长文本的输出能力
- 优化错误输出，在 api 请求出错时会在控制台显示错误信息以供排查
- 优化记忆逻辑，bot 在请求文本错误时不会把错误提示信息一并存入记忆

### [2023/2/12] v1.1.6

- 增加切换会话是否启用的开关功能
- 增加了记忆重置功能，可指定重置当前会话的所有人格或特定人格
- 消息拦截响应、消息处理优先级支持自定义配置
- 简化帮助命令输出，分离管理员命令的帮助信息到 `rg admin` 中

### [2023/2/9] v1.1.5 唤醒词 | 屏蔽词功能更新

- 修复未创建对话前调用 bot 指令报错的问题
- 增加自定义触发词唤醒的功能
- 增加自定义屏蔽词拒绝回复的功能
- 增加 bot 随机参与聊天功能，可选择启用
- 优化了手动 `@bot` 时的信息的聊天 prompt 生成逻辑，使 bot 回复更具有指向性
- 优化配置文件管理逻辑，更新后可继续沿用原配置文件，程序加载后会自动补充更新配置文件字段

### [2023/2/6] v1.1.4

> 注意：本次更新需要删除原 bot 记忆文件重新生成(即./data/naturel_gpt 文件夹)，否则可能产生无法预计的错误

- 修复了 bot 记忆串线的问题(多个群组同时使用场景下记忆混乱)
- 优化 bot 生成记忆和印象摘要的逻辑，提高了 bot 回复的速度
- 优化了控制台输出

### [2023/2/5] v1.1.2

- 新增了人格预设的 锁定/解锁 功能，锁定后非管理员无法编辑该预设
- 更新 README 文档
- 优化 rg 命令显示格式
- 微调了 `config.py` 中的一些默认参数
- 修复本插件拦截其它插件响应的问题，降低了本插件的响应优先级
- 更新了交流群信息(见本文档开头)，欢迎各路大佬加入互相学习、一同探讨更新方向、分享更多玩法等

### [2023/2/2] v1.1.1

- 修复查询人格错误的问题

### [2023/2/2] v1.1.0

> 注意：本次更新需要删除原 bot 记忆文件重新生成(即./data/naturel_gpt 文件夹)，否则可能产生无法预计的错误

- 新增了预设编辑功能
- 新增自定义管理员 id 功能，管理员可以删除预设 / 修改锁定的预设
- 增加 debug 开关控制生成文本时的控制台输出（默认关闭）

</details>

## 🤝 贡献列表

感谢以下开发者对本项目做出的贡献

<a href="https://github.com/KroMiose/nonebot_plugin_naturel_gpt/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=KroMiose/nonebot_plugin_naturel_gpt&max=1000" />
</a>

## ⭐ Star 历史

[![Star History Chart](https://api.star-history.com/svg?repos=KroMiose/nonebot_plugin_naturel_gpt&type=Date)](https://star-history.com/#KroMiose/nonebot_plugin_naturel_gpt&Date)
