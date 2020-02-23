---
layout: page
title: "Documentation"
category: dev
date: 2016-09-04 21:15:55
order: 2
---
We are using Jekyll for the documentation (i.e this website).
If you want to contribute to the documentation, it is availalbe in the
```gh-pages``` branch (the documentation is hosted on Github pages). 
 
The documentation is divided into 3 categories: for users, for authors,
and for developers.
To update a particular page, find the markdown file in the ```_posts```
directory.
To make a new page, run ```bin/jekyll-page [page title] [category_code]```.
The codes for the category are:
 * ```user``` (will be placed in the **For Users** section)
 * ```author``` (**For authors** section)
 * ```dev``` (**For developers** section)
 
After you make changes to the documentation, please make a PR to the
 ```gh-pages``` branch in the upstream repository.
  
Put images in the ```assets``` directory.
To use them in your post, you reference them by writing:
```![alt_text]({{ site.baseurl }}/assets/[the_image_path])```