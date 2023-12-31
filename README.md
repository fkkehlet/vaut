# vaut

## Fonts

https://fonts.google.com/specimen/Ysabeau+SC?preview.text=vaut&preview.text_type=custom

## Tools

- https://transform.tools/typescript-to-zod
- https://www.patterns.dev/
- https://www.uxtoast.com/ui-design/figma-get-started

## Pricing

Let us handle everything so you don't have to.

- Design
- Development
- Hosting
- Analytics

Do interviews? We use XYZ technologies (JAMstack - Astro, Tailwind, Alpinejs,
Svelte).

### Project scope

- Website type – it is more difficult to build a website that has additional functionality, such as an online store.
- Number of pages – the project’s timeline depends on how many pages the website has. Websites with many pages require more assets, wireframes, and user flow plans.
- Required features – some websites, like gaming sites, require additional features to function properly. Installing them requires extra work.
- Website maintenance – consider other work after the project is completed. Clients typically ask for maintenance, revision, and performance monitoring services.
- Project complexity – charge more for a new website. Conversely, your rate should be lower if you update an existing site or build a simple one using a template.
- Back-end tasks – in addition to designing and building their website, clients may ask you to handle its back end. This task may include managing the website’s hosting, domain, and plugins.


### FLAT FEE WEBSITES
- Single page site revision: $200 flat fee

- Single page portfolio: $500 flat fee with unlimited revisions before
  deployment
  (typical delivery time: 1 week)

-

Domain management and hosting is included in the prices!

- Animations:
- Domain management: $5/month + upfront and ongoing costs of the domain name(s)
- Ongoing support: variable ($50-500/month?)

- Performant,
- Web design and development.

- 1 page

You can justify a higher price if your services improve return on investment (ROI). It refers to the proportion of the website cost to the return it generates, like the number of sales.

Bundle your web design service with solutions that improve ROI. These solutions may include applying search engine optimization (SEO) practices, content marketing strategies, or performance tracking.

## What can I offer?

- Processed and optimized media files such as images, fonts, etc.
- Fast as f*ck page loads and SEO optimization
- Enterprise-level website security and 99.99% uptime guarantee
- Custom fonts, brand colors, assets, etc.
- GDPR-compliant, easy-to-use web analytics service with the ability to create and run UTM
  marketing campaigns
- Endless scalability
- A complete package: I will design the website to fit around your brand, or I can assist in building out a new
brand identity if needed.
- Use your own custom colors and layout
- Best-in-class speed and SEO optimization
- Always-online with a secure design and staging website where we can preview
  changes before giving the OK to go live with them
- A website analytics dashboard which is fully compliant with privacy
  regulations such as GDPR
- Create your own blog posts with an easy-to-use content management system
- Sleek animations, stellar interactivity, and more!
- Have lots of content and adding more on a continual basis? No problem at all,
  with the ability to integrate a custom CMS



Methodology:

Understand your needs (key questions: target audience, their problems, your
solutions, what differentiates you)-> determine content -> collect assets + design system + draft responsive design -> code -> extra functionality (analytics, CMS, etc.) -> deploy!




### Animation libraries

- https://auto-animate.formkit.com/#usage-svelte
- https://animxyz.com/
- https://webdevamin.com/
- https://animista.net/


For dynamics tailwind properties in classes (maybe won't work if I want to map
an array...):

```astro
---
const bg = `bg-${color}-500`;
---
```


Draw animation (53 mins https://youtu.be/NniT0vKyn-E):

Custom counter ALSO there.

```astro
<script>
// Do this in Alpine
const path = document.querySelector('#path')
const pathLength = path.getTotalLength().toString()
path.style.strokeDashArray = pathLength
path.style.strokeDathOffset = pathLength
</script>

<style>
.trig {
  animation: draw 1s forwards 1s ease-out;
}
@keyframes draw {
  to {
  stroke-dashOffset: 0;
}
}
</style>
```


Component variants:

https://tailwindcss.com/docs/content-configuration#dynamic-class-names



## FIGMA

- Unsplash
- Icons8 background remover
- Easometric (convert 2D design into isometric to change perspective of frame)
- Content reel (populate text and images)
- Autoflow (for flow diagrams)
- Iconsax (or iconify?)
- Contrast (check accessibility)

- https://www.figma.com/community/plugin/735098390272716381/Iconify
- Diagram / Genius AI: https://www.figma.com/blog/ai-the-next-chapter-in-design/

- Figma mirror for mobile designs!






- nyflit
- recoete.com
- rakas
- fusar.io
- rakas

- Ethical disclaimer: I do not accept projects involving the promotion of animal exploitation. This includes taking on clients directly working with customers who exploit animals for the production of food and beverage products, clothing, experimentation, or entertainment.

## Install sequence

- npm create astro@latest
- npx astro add tailwind
- npm i -D prettier prettier-plugin-tailwindcss prettier-plugin-astro

- "prettier-watch": "onchange \"**/*\" -- prettier --write --ignore-unknown {{changed}}"
- npx onchange "**/*" -- npx prettier --write --ignore-unknown {{changed}}


## Helpful links

- NEWCOM598

https://picocss.com/docs/scroller.html

### Icons

- https://fontawesome.com

### Starters

- https://github.com/hellotham/hello-astro

### Animations

- [Page load transitions with Swup](https://navillus.dev/blog/astro-plus-swup)
- [Animating with Alpine](https://dev.to/benbao/animate-with-alpine-js-gbi)
- [Animating with Alpine + Tailwind](https://greghunt.dev/alpinejs-tailwind-load-animation)
- https://razabayani.com/mastering-animation-in-alpinejs-a-complete-guide/
- [Lightweight CSS Animations on Scroll using Alpine JS](https://www.youtube.com/watch?v=n4LxOtCwlUg0

### Internationalization

- https://www.defined.net/blog/internationalizing-docs-pages-with-astro/

### Search

- https://pagefind.app/

### Security

- https://security.stackexchange.com/questions/142496/which-security-measures-make-sense-for-a-static-web-site
