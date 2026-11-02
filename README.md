# AI image generation cost index — list price per image (2026)

[![Seedream 5.0 price](https://aiapi-pro.com/badge/seedream-5-0.svg?v=2)](https://aiapi-pro.com/chinese-ai-api-pricing)

`/badge` serves a one-line SVG for any of the 111 models — [embed one](https://aiapi-pro.com/badge).

**Full table:** all 111 Chinese models with list prices in one page — [Chinese AI API pricing comparison](https://aiapi-pro.com/chinese-ai-api-pricing)

Eleven image models, list prices in USD, checked **2026-10-30**. Cost per 1,000 images is included because that is the number a real batch is budgeted in.

| Model | Per image | 1,000 images | Images per $10 |
|---|---|---|---|
| Wan 2.2 T2I Flash | $0.0215 | **$22** | 465 |
| WAND Vega Image Lite | $0.0250 | $25 | 400 |
| Seedream 5.0 | $0.0270 | $27 | 370 |
| Vidu Image Q2 | $0.0290 | $29 | 345 |
| Wan 2.5 T2I Preview | $0.0308 | $31 | 325 |
| Hunyuan Image 3.0 | $0.0310 | $31 | 323 |
| Seedream v5.0 Lite (TokenHub) | $0.0340 | $34 | 294 |
| Seedream 5.0 Pro | $0.0340 | $34 | 294 |
| Seedream v5.0 Pro (TokenHub) | $0.0460 | $46 | 217 |
| WAND Vega Image Flash | $0.0690 | $69 | 145 |
| WAND Vega Image Pro | $0.1460 | **$146** | 68 |

**Spread: 6.8x** between the cheapest and most expensive model for the same unit — a single image.

## Three things that change the real bill

1. **Billing unit is per image, not per megapixel.** On most of these rows a 4K render costs the same as a 1K one. Check the model page before assuming a resolution surcharge.
2. **Reject rate is the hidden multiplier.** A 30% discard rate means 1.4 generations per usable image. Budget **1.4x** the table.
3. **The cheapest model is not the cheapest pipeline.** If a model needs more retries for a usable result, the nominal price difference disappears. Measure your own hit rate per model before switching.

## Worked example

1,000 usable images at a 30% reject rate = 1,400 generations:

- cheapest tier: 1,400 × $0.0215 = **$30**
- most expensive: 1,400 × $0.146 = **$204**

That is a 6.8x budget range for the same deliverable — decided entirely by model choice.

## Free options

CogView3-Flash and GLM-4.1V-Thinking-Flash are $0 on NovAI's free tier (10 free-model calls/day, no card). Useful for wiring up a pipeline before paying for anything.

## Tools

- Interactive image cost calculator: https://aiapi-pro.com/image-cost-calculator
- Video equivalent: https://github.com/vvvvking/ai-video-cost-index
- Live price feed for 111 Chinese models: https://github.com/vvvvking/chinese-ai-api-prices
- Sourced HTML table: https://aiapi-pro.com/image-cost-2026

Maintained by [NovAI](https://aiapi-pro.com), an OpenAI-compatible gateway for Chinese AI models at provider list price, 0% platform fee.

_No affiliate links. Model names and prices belong to their respective providers._
