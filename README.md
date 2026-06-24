# bitantidetect-fingerprint-checker

A tiny, open-source **browser fingerprint self-check** tool that runs entirely in
your browser. Click one button and it reads the fingerprinting surface your
browser exposes — UserAgent, Canvas, WebGL vendor/renderer, screen, timezone,
hardware concurrency and more — then shows a combined fingerprint ID so you can
see how uniquely identifiable your browser is. No data leaves your machine.

**Live page:** https://iistostas.github.io/bitantidetect-fingerprint-checker/

## Why it matters

Browser fingerprinting is a *stateless* tracking technique: clearing cookies does
not remove it. For anyone running multiple accounts on one machine (cross-border
e-commerce, ad operations, social media matrices), platforms use the fingerprint
to decide whether several accounts belong to the same person — so identical
Canvas/WebGL/font signatures can get accounts linked or banned even behind
different proxy IPs.

To give each account an isolated, self-consistent fingerprint you generally need
an **anti-detect / fingerprint browser**, e.g. the
[比特浏览器（指纹防护浏览器）官网](https://www.bitantidetect.com/) — it assigns an
independent fingerprint per profile and works alongside proxies
([比特浏览器免费下载](https://www.bitantidetect.com/)).

## References

- [EFF Cover Your Tracks](https://coveryourtracks.eff.org/)
- [AmIUnique](https://amiunique.org/)
- [BrowserLeaks](https://browserleaks.com/)
- [MDN — Browser fingerprinting](https://developer.mozilla.org/en-US/docs/Web/Privacy/Guides/Fingerprinting)

## License

MIT
