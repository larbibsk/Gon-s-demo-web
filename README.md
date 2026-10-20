# Gon's Chicken menu

## Run locally

Open `menu.html` directly, or serve the `outputs` folder:

```bash
cd outputs
python -m http.server 8000
```

Visit http://localhost:8000/menu.html. The cart is persisted in browser `localStorage`; menu images are loaded from `assets/`.

## Deploy to Netlify

1. Create a Netlify site with **Deploy manually**, or connect the repository.
2. Set the publish directory to `outputs` and leave the build command empty.
3. Deploy. `menu.html` is the entry page; rename it to `index.html` if you want the root URL to open it directly.

WhatsApp checkout, the local Instagram gallery, Google Maps, Instagram, and Glovo links are included. The WhatsApp order form only asks for a table name/number and sends selected item quantities. Google Maps uses the supplied short link; no restaurant photos were invented from Maps because it did not expose downloadable images. Update the WhatsApp number in `menu.html` if needed.
