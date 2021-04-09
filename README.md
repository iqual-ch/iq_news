# iq_news

News base module for iqual.
This module provides a basic news functionality where news articles can be created and listed. The publication of news articles is controlled by the scheduler module (https://www.drupal.org/project/scheduler).

Includes:
- «News Article» content type, derived from «Page» type with additional fields:
- Node template for «News Article» type
- «Topics» taxonomy
- «News Article» view with several blocks
- «News teaser» pattern

## Setup & Installation

Install module as usual:

    composer require iqual/iq_news
    drush en iq_news
