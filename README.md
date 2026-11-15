# Birmingham IVF & Fertility website

Static website for Birmingham IVF & Fertility, a consultant-led private IVF and fertility clinic in Sutton Coldfield, Birmingham, led by Dr Adrija Kumar Datta.

## Pages

Each page lives in a folder named after its web address, so the old WordPress URLs keep working.

| Address | Page |
|---|---|
| `/` | Home |
| `/about-us/` | About Dr Datta |
| `/fertility-tests/` | Fertility tests |
| `/ivf-treatment/` | IVF treatment |
| `/iui-intra-uterine-insemination/` | IUI treatment |
| `/ivf-with-donor-eggs/` | IVF using donor eggs |
| `/fet-frozen-embryo-transfer/` | Frozen embryo transfer |
| `/prices/` | Prices |
| `/faqs/` | FAQs |
| `/book-consultation/` | Book a consultation |
| `/contacts-us/` | Contact & directions |
| `/privacy-policy/` | Privacy policy |
| `/terms-and-conditions/` | Terms & conditions |

`/webinar/`, `/webinars/` and `/egg-freezing/` forward to the relevant page. `404.html`, `sitemap.xml`, `robots.txt` and `CNAME` (www.birminghamivf.co.uk) support GitHub Pages hosting.

Shared styles live in `styles.css`; images are in `images/`.

## Running locally

It's plain HTML and CSS with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

then visit http://localhost:8000. Links are root-relative, so serve the folder rather than opening files directly.

## Deploying

Any static host works (GitHub Pages, Netlify, Cloudflare Pages). Online bookings go through the clinic's Wawa patient portal.
