
#### v2.0.0 `February 21, 2023`

**New Features:**
- The `Image|Card` module now respects image size by default, with an additional option to make it full width of the image column. Please note that this is a **breaking change**, and you should be careful when implementing it.
- The `Theme` settings template has been replaced with the site `Brand-book` template with a new design.
- A new supported type for links and buttons has been added: `Pop-up Call To Action`

**Improvements:**
- Default Title and Meta-description have been added for all templates.
- Default English translations for all modules have been added.
- Template preview and content default images have been optimized and compressed.
- Standard HubSpot modules that duplicate functionality of Nimbly have been **hidden**.
- Preview image has been simplified for the `Blank` template.
- The placeholder company name will now be displayed if no real company name is found in the account settings.
- The `Form` module will now show nothing if no form is selected.
- Color contrast accessibility for sections has been improved.

**Bug Fixes:**
- A height attribute has been added for the background image in the `Heroimage` module to fix cumulative layout shift and pagespeed issues.
- The boolean module inside global header settings no longer has a `styles` tab.
- Duplicated `meta viewport` tag has been removed.
- Styling for the skip-to-main-content link has been fixed.
- The dropdown current language item will now only be rendered if "show current language" is true.
- The styling inheritance issue for a secondary button in modules has been fixed.
- Style settings from the HubSpot Style editor will now be applied to the active link in the `Blog pagination` module.
- Textarea placeholder styles have been added to make it editable the same as inputs in the `Form` module.
- Broken styles for `icon macros` have been fixed.

**Changelog:**

- **[TASK]** update @resultify/hubspot-cms-lib, update npm deps ([8aa8c29](https://github.com/Resultify/nimbly-lite/commit/8aa8c29))
- **[TEST]** add new deploy and validate github actions ([69be4ad](https://github.com/Resultify/nimbly-lite/commit/69be4ad))
- **[TASK]** show the placeholder company name if there is no real in the account profile ([bbbb3f3](https://github.com/Resultify/nimbly-lite/commit/bbbb3f3))
- **[TASK]** show nothing if no form selected in the form module ([495f55f](https://github.com/Resultify/nimbly-lite/commit/495f55f))
- **[BUGFIX]** fix broken styles for icon macros ([902b35d](https://github.com/Resultify/nimbly-lite/commit/902b35d))
- **[TASK]** improve color contrast accessibility for sections ([e66465e](https://github.com/Resultify/nimbly-lite/commit/e66465e))
- **[TEST]** add marketplace validation and lighthouse CI tests ([8ccace2](https://github.com/Resultify/nimbly-lite/commit/8ccace2))
- **[TASK]** update hubspot-cms-lib to v2 ([941bd98](https://github.com/Resultify/nimbly-lite/commit/941bd98))
- **[TASK]** add height attribute for heroimage module background image, use tag <img> instead of hubl image tag ([d837497](https://github.com/Resultify/nimbly-lite/commit/d837497))
- **[TASK]** add default title and meta_description for all templates ([1e403bd](https://github.com/Resultify/nimbly-lite/commit/1e403bd))
- **[TASK]** add default en translations for all modules ([5979c56](https://github.com/Resultify/nimbly-lite/commit/5979c56))
- **[TASK]** optimize and compress images ([b144c89](https://github.com/Resultify/nimbly-lite/commit/b144c89))
- **[TASK]** update config for boolean module, add dnd_area to global header settings ([ea431ee](https://github.com/Resultify/nimbly-lite/commit/ea431ee))
- **[TASK]** add marketplace-validate and lighthouse score tasks ([372816d](https://github.com/Resultify/nimbly-lite/commit/372816d))
- **[TASK]** update npm deps ([9d05ae4](https://github.com/Resultify/nimbly-lite/commit/9d05ae4))
- **[BUGFIX]** fix the issue with the boolean module having 'styles' tab (#55) ([2d340a1](https://github.com/Resultify/nimbly-lite/commit/2d340a1))
- **[TASK]** remove theme settings template ([cf5c2c0](https://github.com/Resultify/nimbly-lite/commit/cf5c2c0))
- **[TASK]** hide standard HubSpot modules that duplicate functionality ([24f6085](https://github.com/Resultify/nimbly-lite/commit/24f6085))
- **[BUGFIX]** remove duplicated tag meta viewport ([0c2a644](https://github.com/Resultify/nimbly-lite/commit/0c2a644))
- **[TASK]** remove branding and simplify preview image for blank template ([360a788](https://github.com/Resultify/nimbly-lite/commit/360a788))
- **[FEATURE]** add site-brand-book template ([a412325](https://github.com/Resultify/nimbly-lite/commit/a412325))
- **[BUGFIX]** fix class name for skip-to-main-content link ([ffbada1](https://github.com/Resultify/nimbly-lite/commit/ffbada1))
- **[TASK]** add new supported type for links and buttons (#52) ([e7ac452](https://github.com/Resultify/nimbly-lite/commit/e7ac452))
- **[BUGFIX]** render dropdown current language item only if show_current_l… (#48) ([3bb25ea](https://github.com/Resultify/nimbly-lite/commit/3bb25ea))
- **[FEATURE]** add 'secondary' class for a secondary button in a module (#51) ([ea12bb8](https://github.com/Resultify/nimbly-lite/commit/ea12bb8))
- **[BUGFIX]** apply settings for active link in blog pagination module (#50) ([4c4b49e](https://github.com/Resultify/nimbly-lite/commit/4c4b49e))
- **[BUGFIX]** add textarea:placeholder styles so it editable same as inputs (#49) ([f6f82af](https://github.com/Resultify/nimbly-lite/commit/f6f82af))
- **[TASK]** typo Headquarters (#47) ([d76a676](https://github.com/Resultify/nimbly-lite/commit/d76a676))
- **[TASK]** add upload to HubSpot github action ([375406c](https://github.com/Resultify/nimbly-lite/commit/375406c))
- **[TASK]** update npm deps ([7feadd3](https://github.com/Resultify/nimbly-lite/commit/7feadd3))
- **[TEST]** update github action npm test, use checkout@v3 and setup-node@v3 with cache enabled ([3677236](https://github.com/Resultify/nimbly-lite/commit/3677236))
- **[BUGFIX]** use modules to define global partial content instead of sections due to an unknown bug and not being able to edit global content because of this ([d4f8912](https://github.com/Resultify/nimbly-lite/commit/d4f8912))
- **[BUGFIX]** check for logo.override_inherited_src when defining a logo link ([196fb93](https://github.com/Resultify/nimbly-lite/commit/196fb93))
- **[TASK]** add example_url and documentation_url to theme.json ([39e1131](https://github.com/Resultify/nimbly-lite/commit/39e1131))
- **[TASK]** use bigger width 1900px for template-previews screenshots ([abf6e60](https://github.com/Resultify/nimbly-lite/commit/abf6e60))
- **[TASK]** rename (heading,icon,button,form,text,divider) nimbly modules to have different names compared to Hubspot default modules names ([a964f71](https://github.com/Resultify/nimbly-lite/commit/a964f71))
- **[TASK]** use one style for all module icons, add nimbly branding for each icon ([a6d41f9](https://github.com/Resultify/nimbly-lite/commit/a6d41f9))
- **[TASK]** change global partials dnd_area names to fix warnings ([896a5e1](https://github.com/Resultify/nimbly-lite/commit/896a5e1))
- **[TASK]** use only relative path for all includes, ([9ec509e](https://github.com/Resultify/nimbly-lite/commit/9ec509e))
- **[TASK]** add description to all sections ([4951fe3](https://github.com/Resultify/nimbly-lite/commit/4951fe3))
- **[BUGFIX]** rename image caption text field on image-card module, text -> rich_text (#46) ([67fe9dc](https://github.com/Resultify/nimbly-lite/commit/67fe9dc))

:heavy_exclamation_mark:**Breaking Changes:**
- **[!!!]** **[FEATURE]** respect image size in the image card module as a default behavior,  with an additional option to make it the full width of the image column (#54) ([27706e7](https://github.com/Resultify/nimbly-lite/commit/27706e7))

***

#### v1.0.0 `December 5, 2022`

- **[DOC]** add repo README with quick-start info, cmd list and authentication instruction ([d5054c9](https://github.com/Resultify/nimbly-lite/commit/d5054c9))
- **[TASK]** update @resultify/hubspot-cms-lib to v1.0.0 ([b6fb65d](https://github.com/Resultify/nimbly-lite/commit/b6fb65d))
- **[TASK]** update template-previews, use Nimbly Lite as a label for theme ([f99e34e](https://github.com/Resultify/nimbly-lite/commit/f99e34e))
- **[BUGFIX]** fix the dropdown by downgrade Bootstrap, fix forms and siteheader on mobile ([fac890b](https://github.com/Resultify/nimbly-lite/commit/fac890b))
- **[TASK]** add blog-post and blog-list templates ([1d9ebd2](https://github.com/Resultify/nimbly-lite/commit/1d9ebd2))
- **[TASK]** add blank, contact, about and theme-settings template-previews ([639ae7b](https://github.com/Resultify/nimbly-lite/commit/639ae7b))
- **[TASK]** add absolute path to modules in site-footer section ([ae1d3a3](https://github.com/Resultify/nimbly-lite/commit/ae1d3a3))
- **[TASK]** add contact template ([b9a7b9b](https://github.com/Resultify/nimbly-lite/commit/b9a7b9b))
- **[TASK]** compress images ([4edcf3e](https://github.com/Resultify/nimbly-lite/commit/4edcf3e))
- **[TASK]** use relative path in about template sections ([e352967](https://github.com/Resultify/nimbly-lite/commit/e352967))
- **[TASK]** add about template ([a58936e](https://github.com/Resultify/nimbly-lite/commit/a58936e))
- **[TASK]** update home and about sections, add more section-previews ([0f44343](https://github.com/Resultify/nimbly-lite/commit/0f44343))
- **[TASK]** add sections for about template ([105ffc9](https://github.com/Resultify/nimbly-lite/commit/105ffc9))
- **[TASK]** optimize content images, small layout fixes ([71c74b8](https://github.com/Resultify/nimbly-lite/commit/71c74b8))
- **[TASK]** add nimbly relative path for home template sections ([c647efb](https://github.com/Resultify/nimbly-lite/commit/c647efb))
- **[TASK]** add more svg variants to svg divider, add section-previews, update home template sections ([04631a0](https://github.com/Resultify/nimbly-lite/commit/04631a0))
- **[TASK]** add home template ([273e358](https://github.com/Resultify/nimbly-lite/commit/273e358))
- **[TASK]** add home template sections ([9430714](https://github.com/Resultify/nimbly-lite/commit/9430714))
- **[TASK]** update stylelint config, fix stylelint errors ([a66f76f](https://github.com/Resultify/nimbly-lite/commit/a66f76f))
- **[TASK]** add divider module ([38a4b9b](https://github.com/Resultify/nimbly-lite/commit/38a4b9b))
- **[TASK]** update hubspot-cms-lib and bootstrap pkg-s ([09cf0cd](https://github.com/Resultify/nimbly-lite/commit/09cf0cd))
- **[TASK]** update svg-divider, add header and footer section, use sections in global partials ([f819c4a](https://github.com/Resultify/nimbly-lite/commit/f819c4a))
- **[TASK]** add new design content images ([c9b4057](https://github.com/Resultify/nimbly-lite/commit/c9b4057))
- **[TASK]** add vertical_spacing for grid layout ([8095ed2](https://github.com/Resultify/nimbly-lite/commit/8095ed2))
- **[TASK]** increase default margins for headings, collapse top margins for subheading ([4f11dc1](https://github.com/Resultify/nimbly-lite/commit/4f11dc1))
- **[TASK]** align global heading and icon size with new design ([3c644e2](https://github.com/Resultify/nimbly-lite/commit/3c644e2))
- **[TASK]** update global options according to new design ([b79c91d](https://github.com/Resultify/nimbly-lite/commit/b79c91d))
- **[TASK]** fix CSS styling ([5cb1b46](https://github.com/Resultify/nimbly-lite/commit/5cb1b46))
- **[TASK]** add resultify/hubspot-cms-lib, update npm deps ([d236a67](https://github.com/Resultify/nimbly-lite/commit/d236a67))
- **[TASK]** update form, make error border visible if custom styling ([61616cf](https://github.com/Resultify/nimbly-lite/commit/61616cf))
- **[TASK]** add icons for modules ([741e4d4](https://github.com/Resultify/nimbly-lite/commit/741e4d4))
- **[TASK]** add system templates, subscriptions-confirmation, subscription-preferences, backup-unsubscribe ([ef61e3d](https://github.com/Resultify/nimbly-lite/commit/ef61e3d))
- **[TASK]** update password-prompt template ([08a7018](https://github.com/Resultify/nimbly-lite/commit/08a7018))
- **[TASK]** update/simplify form global option and form module ([7aad3f7](https://github.com/Resultify/nimbly-lite/commit/7aad3f7))
- **[TASK]** add a password-prompt system template ([95d2ff0](https://github.com/Resultify/nimbly-lite/commit/95d2ff0))
- **[TASK]** add custom styles to form module ([a891106](https://github.com/Resultify/nimbly-lite/commit/a891106))
- **[BUGFIX]** fix template warnings ([3455688](https://github.com/Resultify/nimbly-lite/commit/3455688))
- **[TASK]** correct naming according to Nimbly standard module Style tab convention ([d65feed](https://github.com/Resultify/nimbly-lite/commit/d65feed))
- **[TASK]** fix caption styling for image and figure macros ([9d61b36](https://github.com/Resultify/nimbly-lite/commit/9d61b36))
- **[TASK]** update global settings, update grid layout, update theme settings template ([714a195](https://github.com/Resultify/nimbly-lite/commit/714a195))
- **[TASK]** rename buttons, remove default form styling from form module ([0acf966](https://github.com/Resultify/nimbly-lite/commit/0acf966))
- **[TASK]** add form global options, add form module ([170736a](https://github.com/Resultify/nimbly-lite/commit/170736a))
- **[TASK]** refactor faq module ([7960664](https://github.com/Resultify/nimbly-lite/commit/7960664))
- **[TASK]** refactor image-card module ([1d11092](https://github.com/Resultify/nimbly-lite/commit/1d11092))
- **[TASK]** add inline editor tooltips with component name ([29aacf0](https://github.com/Resultify/nimbly-lite/commit/29aacf0))
- **[TASK]** update svg-divider module, add predefined svg options ([75c5935](https://github.com/Resultify/nimbly-lite/commit/75c5935))
- **[TASK]** refactor card, heroimage, template, image-card modules, other fixes ([c95de27](https://github.com/Resultify/nimbly-lite/commit/c95de27))
- **[TASK]** temporary hide unfinished modules, rearrange module fields ([37714af](https://github.com/Resultify/nimbly-lite/commit/37714af))
- **[TASK]** remove old variants of macros and modules ([6e68003](https://github.com/Resultify/nimbly-lite/commit/6e68003))
- **[TASK]** refactor text,richtext, heading, icon macros, upgrade card module ([f6d1c50](https://github.com/Resultify/nimbly-lite/commit/f6d1c50))
- **[TASK]** remove disable button setting from all modules ([32c4640](https://github.com/Resultify/nimbly-lite/commit/32c4640))
- **[TASK]** refactoring button, link, icon macros and modules ([f2a7bfc](https://github.com/Resultify/nimbly-lite/commit/f2a7bfc))
- **[TASK]** add blank layout and template ([c2374c2](https://github.com/Resultify/nimbly-lite/commit/c2374c2))
- **[TASK]** accessibility improvements for main nav, add role=search and role=list ([11add83](https://github.com/Resultify/nimbly-lite/commit/11add83))
- **[TASK]** implement class naming convention ([fef6393](https://github.com/Resultify/nimbly-lite/commit/fef6393))
- **[TASK]** update modules naming, add module icons ([3c258fc](https://github.com/Resultify/nimbly-lite/commit/3c258fc))
- **[TASK]** update accessibility for lang menu, add more styles for prefers-reduced-motion option ([bfcb08a](https://github.com/Resultify/nimbly-lite/commit/bfcb08a))
- **[TASK]** update theme.json info, add screenshot, example_url ([c2b8d28](https://github.com/Resultify/nimbly-lite/commit/c2b8d28))
- **[TASK]** remove filter-content connection, update theme.json, remove bootstrap css ([9de4329](https://github.com/Resultify/nimbly-lite/commit/9de4329))
- **[TASK]** update global settings, add vertical_spacing for grid, remove site header options ([eba35db](https://github.com/Resultify/nimbly-lite/commit/eba35db))
- **[TASK]** aggregate all macros template options in one object ([5afc53f](https://github.com/Resultify/nimbly-lite/commit/5afc53f))
- **[TASK]** refactoring, less bootstrap, remove sticky_header from theme settings, proper naming for templates ([1f46afe](https://github.com/Resultify/nimbly-lite/commit/1f46afe))

***
