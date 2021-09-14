# Chatopera 对话模板

本源码库提供多个 **对话模板** 项目，基于这些项目，您可以：

- 快速掌握 Chatopera 对话机器人开发，实现智能问答，智能客服等应用；
  以对话模板为脚手架，学习最佳实践，开发多轮对话；

- 快速掌握 Chatopera 机器人的系统集成。

## 开始阅读前，请完成

[新手任务：使用入门教程一步步实现智能对话机器人](https://docs.chatopera.com/products/chatbot-platform/tutorials/index.html)

## 模板目录

| 程序             | 语言  | 位置                                                              | 功能                                                                                                                       |
| ---------------- | ----- | ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| FeishuWeatherBot | zh_CN | [projects/FeishuWeatherBot](./projects/FeishuWeatherBot)          | [Chatopera 飞书应用](https://chatopera.feishu.cn/docs/doccnnLcv5AuenV1HHSvgVWbJmd)示例程序，一个能回答天气情况的飞书机器人 |
| GuessNumber      | en_US | [projects/GuessNumber](./projects/GuessNumber)                    | 小游戏， Guess the secret number in the bot's hat.                                                                         |
| 预定机票         | zh_CN | [projects/预定机票](./projects/预定机票)                          | 预约飞机票，查询天气                                                                                                                   |
| 招聘面试         | zh_CN | [projects/招聘面试](./projects/招聘面试)                          | 进行工作面试：提问技能知识、评估性格和心理素质，发送邮件报告面试过程。                                                     |
| 小笑话           | zh_CN | [projects/小笑话](./projects/小笑话)                              | 发送“笑话”，机器人返回一个笑话，逗您一乐。                                                                                 |

查看[所有模板](./projects)。

**对话模板**目录结构

```
.
├── README.md                  # 模板描述文件
├── bot.dicts.json             # 词典导入文件，包括引用词典、词汇表词典和正则表达式词典
├── bot.faqs.json              # 知识库导入文件，包括标准问、扩展问、分类等
├── bot.intents.json           # 意图识别导入文件，包含意图、说法、槽位等
├── bot.conversations.c66      # 多轮对话导入文件，包含脚本、函数等
├── flow.mdj                   # UML 对话流程文件，描述对话流程
└── flow.xlsx                  # Excel 话术文件，描述对话流程
```

## 使用 CLI 导入

[https://docs.chatopera.com/products/chatbot-platform/howto-guides/cli-export-import.html](https://docs.chatopera.com/products/chatbot-platform/howto-guides/cli-export-import.html)

## 系统集成

[https://docs.chatopera.com/products/chatbot-platform/howto-guides/index.html](https://docs.chatopera.com/products/chatbot-platform/howto-guides/index.html#%E5%8F%91%E5%B8%83%E6%9C%BA%E5%99%A8%E4%BA%BA)


## 技术支持

[帮助](https://docs.chatopera.com/products/chatbot-platform/index.html#%E5%B8%AE%E5%8A%A9)

# LICENSE

[Apache 2.0](./LICENSE)

[![chatoper banner][co-banner-image]][co-url]

[co-banner-image]: ./assets/8.png
[co-url]: https://www.chatopera.com
