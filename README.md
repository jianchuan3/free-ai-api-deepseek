

# 免费 DeepSeek AI API 🇨🇳

> **无需注册 · 国内直连 · 每日500次免费调用 · 兼容OpenAI格式**

## 🚀 快速开始

**无需注册，无需API Key**，直接使用以下端点：

\`\`\`bash
curl -X POST https://devapi.local/v1/chat/completions \
  -H \"Content-Type: application/json\" \
  -d \"{\\"model\\":\\"deepseek-chat\\",\\"messages\\":[{\\"role\\":\\"user\\",\\"content\\":\\"你好\\"}]}\"
\`\`\`

## ✨ 特点

- **零门槛**：无需注册，即拿即用
- **高配额**：每日500次免费调用
- **国内直连**：无需翻墙，低延迟
- **兼容OpenAI**：一行代码切换
- **1M上下文**：超长文本支持

## 📝 Python 示例

\`\`\`python
from openai import OpenAI

client = OpenAI(
    base_url=\"https://devapi.local/v1\",  # 只改这一行
    api_key=\"not-needed\"  # 随便填
)

response = client.chat.completions.create(
    model=\"deepseek-chat\",
    messages=[{\"role\": \"user\", \"content\": \"用Python写一个快排\"}]
)
print(response.choices[0].message.content)
\`\`\`

## 💎 付费模型

| 模型 | 价格 |
|------|------|
| DeepSeek V4 Pro | 0.0001 BTC (终身) |

BTC: \`1PgS158ZM9RqsBfCjatbrLw7HdmgMoJiXL\`

## 📊 可用模型

| 模型 | 说明 | 价格 |
|------|------|------|
| deepseek-chat | DeepSeek Chat (V4 Flash) | 免费 |
| deepseek-coder | 代码专用模型 | 免费 |
| deepseek-v4-pro | 最强推理模型 | 0.0001 BTC |

## 🔗 链接

- 网站: https://devapi.local
- API文档: https://devapi.local/docs
- 问题反馈: 在Issues中提交

---

⭐ 如果觉得有用，请点个Star！
