<p align="center">
  <a href="https://joblessjoe.com"><img src="assets/banner.png" alt="hello world — Johannes Tebbert · Freiburg · joblessjoe.com" width="100%"></a>
</p>

<p align="center">
  <a href="https://joblessjoe.com"><img src="https://img.shields.io/badge/website-joblessjoe.com-38cabb" alt="joblessjoe.com"></a>
  <a href="https://findig.app"><img src="https://img.shields.io/badge/product-findig.app-8b5cf6" alt="findig.app"></a>
  <a href="https://itsjoblessjoe.etsy.com"><img src="https://img.shields.io/badge/shop-itsJoblessJoe%20on%20Etsy-f1641e" alt="itsJoblessJoe on Etsy"></a>
  <a href="https://www.npmjs.com/~joblessjoe"><img src="https://img.shields.io/badge/npm-~joblessjoe-cb3837" alt="npm packages"></a>
  <a href="mailto:info@joblessjoe.com"><img src="https://img.shields.io/badge/mail-info%40joblessjoe.com-555" alt="info@joblessjoe.com"></a>
</p>

I'm **Johannes Tebbert**, an independent developer in Freiburg. I run a small handmade and
3D-printed shop, and I write the software I need along the way: an inventory & profit tool
for Etsy sellers, browser add-ons, and plugins for AI coding agents running on local LLMs.
Everything I build, I use daily first.

---

## Findig — inventory & profit software for Etsy sellers

<a href="https://findig.app"><img src="assets/findig-orders.jpg" alt="The Findig orders page: open Etsy orders as cards with ship-by date, items, price and profit after fees" width="100%"></a>

I ran an Etsy shop, got overwhelmed, and built the tool I wished existed. Findig syncs Etsy
orders and listings on its own, tracks every variation down to the material, warns before
stock runs out, and shows the profit that's actually left after fees.

**[findig.app](https://findig.app)** · [the story](https://joblessjoe.com/findig)

<sub>Node · Express · PostgreSQL · Stripe · Docker — self-hosted behind Caddy and a Cloudflare tunnel, with a warm failover box.</sub>

## Open source

Plugins for **Claude Code** and **[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)** (dsh), built for my own
local-LLM setup (Ollama on a Tesla P40). All MIT, zero runtime dependencies.

| Project | What it does |
|---|---|
| **[local&#8209;llm&#8209;worker](https://github.com/JoblessJoe/local-llm-worker)** <br><sub>Claude Code plugin · MCP server</sub><br>[![npm](https://img.shields.io/npm/dw/local-llm-worker?label=npm&color=38cabb)](https://www.npmjs.com/package/local-llm-worker) | Hands the bulk reading — test logs, big files, web pages — to your local LLM, so Claude only gets the answer. ~19,100 tokens read locally, ~130 sent to Claude. |
| **[smart&#8209;compaction](https://github.com/JoblessJoe/smart-compaction)** <br><sub>dsh plugin</sub><br>[![npm](https://img.shields.io/npm/dw/smart-compaction?label=npm&color=38cabb)](https://www.npmjs.com/package/smart-compaction) | Lets the model compact its own context at a safe point, instead of being cut off mid-task. |
| **[dsh&#8209;vitals](https://github.com/JoblessJoe/dsh-vitals)** <br><sub>dsh plugin</sub><br>[![npm](https://img.shields.io/npm/dw/dsh-vitals?label=npm&color=38cabb)](https://www.npmjs.com/package/dsh-vitals) | Live CPU, memory, temperature and GPU load, btop-style, inside the dsh web UI. |
| **[kitchenowl&#8209;extension](https://github.com/JoblessJoe/kitchenowl-extension)** <br><sub>Firefox add-on</sub><br>[![Firefox](https://img.shields.io/badge/Firefox-add--on-ff7139)](https://addons.mozilla.org/firefox/addon/kitchenowl-unofficial/) | One click saves the recipe you're looking at into your self-hosted KitchenOwl. |

<sub>Listed on [awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) and the [official MCP Registry](https://registry.modelcontextprotocol.io). Project pages: [joblessjoe.com/software](https://joblessjoe.com/software)</sub>

## Handmade

<p>
  <a href="https://itsjoblessjoe.etsy.com"><img src="assets/shop-1.jpg" alt="Three spiky fidget balls in blue, purple and yellow" width="32%"></a>
  <a href="https://itsjoblessjoe.etsy.com"><img src="assets/shop-2.jpg" alt="A green 3D-printed dinosaur valve cap on a bicycle wheel" width="32%"></a>
  <a href="https://itsjoblessjoe.etsy.com"><img src="assets/shop-3.jpg" alt="A green wall-mounted soap holder with a leaf design" width="32%"></a>
</p>

Handmade & 3D-printed things, made in small batches in Freiburg — on
**[Etsy as itsJoblessJoe](https://itsjoblessjoe.etsy.com)** and on
[eBay](https://www.ebay.de/sch/i.html?_ssn=joblessjoe). The shop is also Findig's proving ground.
More in the [gallery](https://joblessjoe.com/gallery).

---

<p align="center"><sub><a href="https://joblessjoe.com">joblessjoe.com</a> · small software and handmade things from Freiburg</sub></p>
