# SimpleSingle

SimpleSingle is a super simple one-page hugo theme.

![image](https://user-images.githubusercontent.com/68039/216742173-76e4fa30-43f4-4036-92d7-0daccb946f2e.png)

There's nothing really much to configure, just follow the QuickStart below

## Quickstart

To get started, you can git clone this entire project into your project's `/themes/` directory

```
$ cd /hugo_project/themes
$ git clone https://github.com/davidchua/simplesingle
```

Add the following sample `config.toml` or copy the following params into your existing config

```toml
themesDir = "themes/"
theme = "simplesingle"

[params]
  toc = "enabled" # enabled/disabled; display table-of-contents on right hand of site

  [params.homepage_meta_tags]
    meta_description = ""
    meta_og_title = ""
    meta_og_type = "website"
    meta_og_url = ""
    meta_og_image = ""
    meta_og_description = ""
```

`homepage_meta_tags` is optional and is meant to help you add og tags into your published site. You can choose not to have these filled up.

## How does it work?

SimpleSingle follows a single directory layout and takes in all your content pages and adds them one by one into a single page html page.

To ensure order, you will need to ensure that you set a `weight` in your page params.

eg.

```
# index.md
---
title: "Title"
...
weight: 1
---
<CONTENT>
```

The lower the weight, the higher it appears in the order.

This theme subtlely ignores directory structures, so you can keep your content in subdirectories as long as the weight is properly set.

You can view a example hugo site at our demo page: [https://github.com/davidchua/simplesingle-demo](https://github.com/davidchua/simplesingle-demo)

## Demo

A demo site can be found at [https://peeaao.com](https://peeaao.com) 
