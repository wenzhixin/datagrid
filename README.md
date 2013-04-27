## datagrid

That's an extendable grid system developed on Backbone.js, Twitter Bootstrap, jQuery frameworks and Sea.js.

### Requirements

- [Backbone.js](http://backbonejs.org/) > 0.9.10
- [Twitter Bootstrap](http://twitter.github.io/bootstrap/) v2.2.1
- [jQuery](http://jquery.com/) v1.8.3
- [Sea.js](http://seajs.org/) v1.3.1


### How to use

	var Datagrid = require('../plugins/datagrid');

	new Datagrid.View({
		lang: 'zh_CN',
		container: $datagrid,
		collection: new Backbone.Collection(data),
		multiselect: multiselect,
		colModel: colModel
	});


### Author

this project is forked from bbGrid
 
[Documentation and examples.](http://direct-fuel-injection.github.com/bbGrid/)
