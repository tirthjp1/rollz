# Rollz Ice Cream Vancouver — rollzyvr.com

Jekyll site for the Rollz Ice Cream Vancouver franchise, hosted on GitHub Pages.

## Quick Guide: How to Update Your Site

### Add a New Blog Post / Promotion
1. Create a new file in `_posts/` named `YYYY-MM-DD-your-title.md`
2. Add front matter at the top:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD
   categories: news flavors
   description: "Short description for Google search results"
   ---
   ```
3. Write your content in Markdown below the front matter
4. Commit and push — the site updates automatically

### Update Menu
Edit `menu.md` — add or remove items, update descriptions.

### Update Store Hours / Contact Info
Edit `_config.yml` — change `hours`, `phone`, `email`, `address`.

### Update Clover Links
Edit `_config.yml` — change `clover_order_url` and `gift_card_url`.

### Add Images
Drop images into `assets/images/` and reference them as `/assets/images/filename.png`.

## Important URLs in _config.yml
- `clover_order_url` — Your Clover online ordering link
- `gift_card_url` — Your Clover gift card purchase link
- `google_analytics` — Your GA4 tracking ID
- `instagram_url` — Your Instagram profile

## Structure
- `_posts/` — Blog posts and promotions
- `_config.yml` — Site settings, links, SEO
- `menu.md` — Full menu
- `order.md` — Online ordering page
- `gift-cards.md` — Gift card purchase page
- `qr/` — QR code redirect pages (Instagram, menu PDF)
