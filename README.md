# Patches for WebSolr and Drupal Search API

## search_api_solr-7.x-1.1.patch

Websolr protects the administrative area of the Solr server. Fake a
response to indicate a successful connection.

See https://github.com/omc/websolr-guides/blob/master/drupal7-searchapi.md#getting-started.

Search API Solr 1.6 has a build configuration workaround for this problem.

See https://www.drupal.org/node/2175829 - the patch from the issue should also apply on version 1.4.

## panopoly_search-7.x-1.11.patch

Patch Panopoly Searchs make file to include the
[Search API Solr patch](#search_api_solr-7x-11patch).
