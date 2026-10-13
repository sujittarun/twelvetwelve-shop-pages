# Third-party components

The STEP reader uses unmodified OCCT Import JS 0.0.23, dynamically loaded from `cad/occt-import-js.js` and its WASM file. LGPL and Open CASCADE notices are distributed in `cad/LICENSE`, `cad/license.occt-import-js.txt` and `cad/license.occt.txt`. Corresponding upstream source, pinned Open CASCADE submodule and build scripts: https://github.com/kovacsv/occt-import-js/tree/c2148e54b456b571238d35cac037d304053d64b2 . The import library can be replaced/rebuilt independently of the application using its documented interface.

Three.js 0.186.1 is MIT licensed. Its notice is in `cad/license.three.txt`; source is at https://github.com/mrdoob/three.js/tree/r186 .

Barlow and IBM Plex Mono fonts use the SIL Open Font License. Full license notices are distributed in `licenses/Barlow-OFL.txt` and `licenses/IBMPlexMono-OFL.txt`. Sources: https://github.com/google/fonts/tree/main/ofl/barlow and https://github.com/google/fonts/tree/main/ofl/ibmplexmono .

React and React DOM are MIT licensed. Lucide uses ISC. PDF.js, Tesseract.js and Tesseract.js Core use Apache-2.0. Their shipped license texts and exact installed versions are included in `licenses/` and `licenses/dependencies.json`. Source distributions are available from the corresponding pinned npm packages. OCR English language data is from the Tesseract project, Apache-2.0.
