# 23_Jekyll_blog

Install ruby - https://www.ruby-lang.org/en/documentation/installation/
```cmd
gem install bundler jekyll
jekyll new [project_name]
cd [project_name]
bundle exec jekyll s
```

github
```
set github pages + branch main
github action - static page with jekyll

change url: in _config.yml
  baseurl: "/23_Jekyll_blog" # the subpath of your site, e.g. /blog
  url: "https://mushroomhater07.github.io" # the base hostname & protocol for your site, e.g. http://example.com
```
## ToDo
Fix CSS
use native Jekyll runner
