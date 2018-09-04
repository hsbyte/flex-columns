# Responsive Flex Columns
![](https://img.shields.io/badge/version-1.1.0-green.svg)

A light weight column layout code using 'flex-box` to build responsive, mobile-first projects on the web.

## Instructions
  
After installing the Node.js, from a command shell `bash` or `cmd`, download the project file. Install package dependencies. Run `gulp build` to build the distribution files in the `dist` folder.

```bash
npm install
gulp build
```

`Gulp` was used to compile and minify the `SCSS`.

### Usage

Must declare all `col` classes (`col-xl`, `col-l`, `col-m`, `col-s` and `col-xs`).

-----
Syntax      | Description 
----------- | ------------------------------------------
col-xl-[#]  | Extra large size device (width: < 1200px)
col-l-[#]   | Large size device (width: 992px to 1199px)
col-m-[#]   | Medium size device (width: 768px to 991px)
col-s-[#]   | Small size device (width: 544px to 767px)
col-xs-[#]  | Extra small size device (width: < 543px)
##### where [#] is the number of columns 1 to 12.
-----

#### Example

```html
<div class="container">
    <div class="row">
        <div class="col-xl-8 col-l-8 col-m-6 col-s-6 col-xs-12">
            Hello
        </div>
        <div class="`col-xl-4 col-l-4 col-m-6 col-s-6 col-xs-12">
            World
        </div>
    </div>
</div>
```
### Screenshot

![](https://github.com/hsbyte/flex-columns/blob/master/.md/screenshot.jpg)

## License

Released under the [MIT licence](http://opensource.org/licenses/MIT).


## Author

- Arnold Haban
