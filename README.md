# Чайка · закрытый навигатор

GitHub Pages hosts a password gate and encrypted HTML. All chat content is encrypted with AES-256-GCM, using PBKDF2-SHA-256 (600,000 iterations) and a random salt. No plaintext content, password, or encryption key is stored in this repository. Password entry decrypts locally using Web Crypto; reloading locks the page again.

This is shared-password access, not individual user accounts. Anyone with the password can read and copy content. Deploy main branch / root via GitHub Pages. No build step.
