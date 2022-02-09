
# APP MEGA-MENU

<!-- DOCS-IGNORE:start -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- DOCS-IGNORE:end -->

App Mega-Menu is useful while building menu to your store. User can customise the app as per their prefrence.

![image](https://user-images.githubusercontent.com/93201110/153180447-6d301081-ff0a-4d4e-8b55-e53fe4c7ef69.png)

## Configuration 

1. Install the app "echidna.megamenuapp": "0.x"
2. Add the "echidna.megamenuapp": "0.x" as a theme dependency in the `manifest.json` file

3. Now, you can use the main block exported by the mega-menu app. Check out the list below:

| Blaock name    |           Description    |                                                                                                                             
| ------------ |  --------------------------------------------------------------------------------------------------------------------------------------------- | 
| "megamenu-app"     |   ![image](https://user-images.githubusercontent.com/93201110/148353803-f3e867d2-4fe0-4166-94be-c9aa271df4c4.png) Enables you to customize the menu.            |

5. On the desire store page add the block to display the mega-menu app. 

## configuration

Check all props to configure your mega-menu in the table below:

| Prop name    | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | 
| navItems      | array       | List of array of objects. Each object should contains {id:integer, title:string, path:url of the page}      | undefined     |

further explained => id: should be the unique indentifier, title: title for nav-bar items, path: url of the page


Check all child blocks to configure your mega-menu in the table below:

| Child block name    | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | 
| DropdownItems      | array       | List of array of objects to display drop down items     | undefined     |

Check out below the props to declare the child block:

| Prop name      | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | 
| items      | array       | List of array of objects to display drop down items. Each object contains as {title:string, path:url, content:[array of objects]    | undefined     |

| Prop name    | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | 
| title      | string       |  title of each seaction(column)   | undefined     |
| path      | string       |  url for the items   | undefined     |
| content      | array       |  List of array of objects. Each object contains as {name: list item name, path: url for the item} | undefined     |


Below is the code snippet to display the block declaration:

![image](https://user-images.githubusercontent.com/93201110/153182787-6d29753d-650b-478a-869b-f2bc787d6515.png)

## Customization

`In order to apply CSS customizations in this and other blocks, follow the instructions given in the recipe on [Using CSS Handles for store customization](https://vtex.io/docs/recipes/style/using-css-handles-for-store-customization).`

To apply CSS customization in this and other blocks, follow the instructions given in the recipe on Using CSS Handles for store customization.

| CSS Handles |
| ----------- | 
| 'dropdownitems'|
| 'dropdownList'|
| 'dropdownContainer'|
|  'links'|
|  'menuLinks'|
|  'navbar'|
|  'navItems'|


## Contributors ✨

Thanks goes to these wonderful people

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!

<!-- DOCS-IGNORE:end -->

---- 

Check out some documentation models that are already live: 
- [Breadcrumb](https://github.com/vtex-apps/breadcrumb)
- [Image](https://vtex.io/docs/components/general/vtex.store-components/image)
- [Condition Layout](https://vtex.io/docs/components/all/vtex.condition-layout@1.1.6/)
- [Add To Cart Button](https://vtex.io/docs/components/content-blocks/vtex.add-to-cart-button@0.9.0/)
- [Store Form](https://vtex.io/docs/components/all/vtex.store-form@0.3.4/)
