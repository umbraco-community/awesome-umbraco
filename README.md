# Awesome Umbraco! [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome [Umbraco 7](http://umbraco.com/) packages, resources and shiny things.

Inspired by [awesome lists](https://github.com/sindresorhus/awesome). For general C#/.NET please see the [awesome-dotnet](https://github.com/quozd/awesome-dotnet/) collection!

**Contributions are always welcome!** Please read the [contribution guidelines and quality standard](https://github.com/leekelleher/awesome-umbraco/blob/master/CONTRIBUTING.md) page before making a pull-request.

Thank you to all [contributors](https://github.com/leekelleher/awesome-umbraco/graphs/contributors), you are awesome and this list wouldn't be possible without you!

The goal is to build a categorized community-driven collection of very well-known resources.

* [Backoffice extensions](#backoffice-extensions)
  * [Form Builders](#form-builders)
  * [Grid Editors](#grid-editors)
  * [Property Editors](#property-editors)
  * [SEO Tools](#seo-tools)
* [Developer tools](#developer-tools)
  * [Deployment](#deployment)
* [eCommerce & CRM](#ecommerce-crm)
* [Starter Kits](#starter-kits)
* [Website utilities](#website-utilities)
* [Code Libraries](#code-libraries)

Please note * indicates that the package is commercial or may require a license to unlock all features.

## Backoffice extensions

* [Analytics](https://our.umbraco.org/projects/backoffice-extensions/analytics) - Integrates Google Analytics statistics within the back-office.
* [Config Tree](https://our.umbraco.org/projects/developer-tools/config-tree) - Edit `*.config` files within the back-office.
* [Robots.txt editor](https://our.umbraco.org/projects/developer-tools/robotstxt-editor) - Edit robots.txt from within the back-office.
* [UI-O-Matic](https://our.umbraco.org/projects/developer-tools/ui-o-matic/) - Auto generate an integrated crud UI in Umbraco for a db table based on a petapoco poco.
* [Find and Replace](https://our.umbraco.org/projects/backoffice-extensions/find-and-replace/) - A simple and intuitive package which allows editors to find and replace content.
* [Nexu](https://our.umbraco.org/projects/backoffice-extensions/nexu) - Keeps tracks of internal links by parsing property data. Will warn editors when something is "in use" when deleting or unpublishing. It's extensible so you can create parsers for your own property or grid editors.
* [Umbraco Latch](https://our.umbraco.org/projects/backoffice-extensions/umbraco-latch/) - Protect different operations in the backoffice like login, create content, etc. using the Latch service.

### Form Builders

* [Umbraco Forms*](http://umbraco.com/forms) - The new Contour, use this to add forms to your site. **(Developed by Umbraco HQ)**
* [Form Editor](https://github.com/kjac/FormEditor) - An editor friendly form builder for creating forms as part of the web content.
* [Formulate](https://our.umbraco.org/projects/backoffice-extensions/formulate/) - Build website forms (contact forms, newsletter sign ups, surveys, job applications) with no coding.

### Grid Editors

* [Doc Type Grid Editor](https://our.umbraco.org/projects/backoffice-extensions/doc-type-grid-editor/) - Advanced grid editor for Umbraco.

### Property Editors

* [Archetype](https://our.umbraco.org/projects/backoffice-extensions/archetype) - Group multiple property-editors.
* [Multi Url Picker](https://our.umbraco.org/projects/backoffice-extensions/multi-url-picker/) - Allows editors to pick and sort multiple urls, it uses Umbraco's link picker which supports internal and external links and media.
* [nuPickers](https://our.umbraco.org/projects/backoffice-extensions/nupickers) - Lots of Picker type property-editors.
* [Nested Content](https://our.umbraco.org/projects/backoffice-extensions/nested-content/) - list editing property-editor, uses doc types to define the list item blue prints.
* [Sir Trevor](https://our.umbraco.org/projects/backoffice-extensions/sir-trevor) - An intuitive property-editor for web content.
* [Skybrud.LinkPicker](https://our.umbraco.org/projects/backoffice-extensions/skybrudlinkpicker/) - a configurable link picker that can be used as either a property editor or grid editor. Supports selecting content, media or specify external URLs.
* [Skybrud.ImagePicker](https://our.umbraco.org/projects/backoffice-extensions/skybrudimagepicker/) - a configurable image picker that can be used as either a property editor or grid editor. Each image can be supplemented with a title, description and/or link.
* [Styled Textbox](https://our.umbraco.org/projects/backoffice-extensions/styled-textbox/) - A configural property editor to "replace" the generic textbox & textarea properties. It allows for inline CSS as well as adding classes and having placeholder text.
* [Switcher](https://our.umbraco.org/projects/backoffice-extensions/switcher/) - A simple property editor that works as an alternative to the core true/false datatype.
* [Terratype](https://our.umbraco.org/projects/backoffice-extensions/terratype/) - A fully featured maps data type  supporting multiple map providers (Google Maps, Bing, Leaflet).
* [Vorto](https://our.umbraco.org/projects/backoffice-extensions/vorto) - Property-editor wrapper for multilingual content entry.
* [Meganav](https://our.umbraco.org/projects/website-utilities/meganav/) - A flexible, draggable link picker for constructing site navigation menus, big or small.
* [OEmbed Picker Property Editor](https://our.umbraco.org/projects/backoffice-extensions/oembed-picker-property-editor/) - Property editor to allow embedding 3rd party media like Youtube, Vimeo, ... outside of the rich text editor.

### SEO Tools

* [SEO Checker*](http://soetemansoftware.nl/seo-checker) - find common SEO issues in your Umbraco website.
* [SEO Metadata](https://our.umbraco.org/projects/backoffice-extensions/seo-metadata-for-umbraco/) - Property-editor for maintaining SEO metadata against your DocTypes.
* [RankOne - SEO Toolkit](https://our.umbraco.org/projects/backoffice-extensions/rankone-seo-toolkit/) - provides a collection of SEO tools for Umbraco that aim to optimize your content according to the latest SEO standards.

## Developer tools

* [301 URL Tracker](https://our.umbraco.org/projects/developer-tools/301-url-tracker) - Manage and redirect legacy URLs.
* [Optimus](https://our.umbraco.org/projects/developer-tools/optimus) - Bundling and minification of your CSS and Javascript.
* [CMSImport*](http://soetemansoftware.nl/cmsimport) - import content or members from any datasource into Umbraco.
* [uSync](https://our.umbraco.org/projects/developer-tools/usync/) - Syncing tool for reading and writing the database elements to disk.
* [Diplo Trace Log Viewer](https://our.umbraco.org/projects/developer-tools/diplo-trace-log-viewer/) - view Umbraco log files directly from the Developer section in Umbraco.

### Deployment

* [Courier*](http://umbraco.com/products/more-add-ons/courier-2) - Deploy changes from within the back-office. **(Developed by Umbraco HQ)**

## eCommerce &amp; CRM

* [Merchello](http://www.merchello.com/) - High performance, open source eCommerce package.
* [uCommerce*](http://www.ucommerce.net/) - .NET eCommerce platform, seamlessly integrates with Umbraco.
* [Tea Commerce*](http://www.teacommerce.net/) - eCommerce built on top of Umbraco.
* [Pipeline CRM*](https://our.umbraco.org/projects/backoffice-extensions/pipeline-crm/) - Customer Relationship Management for Umbraco.

## Starter Kits

* [Articulate](https://our.umbraco.org/projects/starter-kits/articulate) - Blogging platform.
* [Dialogue](https://our.umbraco.org/projects/collaboration/dialogue) -  Fully featured forum / bulletin-board.
* [Hybrid Framework](https://our.umbraco.org/projects/developer-tools/hybrid-framework-for-umbraco-v7) - Visual Studio starter-kit, showcasing best practices.
* [LocalGov Starter Kit](https://our.umbraco.org/projects/starter-kits/localgov-starter-kit) - Local government style website.

## Website utilities

* [ezSearch](https://our.umbraco.org/projects/website-utilities/ezsearch) - Add-on website search.
* [Slimsy](https://our.umbraco.org/projects/website-utilities/slimsy) - Responsive Images using Slimmage for Umbraco.
* [Cultiv DynamicRobots](https://our.umbraco.org/projects/website-utilities/cultiv-dynamicrobots) - Updates the host in robots.txt for multisite solution.
* [Robotnik](https://our.umbraco.org/projects/developer-tools/robotnik/) - Specify a different robots.txt for each domain (staging/production, brand 1/brand 2).
* [Full Text Search](https://our.umbraco.org/projects/website-utilities/full-text-search/) - A search solution for Umbraco.
* [UnVersion](https://our.umbraco.org/projects/website-utilities/unversion/) - Removes previous versions of content.

## Code Libraries

* [Ditto](https://our.umbraco.org/projects/developer-tools/ditto/) - a lightweight model mapper for `IPublishedContent`.
* [Zbu Models Builder](https://github.com/zpqrtbnk/Zbu.ModelsBuilder) - generate strongly-typed `IPublishedContent` models automagically.
* [Umbraco Core Property Value Converters](https://our.umbraco.org/projects/developer-tools/umbraco-core-property-value-converters) - implements converters for the Umbraco Core property-editors.
* [Skybrud.Umbraco.GridData](https://our.umbraco.org/projects/developer-tools/skybrudumbracogriddata/) - a package for making the Umbraco grid strongly typed.


---

# License

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
