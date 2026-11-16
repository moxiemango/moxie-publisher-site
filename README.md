# Moxie Mango Publisher – public pages

Static pages for the **Moxie Mango Publisher**, an internal tool of the Etsy shop
[Moxie Mango Design](https://moxiemangodesign.etsy.com) that publishes the shop's own
listings to its own Pinterest boards and Facebook Page.

Served by GitHub Pages at https://publisher.moxiemango.com/ (custom domain; DNS on Cloudflare: CNAME `publisher` → `moxiemango.github.io`, DNS only).

| File | Purpose |
| --- | --- |
| `index.html` | App website (used in the Pinterest and Meta app settings) |
| `privacy.html` | Privacy policy (used by the Meta app) |
| `moxiemangodesign-privacy.html` | Same privacy policy; URL contains the company name, as Pinterest requires |
| `data-deletion.html` | Data deletion instructions (required by Meta) |
| `callback.html` | Pinterest OAuth redirect – displays the authorization code to copy |

The publisher code itself lives in `moxiemango/printify-pipeline` under `src/social/`.
