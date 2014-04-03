EventList
======

> The `EventList` object provides functions to retrieve calendar events from iOS and Android.
 
Methods
-------

- EventList.findByDateRange

EventList.findByDateRange
=================

    StatusBar.overlaysWebView(startDate, endDate, successCallback, errorCallback);

Description
-----------

Returns a list of calendar events with participants for a specified date range.


Supported Platforms
-------------------

- iOS
- Android

Quick Example
-------------

    EventList.findByDateRange('', '', function() {}, function() {});



    