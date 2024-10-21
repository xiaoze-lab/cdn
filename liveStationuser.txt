// ==UserScript==
// @name         liveStation点击购票按钮
// @namespace    http://tampermonkey.net/
// @version      2024-10-21
// @description  try to take over the world!
// @author       You
// @match        https://www.livenation.hk/show/**
// @icon         https://www.google.com/s2/favicons?sz=64&domain=livenation.hk
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
    function clickFrequently(){
        document.querySelector("a[data-gaclick='Ticket;Buy Tickets;']").click()
        console.log("success")
    }

    setInterval(clickFrequently,100)
    // Your code here...
})();