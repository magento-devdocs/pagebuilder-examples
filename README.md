# Page Builder Examples

This repo is a collection of Page Builder content type modules created to teach you how Page Builder content types work. The modules will help you learn by example, and teach you best practices for developing custom Page Builder modules.

The Page Builder team members created these modules to serve as examples for learning. They are not fully tested or guaranteed to work perfectly. However, we will do our best to improve these examples and keep them updated with the latest releases of Page Builder.

## Extension Modules

-  **[Banner_Extension](Banner/Extension/README.md)** — This module shows you how to customize an existing content type: the Banner. This is the completed module featured in the documentation topic [Extend an appearance](https://devdocs.magento.com/page-builder/docs/content-types/extend/extend-an-appearance.html). Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Banner_Appearance](Banner/Appearance/README.md)** — This module shows you how to add a new appearance to the Banner. This is the completed module featured in the documentation topic [Add appearances](https://devdocs.magento.com/page-builder/docs/content-types/extend/add-appearances.html). Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Form_Extensions](Form/Extensions/README.md)** — This module shows you how to remove fields and fieldsets from Page Builder's built-in forms. Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Button_Extension](Button/Extension/README.md)** — This module shows how to add custom button types. Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Columns_Extension](Columns/Extension/README.md)** — This module shows how to add custom button types. Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Deactivate_PageBuilder](Deactivate/PageBuilder/README.md)** — This example module shows you how to disable Page Builder for a particular page in Magento, specifically Pages, Blocks, and Dynamic Blocks. Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Image_LazyLoading](Image/LazyLoading/README.md)** — This module shows how to add lazy loading behavior to the Image content type. For this example, we use the [lazysizes](https://github.com/aFarkas/lazysizes) loader. Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Slider_Extension](Slider/Extension/README.md)** — This module shows you how to add `centerMode` and `centerPadding` settings from the [slick carousel](https://kenwheeler.github.io/slick/) used by the Slider. Create by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Text_Extension](Text/Extension/README.md)** — This module shows you how to customize the Page Builder's Text toolbar, integrate your own theme's typography, and add TinyMCE's `code` plugin to the toolbar so you can view the HTML code directly. Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

## Custom Modules

-  **[Custom Quote](Quote/Custom/README.md)** — This module shows you how to create a content type for a customer testimonial. This is the completed Quote module featured in the documentation tutorial: [Creating content types](https://devdocs.magento.com/page-builder/docs/content-types/create/introduction.html). Created by [Bruce Denham](https://magentocommeng.slack.com/messages/UA3GYB2KW).

-  **[Custom Homepage Grid](Grid/Custom/README.md)** — This module shows you how to create a content type that recreates the layout of the Magento Luma-themed home page using a grid structure with grid items. Created by [Dave Macaulay](https://github.com/davemacaulay).

-  **[Custom FAQ](FAQ/Custom/README.md)** — This module shows you how to create a content type for an FAQ page that uses an accordion for the questions and answers. Created by [Igor Melnikov](https://github.com/melnikovi).

## Module Installation

Install these example modules as you do any other Magento module:

1. Clone the `pagebuilder-examples` repo into your Magento instance root directory.

1. Symlink the repo into the `app/code/` directory, as shown here:

    ```terminal
    ln -s <Relative_route_to_repo_directory>
    ```

1. Install and enable the example modules with the `setup:upgrade` command:

   ```bash
   bin/magento setup:upgrade
   ```

1. Navigate to CMS page to ensure the example content types appear in the Page Builder panel as shown here:

## Contributing

We encourage and welcome you to help us keep these examples current by submitting PRs and issues.
We also welcome your feedback and ideas about creating other code examples to add to this repo.
