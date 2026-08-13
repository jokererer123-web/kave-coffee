## gstack (recommended)

This project uses [gstack](https://github.com/garrytan/gstack) for AI-assisted workflows.
Install it for the best experience:

```bash
git clone --depth 1 https://github.com/garrytan/gstack.git ~/.claude/skills/gstack
cd ~/.claude/skills/gstack && ./setup --team
```

Skills like /qa, /ship, /review, /investigate, and /browse become available after install.
Use /browse for all web browsing. Use ~/.claude/skills/gstack/... for gstack file paths.

## Project: KAVÉ Coffee & Roastery
Derlemesiz statik site — tek `index.html` + `images/*.jpg` (AI-üretimi, optimize).
Önizleme: `python3 -m http.server 8000` → http://localhost:8000
Canlı (GitHub Pages): https://jokererer123-web.github.io/kave-coffee/
Stil kuralı: `<style>` içindeki özel CSS gerçek kaynaktır; Tailwind CDN yalnızca isteğe
bağlı iyileştirmedir (çevrimdışı dayanıklılık için kritik stilleri Tailwind'e taşıma).
Palet: #140A06/#2C1A14 kahve + #D9B88F/#C79A5B altın. Fontlar: Playfair Display + Manrope.
Ürün verileri `PRODUCTS` dizisinde (JS) — menü değişikliği oradan yapılır.
