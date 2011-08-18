jQuery.suggest()
===

## Options

### _string_ def\_value

Default: "" (empty string)

### _string_ def\_image

Default: "default.png"

### _string_ img_path

Default: "" (empty string)

### _function_ search( searchstring, callback )


## Events

### select

### clear


## Demo

[http://demos.e-noise.com/jQuery.suggest/](http://demos.e-noise.com/jQuery.suggest/)

## Example

    ...
    <input name="username" id="username">

    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.6.2/jquery.min.js"></script>
    <script src="js/jquery.suggest.js"></script>
    <script>
    jQuery(document).ready(function ($) {
      $('#username').suggest({
        search: function (s, cb) {
          cb([]);
        }
      });
    });
    </script>
    ...

