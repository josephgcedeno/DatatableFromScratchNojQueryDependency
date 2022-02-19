
## To setup:
- Import the css and js file from dist folder to your html or any templating engine:
  ```
    <link rel="stylesheet" type="text/css" href="assets/dist/css/style.css">
    <script type="text/javascript" src="assets/dist/js/script.min.js"></script>
  ```
- At the bottom. Create a script tag then write this:
  ```
    window.addEventListener("load", function() 
    {

        var ref = new datatable('table'); // this table string is from DOM tag.
        ref.sortableColumn([true,true,true,true,true,true]); // You can specify which column would be sorted

    });
  ```


## Learning
- source for creating DOM div outside the tag element [source](https://plainjs.com/javascript/manipulation/wrap-an-html-structure-around-an-element-28/)

- source for converting table rows into json object [source](https://j.hn/html-table-to-json/)

- [sort1](https://stackoverflow.com/questions/17684921/sort-json-object-in-javascript) [sort2](https://stackoverflow.com/questions/17684921/sort-json-object-in-javascript)

- run style sass --watch assets/src/scss:assets/dist/css --style compressed

- to view visit [datatable from scratch vanilla javascript!!!](https://watchmena.ml/datatable)

