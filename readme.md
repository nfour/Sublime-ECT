
Sublime Text 2 Syntax highlighting for ECT, embedded CoffeeScript HTML

See: http://ectjs.com

Comes with three sets of open and close tags:

```
<? ?>
<% %>
{{ }}
```

Additionally, you may create a new .tmLanguage, from the `{{ }}` template, replacing all occurances with your new open and close tag characters.
Note that html characters must be encoded within the XML .tmLanguage files. eg. `<` is expressed as `&lt;`

