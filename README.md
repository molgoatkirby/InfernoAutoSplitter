# Autosplitter for LiveSplit for Inferno

Connects to livesplit and sends a split at the start and end, and on waves which other inferno plugins commonly show split times for.



Using this plugin requires the LiveSplit program with the LiveSplit server component.

Installation and setup guide can be found here:

[LiveSplit](https://livesplit.org/downloads/)

[LiveSplit Server](https://github.com/LiveSplit/LiveSplit.Server)

## How to use
Download LiveSplit and the LiveSplit server component.

Turn the plugin on and make sure the port in the plugin settings match your LiveSplit server port.

![config](readme_images/config.png)

Start LiveSplit and start the LiveSplit server (right click LS -> control -> start server).
Make sure to add the LS server to your layout, otherwise you won't see "start server" under control.

![lsserver](readme_images/livesplit.png)

Open the sidebar and click "Connect".
If the status turns green it means you have a connection to your LiveSplit server.
If it stays red something went wrong, most likely you did not start the LiveSplit server
or you have mismatching ports in the plugin settings and the LiveSplit server settings.

![sidebar](readme_images/panel.png)

If your status is green you are good to go.


## Templates
Layout and splits templates for LiveSplit can be found in [LiveSplit templates](https://github.com/molgoatkirby/InfernoAutoSplitter/tree/master/LiveSplit%20templates)

## Splits
The plugins sends a split on the following waves:

- Right before Wave 1 starts  
- 9 melee  
- 18 ranger  
- 25 ranger + melee  
- 35 mager  
- 42 mager + melee  
- 50 mager + ranger  
- 57 mager + ranger + melee  
- 60 mager + ranger + melee + blob  
- 63 mager + ranger + melee + blob x2  
- 66 mager x2  
- 67 Jad  
- 68 Jad x 3  
- 69 Zuk  
- After Zuk dies