# snippets
A common snippets used in BSource projects.

##  Javascript
### [Ext JS](https://github.com/BSourceSistemas/snippets/blob/main/javascript/ext.code-snippets)

Import this snippet file on your vscode

This is a snippet that we use during our project developments with [Ext JS](https://www.sencha.com/products/extjs/), there are several interesting routines that are used in our day like the snippet **dg**.

``` javascript
//<debug>
debugger;
//</debug>
```

Or Generating a new viewModel using snippet **newvm**.

``` javascript
Ext.define('BSource.view.products.ProductFeatureViewModel', {
    extend: 'Ext.app.ViewModel',
    alias: 'viewmodel.product-feature',
    data: {
        
    },
    stores: {

    },
    formulas: {

    }
});

```

We plan to bring other snippets that we use here for javascript and C#, so we ask you to give this page a star and follow our work.

Remembering that [BSource](https://www.bsource.com.br/) is a company working on digital transformation focused on the solution for your business.

##  .NET

Onde colocar os snippets: %HOMEPATH%\AppData\Roaming\Code\User\snippets

Comandos para snippets dotnet:

dtos	-> Gera uma classe DTO.
res	-> Gera uma classe Response.
req	-> Gera uma classe Request.
irepo	-> Gera uma interface ppara repositório.
hand	-> Gera uma classe Request Handler.
prepos	-> Gera um repositório para o método POST.
repos	-> Gera um repositório para todos os outros métodos HTTP.
control -> Gera um controller com todos os métodos HTTP.
