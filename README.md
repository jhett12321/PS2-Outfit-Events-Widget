# Planetside 2 Outfit Events Feed Widget #

### What is it? ###

The Planetside 2 Outfit Events Feed Widget is a simple html/embed element that creates a real-time log for the various events exposed by the [Planeside 2 Census PUSH API](http://census.daybreakgames.com/#what-is-websocket).

### Setup ###

Setup is as simple as editing the following lines in the main script tag to match your outfit configuration.

```
#!javascript
	var outfitAlias = "TCFB"; 			//Outfit Tag. Used to retrieve an outfit character list, and used in the combat log entries.
	var serviceID = "example"; 			//Service ID. Required to connect to the SOE Event API.
	var factionID = "1"; 				//Faction ID (1=VS,2=NC,3=TR) Used for colour coding combat entries.
```

Once this has been configured, open the page (widget.html), and check the boxes that you wish to see events for. As events come in, they will be added to the log.

### License ###

MIT License

Copyright (c) 2014-2015 Jhett Black

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.