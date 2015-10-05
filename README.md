# lalit-js-font-detector
lalit patel's js font detector on bower : http://www.lalit.org/lab/javascript-css-font-detect/

Created only the bower.json file, all the good stuff is from [Lalit Patel](http://www.lalit.org/)

To install, the usual:

    bower install lalit-js-font-detector --save

And then include in your html (or concat in your vendor.js) the ```bower_components/lalit-js-font-detector/fontdetect.js``` file.

Usage:

    window.onload = function() {
        var detective = new Detector();
        alert(detective.detect('font name'));
    };
