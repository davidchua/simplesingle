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

## Demo

A demo site can be found at [https://peeaao.com](https://peeaao.com)
