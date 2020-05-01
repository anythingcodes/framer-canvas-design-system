# FramerX-based Canvas design system package

> WIP. Not yet ready for primetime.

## Local installation

Run `yarn` to install

1. Open `mockup.framerx` or create a new Framer file.
2. Open the `library.framerx` project folder and `yarn link` it to the new Framer file [following these steps](https://www.framer.com/learn/guide/writing-packages/).
3. Run `yarn run chokidar "code/**/*" -c "framer build"` to run `library.framerx` within the mockup from step 1.
