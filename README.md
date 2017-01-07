#js-pigpiod

[![Build Tests](https://travis-ci.org/i-am-digital/js-pigpiod.svg?branch=master)](https://travis-ci.org/i-am-digital/js-pigpiod) [![Code Coverage](https://codecov.io/gh/i-am-digital/js-pigpiod/branch/master/graph/badge.svg)](https://codecov.io/gh/i-am-digital/js-pigpiod) [![npm version](https://badge.fury.io/js/js-pigpiod.svg)](https://badge.fury.io/js/js-pigpiod) [![bitHound Dependencies](https://www.bithound.io/github/i-am-digital/js-rigpiod/badges/dependencies.svg)](https://www.bithound.io/github/i-am-digital/js-pigpiod/master/dependencies/npm) [![bitHound Code](https://www.bithound.io/github/i-am-digital/js-pigpiod/badges/code.svg)](https://www.bithound.io/github/i-am-digital/js-pigpiod) [![bitHound Overall Score](https://www.bithound.io/github/i-am-digital/js-pigpiod/badges/score.svg)](https://www.bithound.io/github/i-am-digital/js-pigpiod) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

A pure JS library for interacting with Raspberry Pi GPIO using the 
[pigpio](http://abyz.co.uk/rpi/pigpio/index.html) daemon (for pwm, servo control, etc)
                                                                 
The pigpio library uses direct memory access (DMA) to allow you to sample
the GPIOs up to 1,000,000 times per second. It also makes it fast enough to
give you PWM and servo control on all GPIOs simultaneously. The servo
waveforms are accurate to a few microseconds.
                                                                 
This code is based off of the [python library](http://abyz.co.uk/rpi/pigpio/python.html)
included with the pigpio download.

For managed access to the GPIO using javascript checkout [js-gpiozero](https://github.com/i-am-digital/js-gpiozero).

It's early days and a work in progress!

## Documentation
The API Documentation is available at the repos [github-pages](https://i-am-digital.github.io/js-pigpiod/).


##Thanks
Massive thanks for the inspiration and idea from [pi-fast-gpio](https://github.com/Tobbe/pi-fast-gpio) 