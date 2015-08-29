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

- 'Square' width="75" height="75" 
- 'Large Square' width="150" height="150" 
- 'Thumbnail' width="75" height="100" 
- 'Small' width="180" height="240" 
- 'Small 320' width="240" height="320" 
- 'Medium' width="375" height="500" 
- 'Medium 640' width="480" height="640" 
- 'Medium 800' width="600" height="800" 
- 'Large' width="768" height="1024" 
- 'Large 1600' width="1200" height="1600" 
- 'Original' width="1200" height="1600" 
