# BTI Junk Removal website

One-page phone site for BTI Junk Removal, Tucson AZ. Static files only, no server, no database.

Leads arrive as a text message on 520-486-6490: the quote builder opens the customer's Messages app with their job, size, timing and location filled in, and they attach a photo.

## Deploy
Cloudflare Workers, imported from this GitHub repo. Static assets are served from `public/`.

## Edit prices
All prices are plain text in `public/index.html` (search for `$`).
