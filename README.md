# Hosting settings DB

This database contains MX and other settings for known hosting providers.
When you buy a domain and hosting in 2 different places, often one or the other sends you some settings "to make it work".
This is often very tiresome.

In Automattic, we want to make web a better place and we also think that these kind of settings exchange should be no concern of the user.

This database is designed to be embedded in projects like DNS editors to provide an easy interface to manage your settings.

## Online database

This project introduces online MX database search engine. It lives under:

#### http://automattic.github.io/hosting-settings/

It is powered by GitHub pages.
Whole code of the online version is in `gh-pages` branch of this project.
To update the data in the online version, simply:

- Update `master` branch
- Chekout `gh-pages` branch
- `git merge master`
- `git push`

et voila.

## Data format

## I want to use it in my project!

Feel free to add it as a dependency, it is designed for precisely that purpose.

## I am a hosting provider and my settings changed

Please submit a pull request - they are very welcome!

