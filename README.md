# 言葉の波 · Kotoba no Nami

**The Great Wave off Kanagawa, reimagined with Japanese words.**

An interactive typographic art piece that reconstructs Hokusai's iconic ukiyo-e masterpiece using hundreds of Japanese words, each pixel-matched to the original's colors.

https://sissifeng.github.io/kotoba-nami/

### Interact
- **Move your cursor** — words ripple apart like water
- **Click anywhere** — send a shockwave through the text
- **Touch devices** supported

### How it works
1. The original woodblock print is sampled pixel-by-pixel
2. Each region gets Japanese words by theme: wave words (波, 海, 潮), sky words (空, 風, 富士), foam words (白, 雪, 光)
3. Word colors are sampled from the source image with contrast enhancement
4. [pretext](https://github.com/chenglou/pretext) measures each word's width for tight typographic packing
5. A spring-physics system drives the mouse interaction

### Tech
- [pretext](https://github.com/chenglou/pretext) — fast, accurate text measurement
- Canvas 2D rendering with devicePixelRatio support
- Spring physics (position + velocity + damping)
- Single HTML file, zero dependencies at runtime

---

言葉の波 — pretext × 神奈川沖浪裏
