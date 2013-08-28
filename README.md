jquery-colorpicker-mobile
=========================

fork of http://www.eyecon.ro/colorpicker/ with touch events support


Implement
---------

    <link rel="stylesheet" media="screen" type="text/css" href="css/colorpicker.css" />
    <script type="text/javascript" src="js/colorpicker.js"></script>


Invocation code
---------------

    $('input').ColorPicker(options);

Options
-------

    eventName       string
        The desired event to trigger the colorpicker. Default: 'click'

    color           string or hash
        The default color. String for hex color or hash for RGB and HSB ({r:255, r:0, b:0}) . Default: 'ff0000'

    flat            boolean
        Whatever if the color picker is appended to the element or triggered by an event. Default false

    livePreview     boolean
        Whatever if the color values are filled in the fields while changing values on selector or a field. If false it may improve speed. Default true
    onShow          function
        Callback function triggered when the color picker is shown

    onBeforeShow    function
        Callback function triggered before the color picker is shown

    onHide	        function
        Callback function triggered when the color picker is hidden

    onChange        function
        Callback function triggered when the color is changed

    onSubmit        function
        Callback function triggered when the color it is chosen



colorpicker.less
----------------

Add variable that points to colorpicker image directory before importing:

    @jquery-colorpicker-mobile-dir: './images';

