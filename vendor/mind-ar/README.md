# MindAR browser distribution

Pinned version: **mind-ar 1.2.5**, obtained from the npm `mind-ar` package. Upstream: https://github.com/hiukim/mind-ar-js . Licence: MIT, reproduced in `LICENSE`.

Included unmodified files: `mindar-image.prod.js`, `controller-mGt1s8dJ.js`, `ui-fBadYuor.js`. These are the standalone image-tracking/compiler browser entry and its local dependencies. No A-Frame, alternate Three.js bundle, face tracker, camera images or Merge artwork is included. The prebuilt controller embeds its TensorFlow-based implementation and worker; inspect upstream notices before updating.

Loaded lazily by `src/builder/mergeTracking.ts`. To update, obtain the official npm tarball, review its licence and dependency changes, replace this complete entry/dependency set together, then repeat calibration, camera cleanup and device tracking checks. Do not modify minified vendor code to fix application logic.
