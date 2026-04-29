# 🤖 01 — llms.txt

> `llms.txt` is a Markdown file placed at the root of your website (`/llms.txt`) that helps Large Language Models understand your site's structure, purpose, and key content. It functions like `robots.txt` — but for AI.

---

## What is llms.txt?

Proposed by [Answer.AI](https://llmstxt.org), the `llms.txt` standard provides:
- A human-readable overview of your site
- Links to your most important pages in clean Markdown
- Instructions for how AI models should treat your content

### Example `llms.txt`

```markdown
# My Company Name

> We build SEO tools for developers and content marketers.

## Documentation
- [Getting Started](https://example.com/docs/start): Quick setup guide
- [API Reference](https://example.com/docs/api): Full API docs

## Blog
- [How to rank in AI search](https://example.com/blog/ai-seo): Our top article
```

---

## Checklist

### ✅ File Creation
- [ ] `/llms.txt` exists at the root of your domain
- [ ] `/llms-full.txt` exists with full plain-text content of key pages
- [ ] File uses proper Markdown formatting (H1 title, blockquote tagline, H2 sections)
- [ ] File is publicly accessible (not blocked by auth or robots)

### ✅ Content Quality
- [ ] H1 matches your site/brand name exactly
- [ ] Tagline (blockquote `>`) accurately summarizes your site in 1–2 sentences
- [ ] Every link is absolute (includes full `https://` URL)
- [ ] Each link has a short, descriptive label
- [ ] Most important content is listed first
- [ ] Outdated or irrelevant pages are excluded

### ✅ Technical
- [ ] File served with `Content-Type: text/plain` or `text/markdown`
- [ ] File is UTF-8 encoded
- [ ] File is under 100KB (use `llms-full.txt` for large content)
- [ ] Validated with an llms.txt linter or inspector

### ✅ Maintenance
- [ ] File is updated when major pages are added or removed
- [ ] Version or date stamp included (optional but recommended)

---

## Tools

| Tool | Purpose |
|------|---------|
| [llmstxt.org](https://llmstxt.org) | Official spec |
| [llms-txt-inspector](https://github.com/ikoanti/llms-txt-inspector) | Audit your llms.txt |
| [llms.txt generator](https://llmstxt.firecrawl.dev) | Auto-generate from sitemap |

---

## References
- [llmstxt.org Official Spec](https://llmstxt.org)
- [Answer.AI Blog Post](https://www.answer.ai/posts/2024-09-03-llms-txt.html)
