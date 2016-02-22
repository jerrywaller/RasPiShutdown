# ShutYerPiHole
Python script and schematic for a Raspberry Pi shutdown button.

I wanted something to cover my specific needs: a shutdown button for the Pi that elegantly avoided the problems of a floating pin and didn't rely on a *while* statement.

I set up my Pi to use BCM GPIO 17 (do your homework on those pin numbers, folks; I can't stress that enough), with a 1k resistor to the pin and a 10k resistor to ground.

![alt tag](https://raw.githubusercontent.com/jerrywaller/ShutYerPiHole/master/Pi_shutdown_circuit.png)

Credits:
The original script is authored by AndrewH7, and may be found on Instructables at http://www.instructables.com/id/Simple-Raspberry-Pi-Shutdown-Button/?ALLSTEPS

The schematic and information for working with the resistors is inspired by: https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/robot/buttons_and_switches/
