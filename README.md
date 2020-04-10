# react-native-soundfonts

This repository contains sound libraries for use with [react-native-soundfont](https://www.npmjs.com/package/react-native-soundfont). It is based on [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts), but modified for use with mobile - mainly, a flattened directory structure with lowercase, underscored, filenames to obey Android's resource naming requirements.

To use a library with `react-native-soundfont`, extract the `sounds.7z` into `android/app/src/main/res/raw`.

Instrument names can be found in the `names.json`.
