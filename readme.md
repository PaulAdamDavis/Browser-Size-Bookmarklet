# Display Browser Size

A little bookmarklet to show with browser width & height into the page title attribute.

---

**Drag the below link to your bookmarks bar**

<a href="javascript:function t(){var w, h;if (window.innerWidth && window.innerHeight) {w = window.innerWidth;h = window.innerHeight;}document.title = w + ' x ' + h;}t();window.onresize = function() {t();};">Display Browser Size</a>
