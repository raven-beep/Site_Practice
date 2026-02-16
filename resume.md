---
title: "Resume"
---

Site-wide settings are in the `_config.yml` file. The configuration file for this sample website looks like this:

```yaml
title: Example site title 
description: A short description of the site
theme: minima
header_pages:
    - index.md
    - configure-site.md
    - resources.md
```

### Set a theme

GitHub Pages supports many themes. To try something different, update the `theme: minima` line in the configuration file and replace "minima" with another theme from [this list](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll#supported-themes).


### Page-level settings 

Additional settings for each page are at the beginning of the corresponding file, in a section referred to as the _yaml front matter_. Here's the front matter for this page:

```yaml
---
title: "Configure site"
---
```

The front matter can include other theme-specific settings. An option available in most themes is `pubished: false` which exclude a page from the site. 


For more information see GitHub's [yaml front matter documentation](https://docs.github.com/en/contributing/writing-for-github-docs/using-yaml-frontmatter)
