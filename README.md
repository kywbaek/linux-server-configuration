_Linux Server Configuration_
===================

## Project Overview :
You will take a baseline installation of a Linux server and prepare it to host your web applications. You will secure your server from a number of attack vectors, install and configure a database server, and deploy one of your existing web applications onto it.

## Approach :
- Set up a new Ubuntu Linux server instance on Amazon Lightsail.
- Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
- Install and configure Apache to serve a Python mod_wsgi application.
- Install and configure PostgreSQL.
- Install git.
- Git clone and setup [Catalog project](https://github.com/kywbaek/catalog).

## Usage :
- **IP address:** `18.216.42.243`
- **SSH port:** `2200`
- **URL:** [`http://18.216.42.243`](http://18.216.42.243)
- **SSH key location:** `~/.ssh/authorized_keys`
