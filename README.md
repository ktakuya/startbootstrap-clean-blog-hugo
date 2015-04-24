#Clean Blog by Start Bootstrap - Hugo Version

The Hugo version of the Clean Blog theme by [Start Bootstrap](http://startbootstrap.com/).

## Installation

If you would like to use this theme, clone by this repository.  

Commands:

```sh
$ mkdir themes
$ cd themes
$ git clone https://github.com/ktakuya/startbootstrap-clean-blog-hugo.git themes
```

## Before You Begin

In the config.toml(config.yml) file, it's recommended that you add account ID (e.g. Twitter, Facebook and Github) before working with this theme.  

It should look like this:  

```toml

baseurl = "http://yourSiteHere/"
languageCode = "en-us"
title = "My New Hugo Site"

[params]
  Facebook = "takuya.kuwahara.7"
  Twitter = "taku__9"
  Github = "ktakuya"
```

If you would like to use about page and contact form, you should prepare sections of about and contact.  

Commands:

```sh
$ hugo new about/about.md
$ hugo new contact/contact.md
```

When you write out contents in about.md, you can see it in about page.


### License

Open sourced under the [MIT license](https://github.com/ktakuya/startbootstrap-clean-blog-hugo/blob/master/LICENSE).
