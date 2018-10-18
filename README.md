This buildpack just sets up PATH variable for graphicsmagic

If graphicsmagic is installed via apt buildpack, it does not work for PDF
Currently gm version is hardcoded 1.3.28, so it relies that 1.3.28 version is installed via apt buildpack
