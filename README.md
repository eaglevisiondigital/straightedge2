# Straight Edge Property Services

Premium responsive website based on the owner-approved homepage mockup. Repository: `eaglevisiondigital/straightedge2`.

## Approved design and images

The file `reference/approved-homepage.png` is the visual contract. The supplied approved source photographs were encoded as optimized WebP derivatives without replacing the image content. `reference/approved-logo-original.png` preserves the supplied logo artwork, and `assets/straightedge-logo-header.png` is a transparency-adjusted header rendering of the supplied logo geometry.

## Deployment

Static HTML/CSS/JS. Netlify publish directory: `.` and no build command. The estimate form uses Netlify Forms, so **submission must be tested on the real Netlify deploy**, not from a local filesystem or non-Netlify preview. Configure form notifications in Netlify to deliver requests to the business owner. No domain needed for initial deployment.

## Local preview

`python3 -m http.server 8080` then open `http://localhost:8080`.

## Verification

See QA_STATUS.md for responsive checks, approved-reference differences, and the captured synthetic Netlify Forms test. Local QA screenshots are excluded from Git. Production is deployed automatically from main.
