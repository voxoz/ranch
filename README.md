# Ranch

[![Build Status](https://travis-ci.org/voxoz/ranch.svg?branch=master)](https://travis-ci.org/voxoz/ranch)

Ranch is a socket acceptor pool for TCP protocols.

## Goals

Ranch aims to provide everything you need to accept TCP connections with
a *small* code base and *low latency* while being easy to use directly
as an application or to *embed* into your own.

Ranch provides a *modular* design, letting you choose which transport
and protocol are going to be used for a particular listener. Listeners
accept and manage connections on one port, and include facilities to
limit the number of *concurrent* connections. Connections are sorted
into *pools*, each pool having a different configurable limit.

Ranch also allows you to *upgrade* the acceptor pool without having
to close any of the currently opened sockets.

## Online documentation

* [User guide](https://ninenines.eu/docs/en/ranch/1.6/guide)
* [Function reference](https://ninenines.eu/docs/en/ranch/1.6/manual)

## Getting help

* Official IRC Channel: #ninenines on irc.freenode.net
* [Issues tracker](https://github.com/ninenines/ranch/issues)
* [Commercial Support](https://ninenines.eu/services)

