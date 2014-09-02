# Patches for WebSolr and Drupal Search API

## search_api_solr-7.x-1.1.patch

Websolr protects the administrative area of the Solr server. Fake a
response to indicate a successful connection.

See https://github.com/omc/websolr-guides/blob/master/drupal7-searchapi.md#getting-started.

## panopoly_search-7.x-1.11.patch

Patch Panopoly Searchs make file to include the
[Search API Solr patch](#search_api_solr-7x-11patch).
