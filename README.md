# Easycontroller
Application for using midi-controllers in an easy and convinient way across max/msp and Openframework (Only for Mac users). The idea is to be able to master your controller for live music and visual, independently of the platform you use. Initially, you need to map your midi-controller only by touching your knobs and clicks, and then work with its paramters directly in yout OF app or Max patch (all can be found in the video here <a href="https://www.youtube.com/watch?v=en2tB_PJq-0">User Guide -Easycontroller</a>). Your knobs can be labeled for each program/song/visualization and you can easily re-map the values, and finally create presets to update your midicontroller for each chapter of your performance. We perform with this tool at 42Noir, we've tested it mostely for Novation and Yamaha controllers, but if your controller has unique midi formating (:/) contact us and we would try to sort it out for you.   

# Instrouction for using it with openframework:

   1. Download the application in
 <a href="http://www.42noir.com/es">http://www.42noir.com/es</a>
   2. Follow the guide of how to install and assigne your midi-controller for the use, and also whatch how you can use it with Max/MSP. 
   3. Download the dependant class files: escon.h and escon.cpp and add them to your openframework target files or use it next to a specific programm. 
   4. Download all files to run an example ofapp, to see how to call values (easy.rec("s1")), and to label your knob in the application. Otherwise, in your ofapp.h include the "escon.h" and create an object member of escon (e.g. escon easy). Then use the member functions label, rec, snd, to recieve/send parameters from/to the controller.
   

# Functionality
* Easymapping of the controller.
* Labeling knobs and pads.
* Re-mapping values.
* Applying Presets.
* Control both Max and OF together.

<a href="url"><img src="http://42noir.com/wp-content/uploads/2016/12/3-screenshot@2x-1.png" align="left" height="200" width="300" ></a>






