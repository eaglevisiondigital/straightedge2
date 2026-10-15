# Straight Edge Property Services

Premium responsive website based on the owner-approved homepage mockup. Repository: `eaglevisiondigital/straightedge2`.

## Approved design and images

The file `reference/approved-homepage.png` is the visual contract. The supplied approved source photographs were encoded as optimized WebP derivatives without replacing the image content. `reference/approved-logo-original.png` preserves the supplied logo artwork, and `assets/straightedge-logo-header.png` is a transparency-adjusted header rendering of the supplied logo geometry.

## Deployment

Static HTML/CSS/JS. Netlify publish directory: `.` and no build command. The estimate form uses Netlify Forms, so **submission must be tested on the real Netlify deploy**, not from a local filesystem or non-Netlify preview. Configure form notifications in Netlify to deliver requests to the business owner. No domain needed for initial deployment.

## Local preview

`python3 -m http.server 8080` then open `http://localhost:8080`.

## Outstanding verification

Compare real hosted screenshots at 1440, 1024, 768, 390, and 320px against the design. Validate successful Netlify form submission and notifications on hosted site. Replace example gallery text only when genuine Cody project photos are available. The mockup mentions a 2024 copyright; website uses current year dynamically.
