Description
===========

![OpenEyes-GetButton-flow](https://github.com/nemax68/node-red-contrib-openeyes-voipevent/blob/master/images/flow.png)

A [node.js](http://nodejs.org/) A node-red library that receives JSON message from posix queue 
connected to oesip module with format :
	{
		"type":"REGISTERING",
       		"class":"register",
            	"accountaor":"sip:user@i2make.net"
        }

Requirements
============

* [node.js](http://nodejs.org/) -- tested against v11+

* [node-red](http://nodered.org/)

* Linux 3.4.104+ kernel with POSIX message queue support compiled in (`CONFIG_POSIX_MQUEUE`)

* Need [OpenEyes](http://open-eyes.it) hardware platform

  ![OpenEyes-voipevent-flow](https://github.com/nemax68/node-red-contrib-openeyes-voipevent/blob/master/images/open-eyes.png)

* Depends on [nan](https://www.npmjs.com/package/nan) & [posix-mq](https://www.npmjs.com/package/posix-mq) which will be automatically installed when running `npm install openeyes-voipevent`.

Install
=======

```shell
$ npm install openeyes-voipevent
```
Values
========


Examples
========

API
===
