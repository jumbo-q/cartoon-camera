# Cartoon Camera
A marker based augmented reality camera app for the web. Powered by [AR.js](https://github.com/AR-js-org/AR.js). Fast, light-weight and works on any mobile/desktop browser with [WebGL](https://get.webgl.org/) and [WebRTC](https://webrtc.org/).

## Asset Path

-  3D model in `/assets/3d-models/` and link it using `a-entity` tag in `index.html`. [Learn more](https://ar-js-org.github.io/AR.js-Docs/marker-based/#a-frame).
- By default the marker is preset to the [hiro marker](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png). To create a custom marker,
  - Use [this tool](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) to create your custom marker.
  - Export the `.patt` file and place it in `/assets/custom-markers/`.
  - Link it using `a-marker` tag in `index.html`. [Learn more](https://ar-js-org.github.io/AR.js-Docs/marker-based/#a-frame).
  - You may follow [this article](https://ar-js-org.github.io/AR.js-Docs/marker-based/#how-to-choose-good-images-for-pattern-markers) to create an effective custom marker. 
- Fire up the app and point it to the marker. Default hiro marker can be found [here](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png).
- Translate, rotate or zoom the model as desired and snap a pic!
