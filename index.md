# Hexo Configuration
## Docs: https://hexo.io/docs/configuration.html
## Source: https://github.com/hexojs/hexo/

# Site
title: AnAn
subtitle: 阳光如此美好(*^▽^*)何必自寻烦恼(*^▽^*)
description: 一名网络安全小白的成长之路。。。
keywords: ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDjSVaqV07W9GEOfAiLtrW85N+RpauYElt68LU22ppyJ89agQs2QB43ALRwBKWgijuOfcXDzMfyYS/sJUhiUKPuNNZT1493tY1VgCevRRwJ9i9fVwp9eehB6MaRPmdZZEZASVqXUEtheB2gC5gnECCvqrk8IvCqgdFK8MRocxPj9kMDOHG3lPzforNHVZ0dpmUuI+3L/tgZ6AljrU9NbalplfcQAlnQZ6EkC63ayoHYvnhaaJp31YwaoeI86eEUJV7lgUx6Qq1FhA7gY3KI3UirEFae9VuBZi8eyYF1EUm3ODLV1tHaKWZqZjxTnm9ybpbYT7j8/y7m2Y25o4LENlPr 1004242920@qq.com
author: AnAn-LL
language: zh-CN
timezone: "

# URL
## Set your site url here. For example, if you use GitHub Page, set url as 'https://username.github.io/project'
url: https://anan-ll.github.io/
permalink: :year/:month/:day/:title/
permalink_defaults:
pretty_urls:
  trailing_index: true # Set to false to remove trailing 'index.html' from permalinks
  trailing_html: true # Set to false to remove trailing '.html' from permalinks

# Directory
source_dir: source
public_dir: public
tag_dir: tags
archive_dir: archives
category_dir: categories
code_dir: downloads/code
i18n_dir: :lang
skip_render:

# Writing
new_post_name: :title.md # File name of new posts
default_layout: post
titlecase: false # Transform title into titlecase
external_link:
  enable: true # Open external links in new tab
  field: site # Apply to the whole site
  exclude: ''
filename_case: 0
render_drafts: false
post_asset_folder: false
relative_link: false
future: true
highlight:
  enable: true
  line_number: true
  auto_detect: false
  tab_replace: ''
  wrap: true
  hljs: false
prismjs:
  enable: false
  preprocess: true
  line_number: true
  tab_replace: ''

# Home page setting
# path: Root path for your blogs index page. (default = '')
# per_page: Posts displayed per page. (0 = disable pagination)
# order_by: Posts order. (Order by date descending by default)
index_generator:
  path: ''
  per_page: 10
  order_by: -date

# Category & Tag
default_category: uncategorized
category_map:
tag_map:

# Metadata elements
## https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta
meta_generator: true

# Date / Time format
## Hexo uses Moment.js to parse and display date
## You can customize the date format as defined in
## http://momentjs.com/docs/#/displaying/format/
date_format: YYYY-MM-DD
time_format: HH:mm:ss
## updated_option supports 'mtime', 'date', 'empty'
updated_option: 'mtime'

# Pagination
## Set per_page to 0 to disable pagination
per_page: 10
pagination_dir: page

# Include / Exclude file(s)
## include:/exclude: options only apply to the 'source/' folder
include:
exclude:
ignore:

# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: matery

# Deployment
## Docs: https://hexo.io/docs/one-command-deployment
deploy: 
  type: git
  repo: git@github.com:AnAn-LL/AnAn-LL.github.io.git
  branch: master
0
