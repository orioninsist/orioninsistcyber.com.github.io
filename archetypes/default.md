+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
linkTitle = ""
description = ""
summary = ""
date = "{{ .Date }}"
publishDate = "{{ .Date }}"
lastmod = "{{ .Date }}"
expiryDate = ""
layout = "article"
type = "blog"
markup = "markdown"
slug = ""
url = ""
canonical = ""
robots = "index, follow"
keywords = []
categories = []
tags = []
aliases = []
weight = 10
outputs = ["HTML", "RSS", "JSON"]
isCJKLanguage = false
reading_time = ""
word_count = ""
headless = false
unlisted = false

[sitemap]
  priority = 0.8
  changefreq = "weekly"

[params]
  author = "Murat Kurkoglu"
  author_social = "https://medium.com/@orioninsist"
  featured_image = ""
  thumbnail = ""
  cover_image = ""
  video = ""
  table_of_contents = true
  allow_comments = true

[build]
  render = "true"
  list = "true"
  publishResources = "true"

[resources]
  [resources.featured]
    src = ""
    title = ""

[seo]
  schema_type = "Article"
  schema_context = "https://schema.org"
  schema_article_type = "https://schema.org/Article"
  schema_author_name = "Murat"
  schema_author_url = "https://orioninsistcyber.com/about"
  schema_publisher = "Orion Insist Cyber"
  schema_publisher_logo = "https://orioninsistcyber.com/images/logo.png"
  schema_date_published = "{{ .Date }}"
  schema_date_modified = "{{ .Date }}"
  schema_main_entity_of_page = ""

[openGraph]
  og_title = ""
  og_description = ""
  og_image = ""
  og_url = ""
  og_type = "article"
  og_site_name = "Orion Insist Cyber"
  og_locale = "en_US"

[twitter]
  twitter_card = "summary_large_image"
  twitter_site = "@orioninsist"
  twitter_creator = "@orioninsist"
  twitter_title = ""
  twitter_description = ""
  twitter_image = ""
+++
