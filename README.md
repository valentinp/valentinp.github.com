## Simple Theme

![Simple](http://i.imgflip.com/5r5tp.gif)

I designed this simple and minimalistic theme keeping just one thing in mind. 
> The content should be the king.

Also, I did some sweet modifications as Google pagespeed analytics and suggestion. Along with that full care of SEO done with all required meta tags.

##Usage:

First, clone this repo to your own github account and rename the repo as <githubusernmae>.github.com

In-order to use the theme, go to `.config.yml`  and replace all of the fields with your own content:

```yaml
title:            My Hacks
description:      blog about my hacks
logo:             user.jpg
disqus_shortname:
#Comment out url when working locally to resolve base urls correctly
url: http://vinitkumar.me/Simple              

# Owner/author information
owner:
  name: changer          
  avatar:        
  email:          
  # Social networking links used in footer. Update and remove as you like.
  twitter:       
  github: changer        
  stackexchange:  
  # For Google Authorship https://plus.google.com/authorship
  google_plus: 

# Analytics and webmaster tools stuff goes here
google_analytics:  
google_verify:
# https://ssl.bing.com/webmaster/configure/verify/ownership Option 2 content= goes here
bing_verify:

# Links to include in top navigation
# For external links add external: true
links:
  - title: About
    url: /about
  - title: Blog
    url: /articles
  - title: Code
    url: 

# http://en.wikipedia.org/wiki/List_of_tz_database_time_zones
timezone:    
future:      true
pygments:    true
markdown:    redcarpet

# https://github.com/mojombo/jekyll/wiki/Permalinks
permalink:   /:categories/:title

kramdown:
  auto_ids: true
  footnote_nr: 1
  entity_output: as_char
  toc_levels: 1..6
  use_coderay: false

  coderay:
    coderay_line_numbers:
    coderay_line_numbers_start: 1
    coderay_tab_width: 4
    coderay_bold_every: 10
    coderay_css: class

activate: syntax
include: [".htaccess"]
exclude: ["lib", "config.rb", "Capfile", "config", "log", "Rakefile",
"Rakefile.rb", "tmp", "less", "*.sublime-project", "*" ]
```

Once done setting up the config.yml make sure you have the jekyll installed. Also, replace the content in _posts and add your own blog posts.

Usage:

To checkout the content locally, you must have jekyll installed on your
system, if there is none installed it using:

```bash
$ gem install jekyll
```
And then do:

```bash
$ jekyll server --watch
```
Bugs & Issues:

If you are curious about contributing or have found an issue, kindly
create an [issue here](https://github.com/vinitkumar/Simple/issues)







[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/vinitkumar/simple/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

