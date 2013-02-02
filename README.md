Elusive-Iconfont
================

The Elusive Iconfont is an icons webfont, optimized for use with twitter's bootstrap.

For examples & usage see http://aristath.github.com/elusive-iconfont/

Licence: [SIL](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)


New Font semantic name support
==============================

Inspired by Symbolset http://symbolset.com

An Open-Type ligatures features is now embed to provide a semantic way to directly use the icons.

When text is set in he font, you could directly access icons by writing the name of the icon as writed (just change icon- by i-) on the page http://aristath.github.com/elusive-iconfont/

To use the <code>icon-twitter</code> icon, you will only need to write <code>i-twitter</code>.

In order to make this feature work, you will need to add specific CSS to classes or ids you which could use this features.
```css
	-webkit-font-feature-settings: "liga";
	-moz-font-feature-settings: "liga=1";
	-moz-font-feature-settings: "liga";
	-ms-font-feature-settings: "liga" 1;
	-o-font-feature-settings: "liga";
	font-feature-settings: "liga";
```
