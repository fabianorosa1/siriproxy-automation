SiriProxy Automation Controller
================================
About
-----
A Plugin for [Siri Proxy](https://github.com/plamoni/SiriProxy) to send commands to automation hardware.

Prerequisites
------------
* A [Siri capable device](http://www.apple.com/ios/siri/siri-faq/) – currently that includes the iPhone 4S or newer, the iPad 4th generation or the iPad Mini
* A [Siri Proxy](https://github.com/plamoni/SiriProxy) server

Installation
------------

Install SiriProxy. Some instructions for doing this on a RaspberryPi can be found here: http://www.hometoys.com/emagazine/2013/02/siri-home-automation-integration-from-start-to-finish-brpart-2--raspberry-pi-installation/2090

Edit the SiriProxy config file (`~/.siriproxy/config.yml`) so that it contains the following lines, e.g.

    - name: 'Automation'
      git: 'https://github.com/fabianorosa1/siriproxy-automation.git'

Re-bundle SiriProxy, e.g.

	cd ~/SiriProxy
	rvmsudo siriproxy bundle
	rvmsudo bundle install
	rvmsudo siriproxy server

Version History
-----
* 1.0.0 - Initial Release

To Do
-----
* xxxxxxxx

Licensing
---------
Copyright (c) 2013, Fabiano Rosa

Re-use of my code is fine under a Creative Commons 3.0 [Non-commercial, Attribution, Share-Alike](http://creativecommons.org/licenses/by-nc-sa/3.0/) license. In short, this means that you can use my code, modify it, do anything you want. Just don't sell it and make sure to give me a shout-out. Also, you must license your derivatives under a compatible license (sorry, no closed-source derivatives). If you would like to purchase a more permissive license (for a closed-source and/or commercial license), please contact me directly. See the Creative Commons site for more information.

Disclaimer
---------
THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.