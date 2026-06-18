# Lara Painting Pro — marketing site

Single-page lead-gen site for Lara Painting Pro LLC (Las Vegas painting contractor).
Static HTML served by nginx, deployed on Coolify.

- **Demo URL:** https://larapainting.revenuebeacon.com
- **Source of truth for design/spec:** `~/Desktop/lara-painting-pro/` (SPEC.md, design-preview.html, logo-options.html)
- Phone: (702) 931-7005 (real — matches Google Business Profile NAP). Goal: phone calls + estimate-form leads. No accounts/auth.

## Deploy
Push to `main` → Coolify (Dockerfile build pack) rebuilds the nginx image and serves `index.html`.

## TODO before client handoff
- Real project photos (swap the CSS placeholder gallery tiles)
- NV contractor license # in footer (currently "pending")
- Wire the estimate form to a real destination (Resend email / SMS) + set up `info@larapaintingpro.com`
- Point final domain (larapaintingpro.com) at this app once sold
