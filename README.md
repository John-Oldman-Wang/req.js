[req.js](https://github.com/nokisnojok/req.js) — a simple ajax
==================================================

How to use 
--------------------------------------
var requset = require('./request.js')

var xhr = new request('http://example.com/', (e) => {
    console.log(e.responseText)
})
xhr.send()

--------------------------------------
var requset = require('./request.js')

var xhr = new request()
xhr.get('http://example.com/', (e) => {
    console.log(e.responseText)
})
xhr.send()