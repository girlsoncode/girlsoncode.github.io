# GirlsOnCode Site

Is a pretty [Jekyll](https://jekyllrb.com/) + [Octopress](http://octopress.org/) site.

## Install GirlsOnCode Site

Install bundle:

    $ gem install bundle

And then run:

    $ bundle

Run `bundle` to install the gems specified in  Gemfile.


## Commands to create content

They are the top commands to create contents. If you want to know how octopress-cli manage this blog read [here](https://github.com/octopress/octopress/blob/master/README.md#octopress-cli-commands).

### New Post

This automates the creation of a new post.

```sh
$ octopress new post "My Title"
```

This will create a new file at `_post/YYYY-MM-DD-my-title.markdown`.


### New Page

This automates the creation of a new post.

```sh
$ octopress new page _folder/page_name
```

This will create a new file at `_folder/page_name.html`.

### Build GirlsOnCode Site

```
$ bundle exec jekyll build
```

### Run GirlsOnCode Site

```
$ bundle exec jekyll serve
```

## Deploying GirlsOnCode Site

Once you've built the site (with `bundle exec jekyll build`) you can deploy it like this:

```
$ octopress deploy
```

This reads a `_deploy.yml` configuration and deploys GirlsOnCode site. Read [here](https://github.com/octopress/octopress/blob/master/README.md#deploying-your-site) to learn how Octopress deploy a jekyll blog.

Note: The `_deploy.yml` is processed through ERB, which makes it easy to load configurations from environment variables.


## Which theme GirlsOnCode is using?

GirlsOnCode is using the HPSTR Jekyll Theme to see more informations see his github [here](https://github.com/mmistakes/hpstr-jekyll-theme).


