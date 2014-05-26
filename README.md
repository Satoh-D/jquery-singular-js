jquery-singular-js
==================

__jQuery plugin to create SinglePage Website.__

## Demo

[Demo Page](https://dl.dropboxusercontent.com/u/21601359/140522_singularjs/index.html)

## Usage

```html
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="jquery.imageslider.js"></script>
<script>
$(function() {
	$('.js-singular').singular();
});
</script>
</head>
<body>

<div class="js-singular">
<section id="sec01" class="singular-section"></section>
<section id="sec02" class="singular-section"></section>
<section id="sec03" class="singular-section"></section>
<section id="sec04" class="singular-section"></section>
<section id="sec05" class="singular-section"></section>
<!-- /js-singular --></div>

</body>
```

## Options

- `section`[text]: Sections's classname.
- `nav`[text]: Nav's classname.
- `prev`[text]: The classname that links to the previous section.
- `next`[text]: The classname that links to the next section.
- `navActiveClass`[text]: The classname current section.
- `scrollSpeed`[ing]: scroll speed(ms)
- `easing`[text]: Easing name. (Require [jQuery Easing Plugin](http://gsgd.co.uk/sandbox/jquery/easing/))
- `mousewheel`[bool]: Scroll using th mouse wheel. (Require [jQuery Mouse Wheel Plugin](https://github.com/brandonaaron/jquery-mousewheel))

## Browser Support

- IE8+
- Google Chrome (win/mac)
- Firefox (win/mac)
- Safari (win)

## License

MIT License.

## Copyright

©Sato Daiki. ([@Satoh_D](https://twitter.com/Satoh_D))
