# http-notification-plugin

This is a simple http notification plugin for rundeck.
It uses apache httpclient library to perform the request

## Features

It can perform GET and POST method
	
	In case of a POST request, it can handle xml and json format.
	
## Building

    mvn install

Produces:

	target/http-notification-0.0.1-SNAPSHOT


## Install

First, download the "Rundeck Launcher" [Rundeck](http://rundeck.org/downloads.html)

    cp target/http-notification-0.0.1-SNAPSHOT ${rundeck_home}/libext

## Run rundeck

    java -jar rundeck-launcher-2.11.9.jar