## Capturing JavaScript Errors and Other Messages from Browser Console


Messages can be logged to browser console using one of the following methods.

console.log
console.info
console.warn
console.error

Note that Zindi will mark a test as failed only if console.error message is found. Other messages will be captured
and will be displayed on the Trinity Radar test log but the test itself will not be marked as failed. In order for the test to fail the message should be of level error.

Below is a video on how to capture JavaScript Error and other console messages.
