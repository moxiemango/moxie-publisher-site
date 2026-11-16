# Moxie Mango Publisher – public pages

Static pages for the **Moxie Mango Publisher**, an internal tool of the Etsy shop
[Moxie Mango Design](https://moxiemangodesign.etsy.com) that publishes the shop's own
listings to its own Pinterest boards and Facebook Page.

Served by GitHub Pages: https://moxiemango.github.io/moxie-publisher-site/

| File | Purpose |
| --- | --- |
| `index.html` | App website (used in the Pinterest and Meta app settings) |
| `privacy.html` | Privacy policy (required by Pinterest and Meta) |
| `data-deletion.html` | Data deletion instructions (required by Meta) |
| `callback.html` | Pinterest OAuth redirect – displays the authorization code to copy |

The publisher code itself lives in `moxiemango/printify-pipeline` under `src/social/`.
