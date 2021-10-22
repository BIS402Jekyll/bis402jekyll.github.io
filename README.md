# BIS 402 Jekyll Site

This is a Jekyll site for BIS 402. It is a simple site with a single page that was created in about 5 minutes.

First, go to Jekyll's Quickstart: <https://jekyllrb.com/docs/> and follow the instructions to install Ruby, Ruby Gems, and Jekyll. You will not need GCC or Make as you are not compiling any code.

Then, create a new directory and cd into it.

Then, clone this repository:

```git
git clone https://github.com/BIS402Jekyll/bis402jekyll.github.io.git
```

When ready, build the site and make it available on a local server.

```ruby
cd bis402jekyll.github.io
bundle exec jekyll serve
```

Then, go to the site and click the link to the page: `http://localhost:4000`

Note, at the time of this writing, if you are using Ruby version 3.0.0 or higher, step 5 in the instructions on <https://jekyllrb.com/docs/> may fail. As per the instructions, you may fix it by adding webrick to your dependencies: `bundle add webrick`
