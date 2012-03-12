# Kanban

Kanban helps you visualize your work, and limit the number of items that are in-progress.

This implementation is in JavaScript, using Backbone.js and jQuery UI.

## Current features

* Drag and Drop UI for ordering cards in lanes and moving cards between lanes.

* Client-side Backbone.js models, collections and views. Unit tested.

## Roadmap of Upcoming Features

* Ability to add new cards. Currently uses sample data.

* Persist data. Plan is to add local storage first, then a server-based version (node.js and database).

## To try it

    # clone repository locally
    # open index.html in browser

## How to run tests

    # Setup Jasmine dependencies. From root of repo:
    bundle install
    
    # Run tests
    rake jasmine
    # open browser to http://localhost:8888
    
    # Or for CI
    rake    # which by default runs 'jasmine:ci' task
