## The get() and post() methods

The jQuery get() and post() methods allows you to easily send a HTTP request to a page and get the result back. When you post a form, it's usually either a GET or a POST request, and with jQuery you can mimic that, since both a get() and a post() method exists.

The two methods are pretty much identical, since they simply just invoke different request types against the server. They are both static methods, which means that instead of instantiating a jQuery object and then working with that, we call get() or post() directly on the jQuery class, either by writing jQuery.get() or by using the shortcut character like this: $.get(). In its most simple form, the get() and post() methods takes a single parameter, which is the URL that you wish to request. However, in most cases you will want to do something with the returned data, in which case you can pass a callback function as a parameter, which jQuery will call if the request succeeds.

# Introduction to AJAX

AJAX, short for Asynchronous JavaScript And XML, allows you to load data in the background and display it on your webpage, without refreshing the page. This allows you to create websites with much richer functionality. Popular web applications like Gmail, Outlook Web Access, and Google Maps uses AJAX extensively, to provide you with a more responsive, desktop-like experience.

Using AJAX can be a bit cumbersome, because the various browsers have different implementations to support AJAX. Normally this would force you to write code to respond differently, depending on the browser, but fortunately, jQuery has done this for us, which allows us to write AJAX functionality with as little as a single line of code.
