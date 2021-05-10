# StreamDeck Plugin for OctoPrint

This plugin shows your 3D-Printer completion state in percent on your StreamDeck ([OctoPrint](https://github.com/OctoPrint/OctoPrint) required)

## Installation
Download the latest release. Double click on the file `com.cpeuschel.octodeck.streamDeckPlugin` to install.

## Configuration (Saved automatically)
1. Choose your favourite color and font (see example)
   
   ![txt_conf.png](readme/txt_conf.png)
2. Add your OctoPrint Url e.g `http://192.168.178.13`
3. Add your API-Key [click](https://docs.octoprint.org/en/master/api/general.html#authorization)
4. Choose your update interval
5. Choose your favourite background color

    ![configuration.png](readme/configuration.png)

## Use
Click the icon on your StreamDeck to update the completion. Automatic update time which you are using in the configuration

## Available States
- `rdy` => the printer is connected and is ready to print

    ![rdy.png](readme/rdy.png)
- `off` => the printer is not connected with OctoPrint

    ![off.png](readme/off.png)
- `cncl` => print is canceling
  
    ![img.png](readme/cncl.png)
- `%` => Completion in percent  

    ![img.png](readme/percent.png)
