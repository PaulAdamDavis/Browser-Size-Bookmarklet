# Display Browser Size

Drag this link to your bookmark bar.

<a href="javascript:function t(){
	var w, h;
	if (window.innerWidth && window.innerHeight) {
		w = window.innerWidth;
		h = window.innerHeight;
	}
	document.title = w + ' x ' + h;
}
t();
window.onresize = function() {
	t();
};">Display Browser Size</a>