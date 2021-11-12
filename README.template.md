# 🪐zp_new
A free, new-user-friendly website starter project designed to walk you through creating, editing, and publishing any web project; from a personal blog, to a company website!

Read more at [https://getZP-new.com](https://getZP-new.com)!

## What is zp_new?
### For new users
_zp_new_ is a free, new-user-friendly website starter designed to walk you through creating and publishing a fast, secure web project using modern tools and technology. zp_new makes it easy to "get up to zero" and start building your site.

### For experienced developers
_zp_new_ is a modern, opinionated, bare-bones Jamstack starter using Eleventy to get "up to zero" on a project quickly and easily.
Why you might choose _zp_new_ as your Jamstack starter:
* Powered by Eleventy, which [rocks](https://11ty.rocks)!
* No CSS frameworks or libraries; use whatever you like best
* GitHub Action replaces the zp_new name throughout the site with your project's name!
* Custom generated project-specific [readme file](https://github.com/MikaCaldera/zp_new/blob/master/README.zp_new.md) to help you take the next steps and launch your project!
* Sass for CSS
* Webpack for Javascript
* Browsersync to preview your work

 ## Get started: Use This Template!
<details open>
 <summary>Right from this README</summary>
 
 ###  Create a new project using zp_new and add it to your GitHub account!
 [Click here to use this template](https://github.com/MikaCaldera/zp_new/generate)
 </details>

<details>
 <summary>With GitHub CLI (https://cli.github.com)</summary>

 ### Get started from your command line
 ```sh
  gh repo create example.com --template MikaCaldera/zp_new
 ```
</details>

# Get to Know zp_new
Ready to go deeper? Here's how zp_new is laid out:

```sh
example.com                 # → Root of your zp_new-based project
├── src/                    # → Source directory
│   ├── assets/             # → Site assets
│   │   ├── fonts/
│   │   ├── images/
│   │   ├── scripts/
│   │   ├── styles/
│   │   └── views/
│   ├── config/             # → Eleventy configuration
│   │   ├── collections.js  # → Add and configure collections (https://www.11ty.dev/docs/collections/)
│   │   ├── filters.js      # → Add and configure filters (https://www.11ty.dev/docs/filters/)
│   │   ├── passthroughs.js # → Add and configure passthroughs (https://www.11ty.dev/docs/copy/)
│   │   ├── plugins.js      # → Add and configure plugins (https://www.11ty.dev/docs/plugins/)
│   │   └── watchtargets.js # → Add and configure watch targets (https://www.11ty.dev/docs/watch-serve/)
│   ├── data                # → Customize site data (https://www.11ty.dev/docs/data/)
│   │   └── navigation.json # → Site navigation configuration
│   └── pages               # → Add "pages" collection items here
│       ├── index.md        # → Default index page
│       └── pages.json      # → Shared pages attributes
├── .eleventy.js            # → Core Eleventy config file
├── netlify.toml            # → Netlify deployment and plugin configuration (optional)
├── README.template.md      # → zp_new readme
└── README.md               # → Your project's readme (automatically generated when this template is used)
```

## Eleventy Configuration
Eleventy configuration is abstracted from the typical `.eleventy.js` file and moved to `/src/config/` for easy organization and configuration of collections, filters, passthroughs, etc.
## Install project dependencies
```bash
npm i
```

## Run the project locally
```bash
npm run start
```

## Build for production
```bash
npm run production
```
