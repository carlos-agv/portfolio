# JavaScript

*Framework*
[ExtJS](https://www.sencha.com/products/extjs/)

```JS
Ext.create('principalAPP',{
    extendend: 'application',
    id: 'elProyecto',
    name: 'sinErrores',
    items: [{
        xtype: 'componenteTrabajo',
        dedicacion: true,
        entrega: 100
    }],
    plugins: {
        type: 'analisis',
        value: 1
    },
    rendered: 'body'
})
```
