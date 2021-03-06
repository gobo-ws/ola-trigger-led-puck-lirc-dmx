**OLA trigger config to be used with LIRC to send infra-red commands using DMX (Art-Net, sACN or via DMX input.**  
**Control Eurolite LED Puck Light multicolor IP68 and similar models.**

![LED Puck Light](https://raw.githubusercontent.com/gobo-ws/ola-trigger-led-puck-lirc-dmx/master/led_puck_light.jpg)

**Requirements**

* [OLA](https://www.openlighting.org/ola/)
* [LIRC](http://www.lirc.org)
* IR transmitter that is supported by LIRC

**Installation**
  
* Download the [led_puck_light.conf](led_puck_light.conf) file  
* Download the [led_puck_light.lirc.conf](led_puck_light.lirc.conf) file, rename and copy it to the right LIRC directory  

[OLA trigger documentation](https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage** 

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger led_puck_light.conf`
