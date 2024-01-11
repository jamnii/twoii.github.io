#### Directory
* [_data](_data)
* [_images](_images)
* [_includes](_includes)
* [_layouts](_layouts)
* [_posts](_posts)
* [_sass](_sass)
* [assets](assets)
* [_config.yml](_config.yml)
* [Gemfile](Gemfile)

#### Post
```
---
layout: post
title: 
subtitle:
date:
last_modified_at:
categories:
tags:
---
```

#### Menu
One:
```
cd project

touch new.html

vi _config.yml
    navigation:
      - title: New
        url: /new.html
```

Two:
```
cd project

touch new.md
vi new.md
    ---
    title: New
    layout: new
    ---

cd _layouts

touch new.html
vi new.html
    ---
    layout: default
    ---
    
    This is new
```