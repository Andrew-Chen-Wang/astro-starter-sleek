# Astro starter

Astro starter with tailwind, alpine and i18n support.


<a href="https://astro.build/">![Astro](.github/images/astro-icon.png)</a>
<a href="https://tailwindcss.com/">![Tailwind](.github/images/tailwind-icon.png)</a>
<a href="https://alpinejs.dev/">![Alpine js](.github/images/alpine-icon.png)</a>


[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/zankhq/astro-starter)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/zankhq/astro-starter)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/zankhq/astro-starter)


### [🧑‍🚀 Astro website →](https://astro.build/)

### [🕮 Astro docs →](https://docs.astro.build/en/getting-started/)


## ✅ Features

- [x] Localization (with astro-i18next)
- [x] Light/Dark mode (provided by tailwind)
- [x] Discussion on articles (thanks to giscus)
- [x] Blog
- [x] CMS for editing blog post (thanks to decap CMS)
- [x] PWA (thanks to vite-pwa)

## ✍️ Admin dashboard

You can access the admin dashboard for editing blog post at `/admin`

For more information follow Decap CMS documentation at https://decapcms.org/docs/

In order to access the admin dashboard to change blog articles content you need to have access to the github repo, a quick way to test it test would be fork the repo and than configure decap cms accordingly to your cloud provider (netlify, cloudflare, vercel, etc...).

If you use cloudflare pages you can follow this guide https://github.com/i40west/netlify-cms-cloudflare-pages.

If you use netlify it's actually easier, you will need to change in the file `astro.config.mjs` NetlifyCMS config `config.backend.name` to git-gateway. (See https://decapcms.org/docs/git-gateway-backend/#git-gateway-with-netlify for more info)

<br/>

---

<p align="right"><a href="https://zank.studio" target="_blank">[warps.it](https://zank.studio/)</p>
