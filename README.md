Emscripten Website
==================

This repo holds the static emscripten documentation website.  It gets
built and published automatically based on the files that live in the
main emscripten repo.

To update manually you can run `tools/main/update_docs.py` from the
emscripten repo, or follow the following steps:

1. In the emscripten repo, go to site/
2. Run make clean (to ensure old files are not present)
3. Run make html  (you need sphinx installed)
4. Copy site/build/html into here
