# auramedical.github.io

<!-- font -->
<!-- https://fonts.google.com/specimen/Space+Mono -->


# Overview
https://auramedical.com/ uses jekyll (a liquid html templating tool) to generate static html and css. Github pages auto compiles the code here to static html to serve on the website. Cloudflare acts as the DNS and does caching on their end so watch out for that.

# Setup
## Install Jekyll - https://jekyllrb.com/docs/installation/
mac
- see https://jekyllrb.com/docs/installation/macos/

windows
- see https://jekyllrb.com/docs/installation/windows/

# Editing
## Writing pages w/ Markdown
- you can write pages in html or markdown. for markdown see here: https://commonmark.org/help/

## Declaring css
- object oriented css via: https://basscss.com/. To specify in markdown you do something like this...

`{:.pt4}`

`## Main`

## File Structure
- `_includes` are re-useable components
- `_layouts` hold core layout templates
- `res` holds all resources and media including sidekick ipa
- `root` these are the core pages

Build with `jekyll serve -ol` to get a local preview of what you're working on. -o opens the url and -l livereloads changes

# Deploying
- If you push a commit it goes to github pages and autodeploys. Sometimes it won't show up immediately because of caching

# Other

## need to do analytics one day
