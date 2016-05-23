# level-up

This is the source code for the https://level-up.cc website.

In 2016, all Level Up content was added to Github in an effort to make the content accessible for remixing and sharing.

All content on this site is available under a Creative Commons Attribution-Share Alike Unported 3.0 license by multiple authors.

Explore advice from fellow digital safety trainers and experienced facilitators, customize curriculum keyed to how adults learn, learn more from experts on the Psychology of Security Trainings and self-care (including how stress and trauma affect the ability to learn as well as train effectively), get ideas from icebreakers and activities to start your workshops and make them fun, check out guides on developing trainings and crafting agendas, and more. All made for trainers by their fellow trainers.

###Who built the site?

The website was built by [the engine room](www.theengineroom.org) in the spring of 2016.

User Experience - Julie Lorch

Designer - Dimitris Stamatis

Developer - Hannah Edrosa

###How can I contribute?

If you want to contribute:
- email the community maintainer
- fork the repo, edit and submit a pull request

### Building the source code
- Clone the repo
- Install Jekyll 3

```
cd level-up
jekyll build
```

The compiled code can be found in the _site folder. If you want to build it with a different baseurl, change the baseurl value in _config.yml.

```
# Site settings
title: LevelUp
description: Resources for the global digital safety training community.
baseurl: "" # the subpath of your site, e.g. /blog
url: "" # the base hostname & protocol for your site

```

Or change it on the fly when you run the serve command with the baseurl of your choosing.

```
jekyll serve --baseurl ''
```
