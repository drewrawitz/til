# Making a div visible on top of an HTML5 full screen video

This is a neat trick that will allow you to place an absolutely positioned element on top of a full screen HTML5 video. You'll need to set the maximum z-index value possible which is *2147483647*.

```css
z-index: 2147483647;
```

Any other value will not work.

[source](http://stackoverflow.com/questions/15770080/how-do-i-make-a-div-visible-on-top-of-an-html5-fullscreen-video)
