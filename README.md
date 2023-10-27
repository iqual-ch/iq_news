# iq_news

News base module for iqual.
This module provides a basic news functionality where news articles can 
be created and listed. The publication of news articles is controlled by 
the scheduler module (https://www.drupal.org/project/scheduler).

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


Rebuild CSS:

    drush iq_barrio_helper:sass-compile


Follow installation instructions for entity browsers:
https://github.com/iqual-ch/iq_entity_browsers/blob/8.x-1.x/README.md#iq_entity_browsers 
(skip step «Install the module using composer»)


If needed:
- Add News as filterable content type in content view
