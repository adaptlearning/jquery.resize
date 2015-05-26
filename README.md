jquery.resize
=============

Allows normal DOM elements to make use of the jQuery.on("resize") event.

```
$(window).on("resize", function() {
	/* works as standard in jquery */
})

$("selector").on("resize", function() {
	/* works when this plugin is added */
});
```