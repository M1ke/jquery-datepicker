# jQuery Datepicker
#### by [Kelvin Luck _(2007)_](http://www.kelvinluck.com/assets/jquery/datePicker/v2/demo/index.html)

## Summary

"This is an clean, unobtrusive plugin for jQuery which allows you to easily add date inputing functionality to your web forms and pages. Designed from the ground up to be flexible and extensible, the date picker can be used in unlimited ways to allow you to add calendar widgets to your pages."

## Amends
#### by Mike Lehan _(2012 onwards)_

This plugin is a great way to get a quick date picker in jQuery. Unfortunately it stopped working as of jQuery 1.7 because of deprecation of $.event and changes to how class attributes are handled. I have fixed these, and will try and maintain/add to the plugin as I see fit.

I have also added a useful document.ready helper - any input with the class of "date" will change automatically. I will attempt to make further changes so that the plugin works with [type="date"] but this breaks it in some browsers at present.
