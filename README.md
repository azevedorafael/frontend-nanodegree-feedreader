# Project Overview

Tests wrote in [Jasmine](http://jasmine.github.io/) against a web-based application that reads RSS feeds.

## How to run?

Open the `index.html` file in the browser and check the tests result.

## List of Tests

1. loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
4. ensures the menu element is hidden by default.
5. ensures the menu changes visibility when the menu icon is clicked.
7. ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
9. ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
