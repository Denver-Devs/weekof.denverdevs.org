WeekOf Denver Devs
=============

The schedule page for weekof.denverdevs.org

Setup
=====

The site uses [jekyll](http://jekyllrb.com), to run the site do the following in your
terminal:

* `git clone git@github.com:denver-devs/weekof.denverdevs.org.git`
* `cd weekof.denverdevs.org`
* `gem install bundler`
* `bundle install`
* `bundle exec jekyll serve --watch`

The site should then be available on [http://localhost:4000](http://localhost:4000)

Create an event
===============

To create an event you just have to add a new markdown file to the _posts folder:

year-month-day-nameOfTheEvent.md

The following points are necessary:

* layout: post
* title: "name of the event"
* date: year-month-day
* venue: "name of the venue"
* ticket: "ticket status - RSVP, Register, Sold out, etc."
* time: "hours:minutesam/pm"
* href: "link to the page of the event host"

The href is crucial as long as the detail pages on weekof.denverdevs.org aren't finished.
