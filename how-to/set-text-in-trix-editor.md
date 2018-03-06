## Set text in trix editor

[trix](https://github.com/basecamp/trix) is a popular text editor. Because of the way trix is written using chreom extension it was not possible to write to the text area.

We could do that using custom JavaScript.

``` javascript
var element = document.getElementById('trix-editor');
element.editor.insertString('A quick brown fox jumps over the lazy dog');
```

