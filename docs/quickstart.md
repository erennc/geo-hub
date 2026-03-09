# GEO Quickstart — From 0 to AI-visible in 1 hour

> Get your website cited by AI search engines with these essential steps.

## Step 1: Create `llms.txt` (10 min)

Create a file at `https://yoursite.com/llms.txt` that describes your site for AI engines.

```
# Your Company Name

> What you do in one sentence.

## About
2-3 sentences about your company and unique value.

## Products
- Product 1: Description
- Product 2: Description

## Key Resources
- Docs: https://yoursite.com/docs
- Blog: https://yoursite.com/blog
```

Use our template: [`/templates/llms.txt`](../templates/llms.txt)

## Step 2: Add Schema.org Markup (15 min)

Add JSON-LD structured data to your key pages:

1. **Organization schema** on your homepage
2. **FAQ schema** on pages with Q&A content
3. **Article schema** on blog posts

Use our templates: [`/templates`](../templates/)

## Step 3: Audit Your robots.txt (5 min)

Make sure AI crawlers can access your content:

```
# Allow AI crawlers
User-agent: GPTBot
Allow: /

User-agent: ChatGPT-User
Allow: /

User-agent: Claude-Web
Allow: /

User-agent: PerplexityBot
Allow: /

User-agent: Google-Extended
Allow: /
```

## Step 4: Add Authority Signals (20 min)

Review your key pages and add:

- **Statistics** with sources (e.g., "According to [Study], X increased by Y%")
- **Expert quotes** with attribution
- **Citations** to authoritative sources
- **Last updated dates** on all content

## Step 5: Verify (10 min)

1. Run `geo-audit https://yoursite.com` to check your score
2. Ask ChatGPT, Perplexity, or Claude about your brand/product
3. Track mentions with monitoring tools from our [Awesome List](../README.md#awesome-list)

## Next Steps

- Read the full [Authority Signals Guide](./authority.md)
- Implement [Schema.org best practices](./schema.md)
- Set up ongoing [metrics tracking](./metrics.md)
