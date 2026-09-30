# ERICA AI V19 — Password Recovery robust

V19 keeps the V18 app and adds a more robust Supabase recovery bootstrap for GitHub Pages, including explicit PKCE `code` exchange and early `PASSWORD_RECOVERY` listener registration.

Deploy by replacing only `index.html` in the existing `ERICA-AI` GitHub repository.

After deployment, request a NEW password reset email and use the newest link. Do not reuse an older reset link.

Supabase URL configuration should include:
- Site URL: https://ericabloisefit-star.github.io/ERICA-AI/
- Redirect URL: https://ericabloisefit-star.github.io/ERICA-AI/
