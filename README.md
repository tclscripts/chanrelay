# ChanRelay v3.11
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/crazycat)

This TCL is a complete relay script wich works with botnet.

## DESCRIPTION

This TCL is a complete relay script wich works with botnet.
All you have to do is to include this tcl in all the eggdrop who are concerned by it.

You can use it as a spy or a full duplex communication tool.

It don't mind if the eggdrops are on the same server or not, it just mind about the channels and the handle of each eggdrop.

## CHANGELOG
### 3.11
- Made the "oper" setting functionnal
- Removed MDS support
### 3.10
- Added debug log. It can be enable and disable in configuration and with /msg rc.debug <on|off>

### 3.9
- Added exclusion list to ignore some users
- Added a way to restrict relay to an internal user list
### 3.81
- Action mades by server are no more using nick "*"
- Added a protection on oper actions: the action must come from the oper bot
- Correction of the quit transmission: when the bot leaves, it now detect and transmit
- Added botnet status broadcast
- Changed the unload system (thanks to MenzAgitat)
### 3.8
- Correction : the config file can now use username for naming, allowing to have relaying eggdrops in the same place with different settings

## TODO
- Enhance configuration
- Allow save of configuration
- Multi-languages

