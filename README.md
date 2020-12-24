# Stream Deck Plugin for OctoPrint

This plugin shows your printer completion state in percent on your StreamDeck with OctoPrint.

## Installation
1. Download the latest release. Double click on the file `com.cpeuschel.octodeck.streamDeckPlugin` to install.
2. You should see in the StreamDeck Application under `Custom` the octodeck plugin.  

## Configuration
1. Choose your favourite color and font (see example)
   
   ![txt_conf.png](readme/txt_conf.png)
2. Add your OctoPrint Url e.g `http://192.168.178.13`
3. Add your API-Key (https://docs.octoprint.org/en/master/api/general.html#authorization)
4. Hit Save.
   
    ![configuration.png](readme/configuration.png)

## Use
Click the icon on your StreamDeck to update the current completion. Automatic update every 5 minutes

## Available States
- `rdy` => the printer is connected and is ready to print

    ![rdy.png](readme/rdy.png)
- `off` => the printer is not connected with OctoPrint

    ![off.png](readme/off.png)
- `cncl` => print is canceling
  
    ![img.png](readme/cncl.png)
- `%` => Completion in percent  

    ![img.png](readme/percent.png)
