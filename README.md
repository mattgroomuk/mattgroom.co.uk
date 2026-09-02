# mattgroom.co.uk

Static personal website hosted by GitHub Pages from the root of the `main` branch.

## Published routes

- `https://www.mattgroom.co.uk/` - minimal image-led homepage
- `https://www.mattgroom.co.uk/cv/` - public HTML CV with A4 and mobile-friendly PDF downloads
- `/cvmmg677/` - unlinked CV theme studio for private editing (obscured, not authenticated)

The downloadable PDFs are committed alongside the public CV:

- `cv/Matt-Groom-CV-A4.pdf`
- `cv/Matt-Groom-CV-Mobile.pdf`

The site has no build step or server-side runtime. GitHub Pages serves the committed files directly.

## Domain configuration

The root `CNAME` file preserves the configured GitHub Pages custom domain: `www.mattgroom.co.uk`.

DNS is managed separately. Microsoft 365 mail-related DNS records are outside the scope of this repository and must not be changed as part of website deployment.
