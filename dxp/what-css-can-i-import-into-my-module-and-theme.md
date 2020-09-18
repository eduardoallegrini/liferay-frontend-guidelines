# What CSS can I import into my module and theme?

CSS libraries that are available in DXP and how to import in your module or theme

### What does it provide?
Table of variables, mixins, functions

### How to import it?

In your main SCSS file
```scss
@import 'atlas';
```

In your build.gradle
```js
buildCSS {
	imports = [
		new File(npmInstall.nodeModulesDir, "@clayui/css/src/scss")
	]
}
```


### How to use it?
Example of code

## atlas

## clay

## clay-variables

## css-custom-properties

## font-awesome & font-glyphicon?

## bourbon?

## compat-layer?

## aui-css?

```scss
@import url(portal/aui_deprecated.css);
```

## mixins?

```scss
@import 'mixins';
```

## minium?

## speedwell?

