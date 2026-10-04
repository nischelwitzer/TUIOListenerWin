# TUIOListener Update with EXE and format

**Simple C# TUIO v1.1 / OSC v1.1 network listener.**

Listen for [TUIO](http://www.tuio.org/) or [OSC](http://opensoundcontrol.org/) network traffic and output it to the console. Useful for quickly checking/debugging data sent from TUIO server apps.

Defaults to listening for TUIO on port 3333. Output radians/degrees values in TUIO data using the rads/degs option. Invert X/Y axis values in TUIO data using the invertx/y/xy option.

Usage (Windows):

    > TUIOListener.exe [port] [tuio|osc] [rads|degs] [invertx|inverty|invertxy]
    > TUIOListener.exe -help

Output examples:

	> TUIOListener.exe
	TUIO Listener.exe Windows V2 [FHJ/NIS 10/2026]
         Usage: TUIOListener.exe -h|help [port] [tuio|osc] [rads|degs] [invertx|inverty|invertxy]
         listening on port 3333... (Press escape to quit)
	...
	FNum:000764 Curs-ADD id=04 x=0,1582 y=0,0552
	FNum:000771 Curs-MOV id=04 x=0,1575 y=0,0552
	FNum:000776 Curs-MOV id=04 x=0,1567 y=0,0552
	FNum:000777 Curs-DEL id=04 
	...
    FNum:004738 Obje-ADD id=02 x=1,0000 y=0,3235 a=+0,000 cnt=005
	FNum:004739 Obje-MOV id=02 x=1,0000 y=0,3251 a=+0,000 cnt=005
	FNum:004740 Obje-MOV id=02 x=1,0000 y=0,3267 a=+0,000 cnt=005
	FNum:006030 Obje-MOV id=02 x=1,0000 y=0,2919 a=-0,479 cnt=005
	FNum:006032 Obje-MOV id=02 x=1,0000 y=0,2935 a=-0,479 cnt=005
	FNum:006033 Obje-DEL id=02
	...

	Bye!


Libraries / Assemblies:
* [https://github.com/gregharding/TUIOsharp](https://github.com/gregharding/TUIOsharp)
* [https://github.com/gregharding/OSCsharp](https://github.com/gregharding/OSCsharp)

Currently fixed versions of;
* [https://github.com/valyard/TUIOsharp](https://github.com/valyard/TUIOsharp)
* [https://github.com/valyard/OSCsharp](https://github.com/valyard/OSCsharp)

**Author**

Greg Harding [http://www.flightless.co.nz](http://www.flightless.co.nz)

Copyright 2015 Flightless Ltd

**License**

> The MIT License (MIT)
> 
> Copyright (c) 2015 Flightless Ltd
> 
> Permission is hereby granted, free of charge, to any person obtaining
> a copy of this software and associated documentation files (the
> "Software"), to deal in the Software without restriction, including
> without limitation the rights to use, copy, modify, merge, publish,
> distribute, sublicense, and/or sell copies of the Software, and to
> permit persons to whom the Software is furnished to do so, subject to
> the following conditions:
> 
> The above copyright notice and this permission notice shall be
> included in all copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
> EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
> MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
> NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS
> BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN
> ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
> CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.
