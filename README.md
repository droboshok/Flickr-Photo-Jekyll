Flickr-Photo-Jekyll
=============
### Installation
To register it as a plugin, copy _plugins/main_flickr.rb to the
_plugins directory of your jekyll project.

#### Requires an API Key

  The plug-in requires a Flickr API key in _config.yml (where "flickr:" is defined on the root level):

    flickr:
      api_key: 84ad7df61b82e136a98bbf99fa997b3e

  [Get your API key here](http://www.flickr.com/services/apps/create/).
A Jekyll plug-in for embedding Flickr photos in your Liquid templates.

### Usage:

    {% main_photo 20348431344 %}
    {% main_photo 20348431344 "Square" %}

  ... where 20348431344 is the Flickr photo ID, and "Square" is the size label [as defined here by Flickr](http://www.flickr.com/services/api/flickr.photos.getSizes.html).

  Medium (~500px width) is the default.

  