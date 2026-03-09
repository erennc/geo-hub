# llms.txt — Complete Implementation Guide

> `llms.txt` is a standardized file that helps AI engines understand your website, similar to how `robots.txt` helps search engine crawlers.

## What is llms.txt?

A plain text file placed at the root of your website (`/llms.txt`) that provides structured information about your organization, products, and resources in a format optimized for LLM consumption.

## Why It Matters

- AI engines check for `llms.txt` when crawling your site
- Provides structured context that improves citation accuracy
- Reduces hallucination risk about your brand
- Growing adoption across the industry

## Format Specification

```
# Company Name

> One-line description

## About
Company description (2-3 sentences)

## Products
- Product Name: Description

## Key Resources
- Resource: URL
```

## Best Practices

1. **Keep it concise** — Under 500 words
2. **Be factual** — Only include verifiable information
3. **Update regularly** — Keep product info and URLs current
4. **Use plain language** — Avoid marketing speak
5. **Include key URLs** — Docs, blog, API references

## Common Mistakes

- ❌ Too long (over 1000 words)
- ❌ Marketing copy instead of facts
- ❌ Broken URLs
- ❌ Outdated product information
- ❌ Missing contact/support info

## Verification

After deploying, verify:
1. Accessible at `https://yoursite.com/llms.txt`
2. Returns `text/plain` content type
3. No authentication required
4. Not blocked by robots.txt
