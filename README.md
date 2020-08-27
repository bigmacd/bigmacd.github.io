# bigmacd.github.io

# Me

# My Projects

# C++

## Trap Receiver

[This GitHub Repo](https://github.com/bigmacd/trapreceiver) holds the code for the world's greatest SNMP Trap processing system.  This project started as a close source project in 1997.  It is built on my C++ SNMP Packet Library for SNMP marshalling.

Trap Receiver is extremely popular.  It is simple to use while also being full featured.  You can load your MIBs (or not), define a watch (the receiption of a specific trap, OID, value, etc), and define an action.  The real beauty is that a lot of users found unique ways to perform actions of all kinds.  In hindsight, I wish I fostered this community better.

## SNMP Packet Libary

Back in the day, and perhaps still, a lot of SNMP software was based on the Carnegie Mellon University software base.  I found it terribly difficult and cumbersome, [so I wrote my own](https://github.com/bigmacd/pktlib).  The CMU codebase (which is used by a lot of 3rd parties including Cisco networking equipment, NET-Snmp, and a number of device manufacturers)  has had numerous US-CERT advisories published related to various vunlerabilities.  Mine did not.

I would love one day to get back to this software and implement SNMPv3.  I was hoping to get some support from the community when it went open source.

## Mib Parser

This software is responsible for translating OIDs to human readable names (well as humanly possible as it depends on the MIB author).  [This software](https://github.com/bigmacd/mibparse) takes a slightly different approach.  A lot of the base MIBs don't change, so mibparse simply caches these parsed based MIBs in an embedded SQLite database.

## TrapGen

# Python

## Soccer Ref Calendar

This is a Python web scraper that retrieves my current refereeing assignments and places them in my Google calendar.  [This project](https://github.com/bigmacd/SoccerRefCalendar) use a bunch of technologies:
* Python 3.8
* MechanicalSoup and the Google API
* AWS Lambda layer
* AWS Lambda
* Cloudwatch Trigger
* AWS Destination
* Pushbullet Notifications

I realize this software is solving a very specific issue, but hopefully the application of these technologies can be beneficial to others looking for a similar architecture.

## Container Monitor

[Container Monitor](https://github.com/bigmacd/containerMonitor) is a lightweight Flask app to give you a quick view of your local docker environment.

## aMilli

## deDup

# Dot Net Core

## ShellApi

## csharpRedisWorkerQueue

# Bots

## Magic9Bot

## 666co

## happysac

# Embedded / Arduino

## Spark Plotly

[This](https://github.com/bigmacd/spark-plotly) is a port of the Plotly library to the Spark platform, now know as the Particle Photon.

## I2c16by2LCD

This library provides a nice wrapper and interface around the 16x2 I2C LCD.  Used in the Magic 9 box project below.

## Magic 9 Box

The magic 9 box is a hardware/software project that I devised to be used during backlog refinement to break ties in estimation.  Based loosely on the old Magic 8 Ball, power on this device, ask it a question, give it a shake, and your answer will be revealed.
