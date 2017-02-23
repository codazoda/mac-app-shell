# Mac App Shell

This is a minimalist shell for a MacOS Application bundle (just a directory) that will execute as an app on MacOS and open a terminal window with a simple "Hello World" bash script.

## File Structure

```
Console.app    The App bundle (just a directory with the .app extension)
  Contents     The first required folder
  	MacOS      The second required folder
      console  The initial bash script or other executable (filename must match the app name)
      main.sh  Another bash script that setup runs in a terminal window
  	Icon?	   The icon (see setup instructions below)
```

## Setting an Icon

- Open the icon you want to use in Preview and press Command-C to copy it.
- Select the Setup.app directory and choose "Get Info".
- Click the icon in the top-left corner, it outlines in blue.
- Press Command-V to paste the new icon.