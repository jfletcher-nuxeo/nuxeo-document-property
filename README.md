# IMPORTANT - This element is obsolete

This element is not really necessary. I discovered later that Polymer epxressions support complex types.  So you can simply use `nuxeo-document` to fetch the document and then use `[[doc.properties.dc:title]]`, for example.

However it is possiuble this could break, because the [Polymer binding documentation](https://www.polymer-project.org/1.0/docs/devguide/data-binding.html#array-binding) implies you should not use this syntax.

# nuxeo-document-property

An element to fetch a document property value. It supports scalar properties (e.g. `doc.properties["dc:title"]`) and one level of complex properties (e.g. `doc.properties["file:content"].name`).

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Quickstart

We recommend that you use [Polyserve](https://github.com/PolymerLabs/polyserve), which you can install via:

    npm install -g polyserve

And you can run it via:

    polyserve -p 3000

Once running, you can checkout demo at `http://localhost:3000/components/nuxeo-document-property/demo`.

## About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris. More information is available at [www.nuxeo.com](http://www.nuxeo.com).
