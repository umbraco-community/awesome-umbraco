# Awesome Umbraco! [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/main/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome [Umbraco CMS](https://github.com/umbraco/Umbraco-CMS/) packages, resources and shiny things.

Inspired by [awesome lists](https://github.com/sindresorhus/awesome). For general C#/.NET please see the [awesome-dotnet](https://github.com/quozd/awesome-dotnet/) collection!

### Contributing

**Contributions are always welcome!** 

Please read the [contribution guidelines and quality standard](https://github.com/umbraco-community/awesome-umbraco/blob/master/CONTRIBUTING.md) page before making a pull-request. If you see a resource or package here that is no longer maintained, please submit a pull request to help improve this collection.

Thank you to all [contributors](https://github.com/umbraco-community/awesome-umbraco/graphs/contributors), you are awesome and this list wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

### Contents
This list is for Umbraco v8, if you looking for v7, you can find those [here](UMBRACO-V7.md).

* [Official](#official)
* [Community](#community)
* [Backoffice extensions](#backoffice-extensions)
  * [Form Builders](#form-builders)
  * [Grid Editors](#grid-editors)
  * [Property Editors](#property-editors)
  * [SEO Tools](#seo-tools)
* [Developer tools](#developer-tools)
  * [Deployment](#deployment)
* [eCommerce & CRM](#ecommerce--crm)
* [Starter Kits](#starter-kits)
* [Website utilities](#website-utilities)
* [Code Libraries](#code-libraries)

Please note * indicates that the package is commercial or may require a license to unlock all features.

## Official

* [Umbraco website](https://umbraco.com)
* [CodeGarden Conference](https://codegarden20.com/)
* [Documentation](https://our.umbraco.com/documentation/)
* [Download](https://our.umbraco.com/download/)
* [Forum](https://our.umbraco.com/forum/)
* [Meetups](https://www.meetup.com/pro/umbraco)
* [Official YouTube Channel](https://www.youtube.com/umbracohq) - tutorials and other helpful videos about Umbraco products.

## Community

* [#h5yr](https://h5yr.com/) - High Five, You Rock!
* [24 Days In Umbraco](https://24days.in/umbraco-cms/) - yearly advent calendar for Umbraco content.
* [Blog Posts](https://our.umbraco.com/community/blog-posts/) - blog posts by members of the Umbraco community and Umbraco HQ.
* [Candid Contributions](https://candidcontributions.com/) - a fortnightly podcast discussing all things Umbraco and open source.
* [Skrift](https://skrift.io/) - a monthly magazine for sharing knowledge in the Umbraco community.
* [umbraCoffee](https://www.youtube.com/umbracoffee) - a weekly YouTube series discussing recent Umbraco news.
* [Unicorner](https://www.youtube.com/playlist?list=PLG_nqaT-rbpwZDRQmlfzslbJ-4UjgDcw0) - YouTube series from the Chief Unicorn, Niels Hartvig.
* [Official YouTube Channel](https://www.youtube.com/c/umbracocommunity/) - the Umbraco community YouTube channel.

---

## Backoffice extensions

* [Find and Replace](https://our.umbraco.org/projects/backoffice-extensions/find-and-replace/) - A simple and intuitive package which allows editors to find and replace content.
* [Nexu](https://our.umbraco.org/projects/backoffice-extensions/nexu) - Keeps tracks of internal links by parsing property data. Will warn editors when something is "in use" when deleting or unpublishing. It's extensible so you can create parsers for your own property or grid editors.
* [Plumber](https://our.umbraco.com/packages/backoffice-extensions/plumber-workflow-for-umbraco/) - adds a heap of useful bits and pieces to Umbraco, to allow multi-staged workflow approval.
* [Robots.txt editor](https://our.umbraco.org/projects/developer-tools/robotstxt-editor) - Edit robots.txt from within the back-office.
* [Translation Manager*](https://our.umbraco.com/packages/backoffice-extensions/translation-manager/) - lets you handle all of the steps of the translation process from within Umbraco.
* [UI-O-Matic](https://our.umbraco.org/projects/developer-tools/ui-o-matic/) - Auto generate an integrated crud UI in Umbraco for a db table based on a petapoco poco.
* [Page Not Found Manager] (https://our.umbraco.com/packages/backoffice-extensions/umbraco-page-not-found-manager/) - Manage your sites 404 page(s) from Umbraco

### Form Builders

* [Formulate](https://our.umbraco.org/projects/backoffice-extensions/formulate/) - Build website forms (contact forms, newsletter sign ups, surveys, job applications) with no coding.
* [Umbraco Forms*](https://umbraco.com/products/umbraco-forms/) - The new Contour, use this to add forms to your site. **(Developed by Umbraco HQ)**

### Grid Editors

* [Doc Type Grid Editor](https://our.umbraco.org/projects/backoffice-extensions/doc-type-grid-editor/) - Advanced grid editor for Umbraco.

### Property Editors

* [Meganav](https://our.umbraco.org/projects/website-utilities/meganav/) - A flexible, draggable link picker for constructing site navigation menus, big or small.
* [OEmbed Picker Property Editor](https://our.umbraco.org/projects/backoffice-extensions/oembed-picker-property-editor/) - Property editor to allow embedding 3rd party media like Youtube, Vimeo, ... outside of the rich text editor.
* [Personalisation Groups](https://our.umbraco.com/packages/website-utilities/personalisation-groups/) - allow personalisation of content to different groups of site visitors
* [Skybrud.ImagePicker](https://our.umbraco.org/projects/backoffice-extensions/skybrudimagepicker/) - a configurable image picker that can be used as either a property editor or grid editor. Each image can be supplemented with a title, description and/or link.
* [Skybrud.LinkPicker](https://our.umbraco.org/projects/backoffice-extensions/skybrudlinkpicker/) - a configurable link picker that can be used as either a property editor or grid editor. Supports selecting content, media or specify external URLs.
* [Styled Editors](https://our.umbraco.com/packages/developer-tools/styled-editors-for-umbraco-8/) - A configural property editor to "replace" the generic textbox & textarea properties. It allows for inline CSS as well as adding classes and having placeholder text.
* [Switcher](https://our.umbraco.org/projects/backoffice-extensions/switcher/) - A simple property editor that works as an alternative to the core true/false datatype.
* [Terratype](https://our.umbraco.org/projects/backoffice-extensions/terratype/) - A fully featured maps data type  supporting multiple map providers (Google Maps, Bing, Leaflet).
* [uEditorNotes](https://our.umbraco.org/projects/backoffice-extensions/ueditornotes/) - Provides a way to display instructional messages for content editors, at the point of content entry.

### SEO Tools

* [SEO Checker*](https://soetemansoftware.nl/seo-checker) - find common SEO issues in your Umbraco website.

## Developer tools

* [CMSImport*](https://soetemansoftware.nl/cmsimport) - import content or members from any datasource into Umbraco.
* [Optimus](https://our.umbraco.org/projects/developer-tools/optimus) - Bundling and minification of your CSS and Javascript.
* [uSync](https://our.umbraco.org/projects/developer-tools/usync/) - Syncing tool for reading and writing the database elements to disk.
* [Skybrud.Umbraco.Redirects](https://our.umbraco.com/packages/website-utilities/skybrud-redirects/) - Redirects manager for Umbraco.
* [Our HealthChecks](https://our.umbraco.com/packages/backoffice-extensions/ourumbracohealthchecks/) - Adds addtional health checks to the back office.

### Deployment

* [Deploy Contrib](https://github.com/umbraco/Umbraco.Deploy.Contrib) - Offers value-connectors for the most popular Umbraco community packages. To allow Umbraco Cloud deploy to transfer content/property-data to a target environment. **(Maintained by Umbraco HQ)** _Umbraco Cloud only_

## eCommerce &amp; CRM

* [Vendr*](https://vendr.net/) - eCommerce built on top of Umbraco.
* [uCommerce*](https://ucommerce.net/) - .NET eCommerce platform, seamlessly integrates with Umbraco.

## Starter Kits

* [Articulate](https://our.umbraco.org/projects/starter-kits/articulate) - Blogging platform.

## Website utilities

* [Slimsy](https://our.umbraco.org/projects/website-utilities/slimsy) - Responsive Images using Slimmage for Umbraco.
* [UnVersion](https://our.umbraco.org/projects/website-utilities/unversion/) - Removes previous versions of content.
* [Matryoshka](https://our.umbraco.com/packages/backoffice-extensions/matryoshka-tabs-for-umbraco-8/) - Adding back tabs in Umbraco

## Code Libraries

* [Skybrud.Umbraco.GridData](https://our.umbraco.org/projects/developer-tools/skybrudumbracogriddata/) - a package for making the Umbraco grid strongly typed.


---

# License

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
