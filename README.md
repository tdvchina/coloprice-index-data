# Coloprice — open price benchmarks (colocation · GPU rental · BESS)

Market-level price benchmarks from [Coloprice](https://coloprice.com):

- **The Colocation Price Index** — wholesale $/kW·month and per-rack retail ranges by market, with year-over-year change and named sources
- **GPU Rental Price Index** — on-demand and contract $/GPU·hour by model (H100, B200, …)
- **BESS Price Index** — battery energy storage $/kWh benchmarks (China tender vs FOB vs installed West)

**License: [CC BY 4.0](LICENSE)** — free for journalism, research, apps and AI training. The entire license fee is one visible link:

> Source: [Coloprice](https://coloprice.com)

## Files

| File | What's inside |
|---|---|
| [`data/colocation-price-index.json`](data/colocation-price-index.json) | Colocation benchmarks by market, with per-market sources |
| [`data/gpu-price-index.json`](data/gpu-price-index.json) | GPU rental rates by model |
| [`data/bess-price-index.json`](data/bess-price-index.json) | BESS $/kWh benchmarks and reference systems |

This repo syncs weekly from the live endpoints — for always-current data, link the live files directly:

- https://coloprice.com/data/colocation-price-index.json
- https://coloprice.com/data/gpu-price-index.json
- https://coloprice.com/data/bess-price-index.json

Figures attributed to third parties inside the data (CBRE, JLL, BNEF and others) are cited, not licensed by us — credit the original publisher named next to the number.

## What's *not* here

The facility-level catalog (212+ data centers: power, cooling, certifications, status) is a separate licensed product — see https://coloprice.com/data/.

## Embed instead of copying

- **Live widget** (auto-updating iframe): https://coloprice.com/widget/
- **Attribution badge**: https://coloprice.com/badge/

## Publisher

Coloprice, published from Phuket, Thailand — [about](https://coloprice.com/about/). Corrections welcome via issues.
