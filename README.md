## Homepage

### Change basic information
Edit this file: [_config.yml](_config.yml)

### Update the index page
Edit this file: [index.md](index.md)

### Update the publication page
Edit this file: [publications.md](publications.md)

### How to add a new page
- Create a new file named 'abc.md'
- Copy the following lines to the new file:
```
---
layout: normal
title: ABC
---
```
- Add your content using Markdown

The link of this page is `abc.html`

### How to change the navigation bar
Edit this file: [_data/navigation.yml](_data/navigation.yml).


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
