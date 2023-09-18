# IEOle
A simple web browser that allows to browse with IE style. It has no navigation buttons like back and forward (but possible via context menu) or other comfort functions that most modern browsers offer.
I just needed a browser to browse my local network, especially the frontends of my Hikvision cameras. With newer browsers it is not possible to login to the frontend of older Hikvision cameras and watch the live stream or playback recorded data (at least not without any additional plugins).
So, be careful and please don't use this browser to browse the internet. I have no idea how safe it will be because it just uses the WinForms WebBrowser object. The code is very simple and I also did not spend a lot of time for error handling.
Just put your address (like http://192.168.1.1) in the address box on the top and hit enter or press the Go-button.
