# CharlesAnHalJulIGe

## Summary

This page use jekyll, ruby-gem for static website.
This page also use following ruby gems for more features.

- jekyll-sitemap: Google, Naver SEO
- jekyll-admin: Admin page for our website

Now you can write with GUI editor with jekyll-admin

## Development Environment

This assume Ubuntu 16.04 LTS is our operating system.

	sudo apt install ruby ruby-bundler jekyll
	sudo apt install clang make ruby-dev libffi-dev
	sudo gem install bundler
	bundle install

## Run jekyll server

	bundle exec jekyll serve

## Check jekyll page

	http://localhost:4000
	http://localhost:4000/admin
