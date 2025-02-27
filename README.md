# pokedecks-theme-custom

Theme follows the standard shopify directory structure
|_assets
|_ blocks
|_ config
|_ layout
|_ locales
|_ sections
|_ snippets
|_ templates
    |__ customers
    |__ metaobjects

Assets
The assets directory contains all assets used in the theme.
Assets can be referenced using asset_url Liquid URL filter.

Config
The config directory contains the config files for the theme.
These files define the settings and store their values.

Layout
The Layout directory contains the layout files used to render templates.
The theme.liquid file contains content to be repeated across multiple pages.

Locales
Includes locale files used to translate content.

Sections
Contains the themes sections and section groups.
Sections can be used to create reusable content modules and blocks.

Snippets
Contains reusable code snippets. 
Snippets can be referenced using the render tag and filename {% render 'filename' %}

Templates
Contains the template files which control the content rendered on each page.
Each page type in an online store is associated with a template type.