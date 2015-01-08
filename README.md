
 Style guide
===================

Getting started
----------------
Requires: npm, grunt, bower

    brew install node
    gem update --system && gem install scss-lint
    npm install -g grunt-cli bower

To setup:

    npm install
    bower install

To run:

    grunt run
    open dist/index.htm

Or to run with live automatic browser reloading:
  
    grunt server

To configure your sublime text to use only 2 spaces per tab for scss, install the scss plugin,
open a .scss file, and open preferences > settings - more > syntax specific, and paste:
{ "tab_size": 2, "translate_tabs_to_spaces": true }


Requirements
-------------

Reqs:
- gallery
  how do we build it?
- html elements (radio, buttons, forms, modals, carousels, etc.)
- patterns (box that takes a topic object as a parameter for instance)
- scss
- must be updatable by the design people
- set of directions on using mixins and extend
- how to use and define colors
- how to use and define fonts
- patterns must give instructions on how to include/enable them
- explain grid/bourbon

see: https://projects.invisionapp.com/share/651WJ68DW#/screens/47517972?maintainScrollPosition=false

Tools:
- bower package, use a local path as a repository
- autoprefixer
- scss-lint
  see: http://davidtheclark.com/scss-lint-styleguide/
  https://gist.github.com/davidtheclark/d764f70ffaca09892293
- git submodule?
- minifier
- spritifier

Styling:
- colors
- fonts
- how to use mixins and extend

Elements:
- radio
- button
  button groups
  button dropdowns
  button colors
  button sizes
- text
- textarea
- dropdown
- checklists
- tables
- forms
  labels left aligned
  labels on top
  no labels (placeholder)
- badge (see bootstrap)
- progress bars
- pagination
- header styles
- links

Patterns (ways of doing things):
- Editing an object
  Text turns into editable element like jira?
- grid
- alerts/ajax notifications (hupspot notification library?)
- how to use fonts, fontastic
- modals
- tabs
- tooltips
  interrogation mark/contextual help tooltip
- carousel
- spinner
- datepicker
- responsive sizes/devices:
  large
  medium
  small
  touch


Components (dust templates used for rendering):
- page layouts


Misc:
- put the bootstrap dependency inside the style package?
- duster for autorecompiling
- client side dust rendering
- how to do event driven (pubsub)
- helpers:
  formatDate
  plural
- structure:

knewton-style/
    dist/
        js/     (minified and not minified)
        css/    (same)
        img/    (spritified?)
    scss/
    js/
    img/

todo:
headers: -webkit-font-smoothing
