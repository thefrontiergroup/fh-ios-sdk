# CHANGELOG - FeedHenry iOS SDK
## 2.2.12 - 2015-08-14
* PR 40 - Fix build errors

## 2.2.11 - 2015-08-14
* PR 37 - downgrade cocoapods version
* PR 38 - Added a check for null response (otherwise App crashes on SSL Handshake error) 
* PR 39 - ensure we are loading from the main bundle for the config file

## 2.2.10 - 2015-07-27 - Wei Li
* Fix an uncaught exception thrown by the sync framework when the cloud app is not running.

## 2.2.9 - 2015-06-23 - Corinne Krych
* Add AeroGear UnifiedPush support for push notification

## 2.2.8 - 2015-04-20 - Christos Vasilakis
* Refactor constructor

## 2.2.7 - 2015-04-16 - Wei Li
* Add environment to the auth API requests if it's available

## 2.2.6 - 2015-04-14 - Wei Li
* Add new auth APIs

## 2.2.5 - 2015-03-08 - Christos Vasilakis
* added cocoapods support

## 2.2.4 - 2015-03-05 - Christos Vasilakis
* extract SDK to be a standalone library target

## 2.2.3 - 2015-02-27 - Wei Li
* Fix failed sync test

## 2.2.2 - 2014-10-02 - Cian Clarke

* Fix oAuth view controller mistaking oAuth page redirect with no query string for success

## 2.2.1 - 2014-09-19 - Wei Li

* 7988 - Update Sync framework to use mBAAS service

## 2.2.0 - 2014-09-04 - Jason Madigan

* 7920 - Removing advertisingIdentifier

## 2.1.0 - 2014-07-01 - Jason Madigan

* 7545 - Tweaks to SDK to fix cloud path

## 2.0.0 - 2014-04-29 - Wei Li

* 6995 - Add support for FH.cloud API
