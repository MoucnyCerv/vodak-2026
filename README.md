# Vodák microsite starter

Jednoduchý Quarto projekt pro statickou pozvánku / info balíček na vodáckou akci.

## Jak spustit lokálně

```bash
quarto preview
```

## Jak vyrenderovat

```bash
quarto render
```

Výstup jde do složky `docs/`, takže projekt lze rovnou nasadit přes GitHub Pages z větve `main` a složky `/docs`.

## Co upravit jako první

1. `index.qmd` – texty, termín, trasa, kontakt
2. `styles.css` – barvy a spacing
3. `images/hero.jpg`, `images/foto-1.jpg`, `images/foto-2.jpg`
4. Odkaz na Google Form v `_quarto.yml` a `index.qmd`
