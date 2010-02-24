Eclipse Filters
===============

This plugin allows you to easily add additional file filter patterns to Eclipse's Project and Navigator views.
There is currently no UI for adding filters via Eclipse, but adding your own patterns is a simple matter. See 'Customization'.

Installation
------------

To install, simply download the directory com.jasonkarns.eclipse.filters as well as its plugin.xml file. Then simply drop this folder into your Eclipse installation's plugins directory. Restart Eclipse and you'll have new filters in your views.

Defaults
--------

By default, this plugin adds the following filter patterns:

- .svn
- .git
- .project
- Thumbs.db

Customization
-------------

To add your own filter patterns, simply add additional `filter` elements to the `extension` element in plugin.xml.
Patterns may use `*` and `?` wildcards.

[Eclipse Documentation](http://help.eclipse.org/ganymede/index.jsp?topic=/org.eclipse.platform.doc.isv/reference/extension-points/org_eclipse_ui_ide_resourceFilters.html)

Todo
----

Create a UI for adding/removing custom filters directly through Eclipse.
