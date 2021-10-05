# README

This will contain several sections on how to write, build, add new events to Uncle Punch. WIP, and most will be guesswork.

## Creating Uncle Punch Root Folder

To actually use new events, we will need to recreate the root folder for UnclePunch. This just has to be done once.

1. Download a copy of [GCRebuilder](http://www.romhacking.net/utilities/619/)
2. Open GCR. Click Image -> Open. Find your UnclePunch ISO.
3. In the structure section, right click on `root` and export. Save the location of this folder -- all events we create will go here to rebuild.

## Writing New Events

Undetermined. Current questions that need to be addressed:

- How do we create the necessary event data files found in `assets`?

## Building Events

1. Write a `build.bat` file in the event folder. Follow same structure as other events.
2. Run `build.bat`. **TODO**: Figure out why it's bugged out: [Issue](https://github.com/UnclePunch/Training-Mode/issues/21)
3. Obtain `.dat` files in output. Copy over to `root/TM` folder obtained from GCR (refer to Creating Uncle Punch Root Folder).

## Building Custom Uncle Punch ISO

1. Open GCR. Click Root -> Open and choose your saved root folder.
2. Modify info on the left side as desired. 
3. Click Root -> Save with your desired ISO name. 
4. Click Root -> Rebuild.
