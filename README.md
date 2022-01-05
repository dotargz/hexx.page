# hexx.page
### Very Heavily Inspired by js.org
[![pages-build-deployment](https://github.com/dotargz/hexx.page/actions/workflows/pages/pages-build-deployment/badge.svg?branch=gh-pages)](https://github.com/dotargz/hexx.page/actions/workflows/pages/pages-build-deployment)

To get a Free, Performant, Easy-to-use subdomains for your own GitHub Pages site follow these 4 Steps:

## Step 1
If you haven't already, now it's time to log in to your GitHub account and set up your GitHub Pages site following the instructions [here](https://pages.github.com/). To get a head start you can simply use the generator with one of the provided themes and **add some reasonable content to your new page.**

## Step 2
Now determine your hexx.page subdomain: either choose your username or the name of your repo according to the existing GitHub Pages URL (for ``http://foo.github.io/bar``, either ``foo.hexx.page`` or ``bar.hexx.page`` would be possible).

## Step 3
Add a file named ``CNAME`` to your repo (in the ``gh-pages`` branch for project pages) with a single line matching the domain you have chosen (e.g. ``foo.hexx.page``). If you prefer a webinterface form, have a look at [GitHub Pages Help](https://help.github.com/articles/adding-or-removing-a-custom-domain-for-your-github-pages-site/).

## Step 4
To finish the procedure, make a pull request in this GitHub repository that adds your subdomain to the [list](https://github.com/dotargz/hexx.page/blob/master/cnames_active.js) of existing HEXX.PAGE domains. Your new URL should go live within 24 hours (keep an eye on your pull request in case of a naming conflict).
