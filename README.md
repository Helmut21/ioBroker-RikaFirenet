![Logo](admin/logo.png)

## ioBroker.RikaFirenet 0.0.1 Adapter
D
 
## DMXface adapter for ioBroker
This adapter connects the DMXfaceXP controller with ioBroker.
The communication protocoll used is the DMXface ACTIVE SEND protocoll.
Rev 1.1.0 supports additional features like min/max tracking of channels as well 
the calculation of power consumed for selected channels.

## Setup the DMXface
To configure the DMXface controller, you need the 'DMXface Console' downloadable at http://www.dmxface.at
After connecting by USB, you can access and change the controllers setup und network settings as well programm the controller.

## DMXface network settings (Menu: DMXface settings / Network setup)<br>
Here you can configure a valid IP address for the DMXface controller.
To get the DMXface connected to the IO Broker you have as well to setup the socket 6 or 7:
Set it to 'TCP SERVER', 'ACTIVE SEND PROTOCOLL' with a valid PORT (Default = 6000).

## DMXface setup settings (Menu: DMXface settings / Basic setup)<br>


## Add adapter to ioBroker
Add the DMXface adapter from github  https://github.com/DMXface/ioBroker.dmxface.git
Create an instance of the adapter.

## Adapter configuration
.<br>

## 1.1.0
released for use with DMXfaceXP Controller

##  Changelog
1.0.0  Initial release<br>
1.0.1  Bugfixes (reconnect procedure after loosing TCP connection)<br>
1.0.2  File cleanup+ Bugfix (List of additional ports causes error @ first start due to NULL value<br>
1.1.0  New version of the adapter containing min/max tracking and power tracking)
## License
MIT License<br>

Copyright (c) 2020 HST <mail@HST.at><br>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.