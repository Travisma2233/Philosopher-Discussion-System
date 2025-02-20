# 🤖 哲学家对话系统 | Philosopher Discussion System

一个基于大语言模型的多轮哲学对话系统，模拟了三位伟大哲学家之间的深度思想交流。
A multi-round philosophical discussion system based on LLMs, simulating deep intellectual exchanges between three great philosophers.

![幻灯片2](https://github.com/user-attachments/assets/56202129-b04f-410c-ad3c-1c9e7ee6935b)
----------------------------------------------------------------------------------------------
![幻灯片1](https://github.com/user-attachments/assets/9410f6d6-eeb9-48fb-aa0a-d72ee371bd40)
----------------------------------------------------------------------------------------------








## ✨ 特色功能 | Features

- 🎯 支持自动/手动选择哲学问题 | Support automatic/manual selection of philosophical questions
- 🗣️ 模拟三位哲学家的多轮对话 | Multi-round dialogue between three philosophers:
  - 亚里士多德 | Aristotle
  - 孔子 | Confucius
  - 康德 | Kant
- 👨‍⚖️ 智能裁判系统引导讨论深入 | AI judge system guides deeper discussions
- 📝 自动生成学术总结文章 | Auto-generate academic summary
- 📄 输出Word文档和JSON数据 | Export to Word and JSON formats

## 🛠️ 安装要求 | Requirements

- Python 3.7+
- 稳定的网络连接 | Stable network connection
- 代理服务器（用于API访问）| Proxy server (for API access)

## 📦 依赖安装 | Installation

```bash
pip install requests python-docx
```

## ⚙️ 配置说明 | Configuration

1. 项目文件结构 | Project structure:
```
philosopher_discussion/
├── prompts/
│   ├── aristotle.txt
│   ├── confucius.txt
│   ├── kant.txt
│   └── judge.txt
├── fixed_simple_question.json
├── philosopher_discussion_openai.py
└── README.md
```

2. 代理配置 | Proxy configuration:
```python
proxies = {
    'http': 'http://127.0.0.1:7890',
    'https': 'http://127.0.0.1:7890'
}
```

## 🚀 使用方法 | Usage

1. 运行程序 | Run the program:
```bash
python philosopher_discussion_openai.py
```

2. 选择问题来源 | Choose question source:
   - 1️⃣ 从问题库随机选择 | Random selection from question bank
   - 2️⃣ 手动输入问题 | Manual input

3. 等待系统自动 | Wait for the system to:
   - 🔄 进行多轮哲学讨论 | Conduct multi-round discussions
   - 📊 生成总结文章 | Generate summary article
   - 📎 创建Word文档 | Create Word document
   - 💾 保存JSON数据 | Save JSON data

## 📂 输出文件 | Output Files

所有文件保存在 `discussion_records` 目录 | All files are saved in `discussion_records` directory:
- 📝 `{topic}_{timestamp}.docx`: Word文档 | Word document
- 📊 `{topic}_{timestamp}.json`: JSON数据 | JSON data
- 📄 `{topic}_{timestamp}.txt`: 备份文本 | Backup text file

## 🔍 技术细节 | Technical Details

- 🤖 讨论使用 OpenAI GPT-4
- 📝 总结使用 DeepSeek-R1
- 🈺 支持中英文交互 | Supports Chinese and English interaction
- 💫 实时保存讨论记录 | Real-time discussion saving

## ⚠️ 注意事项 | Notes

1. 确保API密钥有效 | Ensure API key is valid
2. 检查网络连接 | Check network connection
3. 确认代理服务器运行 | Verify proxy server is running
4. 系统需安装微软雅黑字体 | System needs Microsoft YaHei font

## 🐛 问题反馈 | Issues

如有问题请访问 | Please visit for issues:
[GitHub Issues](https://github.com/travisma2233/philosopher_discussion/issues)

## 📜 许可证 | License

MIT License



## 👨‍💻 作者 | Author

[travisma2233](https://github.com/travisma2233)

---

如果这个项目对你有帮助，请给个 Star ⭐️
If this project helps you, please give it a Star ⭐️
