# Flickr-API

Simon Tharby's solution to [Project 2: Using a Third Party API](https://www.theodinproject.com/courses/ruby-on-rails/lessons/apis?ref=lnav), Project: APIS, Ruby on Rails unit, Odin Project.

## My additional features:

As well as satisfying the project criteria, I also added the following features:

  * mobile/desktop responsive layout (all views)
  * pagination of photo display, using 'will-paginate' gem
  * find Flickr user via user id or username
  * return basic info of Flickr user (id, username, real name, total public photos count, public albums count)
  * view all Flickr user's photos or view by album (select album title)
  * clicking on photo redirects to Flickr photo page
  * error handling for form submission (including Flickr-API errors)

## Screenshots:

Find user form(s) -> User info. -> Select 'view album(s)' -> Select 'view album'

![findr-row.png](app/assets/images/findr-row.png)

Desktop layout:

![findr-desktop.jpg](app/assets/images/findr-desktop.jpg)

Example Flickr-API error on form submission:

![findr-error.png](app/assets/images/findr-error.png)

## Getting started:

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Run the app in a local server:

```
$ rails server
```
