jQuery Show / Hide Plugin
==========================

For a demo check out http://papermashup.com/jquery-show-hide-plugin/

Usage and options
-----------------

Here we setup the options for the plugin. you can set the speed of the toggle, if you include the jQuery UI plugin you can specify an easing effect. Also there’s an option to change the text for the button. 1 is change 0 is dont change. and the final options are the show and hide text.


        speed: 1000,  // speed you want the toggle to happen
        easing: '',  // the animation effect you want. Remove this line if you dont want an effect and if you haven't included jQuery UI
        changeText: 1, // if you dont want the button text to change, set this to 0
        showText: 'View',// the button text to show when a div is closed
        hideText: 'Close' // the button text to show when a div is open

	