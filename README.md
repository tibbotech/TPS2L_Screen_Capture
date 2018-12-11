# TPS2L_SCREEN_CAPTURE

Ever had to produce high-quality images of your device's LCD screen? This need often arises when you are working on web pages or user manuals describing your product's functionality. If you ever tried taking photos of LCD screens with a camera, you know that the result always looks somewhat skewed, over- or under-exposed, and amateurish.

Tibbo [SCAP library](http://docs.tibbo.com/taiko/index.html?lib_scap.htm) to the rescue! This library adds screen-grabbing to your Tibbo BASIC/C app.

This project allows you to test the library on a TPS2L(G2) device.
To take a screenshot, point the browser to _http://<your device's IP address>/scap.html_ and click **Capture the Screen**. The app even adds a TPS2L "frame" around the screenshot.

Before testing, set the suitable IP address (**net.ip="...** in **on_sys_init()** of **main.tbs**).

![startscreen](startscreen.PNG)
