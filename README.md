[Pusher](https://pusher.com) for Rails 3.1+
=====================

Adds:
- [pusher-gem v0.12.0](https://github.com/pusher/pusher-gem/)
- [pusher.js v2.1.2](https://github.com/pusher/pusher-js/)
- [backpusher.js](https://github.com/pusher/backpusher)

This pulls in the *pusher-gem* as well as adding *pusher.js* and *backpusher.js* to the assets pipeline of your Rails 3.1+ app.

Add this to your app/assets/javascripts/application.js:

    // if you want to use pusher.js
    //= require pusher

    // if you want to use pusher.min.js
    //= require pusher.min

    // if you are using pusher.js + backbone.js
    //= require backpusher

Licenses
========

    /*!
     * Pusher JavaScript Library v1.12.2
     * http://pusherapp.com/
     *
     * Copyright 2011, Pusher
     * Released under the MIT licence.
     */

    //     Backpusher.js 0.0.2
    //     (c) 2011-2012 Pusher.
    //     Backpusher may be freely distributed under the MIT license.
    //     For all details and documentation:
    //     http://github.com/pusher/backpusher

