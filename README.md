# removeAccented
A jQuery plugin to remove accented characters from the input fields (good for roman characters used in European languages). The list of characters came from CodeIgniter version 3's array in foreign_chars.php.

To use this plugin to remove accented characters from the input fields:

```javascript
$(function () {
  $('#selector').change(function () {
    $(this).removeAccentedChar();
  });
});
```
