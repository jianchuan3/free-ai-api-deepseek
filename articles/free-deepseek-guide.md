# 白嫖党的胜利：免费 DeepSeek AI API 实测

## 免费，无需注册
每天 50 次请求，兼容 OpenAI SDK，国内直连。

```bash
curl -X POST https://ai-proxy.free-ai-api.workers.dev/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{"model":"deepseek-v4-flash-free","messages":[{"role":"user","content":"你好"}]}'
```

## 为什么用 Cloudflare Workers？
- 全球 CDN 加速，延迟极低
- 免费计划每天 10 万次请求
- 无需管理服务器

## 升级 Premium
不够用？0.0001 BTC 终身无限使用。
BTC: `1PgS158ZM9RqsBfCjatbrLw7HdmgMoJiXL`

👉 https://jianchuan3.github.io/free-ai-api-deepseek/
