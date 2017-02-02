# http-vue-loader
load .vue files from your html/js

# examples

```
<script type="text/javascript">

	new Vue({
		components: {
			scrollbar: httpVueLoader('scrollbar.vue')
		},
		...
```

or

```
<script type="text/javascript">

	httpVueLoaderRegister(Vue, 'scrollbar.vue');

	new Vue({
		components: [
			'scrollbar'
		},
		...
```


# Dependances
* Vue.js 2
* axios
* es6-promise (optional)


# API

httpVueLoader(url)




httpVueLoaderRegister(Vue, url)
