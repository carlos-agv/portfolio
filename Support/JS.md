# JavaScript

*Framework*
[ExtJS](https://www.sencha.com/products/extjs/)

```JS
// Ejemplo:
Ext.define('MyApp.Application', {
    extend: 'Ext.app.Application',
    name: 'MyApp',
    launch: function () {
        Ext.create('Ext.panel.Panel', {
            renderTo: Ext.getBody(),
            width: 400,
            height: 200,
            title: 'Hola desde ExtJS.',
            html: 'La APP en ExtJS!'
        });
    }
});
Ext.create('MyApp.Application');
```
