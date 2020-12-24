# Stream Deck Plugin for OctoPrint

This plugin shows your printer completion state in percent on your StreamDeck with OctoPrint.

## Installation
1. Download the latest release. Double click on the file `com.cpeuschel.octodeck.streamDeckPlugin` to install.
2. You should see in the StreamDeck Application under `Custom` the octodeck plugin.  

## Configuration
1. Change the font to 18 pt, choose your favourite color and center the title to middle (see e example)
   
   ![txt_conf.png](readme/txt_conf.png)
2. Add your OctoPrint Url e.g `http://192.168.178.13`
3. Add your API-Key (https://docs.octoprint.org/en/master/api/general.html#authorization)
4. Hit Save.
   
    ![configuration.png](readme/configuration.png)

## Use
Click the icon on your StreamDeck to update the current completion. (automatic refresh in future release available)

## Available States
- `rdy` => the printer is connected and is ready or the current print is finish

    ![rdy.png](readme/rdy.png)
- `off` => the printer is not connected with OctoPrint

    ![off.png](readme/off.png)
- `%` => Completion in percent  

    ![img.png](readme/percent.png)
