# Interactive Research Preview

Password-protected interactive manuscript companion: **[https://lc82111.github.io/rt-motion-tsfm/](https://lc82111.github.io/rt-motion-tsfm/)**

All site content, interactive modules, benchmark summaries, and figures are encrypted at rest using **PBKDF2-HMAC-SHA256** (200,000 iterations, random 128-bit salt) and **AES-256-GCM** authenticated encryption, and decrypted client-side via the W3C Web Crypto API (`crypto.subtle`).
