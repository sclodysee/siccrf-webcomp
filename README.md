# siccrf-webcomp


Libraries de composants VueJS

## Table of contents

- [Installation](#installation)
- [Example](#example)

# Installation

- Télécharger les fichiers [siccrf-webcomp.browser.js](https://raw.githubusercontent.com/sclodysee/siccrf-webcomp/master/dist/siccrf-webcomp.browser.js) et 
[siccrf-webcomp.css](https://raw.githubusercontent.com/sclodysee/siccrf-webcomp/master/dist/siccrf-webcomp.css)
- Référencer ces fichiers dans la page html

# Example

```html
<!doctype>
<html>
	<head>
	<meta lang="fr">
	<link rel="stylesheet" type="text/css" href="siccrf-webcomp.css">
	<script src="https://cdnjs.cloudflare.com/ajax/libs/vue/2.5.3/vue.min.js"></script>
	</head>
	<body>
	 Test du composant 'test'
	 <div id="app">
		 <test></test>
	 </div>
	 <script src="siccrf-webcomp.common.js"></script>
	 <script>
		 new Vue({
			 el : "#app"
		 })
	 </script>
	</body>
</html>
```