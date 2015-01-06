am2301_poll
======
This is a demonstrational program using the AM2301 temperature/humidity sensor.
It uses [wiringPI library] (http://wiringpi.com/) in polling mode.

This fork does not use mysql to save the temperature and humidity values.

To compile you can use the GCC compiler with the parameter -lwiringPi (Ex.: gcc am2301_poll.c -lwiringPi)

License
-------
This program is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
Lesser General Public License for more details.

