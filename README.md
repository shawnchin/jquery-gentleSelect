# jQuery plugin: gentleSelect

gentleSelect is a jQuery plugin for transfoming select boxes into
a skinnable alternative. The selection list can be rendered with
multiple columns/rows to present larger datasets in a more 
manageable format.

This plugin was developed to fulfil the requirements that arose
from the [BBotUI Project].
As such, while we do try to make the implementation as generic
as possible, we dare not claim this plugin to be as flexible
as one would expect a sensible jQuery plugin to be.

There is much to be done on the flexibility and robustness front, 
and we welcome contributions and bug fixes. Feel free to fork 
and send us pull requests!


## Usage

To use this plugin, one simply needs to load jQuery and the 
JS/CSS scripts for gentleSelect, then attach it to your
select boxes on DOM ready:

    <link type="text/css" src="gentleSelect/jquery-gentleSelect.min.css" />
    <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4/jquery.min.js"></script>
    <script type="text/javascript" src="gentleSelect/jquery-gentleSelect.min.js"></script>
    <script type="text/javascript">
    $(document).ready(function() {
        $('#your-select-box-id').gentleSelect();
    });
    </script>

For more options, see the [gentleSelect website].


## Others

Copyright (c) 2010, Shawn Chin.

This project is licensed under the [MIT license].


 [BBotUI Project]: https://github.com/shawnchin/bbotui "BBotUI project"
 [gentleSelect website]: http://shawnchin.github.com/jquery-gentleSelect "gentleSelect Website"
 [MIT License]: http://www.opensource.org/licenses/mit-license.php "MIT License"
