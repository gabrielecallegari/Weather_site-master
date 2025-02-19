# SCSS
======
We will write scss using BEM+ITCSS

## Directory structure
-----------------------
* **Settings** – used with preprocessors and contain font, colors definitions, etc.
* **Tools** – globally used mixins and functions. It’s important not to output any CSS in the first 2 layers.
* **Generic** – reset and/or normalize styles, box-sizing definition, etc. This is the first layer which generates actual CSS.
* **Elements** – styling for bare HTML elements (like H1, A, etc.). These come with default styling from the browser so we can redefine them here.
* **Objects** – class-based selectors which define undecorated design patterns, for example media object known from OOCSS
* **Components** – specific UI components. This is where majority of our work takes place and our UI components are often composed of Objects and Components
* **Vendors**
* **Utilities** – utilities and helper classes with ability to override anything which goes before in the triangle, eg. hide helper class

#### Here are some useful link :
-----------------------

* [itcss] - Scalable and maintainable css architecture
* [BEM] - BEM - Block Element Modifier is a methodology that helps you to create reusable components and code sharing in front-end development

[itcss]:<https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/>
[BEM]:<http://getbem.com/>