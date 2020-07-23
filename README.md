# What tech are we using to build this?
- [X] Gridsome
- [X] Netlify CMS

## Site Owner Features
- [ ] pull photos from instagram
- [X] blog
- [X] upload photos; handled in Netlify CMS Media
- [ ] upload videos; [netlify cms youtube widget](https://github.com/hennessyevan/netlify-cms-widget-youtube)

## 3rd Party Services
- [ ] Netlify
    - [ ] Configure Domain; currently propagating
    - [X] Configure CMS
    - [ ] How do I handle my sister logging into this? Github account? How do I give her access?

## To Build
- [ ] Build script to pull instagram photos and save to repo
    - hook into build script
    - get instagram api key from ENV vars
    - pull instagram photos and meta data (datetime/link)
    - get github api key from ENV vars
    - push photos and metadata to github repo as static assets
    - graphql inside project can query this data
    - continue building
- [ ]

