# Schema.org for GEO — Which Types Matter

> Structured data helps AI engines understand your content. Here's what to implement and why.

## Priority Schema Types for GEO

### 1. FAQPage (High Priority)
AI engines frequently pull from FAQ-structured content.

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [{
    "@type": "Question",
    "name": "Your question?",
    "acceptedAnswer": {
      "@type": "Answer",
      "text": "Your answer."
    }
  }]
}
```

### 2. Organization (High Priority)
Establishes brand identity and authority.

### 3. Article / BlogPosting (Medium Priority)
Helps AI engines understand content authorship and freshness.

### 4. Product (Medium Priority)
Critical for e-commerce GEO.

### 5. HowTo (Medium Priority)
Step-by-step content that AI engines love to cite.

## Implementation Tips

1. Place JSON-LD in `<head>` section
2. Validate with Google's Rich Results Test
3. One schema type per page (primary), multiple allowed
4. Keep `description` fields concise and factual
