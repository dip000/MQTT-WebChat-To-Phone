# MQTT-WebChat-To-Phone
Routes text messages though MQTT websockets from the user's web to the server side mobile phone. The WebChat Can be implemented on HTTP or HTTPS web pages.

# Use
1.  Copy-paste WebClient.js contents to your webpage as a javaScript script. This is the text message input interface.
2.  Open MobileServer.js on mobile phone. Messages in webChat will appear in this interface alongside a response text input.

# Notes
To use the WebChat over HTTP you'll need to change the user and password. Go to file: "MQTT-WebChat-To-Phone/MobileServer/MobileServer.js" and change variables to your TLS websockets specifications (i used cloudmqtt.com to serve as a broker):
  
      var user = "userName";
      var password = "123";
