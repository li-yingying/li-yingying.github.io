## Jekyll + jemdoc

### How to add a new page
- Create a new file named 'abc.md'
- Copy the following lines to the new file:
```
---
layout: normal
title: Publications
---
```
- Add your content using Markdown

### How to change the navigation bar
Edit this file: [_includes/navbar.html](_includes/navbar.html), then the navigation bar on all pages will change
- Add a new item in the navigation bar:
```
<div class="menu-item"><a href="abc.html">ABC</a></div>
```
- Add a new category in the navigation bar:
```
<div class="menu-category">Category ABC</div>
```

### Using Locally with Jekyll

*You need to install [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/) fisrt.*

Clone this repository:

```bash
git clone https://github.com/li-yingying/li-yingying.github.io
cd li-yingying.github.io
```
Install and run:

```bash
bundle install
bundle exec jekyll server
```
View the live page using `localhost`:
<http://localhost:4000>. You can get the html files in `_site` folder.
