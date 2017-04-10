# Split plugin for Ractive.js

*Find more Ractive.js plugins at [docs.ractivejs.org/latest/plugins](http://docs.ractivejs.org/latest/plugins)*

[See the demo here.](http://dagnelies.github.io/ractive-split/)

## Usage

Include this file on your page below Ractive, e.g:

```html
	<link href='https://cdn.rawgit.com/dagnelies/ractive-split/master/bin/ractive-split.css' rel="stylesheet" />
	<script src='https://cdn.rawgit.com/dagnelies/ractive-split/master/bin/ractive-split.min.js'></script>

	<split direction="horizontal" sizes="[30,40,30]">
		<div>this is</div>
		<div>horizontally</div>
		<div>split</div>
	</split>
	
	<split direction="vertical" sizes="[10,80,10]">
		<div>this is</div>
		<div>vertically</div>
		<div>split</div>
	</split>
```


## License

Copyright (c) Arnaud Dagnelies. Licensed MIT
