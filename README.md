# weepay Opencart Payment Module 
![](https://service.weepay.co/form/normal.svg)

weepay opencart is the simple and lightweight implementation of [weepay.co](https://www.weepay.co) payment service for Opencart. It's licensed under LGPL v3.0 license, therefore feel free to use it in any project or modify the source code.

# Getting Started


  ### Features
  
  - Supported version  2.0.0.0 - 2.2.0.0;
  - Other versions [Opencart 1.5.x](https://www.weepay.co)  [Opencart 2.3.x](https://www.weepay.co) [Opencart 3.0.x](https://www.weepay.co)
  - Supported One Page Checkout


## Installation
* Backup your webstore and database
* Download the source, just copy all the files in the zip to your OpenCart directory.
* Click Extensions tab and Payments subtab in your OpenCart admin panel.
* Find iyzico extension and install the module. Then click Edit.
* Get your api keys from iyzico merchant backend.
* Select "Enabled" to activate iyzico plugin for your OpenCart.
* Select "popup" or "responsive" to display form on checkout page.
* Define alignment number for the payment sort order.(etc 1,2,3...)
* User on checkout page will find iyzico payment extension in payment methods.
* In order details on admin interface, find "iyzico Checkout Form" tab in "Order History" section.
* From there, admin can Cancel order and/or Full/Partial Refund item.


#### Disabled options

- TeX (Based on KaTeX);
- Emoji;
- Task lists;
- HTML tags decode;
- Flowchart and Sequence Diagram;

#### Editor.md directory

    editor.md/
            lib/
            css/
            scss/
            tests/
            fonts/
            images/
            plugins/
            examples/
            languages/     
            editormd.js
            ...

```html
<!-- English -->
<script src="../dist/js/languages/en.js"></script>

<!-- 繁體中文 -->
<script src="../dist/js/languages/zh-tw.js"></script>
```
