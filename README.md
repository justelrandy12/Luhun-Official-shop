**Shoes**
```bash
curl.exe -sL "https://luhun.store/collections/size-10/products.json?limit=250" -o col-size-10.json
# Repeat for: kids-sneakers, size-7 … size-14 (see scripts/import-shoes.mjs)
node scripts/import-shoes.mjs
```
**Clothing**
```bash
curl.exe -sL "https://luhun.store/collections/t-shirts/products.json?limit=250" -o col-t-shirts.json
node scripts/import-clothing.mjs
```
---
## Store location
**3373 Princeton Rd Suite 131**  
Hamilton, Ohio 45011
---
## Tech stack
- HTML, CSS, JavaScript (ES modules)
- No build step — static files only
- Product data imported from Shopify collection JSON
Checkout is demo-only; connect Shopify or Stripe for live payments in production.
---
## License
All rights reserved.
