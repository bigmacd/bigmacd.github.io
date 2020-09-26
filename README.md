# bigmacd.github.io

# Me

<h1 align="center">Hi 👋, I'm Martin</h1>
<h3 align="center">Software Architect, constant coder, frequent tinkerer.</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=bigmacd" alt="bigmacd" /> </p>

- 🔭 I’m currently working on **Docker Environment Monitor**

- 🌱 I’m currently learning **Azure and AWS**

- 👯 I’m looking to collaborate on **Python Projects**

- 👨‍💻 All of my projects are available at [https://github.com/bigmacd](https://github.com/bigmacd)

- 📫 How to reach me **martin.cooley@gmail.com**

- ⚡ Fun fact **There is no iron in the iron you use to iron shirts.**

<p align="left"><img src="https://devicons.github.io/devicon/devicon.git/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/c/c-original.svg" alt="c" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/apache_cassandra/apache_cassandra-icon.svg" alt="cassandra" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" alt="kafka" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/python/python-original.svg" alt="python" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> <img src="https://devicons.github.io/devicon/devicon.git/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/></p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bigmacd&layout=compact" alt="bigmacd" /></p>

<p align="center">
<a href="https://linkedin.com/in/martin.cooley" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="martin.cooley" height="30" width="30" /></a>
<a href="https://stackoverflow.com/users/7102225/martin" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/stackoverflow.svg" alt="7102225/martin" height="30" width="30" /></a>
</p>s

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
