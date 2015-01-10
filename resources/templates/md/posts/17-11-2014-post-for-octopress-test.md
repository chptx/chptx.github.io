{:title "Post for octopress test!"
 :layout :post
 :tags  ["blog"]}

### setup & work with Octopress

<!--more-->

```bash
git clone git://github.com/imathis/octopress.git octopress
cd octopress

gem install bundler
rbenv rehash
bundle install

rake install

rake setup_github_pages

rake generate
rake deploy

git add .
git commit -m 'your message'
git push origin source

rake new_post

rake new_page

rake generate

rake deploy 
```

* [posts syntax](http://jekyllrb.com/docs/posts/)
* [Octopress posts](http://octopress.org/docs/blogging)
* [Pygments Lexers](http://pygments.org/docs/lexers/)
