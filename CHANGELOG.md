## Release Notes:

### v0.2.6 (December 12, 2014)
* fix for DRF 3.0.1

### v0.2.5 (December 10, 2014)
* fix support for Django Rest Framework 3

### v0.2.4 (December 9, 2014)
* fix support for Django Rest Framework 3

### v0.2.3 (December 8, 2014)
* fix support for Django Rest Framework 3

### v0.2.2 (December 7, 2014)
* add support for Django Rest Framework 3
* add docExpansion to settings
* add `token_type` to settings

### v0.2.1 (November 15, 2014)
* add readthedocs based documentation 
* add request and response serializer spec to yaml
* preserve order of fields in serializers
* support nested serializers

### v0.2.0 (October 31, 2014)
* Added YAML Parser to docstring handling
* Fixed Python 3 bugs

### v0.1.14 (March 7, 2014)
* Fixed resource name truncation bug

### v0.1.13 (Feb 25, 2014)
* Fixed grouping bug

### v0.1.12 (Feb 24, 2014)
* Improved resource grouping
* Alphabetical sorting of resources
* Fixed CSRF headers
* Misc bug fixes & improvements

### v0.1.11 (Dec 1, 2013)
* Added proper unicode support for Python 2
* Compatibility fixes for Python 3
* Changed settings template var to avoid naming conflicts
* Fixed mapping dict constructor in introspectors for Python 2.6 support

### v0.1.10 (Nov 23, 2013)
* Upgraded Swagger UI version
* Now supports Django ViewSet method-level documentation
* Now supports ViewSet @action & @link method implementation
* Added blank HttpRequest to the callback for those who like to hack the get_serializer classes
* HTML Markdown supported in docstrings (use responsibly)

### v0.1.9 (Oct 1, 2013)
* Revisited doc algorithm
* Added support for APPEND_SLASH = False

### v0.1.8 (Sept 16, 2013)
* Fixed broken imports - Now supports DRF 2.3.8
* Added description on the model field

### v0.1.7 (Sept 4, 2013)
* URL flattening fixes
* API root prefix fix

### v0.1.6 (August 3, 2013)
* Improvments and bug fixes with relative imports in Python 3
* throbber.gif image is being pointed to local copy

### v0.1.5 (July 30, 2013)
* Added permission settings for Swagger docs. Default is now allow any, which will override REST Framework settings
* Fixed throbber.gif URL in the swagger-ui.min.js to point to Wordnik's resource
