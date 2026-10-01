# Money Internals — tools

The interactive pages used in [Money Internals](https://www.youtube.com/@MoneyInternals) videos, served at [moneyinternals.com](https://moneyinternals.com) via GitHub Pages.

Every page is **frozen as broadcast**: it's the exact build that appeared in the video, so links in old video descriptions keep matching what viewers saw. A page is only added or changed here deliberately, when an episode publishes.

## What's here

| Path | What it is | Series |
|---|---|---|
| [`/`](https://moneyinternals.com/) | Index of every tool | — |
| [`/orderbook/`](https://moneyinternals.com/orderbook/) | Series index — one order book terminal per episode | Build an Exchange |
| [`/orderbook/ep01-order-book/`](https://moneyinternals.com/orderbook/ep01-order-book/) | How every market price is made | Build an Exchange · 01 |
| [`/orderbook/ep02-market-vs-limit/`](https://moneyinternals.com/orderbook/ep02-market-vs-limit/) | Market vs limit orders | Build an Exchange · 02 |
| [`/orderbook/ep03-price-time-priority/`](https://moneyinternals.com/orderbook/ep03-price-time-priority/) | Price-time priority and partial fills | Build an Exchange · 03 |
| [`/pension/`](https://moneyinternals.com/pension/) | Series index — one page per episode | Pension series |
| [`/pension/ep01-compounding/`](https://moneyinternals.com/pension/ep01-compounding/) | Why a UK pension doubles before it grows | Pension series · 01 |
| [`/pension/ep02-100k-trap/`](https://moneyinternals.com/pension/ep02-100k-trap/) | The £100k personal allowance taper | Pension series · 02 |
| [`/pension/ep03-pension-relief/`](https://moneyinternals.com/pension/ep03-pension-relief/) | Higher-rate relief nobody claims | Pension series · 03 |
| [`/book-to-bill/`](https://moneyinternals.com/book-to-bill/) | The order queue — why revenue stops at capacity | Market Mechanics |
| [`/pension-vs-isa/`](https://moneyinternals.com/pension-vs-isa/) | Pension vs ISA — the same £1,000, two jars | UK Money Mechanics |
| [`/mortgage-split/`](https://moneyinternals.com/mortgage-split/) | Your first mortgage payment — where the £1,461 goes | UK Money Mechanics |

`/pension/ep03-relief-at-source/` is a redirect to `/pension/ep03-pension-relief/`, kept so an older link keeps working.

## How pages are built

Every page is a single self-contained HTML file: no build step, no server, no tracking. The only external requests are Google Fonts. Open any `index.html` directly in a browser and it works.

The order book pages come from the open-source matching engine at [`mini-exchange`](https://github.com/MoneyInternals/mini-exchange). Each episode's page matches a tagged release there (`ep01-order-book`, `ep02-market-vs-limit`, `ep03-price-time-priority`), so you can read the exact code each episode ran on.

Tax figures on the UK pages are stamped with the tax year they were built for and are not updated afterwards. Each page is a record of an episode, not a maintained calculator.

## Disclaimer

Everything here is education, not financial advice. For decisions about your own money, speak to a regulated adviser.

## Licence

MIT — see [LICENSE](LICENSE).
