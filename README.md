# Fernando Quijada · Product Design Portfolio

The product design version of [fe17-q.github.io](https://fe17-q.github.io), served at **https://fe17-q.github.io/design/**.
Same structure, interactions, and look as the engineering site; the content is written for product design roles.
Plain HTML, CSS, and JavaScript. No build step. Every path is relative, so the site works under `/design/`.

```
index.html                           the drink menu plus every section
projects/this-portfolio.html         case study: designing this portfolio (AI in the design process)
projects/microscope-stage.html       case study: LED microscope stage (user-centered iteration)
projects/lightbox.html               case study: Wall-E lightbox
projects/ultrasound-water-tank.html  case study: flood alarm for an ultrasound lab
assets/css/style.css                 all styles (Latte and Espresso themes)
assets/js/main.js                    menu, brewing animation and order tracker, glass, Behind the counter, analytics
assets/img/process/                  screenshots used in the portfolio case study
resume/Fernando_Quijada_Resume.pdf   TODO: replace with the product design resume (same file name)
```

## Hash routes
`#about` `#projects` `#experience` `#interests` `#connect` `#all` `#menu`. Direct links skip the brewing animation.

## Behind the counter
The toggle in the top bar shows `<aside class="counter-note" hidden>` notes that explain design decisions in place.
To add one, put a `counter-note` aside next to the thing it explains. The setting is remembered per visitor.

## Analytics (GoatCounter)
Off until a site code is set. Sign up free at goatcounter.com, then put your code in
`<meta name="goatcounter" content="YOURCODE">` in `index.html` and each page in `projects/`.
It counts page views plus events: `order-<drink>`, `skip-<drink>`, and `behind-the-counter-on`. No cookies.

## Coming next
grain and Pendo AI onboarding case studies. Their cards are commented out in the Projects section of `index.html`
until their pages exist.
