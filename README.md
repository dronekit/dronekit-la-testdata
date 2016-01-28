# DroneKit LA Test Data

![Logo](https://cloud.githubusercontent.com/assets/5368500/10805537/90dd4b14-7e22-11e5-9592-5925348a7df9.png)

<a href="https://discuss.dronekit.io/c/dronekit-la-log-analyzer"><img align="right" src="https://img.shields.io/badge/support-discuss.dronekit.io-blue.svg"></img></a>

Logs and output for testing [Dronekit-LA](http://la.dronekit.io/).

## Overview

This repo contains sample ArduPilot DataFlash logs and MAVLink telemetry logs that you can [freely use](#license) for testing [DroneKit Log Analyzer (DroneKit-LA)](http://la.dronekit.io/). 

It also contains typical dronekit-la output which can be used to validate log analyzer changes.


## Contributing new logs

We welcome new logs and analysis-output updates. These must be provided with the permission of the owner, and permit [free use](#license) by anyone. 

Here are a few basic rules for adding logs:

* The permission of the log owner must be granted before a log is uploaded
* Logs should be kept as short as possible (to make the repo usable). 5MB is the "nominal" maximum size.
* Please state log ownership in the commit message.
 
**NOTE:** Before adding a log, please consider any sensitive information that it may contain.


## Using Analyzer Output

The Analyser output is used to validate that changes to (DroneKit-LA)](http://la.dronekit.io/) output are improvements. Typically we use a diff tool (e.g. *WinDiff*, *Beyond Compare*) to verify that changes result in better/more useful output.

**Note:** When comparing outputs, ensure that changes aren't due to platform issue (e.g. precision of floats on output).


## License

All the files are licensed under [Creative Commons: Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)](http://creativecommons.org/licenses/by-sa/3.0/).

