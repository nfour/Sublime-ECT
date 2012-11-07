
Sublime Text 2 Syntax highlighting for ECT, embedded CoffeeScript HTML

See: http://ectjs.com

Comes with three sets of open and close tags:

```
<? ?>
<% %>
{{ }}
```

You would specify `open` and `close` options when you create a new ECT engine/renderer, within your application.

### Optional

Additionally, you may use your own tags by copying a .tmLanguage file.  
The `{{ }}` template, `ect_html3.tmLanguage`, would be the easiest.  

Replace all occurances of each open and close tag with your own open and close tag characters.

Also, be sure to rename the .tmLanguage near the top of the file:
```
<key>name</key>
<string>ECT {{</string>
```
Note that html characters must be encoded within the XML .tmLanguage files. eg. `<` is expressed as `&lt;`

