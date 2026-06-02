# Free AI API - DeepSeek 🔥

> **免费 DeepSeek AI 接口 · Cloudflare Workers 全球加速 · 无需注册**

[![Cloudflare Workers](https://img.shields.io/badge/Powered%20by-Cloudflare%20Workers-orange)](https://ai-proxy.free-ai-api.workers.dev/)

## 🚀 API 端点

```
https://ai-proxy.free-ai-api.workers.dev/v1/chat/completions
```

## 📦 快速开始

```bash
curl -X POST https://ai-proxy.free-ai-api.workers.dev/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{"model":"deepseek-v4-flash-free","messages":[{"role":"user","content":"Hello"}]}'
```

## 🐍 Python

```python
from openai import OpenAI
client = OpenAI(
    base_url="https://ai-proxy.free-ai-api.workers.dev/v1",
    api_key="not-needed"
)
response = client.chat.completions.create(
    model="deepseek-v4-flash-free",
    messages=[{"role":"user","content":"你好"}]
)
print(response.choices[0].message.content)
```

## 💎 Premium

| 价格 | 权益 |
|------|------|
| 0.0001 BTC（终身） | 无限制请求、优先带宽 |

**BTC:** `1PgS158ZM9RqsBfCjatbrLw7HdmgMoJiXL`

## 📊 模型

| 模型 | 价格 |
|------|------|
| deepseek-v4-flash-free | 免费 |
| deepseek-v4-flash | 免费 |
| deepseek-chat | 免费 |

## 📄 文档

👉 [GitHub Pages 官网](https://jianchuan3.github.io/free-ai-api-deepseek/)

---
⭐ Star 这个仓库以支持我们！
> 🌐 **Official Domain**: [https://free-ai-api.is-a.dev](https://free-ai-api.is-a.dev) (Coming Soon)
