# crunix theme customization of So Simple Theme

## Setup for Existing Jekyll site

``` yaml
title:            Site Title
description:      Site description for the metas.
logo:             site-logo.png
disqus_shortname: shortname
search:           true
# Your site's domain goes here. When working locally use localhost server leave blank
# PS. If you set this wrong stylesheets and scripts won't load and most links will break.
# PPS. If you leave it blank for local testing home links won't work, they'll be fine for live domains though.
url:              http://localhost:4000

# Owner/author information
owner:
  name:           Your Name
  avatar:         your-photo.jpg
  email:          your@email.com
  # Social networking links used in footer. Update and remove as you like.
  twitter:
  facebook:
  github:
  linkedin:
  instagram:
  tumblr:
  # For Google Authorship https://plus.google.com/authorship
  google_plus:    "http://plus.google.com/123123123123132123"

# Analytics and webmaster tools stuff goes here
google_analytics:
google_verify:
# https://ssl.bing.com/webmaster/configure/verify/ownership Option 2 content= goes here
bing_verify:

# Links to include in top navigation
# For external links add external: true
links:
  - title: About
    url: /about
  - title: Articles
    url: /articles
  - title: Google
    url: http://google.com
    external: true

# http://en.wikipedia.org/wiki/List_of_tz_database_time_zones
timezone:    America/New_York
pygments:    true
markdown:    kramdown

# https://github.com/mojombo/jekyll/wiki/Permalinks
permalink:   /:categories/:title/
```

---

## Folder Structure

``` bash
so-simple-theme/
├── _includes/
|    ├── browser-upgrade.html  #prompt to upgrade browser on < IE8
|    ├── footer.html  #site footer
|    ├── head.html  #site head
|    ├── navigation.html #site navigation and masthead
|    └── scripts.html  #jQuery, plugins, GA, etc.
├── _layouts/
|    ├── page.html  #page layout
|    └── post.html  #post layout
├── _posts/
├── assets/
|    ├── css/  #preprocessed less styles
|    ├── fonts/  #icon webfonts
|    ├── js/
|    |   ├── _main.js  #main JavaScript file, plugin settings, etc
|    |   ├── plugins  #jQuery plugins
|    |   └── vendor/  #jQuery and Modernizr
|    └── less/
├── images  #images for posts and pages
├── _config.yml  #Jekyll site options
├── about.md  #about page
├── articles.html  #lists all posts from latest to oldest
├── index.html  #homepage. lists 10 latest posts
├── tags.html  #lists all posts sorted by tag
└── sitemap.xml  #autogenerated sitemap for search engines
```

---

## Customization
For full customization details and more information on the theme check out the [So Simple theme setup guide](http://mmistakes.github.io/so-simple-theme/theme-setup/).

---

## Questions?
Having a problem getting something to work or want to know why I setup something in a certain way? Ping me on Twitter [@mmistakes](http://twitter.com/mmistakes) or [file a GitHub Issue](https://github.com/mmistakes/so-simple-theme/issues/new).

---

## License
This theme is free and open source software, distributed under the [GNU General Public License](LICENSE) version 2 or later. So feel free to to modify this theme to suit your needs. 
If you'd like to give me credit somewhere on your blog or tweet a shout out to [@mmistakes](https://twitter.com/mmistakes), that would be pretty sweet.
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/mmistakes/so-simple-theme/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

