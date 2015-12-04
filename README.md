# origin.html

**origin.html** is the starting base for your (X)HTML5 templates.

The template is conforming to the [Polygot Markup specification](http://www.w3.org/TR/html-polyglot/), making it both parsable by a HTML5 and a XML processors.

**origin.html** is shipped with the support of the [Open Graph protocol](http://opengraphprotocol.org/).

## Template variables

### Site variables

- ```site.url``` preferred website's domain name and protocol. e.g. ```http://example.org```
- ```site.baseurl``` The relative path of the website. e.g. ```/website```
- ```site.name``` Main name
- ```site.alternate_name``` Alternative name

### Page variables

- ```page.date ``` [ISO 8601](http://www.iso.org/iso/home/standards/iso8601.htm) date format
- ```page.lang``` [ISO 639-1](http://www.iso.org/iso/home/standards/language_codes.htm) language and territory codes separated by a minus. e.g ```fr-FR```
- ```page.og_lang``` language and territory codes separated by an underscore. e.g ```fr_FR```
- ```page.permalink``` Desired URL to the resource (relative to ```site.baseurl```). e.g; ```/page```
- ```page.type``` Type of the resource. See the [types supported by the Open Graph protocol](http://opengraphprotocol.org/#types).
- ```page.title``` Name of the resource
- ```page.description``` Description of the resource
- ```page.tags``` Keywords
- ```page.author.display_name``` author's common name
- ```page.author.online_identity``` URI of the resource which represents the author on the web or url to a [human.txt](http://humanstxt.org/) file

## Libraries

**origin.html** loads [normalize.css](https://github.com/necolas/normalize.css) in order to improve the consistency between browsers.

