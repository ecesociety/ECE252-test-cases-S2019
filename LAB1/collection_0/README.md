# `collection_0`
These file are the ones provided in the starter code repository

- `/catpng/` contains the 5 cropped files and the combined file. At the moment there is no assert to compare the two files, but you could possibly use `diff all.png combined.png` where `all.png` is the output of `catpng` and  `combined.png` is the expected output file

  _Note: This may fail if the file `combined.png` actually has multiple IHDRs since `catpng` only uses one, obviously visual comparison can be done at this point to make sure that the images are identical_

- `/findpng/` contains 2 files, one an actual png and one a txt file disguised as a png.
  When `./findpng` is called on the `findpng` folder it should only show as output the real PNG file i.e. `red-green-16x16.png`
