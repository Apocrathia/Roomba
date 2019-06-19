[![Build Status](https://travis-ci.org/Apocrathia/Roomba.svg?branch=master)](https://travis-ci.org/Apocrathia/Roomba)
[![Build Status](https://travis-ci.org/Apocrathia/Roomba.svg?branch=dev)](https://travis-ci.org/Apocrathia/Roomba)

[![Black Duck Security Risk](https://copilot.blackducksoftware.com/github/repos/Apocrathia/home-assistant-config/branches/master/badge-risk.svg)](https://copilot.blackducksoftware.com/github/repos/Apocrathia/home-assistant-config/branches/master)
[![Black Duck Security Risk](https://copilot.blackducksoftware.com/github/repos/Apocrathia/home-assistant-config/branches/dev/badge-risk.svg)](https://copilot.blackducksoftware.com/github/repos/Apocrathia/home-assistant-config/branches/dev)

Roomba library for Arduino
This is the Arduino **Roomba** library. It provides an object-oriented interface for talking to iRobot **Roomba** and Create robots via a serial port. The Roomba is the original device from iRobot. It has a serial port DIN socket on the side. The Create is a more full-featured robot platform for hobbyists. It has both the DIN socket and a DB25 connector called the CArgo Bay Connector

The Create understands a superset of the **Roomba** commands. This library supports both devices. Where comands are only available on one or the other platform it is noted.

The version of the package that this documentation refers to can be downloaded from http://www.airspayce.com/mikem/arduino/Roomba/Roomba-1.3.zip You can find the latest version at http://www.airspayce.com/mikem/arduino/Roomba

Tested on Arduino Duemilanove, Diecimila and Mega with arduino-0018 on OpenSuSE 11.1 and avr-libc-1.6.1-1.15, cross-avr-binutils-2.19-9.1, cross-avr-gcc-4.1.3_20080612-26.5.

A number of example programs are included that work with the iRobot Create:
- TestSuite Runs on a Mega and exercises a number of the functions, checking for correct operation
- RoombaTest1 Runs in any Arduino, checks that sensors can be read from Create using the stream() command
- RoombaRCRx Demo program that shows how to control a Create using the RCRx Arduino library, an Arduino WiFi shield such as BlackWidow and the RCTx iPhone app. Control a Create from your iPhone!

A video domonstating this library (along with the http://www.airspayce.com/mikem/arduino/RCKit library) being used to control a Create from an iPhone or iPad can be found at http://www.youtube.com/watch?v=Qv-5ZOb5WW4

## Installation
  Install in the usual way: unzip the distribution zip file to the libraries sub-folder of your sketchbook.

This software is Copyright (C) 2010 Mike McCauley. Use is subject to license conditions. The main licensing options available are GPL V2 or Commercial:

## Open Source Licensing GPL V2
  This is the appropriate option if you want to share the source code of your application with everyone you distribute it to, and you also want to give them the right to share who uses it. If you wish to use this software under Open Source Licensing, you must contribute all your source code to the open source community in accordance with the GPL Version 2 when your application is distributed. See http://www.gnu.org/copyleft/gpl.html
## Commercial Licensing
  This is the appropriate option if you are creating proprietary applications and you are not prepared to distribute and share the source code of your application. Contact info@airspayce.com for details.
## Revision History
|Version|Description|
|---|---|
|1.0|Initial release|
|1.1|Updated docs, added Youtube video|
|1.2|Compiles under Arduino 1.0|
|1.3|Updated author and distribution location details to airspayce.com|

## Author:
Mike McCauley (mikem@airspayce.com)
