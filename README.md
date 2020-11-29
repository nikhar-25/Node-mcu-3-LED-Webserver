# Node-mcu-3-LED-Webserver
Controlling 3-LED using Nodemcu By Creating a Lightweight Webserver for controlling the led

Here we are using Nodemcu(ESP8266) as our microcontroller for controlling the three leds

Concept How i am controlling the three leds through Node MCU?
When you type a URL in a web browser and hit ENTER, the browser sends a HTTP request (a.k.a. GET request) to a web server. It’s a job of web server to handle this request by doing something. You might have figured it out by now that we are going to control things by accessing a specific URL. For example, suppose we entered a URL like http://192.168.1.1/ledon in a browser. The browser then sends a HTTP request to ESP8266 to handle this request. When ESP8266 reads this request, it knows that user wants to turn the LED ON. So, it turns the LED ON and sends a dynamic webpage to a browser showing LED status : ON As easy as Pie!

