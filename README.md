# Birmingham IVF & Fertility website

Static website for Birmingham IVF & Fertility, a consultant-led private IVF and fertility clinic in Sutton Coldfield, Birmingham, led by Dr Adrija Kumar Datta.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `about.html` | About Dr Datta |
| `fertility-tests.html` | Fertility tests |
| `ivf-treatment.html` | IVF treatment |
| `iui-treatment.html` | IUI treatment |
| `ivf-donor-eggs.html` | IVF using donor eggs |
| `frozen-embryo-transfer.html` | Frozen embryo transfer |
| `prices.html` | Prices |
| `faqs.html` | FAQs |
| `book.html` | Book a consultation |
| `contact.html` | Contact & directions |

Shared styles live in `styles.css`; images are in `images/`.

## Running locally

It's plain HTML and CSS with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Deploying

Any static host works (GitHub Pages, Netlify, Cloudflare Pages). Online bookings go through the clinic's Wawa patient portal.
