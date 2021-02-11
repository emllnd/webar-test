# webar-test

[AR.js Documentation](https://ar-js-org.github.io/AR.js-Docs/)

[AR.js Image Tracking](https://ar-js-org.github.io/AR.js-Docs/image-tracking/)

[Prepare image for tracking (NFT)](https://carnaux.github.io/NFT-Marker-Creator/)

This quick WebAR example uses AR.js for tracking images (could also track geolocation anchors) and [A-Frame](https://aframe.io/) as content technology. Other content option to use with AR.js would be THREE.js, but A-Frame is easier for getting started. For instructions and inspiration on what kind of things you can do, have a look here: [A-Frame documentation](https://aframe.io/docs/1.2.0/introduction/).

Interesting code is in the file [index.html](https://github.com/emllnd/webar-test/blob/main/index.html). Simplified, "less scary" version of index.html for getting started is [index-simple.html](https://github.com/emllnd/webar-test/blob/main/index-simple.html).

Live demo: open the [T-Rex](https://github.com/emllnd/webar-test/blob/main/trex-image-big.jpeg) or [OLebre](https://github.com/emllnd/webar-test/blob/main/taberna_o_lebre.png) image on your computer/tablet and open the [webar-test](https://emllnd.github.io/webar-test/) page on your phone. Point the phone camera at the image and you should see a 3D chest/cube.

For example, you could add you own .png image into the application by using the a-image primitive, details here: [a-image](https://aframe.io/docs/1.2.0/primitives/a-image.html). Your own image could be displayed where the tracked image is detected, or any other position. For videos or GIFs/short loops you can use [a-video](https://aframe.io/docs/1.2.0/primitives/a-video.html). For starters, you could replace the a-entity tags (3D models) in index.html with a-image or a-video.

Recommended hosting environment for testing is [GitHub Pages](https://pages.github.com/), but other web host can work just as well.

