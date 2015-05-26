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

Will listen for resizes on window mousedown mouseup keyup keydown and scroll events for 500 milliseconds or until no other resize changes are detected. Will trigger at 250 millisecond intervals.
