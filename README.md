# 📸 Cartoon Camera ✨

A marker-based augmented reality camera app for the web! Powered by [AR.js](https://github.com/AR-js-org/AR.js), it's fast, lightweight, and works on any mobile or desktop browser with [WebGL](https://get.webgl.org/) and [WebRTC](https://webrtc.org/). 🤳

![cartoon-camera.png](page%2Fassets%2Fcartoon-camera.png)

## Asset Paths 📁

*   **3D Models:** Place your 3D models in the `/assets/3d-models/` directory and link them using the `a-entity` tag in `index.html`. [Learn more](https://ar-js-org.github.io/AR.js-Docs/marker-based/#a-frame). 📦
*   **Markers:**
  *   The app defaults to the [hiro marker](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png). 🎯
  *   To create a custom marker:
    1.  Use [this tool](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) to generate your custom marker. 🛠️
    2.  Export the `.patt` file and place it in `/assets/custom-markers/`.
    3.  Link it using the `a-marker` tag in `index.html`. [Learn more](https://ar-js-org.github.io/AR.js-Docs/marker-based/#a-frame).
    4.  Check out [this article](https://ar-js-org.github.io/AR.js-Docs/marker-based/#how-to-choose-good-images-for-pattern-markers) for tips on creating effective custom markers. 💡
*   **Ready to Play:** Fire up the app and point your camera at the marker. You can find the default hiro marker [here](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png). 🕹️
*   **Capture the Moment:** Translate, rotate, or zoom your 3D model to your liking, and then snap a pic! 📸

---

**Created by QI JUNBO, Community Computing Lab** 🧑‍💻🔬
