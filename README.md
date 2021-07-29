# Readme

This repository is for the group webpage of HKUST Vislab AI4VIS team. It is modified from theme [beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)
## Set up
- [install depandencies (ruby 2.7, gem)](https://jekyllrb.com/docs/installation/)
- `gem install`

## Run
```
bundle exec jekyll serve
```

## Build
```
bundle exec jekyll build
```

## Update
- **Data**: go to the `_data` folder and update entries following existed examples
  - news: news (message, date, type)
  - publications: work (title, authors, doi, arxiv, link, pdf, video, recording, slides, demo, award, osf)
  - people: enable url in the author list (url)
  - team: members, alumini, and partner institutes (name, url, image, title)
  - venue: venue details (full, short)
- **Layout and styles**: go to the `_component` folder or `_sass` folder
