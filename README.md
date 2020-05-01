# tracerEpever
Raspberry pi data logger for the Epever tracer RS485 and 8 channel relay 

i included the driver  for the usb to rs485  but you will need to build them for your pi follow instrustion in the folder


you will need node red installed with npm

node-red 1.0.3

node-red-contrib-influxdb   0.4.0       this one

node-red-contrib-modbus   5.8.0       this one  

node-red-contrib-moment 3.0.3 

node-red-contrib-play-audio 2.4.0 

node-red-dashboard   2.20.0          this one

 node-red-node-pi-gpio 1.0.6

 node-red-node-ping 0.1.0 

node-red-node-random 0.1.4 

node-red-node-rbe    0.2.5            this one

node-red-node-serialport 0.9.1

node-red-node-smooth 0.1.2

node-red-node-tail 0.0.3
or newer most of these get install by default but ive marked the one are a must have (this one)

once node red install and all node are installed then import the newest json file into node read and i left some explanation in there that happening

install influxdb 

And grafana work very well to display past  data that stored in influxDB but you will need to set that up 

and you will need to install and setup the pi as a wifi hot spot and connect to it that way or hock it to a router and ssh in the normal way 

have fune and play around if you fell you could add to it speak up and we can chat about it or if you think i could of done it a diffrant way im open for new idea's
