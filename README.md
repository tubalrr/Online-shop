# Online Shop Template
A polished, responsive online shop template — ready to rebrand and resell.
## Features
- Product grid with category filters and live search
- Add-to-bag cart with slide-in drawer
- PayMongo-ready checkout (GCash / Maya / cards) via payment links — no fake pay buttons
- Copyable order summary (demo fallback when no payment links are configured)
- Light/dark themes, mobile-friendly layout
- Single self-contained index.html, no build step
## Tunay na bayad (PayMongo)
1. Gumawa ng libreng account sa https://www.paymongo.com at i-verify ito.
2. Sa PayMongo dashboard, pumunta sa "Links" at gumawa ng payment link para sa bawat produkto (o fixed amounts). Tandaan: ang bawat link ay para sa eksaktong presyo.
3. Buksan ang index.html, hanapin ang PAYMONGO_PAYMENT_LINKS sa itaas ng file, at i-paste ang iyong mga link.
4. I-upload ulit ang index.html sa repo (o i-deploy).
Kapag walang naka-configure na link, naka-disable ang checkout at malinaw na nakasaad na hindi pa naka-setup ang bayad — walang pekeng payment flow.
## Customize
Palitan ang sample products, prices, store name, at images sa index.html.
## Preview
Buksan ang index.html sa browser, o buksan ang live demo: https://tubalrr.github.io/Online-shop/
