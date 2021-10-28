# WKWebviewPoc
Trying to disable certificate pinning. I.e. run the app on a device with a proxy setup (e.g. [Charles Proxy](https://www.charlesproxy.com) or [Proxyman](https://proxyman.io)), enable SSL Proxying for `developer.apple.com` and try to run the app.

The expected/desired behavior would be that the request succeeds, but it fails with an NSURLErrorDomain -1200 or -1202.