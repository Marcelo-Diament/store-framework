# store-framework-template
The template repository for the Store Framework course on Learning Lab.
___

### Installation

In order to run as expected, store-framework requires the following resources/tools:

* [gitBash](https://git-scm.com/downloads), 
* [Node.js](https://nodejs.org/) v4+
* Toolbelt (`` `npm i -g vtex` ``)

It is necessary to create a develop workspace, with a specific name. So you must:

1. Login in you VTEX account:
`` `vtex login applianctetheme` ``

2. Test you access status:
`` `vtex whoami` ``

3. Use (and create if necessary) a workspace
`` `vtex use {workspace}` ``

4. Access you Workspace
`` `https://{workspace}--{account}.myvtex.com` ``

5. Link you Workspace to the browser
`` `vtex link` ``

## Lessons x branches

| # | Lesson | Branch |
| ------ | ------ | ------ |
| 01 | Basic Configurations |  |
| 02 | Store Framework 101 |  |
| 03 | Course Functioning |  |
| 04 | Hello, World! | helloworld |
| 05 | InfoCard | infocard |
| 06 | CSS Handles | csshandles |
| 07 | Flex Layout | flexlayout |
| 08 | Product Shelf | shelf |
| 09 | Blocks Carousel | slider |
| 10 | Responsive | responsive |
| 11 | PDP (Product Page) | pdp |
| 12 | PDP 2 (Evolving) | pdp2 |
| 13 | PDP 3 (Finishing) | pdp3 |
| 14 | Search Page | search |
| 15 | Search Page Layout | search2 |
| 16 | Global Styles | styles |
| 17 | Custom Templates | custom-template |
| 18 | Tab Layout | tab-layout |
| 19 | Rich Text | richtextmarkdown |
| 20 | iFrame | iframe |
| 21 | Search Landing Page | landing |
| 22 | Header | header |
| 23 | Menu | menu |
| 24 | Flex Menu | menuflex |
| 25 | Footer | footer |

## Workspace Structure

| path | comment |
| ------ | ------ |
| **store/**  | structure |
| store/ | **routes.json** | routes definition |
| store/**blocks/** | blocks definition |
| store/blocks/**about-us.json** | about us custom page |
| store/blocks/**default.json** | default blocks config |
| store/blocks/**header.json** | header config |
| store/blocks/**home.json** | home config |
| store/blocks/**menu.json** | menu config |
| store/blocks/**menu-flex.json** | submenu flex items config |
| store/blocks/**menu-items.json** | submenu items config |
| store/blocks/**product.json** | pdp (product page) config |
| store/blocks/**search.json** | search config |
| store/blocks/**search-landing.json** | search custom landing page config |
| store/blocks/**shelf.json** | shelf config |
| store/blocks/**slider-layout.json** | slider config |
| **styles** | style |
| styles/**configs/** | style config |
| styles/configs/**style.json** | default theme style |
| styles/**css/** | style files |
| styles/css/**vtex.store-components.css** | theme custom style (CSS) |
| styles/**iconpacks/** | icon package files |
| styles/iconpacks/**iconpack.svg** | icons file (SVG) |
