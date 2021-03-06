# CocoaHTTPServer

[![Build Status](https://travis-ci.org/appium/CocoaHTTPServer.svg)](https://travis-ci.org/appium/CocoaHTTPServer)

CocoaHTTPServer is a small, lightweight, embeddable HTTP server for Mac OS X or iOS applications.

Sometimes developers need an embedded HTTP server in their app. Perhaps it's a server application with remote monitoring. Or perhaps it's a desktop application using HTTP for the communication backend. Or perhaps it's an iOS app providing over-the-air access to documents. Whatever your reason, CocoaHTTPServer can get the job done. It provides:

-   Built in support for bonjour broadcasting
-   IPv4 and IPv6 support
-   Asynchronous networking using GCD and standard sockets
-   Password protection support
-   SSL/TLS encryption support
-   Extremely FAST and memory efficient
-   Extremely scalable (built entirely upon GCD)
-   Heavily commented code
-   Very easily extensible

SSL/TLS encryption is implemented via OpenSSL, which must be installed separately.
To install OpenSSL using Homebrew, run `brew install openssl`.

## Project History

The (original CocoaHTTPServer project)[https://github.com/robbiehanson/CocoaHTTPServer] project hasn't been maintained in a while.

This fork of CocoaHTTPServer is maintained by the Appium team, for the sole purpose of using
it as a dependency of Appium's WebDriverAgent.